## 313SpringBoot垃圾管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/190.html

垃圾管理系统基于SpringBoot+Mybatis开发，系统分为管理员，用户和垃圾车司机三种角色。

管理员：

- 用户管理
- 登录日志
- 操作日志
- 站点管理
- 车辆管理
- 垃圾处理请求审核
- 垃圾处理请求确认

垃圾车司机：

- 垃圾处理请求处理

普通用户：

- 垃圾站点查看
- 添加垃圾处理请求

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
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456 ，垃圾车司机账号密码 zsf/123456，普通用户账号密码 mayun/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230804103702448](http://image.javatip.cn/bysj/20230804103702.png)

![image-20230804103608505](http://image.javatip.cn/bysj/20230804103615.png)

![image-20230804103644135](http://image.javatip.cn/bysj/20230804103644.png)
