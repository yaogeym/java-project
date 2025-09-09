## 432SpringBoot+vue旅游景区预约服务系统

### 一、项目介绍

项目地址：http://javatip.cn/store/821.html

旅游景区预约服务系统是基于SpringBoot+mybatis开发，系统分为前台和后台，后台分为管理员对用户、景区等信息进行管理，前台用户注册后可以进行预约景区，后台管理员审核预约信息，功能如下：

后台：

- 站点管理
- 用户管理
- 资讯管理
- 景点信息
- 预约信息

前台：

- 注册登录
- 资讯查看
- 公告查看
- 评论
- 收藏
- 点赞
- 预约景区

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

![image-20240821162748467](http://image.javatip.cn/bysj/20240821162749.png)

![image-20240821162805249](http://image.javatip.cn/bysj/20240821162805.png)

![image-20240821162248754](http://image.javatip.cn/bysj/20240821162249.png)

![image-20240821162854027](http://image.javatip.cn/bysj/20240821162854.png)

![image-20240821162837367](http://image.javatip.cn/bysj/20240821162837.png)
