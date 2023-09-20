## 132SpringBoot+vue校园兼职平台

### 一、项目介绍

项目地址：http://javatip.cn/store/158.html

校园兼职平台基于SpringBoot+vue进行开发，用户通过平台注册进入平台，然后在平台上发布兼职信息，系统分为管理员和普通用户良种角色。

平台主要功能：

- 兼职浏览
- 兼职发布
- 兼职收藏
- 兼职管理
- 兼职评论
- 兼职上架
- 兼职下架
- 兼职搜索
- 消息沟通

管理员可以审核上架普通用户发布的兼职。

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：vue，elementui

### 三、安装教程

1. 解压目录后，前台项目在part-job-website-vue目录中，idea打开这个目录，后台项目在part-job-website-springboot目录中，新开一个idea窗口打开这个目录
2. 在后台idea中配置jdk环境
3. 在后台配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.properties文件中将数据库账号密码改成自己本地的

6. 在application.yml文件中将redis信息修改成自己本地的，redis默认密码为空（需要启动redis）

7. 在idea中进入前台文件夹part-job-website-vue。在idea底部打开**Terminal**，然后分别输入命令**npm install** 下载依赖。等到进度条走完后在**Terminal**中输入命令 **npm run serve**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.22.12）。

8. 后台管理员账号密码 admin/123456。普通用户账号密码 xiaoli/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230726211534069](http://image.javatip.cn/bysj/20230726211534.png)

![image-20230726211618699](http://image.javatip.cn/bysj/20230726211619.png)

![image-20230726211643131](http://image.javatip.cn/bysj/20230726211643.png)

![image-20230726211656794](http://image.javatip.cn/bysj/20230726211656.png)

![image-20230726211713348](http://image.javatip.cn/bysj/20230726211713.png)
