## 102SSM汽车租赁系统

### 一、项目介绍

项目地址：http://javatip.cn/store/89.html

汽车租赁系统基于Spring+SpringMVC+Mybatis开发，系统使用shiro框架做权限安全控制，超级管理员登录系统后可根据自己的实际需求配角色，然后新建用户选择角色即可。

超级管理员功能如下：

- 客户管理
- 车辆管理
- 汽车出租
- 出租单管理
- 汽车入库
- 检查单管理
- 统计分析
- 系统管理
    - 菜单管理
    - 角色管理
    - 用户管理
- 公告管理
- 系统日志

### 二、技术框架

- 后端：Spring，Springmvc，Mybatis
- 前端：layui，echarts

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 配置tomcat8.0
5. 新建数据库，导入数据库文件
6. 在db.properties文件中将数据库账号密码改成自己本地的
7. 系统的静态资源存储在D盘，如果你的电脑没有D盘，则需要改成其他盘，具体位置在file.properties，将文件里面的D:/upload 改成你本地的即可。
8. 启动运行，访问 http://localhost:8080  , 管理员账号密码 admin/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230710141750885](http://image.javatip.cn/bysj/20230710141751.png)

![image-20230710141828487](http://image.javatip.cn/bysj/20230710141828.png)

![image-20230710141847644](http://image.javatip.cn/bysj/20230710141847.png)

![image-20230710141933437](http://image.javatip.cn/bysj/20230710141933.png)

![image-20230710141948519](http://image.javatip.cn/bysj/20230710141948.png)

![image-20230710142010136](http://image.javatip.cn/bysj/20230710142010.png)

![image-20230710142027866](http://image.javatip.cn/bysj/20230710142027.png)
