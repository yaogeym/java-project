## 423SpringBoot+vue企业绩效考核管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/811.html

电子商城系统是由SpringBoot+vue开发的前后端分离的项目，系统分为用户前台和管理员后台，总共有四类角色，管理员负责后台管理，前台分为员工、组长、领导，功能如下：

前台：

- 注册登录
- 考核项目查看
- 考核自评
- 成绩公告
- 个人中心
- 查看评分

后台：

- 考核项目管理
- 评分管理
- 用户管理
- 考核成绩管理
- 轮播图管理

### 二、技术框架

- 后端：SpringBoot，mybatis
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开后端项目（总共有三个项目，一个后台，一个前台的前端项目，一个后台的前端项目。用idea打开三个窗口）
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 找到**FileController**，大概第70行的位置，将 **D:\\cl123456\\**路径替换为你本地的项目存放**根路径**，路径中不要使用中文
7. 启动后台运行
8. idea分别打开两个前端项目，分别使用命令**npm install**下载依赖，然后使用命令 **npm run serve**运行。

>前台和后台分别使用两个浏览器进行访问，同一个浏览器访问可能会造成token失效
>
>后台路径地址：localhost:8081  账号密码：admin/123456
>前台路径地址：localhost:8082  员工账号密码：wm/123456，组长账号密码：zsf/123456，领导账号密码：sx/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240819172815738](http://image.javatip.cn/bysj/20240819172815.png)

![image-20240819141608907](http://image.javatip.cn/bysj/20240819141616.png)

![image-20240819141654179](http://image.javatip.cn/bysj/20240819141654.png)

![image-20240819143615948](http://image.javatip.cn/bysj/20240819143616.png)

![image-20240819144354953](http://image.javatip.cn/bysj/20240819144355.png)
