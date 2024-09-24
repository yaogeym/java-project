## 428SpringBoot+vue社区疫苗接种管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/817.html

社区疫苗接种管理系统是基于SpringBoot+mybatis开发，系统分为前台和后台，功能如下：

后台：	

- 公告管理
- 用户管理
- 论坛管理
- 新闻管理
- 接种者管理
- 疫苗管理
- 疫苗预约
- 预约计划
- 疫苗出入库
- 接种记录

前台：

- 发布帖子
- 评论帖子
- 收藏帖子
- 点赞帖子
- 查看公告
- 查看新闻
- 查看疫苗
- 预约疫苗

### 二、技术框架

- 后端：SprinBoot，mybatis
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开后端项目（总共有三个项目，一个后台，一个前台的前端项目，一个后台的前端项目。用idea打开三个窗口）
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 启动后台运行
7. idea打开前端项目**client-admin**，使用命令**npm install**下载依赖，然后使用命令 **npm run dev**运行。
8. idea打开前端项目**client-home**，使用命令**npm install**下载依赖，然后使用命令 **npm run serve**运行。

>前台和后台分别使用两个浏览器进行访问，同一个浏览器访问可能会造成token失效
>
>后台路径地址：localhost:8080  管理员账号密码：admin/123456
>前台路径地址：localhost:8081  账号密码：wm123/123456
>
>多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240820180132830](http://image.javatip.cn/bysj/20240820180133.png)

![image-20240820180112237](http://image.javatip.cn/bysj/20240820180112.png)

![image-20240820180102571](http://image.javatip.cn/bysj/20240820180102.png)

![image-20240820180009044](http://image.javatip.cn/bysj/20240820180009.png)

![image-20240820180035495](http://image.javatip.cn/bysj/20240820180035.png)

![image-20240820180046484](http://image.javatip.cn/bysj/20240820180046.png)
