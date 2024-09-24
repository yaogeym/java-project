## 410SpringBoot大型仪器管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/345.html

大型仪器管理系统主要是实现仪器设备的统一管理，提高设备的利用率和管理效率，为科研工作提供更好的支持和保障.

大型仪器管理系统是基于SpringBoot开发的，系统分为设备处、设备管理员和普通用户三种角色，普通用户预约使用设备，设备管理员进行核实预约申请，设备处主要是查看设备状态。普通用户注册后，经设备管理员进行审批，审批通过后可正常登入系统。具体角色功能如下：

设备处：

- 角色管理

- 用户管理
- 设备状态查看
- 设备维护
- 设备统计分析

设备管理员：

- 用户审批
- 设备管理
- 预约审核

普通用户：

- 注册登录
- 设备信息导出
- 设备预约
- 设备归还

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

>访问地址：http://localhost:8080，设备处账号密码：system/123456，设备管理员账号密码：root/123456，普通用户账号密码：15000000000/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240729110809486](http://image.javatip.cn/bysj/20240729110816.png)

![image-20240729111131434](http://image.javatip.cn/bysj/20240729111131.png)

![image-20240729111229512](http://image.javatip.cn/bysj/20240729111229.png)

![image-20240729111029388](http://image.javatip.cn/bysj/20240729111029.png)

![image-20240729111045081](http://image.javatip.cn/bysj/20240729111045.png)

![image-20240729111450229](http://image.javatip.cn/bysj/20240729111450.png)
