## 224SpringBoot校友管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/157.html

校友管理系统基于SpringBoot+Mybatis开发，系统分为管理员和校友两种角色。系统提供校友注册功能，管理员可以设置校友为优秀校友。

管理员功能如下：

- 优秀校友墙
- 学院管理
- 用户管理
- 设置/取消优秀校友

- 意见反馈管理
- 留言墙

校友：

- 注册登录
- 校友墙
- 留言
- 意见反馈
- 留言查看

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 将压缩包中的图片下的upload文件夹，移动到F盘。如果你的电脑没有F盘，则移动到其他盘，同时需要修改 file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 1001/123456， 校友账号密码 10001/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230726163142630](http://image.javatip.cn/bysj/20230726163143.png)

![image-20230726162948154](http://image.javatip.cn/bysj/20230726162948.png)

![image-20230726163408567](http://image.javatip.cn/bysj/20230726163408.png)

![image-20230726163421851](http://image.javatip.cn/bysj/20230726163422.png)
