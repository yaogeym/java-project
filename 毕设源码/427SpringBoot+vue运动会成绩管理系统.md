## 427SpringBoot+vue运动会成绩管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/815.html

运动会成绩管理系统是基于SpringBoot+mybatis开发，系统分为前台和后台，总共有三种用户类型，管理员和裁判登录后台进行管理，运动员可以登录前台进行项目赛事报名，功能如下：

管理员：

- 站点管理
- 用户管理
- 运动会资讯
- 项目类型管理
- 比赛项目管理
- 参赛信息
- 参赛成绩
- 成绩排名

裁判：

- 参赛信息
- 参赛成绩
- 成绩排名

运动员：

- 运动会资讯查看
- 公告查看
- 比赛项目报名
- 比赛项目收藏
- 参赛成绩

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
>后台路径地址：localhost:8080  管理员账号密码：admin/123456，裁判账号密码：zsf/123456
>前台路径地址：localhost:8081  账号密码：wm/123456
>
>多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240820163442311](http://image.javatip.cn/bysj/20240820163442.png)

![image-20240820163427794](http://image.javatip.cn/bysj/20240820163427.png)

![image-20240820163418413](http://image.javatip.cn/bysj/20240820163418.png)

![image-20240820163143687](http://image.javatip.cn/bysj/20240820163144.png)

![image-20240820163337789](http://image.javatip.cn/bysj/20240820163338.png)

![image-20240820163405407](http://image.javatip.cn/bysj/20240820163405.png)
