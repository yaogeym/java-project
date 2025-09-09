## 326SpringBoot泳场管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/207.html

泳场管理系统基于SpringBoot+Mybatis开发，系统分为管理员、经理和员工三种角色。

管理员：

- 经理管理
- 员工管理
- 工作安排
- 设备检查
- 考勤管理
- 薪资管理

经理：

- 注册登录
- 考勤管理
- 日常支出
- 日常收入

员工：

- 注册登录

- 考勤
- 个人考勤记录

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456 ，经理账号密码 lm/123456，员工账号密码 xl/123456。

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230811093325006](http://image.javatip.cn/bysj/20230811093336.png)

![image-20230811093720209](http://image.javatip.cn/bysj/20230811093720.png)

![image-20230811093901699](http://image.javatip.cn/bysj/20230811093901.png)

![image-20230811093913856](http://image.javatip.cn/bysj/20230811093913.png)

![image-20230811093956550](http://image.javatip.cn/bysj/20230811093956.png)

![image-20230811094148026](http://image.javatip.cn/bysj/20230811094148.png)
