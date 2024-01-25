## 153SpringBoot+vue宿舍管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/271.html

宿舍管理系统基于SpringBoot+vue进行开发。系统分为管理员、宿管和学生三种角色。具体功能如下：

管理员：

- 学生管理
- 宿管管理
- 楼宇管理
- 宿舍管理
- 宿舍床位分配
- 公告管理
- 报修管理
- 调宿申请处理
- 访客管理
- 水费管理
- 电费管理
- 卫生检查

宿管：

- 学生管理
- 楼宇管理
- 宿舍管理
- 宿舍床位分配
- 报修管理
- 调宿申请处理
- 访客管理
- 卫生检查

学生：

- 我的宿舍
- 申请调宿
- 报修申请
- 水费管理
- 电费管理
- 我的宿舍卫生

### 二、技术框架

- 后端：SpringBoot，mybatis
- 前端：vue，elementui，echarts

### 三、安装教程

1. 用idea打开后台项目

2. 在idea中配置jdk环境

3. 配置maven环境并下载依赖

4. 新建数据库，导入数据库文件

5. 在application.prperties文件中将数据库账号密码改成自己本地的

6. 在idea中打开前台项目。在idea底部打开**Terminal**，然后在输入命令**npm install --registry=https://registry.npmmirror.com** 下载依赖。等到进度条走完后输入命令 **npm run serve**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.12.0）。

7. 在idea中启动后台项目。

8. > 管理员账号密码：admin/123456，宿管账号密码：dorm1/123456，学生账号密码：1001/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20231214110159984](http://image.javatip.cn/bysj/20231214110200.png)

![image-20231214105936657](http://image.javatip.cn/bysj/20231214105936.png)

![image-20231214110314861](http://image.javatip.cn/bysj/20231214110315.png)

![image-20231214110037549](http://image.javatip.cn/bysj/20231214110037.png)

![image-20231214110054730](http://image.javatip.cn/bysj/20231214110054.png)

![image-20231214110117620](http://image.javatip.cn/bysj/20231214110117.png)

![image-20231214110805472](http://image.javatip.cn/bysj/20231214110805.png)
