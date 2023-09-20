## 107SpringBoot房屋租赁网站

### 一、项目介绍

项目地址：http://javatip.cn/store/96.html

房屋租赁网站基于SpringBoot+Mybatis开发，系统分为管理员和普通用户两种角色。

管理员功能如下：

- 登录
- 修改密码
- 查看用户
- 房屋管理
- 图片上传

普通用户功能如下：

- 网站首页
- 房屋浏览
- 房屋查询
- 注册登录
- 房屋预定
- 我的租房信息
- 发布房源

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.properties文件中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在D盘，如果你的电脑没有D盘，则需要改成其他盘，具体位置在WebConfig.java和AddHouseController.java两个文件，将文件里面的D:改成你本地有的盘符即可。
7. 启动运行，访问 http://localhost:8090/toIndexPage  , 管理员账号密码 admin/123456，普通用户直接注册或者使用默认账户 zhang/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![ocalhost](http://image.javatip.cn/bysj/20230711151423.png)

![localhost](http://image.javatip.cn/bysj/20230711151542.png)

![image-20230711151605673](http://image.javatip.cn/bysj/20230711151606.png)

![image-20230711151617812](http://image.javatip.cn/bysj/20230711151617.png)

![image-20230711151643187](http://image.javatip.cn/bysj/20230711151643.png)
