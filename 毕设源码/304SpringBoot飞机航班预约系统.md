## 304SpringBoot飞机航班预约系统

### 一、项目介绍

项目地址：http://javatip.cn/store/182.html

飞机航班预约系统基于SpringBoot+Mybatis开发，系统分为管理员和普通用户两种角色。

管理员功能如下：

- 会员管理
- 公告管理
- 航空公司管理
- 航班管理
- 订票信息查询

普通用户：

- 注册登录
- 公告查看
- 订票
- 改签
- 退票
- 付款

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui，echarts，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456 ，普通用户账号密码 lm/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230802115954854](http://image.javatip.cn/bysj/20230802115955.png)

![image-20230802120112215](http://image.javatip.cn/bysj/20230802120112.png)

![image-20230802120122402](http://image.javatip.cn/bysj/20230802120122.png)

![image-20230802120144051](http://image.javatip.cn/bysj/20230802120144.png)

![image-20230802120208671](http://image.javatip.cn/bysj/20230802120208.png)
