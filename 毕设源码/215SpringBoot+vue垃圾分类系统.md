## 215SpringBoot+vue垃圾分类系统

### 一、项目介绍

项目地址：http://javatip.cn/store/139.html

垃圾分类系统基于SpringBoot+vue进行开发，系统分为前台和后台，后台主要进行数据管理，前台主要功能有垃圾分类介绍，公告等功能。下面是详细功能

后台主要功能：

- 个人中心
- 用户管理
- 分类管理
- 垃圾管理
- 垃圾统计
- 公告管理

前台主要功能

- 公告栏
- 垃圾分类
- 垃圾搜索
- 垃圾详情

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：vue，echarts，bootstrap

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application-druid.yml文件中将数据库账号密码改成自己本地的
6. 在application.yml文件中将redis信息修改成自己本地的，redis默认密码为空（需要启动redis）
7. 在idea中进入前台文件夹gc-ui。在idea底部打开**Terminal**，使用命令**cd gc-ui**，然后在输入命令**npm install** 下载依赖。等到进度条走完后输入命令 **npm run dev**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.22.12）。
8. 在idea中启动后台项目。管理员账号密码 system/123456。

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230721155734654](http://image.javatip.cn/bysj/20230721155735.png)

![image-20230721155801376](http://image.javatip.cn/bysj/20230721155801.png)

![image-20230721155812629](http://image.javatip.cn/bysj/20230721155812.png)

![image-20230721155832804](http://image.javatip.cn/bysj/20230721155833.png)
