## 417SpringBoot网页资源共享平台

### 一、项目介绍

项目地址：http://javatip.cn/store/803.html

网页资源共享平台是基于SpringBoot开发的，主要用来分享html网页资源，可以进行进行预览和下载。系统分为前台和后台，前台用于用户查询网页，预览网页和下载网页，后台由管理员进行网页管理和用户管理。具体功能如下：

前台用户：

- 注册登录
- 查询网页资源
- 预览
- 下载
- 查看通知公告
- 上传资源

管理员：

- 管理员管理
- 用户管理
- 通知管理
- 网页资源管理

### 二、技术框架

- 后端：SpringBoot，mybatis
- 前端：layui，jquery，thymeleaf

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 后台启动运行

>后台访问地址：http://localhost:8080，管理员账号密码：system/123456
>
>前台访问地址：http://localhost:8080/web，普通用户账号密码：yaoge/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240805153233078](http://image.javatip.cn/bysj/20240805153233.png)

![image-20240805153207360](http://image.javatip.cn/bysj/20240805153207.png)

![image-20240805153219038](http://image.javatip.cn/bysj/20240805153219.png)

![image-20240805153250293](http://image.javatip.cn/bysj/20240805153250.png)

![image-20240805153314388](http://image.javatip.cn/bysj/20240805153314.png)
