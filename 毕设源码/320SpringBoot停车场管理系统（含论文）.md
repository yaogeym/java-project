## 320SpringBoot停车场管理系统（含论文）

### 一、项目介绍

项目地址：http://javatip.cn/store/197.html

停车场管理系统基于SpringBoot+Mybatis开发，车辆驶入时系统使用ocr技术进行车牌识别，开始计费，车辆理财时根据停车时长计算停车费，汽车入场后自动分配空余车位，并将改车位改为占用状态。系统分为管理员和普通用户两种角色。

管理员主要功能：

- 用户管理
- 公告管理
- 停车场管理
- 车位管理
- 计费规则
- 停车管理
- 车牌识别
- 车辆报修处理
- 停车记录
- 停车费支付

普通用户功能：

- 公告查看
- 停车场查看
- 车位查看
- 停车记录查看
- 车辆报修

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
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456，普通用户账号密码：mayun/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230808143802186](http://image.javatip.cn/bysj/20230808143802.png)

![image-20230808143739077](http://image.javatip.cn/bysj/20230808143739.png)

![image-20230808143129847](http://image.javatip.cn/bysj/20230808143130.png)

![image-20230808143447775](http://image.javatip.cn/bysj/20230808143447.png)

![image-20230808143719380](http://image.javatip.cn/bysj/20230808143719.png)
