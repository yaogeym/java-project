## 416SpringBoot高校专家管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/802.html

高校专家管理系统是基于SpringBoot开发的，系统分为前台和后台，前台用于用户查看专家信息，后台由管理员进行专家信息及用户信息管理等。具体角色功能如下：

用户：

- 注册登录
- 查看专家

管理员：

- 管理员管理
- 用户管理
- 专家管理

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
>前台访问地址：http://localhost:8080/web，普通用户账号密码：wm/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240805113120624](http://image.javatip.cn/bysj/20240805113121.png)

![image-20240805113031494](http://image.javatip.cn/bysj/20240805113031.png)

![image-20240805113014733](http://image.javatip.cn/bysj/20240805113021.png)

![image-20240805113152909](http://image.javatip.cn/bysj/20240805113153.png)

![image-20240805113221539](http://image.javatip.cn/bysj/20240805113222.png)
