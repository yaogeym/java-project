## 414SpringBoot马拉松管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/800.html

马拉松管理系统是基于SpringBoot开发的，系统分为前台和后台，前台用于用户查看赛事信息，报名，查询自己的成绩，后台主要由管理员和裁判登录，用户管理赛事信息和成绩信息等。具体角色功能如下：

用户：

- 注册登录
- 赛事查看、搜索
- 报名
- 查看成绩

裁判：

- 用户审批
- 设备管理
- 预约审核

管理员：

- 角色管理
- 裁判管理
- 选手管理
- 赛事管理
- 选手国籍统计

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

>后台访问地址：http://localhost:8080，管理员账号密码：system/123456，裁判账号密码：majie/123456；
>
>前台访问地址：http://localhost:8080/web，普通用户账号密码：18888888888/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240802110622617](http://image.javatip.cn/bysj/20240802110623.png)

![image-20240802110109500](http://image.javatip.cn/bysj/20240802110109.png)

![image-20240802110119576](http://image.javatip.cn/bysj/20240802110119.png)

![image-20240802110422156](http://image.javatip.cn/bysj/20240802110422.png)

![image-20240802110502527](http://image.javatip.cn/bysj/20240802110502.png)

![image-20240802110643866](http://image.javatip.cn/bysj/20240802110643.png)
