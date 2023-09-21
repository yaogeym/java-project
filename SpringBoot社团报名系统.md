## 221SpringBoot社团报名系统

### 一、项目介绍

项目地址：http://javatip.cn/store/151html

社团报名系统基于SpringBoot+Mybatis开发，系统使用shiro框架做权限安全控制，系统分为管理员，社团负责人，普通用户三种角色。

管理员功能如下：

- 用户管理
- 社团管理
- 会员管理
- 留言查看

社团负责人：

- 活动管理
- 报名申请审核

普通用户：

- 活动报名
- 添加留言
- 我的申请

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456， 社团负责人账号密码 zhagnfeng/123456，普通账号密码 lisi/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230725153511390](http://image.javatip.cn/bysj/20230725153512.png)

![image-20230725153248811](http://image.javatip.cn/bysj/20230725153248.png)

![image-20230725153300431](http://image.javatip.cn/bysj/20230725153300.png)

![image-20230725153332357](http://image.javatip.cn/bysj/20230725153332.png)

![image-20230725153453109](http://image.javatip.cn/bysj/20230725153453.png)
