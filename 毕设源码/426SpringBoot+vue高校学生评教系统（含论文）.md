## 426SpringBoot+vue高校学生评教系统（含论文）

### 一、项目介绍

项目地址：http://javatip.cn/store/814.html

高校学生评教系统是基于SpringBoot+mybatis开发，用于高校学生对老师进行评教管理，功能如下：

管理员：

- 管理员管理
- 学生管理
- 教师管理
- 评教信息
- 评价打分查看
- 指标管理
- 课程管理
- 教师评分统计

学生：

- 评教信息
- 评价打分

教师：

- 学生管理
- 课程管理
- 指标管理

### 二、技术框架

- 后端：SprinBoot，mybatis
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开后端项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 启动后台运行
7. idea打开前端项目，使用命令**npm install**下载依赖，然后使用命令 **npm run dev**运行。

>前台和后台分别使用两个浏览器进行访问，同一个浏览器访问可能会造成token失效
>
>后台路径地址：localhost:8081  管理员账号密码：admin/123456，旅行社账号密码：lxs/123456
>前台路径地址：localhost:8082  账号密码：wm/123456
>
>多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240904161311293](http://image.javatip.cn/bysj/20240904161318.png)

![image-20240820151625425](http://image.javatip.cn/bysj/20240820151625.png)

![image-20240820151546434](http://image.javatip.cn/bysj/20240820151546.png)

![image-20240820151557860](http://image.javatip.cn/bysj/20240820151557.png)

![image-20240820151748259](http://image.javatip.cn/bysj/20240820151748.png)
