## 114SSM图书管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/110.html

图书管理系统基于Spring+SpringMVC+Mybatis开发，系统主要实现了图书馆借书还书功能，系统分为管理员和读者两种角色。

管理员功能如下：

- 图书管理
- 类型管理
- 借书管理
- 还书管理
- 读者管理
- 公告管理
- 管理员管理
- 图书统计

读者功能如下：

- 密码修改
- 公告查看
- 个人借还书查看

### 二、技术框架

- 后端：Spring，Springmvc，Mybatis
- 前端：layui，echarts，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 配置Tomcat8.0
5. 新建数据库，导入数据库文件
6. 在db.properties文件中将数据库账号密码改成自己本地的
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 admin/123456，读者账号密码 wm/123456，新创建的用户密码默认都是123456

### 四、项目截图

![image-20230717112721057](http://image.javatip.cn/bysj/20230717112721.png)

![image-20230717112539033](http://image.javatip.cn/bysj/20230717112547.png)

![image-20230717112634513](http://image.javatip.cn/bysj/20230717112634.png)

![image-20230717112647322](http://image.javatip.cn/bysj/20230717112647.png)

![image-20230717112700115](http://image.javatip.cn/bysj/20230717112700.png)

![image-20230717112747177](http://image.javatip.cn/bysj/20230717112747.png)
