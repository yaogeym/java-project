## 111SpringBoot在线论坛

### 一、项目介绍

项目地址：http://javatip.cn/store/100.html

在线论坛是由SpringBoot+Mybatis开发的，论坛提供用户注册，整体分为管理员和普通用户两种角色。管理员端可以生产邀请码，用户注册时提供邀请码进行注册，不输入邀请码也可以注册。

管理员功能如下：

- 邀请码管理
- 用户查询
- 用户禁言
- 用户解禁
- 网盘管理
- 发帖
- 看帖
- 删帖
- 回复贴

普通用户功能如下：

- 注册登录

- 发帖
- 回复贴
- 删除自己的贴子
- 看帖

- 网盘管理

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：bootstrap，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 网盘上传的资源存储在E盘，如果你的电脑没有E盘，则需要改成其他盘，具体位置在application.yml文件，将文件里面的E:\\\file改成你本地的即可。
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 admin/123456 

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230712094509345](http://image.javatip.cn/bysj/20230712094509.png)

![image-20230712094552408](http://image.javatip.cn/bysj/20230712094552.png)

![image-20230712094607590](http://image.javatip.cn/bysj/20230712094607.png)

![image-20230712094617860](http://image.javatip.cn/bysj/20230712094617.png)
