## 314SpringBoot民宿管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/191.html

民宿管理系统基于SpringBoot+Mybatis开发，系统分为管理员，租户和住户三种角色。

管理员：

- 租户管理
- 住户管理
- 公告管理
- 房间审核

租户：

- 注册登录

- 房间管理
- 退房
- 报修查看
- 评价查看

住户：

- 注册登录
- 房间查看
- 房间预定
- 房间报修
- 房间评价

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456 ，租户账号密码 zu/123456，住户账号密码 zhu/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230804112307853](http://image.javatip.cn/bysj/20230808153502.png)

![image-20230804112508905](http://image.javatip.cn/bysj/20230804112509.png)

![image-20230804112822466](http://image.javatip.cn/bysj/20230804112822.png)

![image-20230804112844457](http://image.javatip.cn/bysj/20230804112844.png)
