## 303SpringBoot地摊管理系统（含论文）

### 一、项目介绍

项目地址：http://javatip.cn/store/181.html

地摊管理系统基于SpringBoot+Mybatis开发，系统分为管理员和摊主两种角色。

管理员功能如下：

- 摊主管理
- 摊位政策管理
- 摊位攻略管理
- 摊位管理
- 摊位使用日志
- 缴费统计

摊主：

- 注册登录
- 政策查看
- 攻略查看
- 摊位申请

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
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456 ，摊主账号密码 lm/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230802104317721](http://image.javatip.cn/bysj/20230802104318.png)

![image-20230802104216282](http://image.javatip.cn/bysj/20230802104224.png)

![image-20230802104241356](http://image.javatip.cn/bysj/20230802104241.png)

![image-20230802104259833](http://image.javatip.cn/bysj/20230802104300.png)

![image-20230802104416811](http://image.javatip.cn/bysj/20230802104416.png)
