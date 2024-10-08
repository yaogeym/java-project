## 405SpringBoot+vue交通信息查询系统

### 一、项目介绍

项目地址：http://javatip.cn/store/337.html

交通信息查询系统可以通过收集、分析和管理交通信息，系统可以帮助城市规划更有效的交通流动，减少拥堵，提高道路利用率。该系统可以监测交通事故和违规行为，及时发出警报，以减少交通事故和增加道路安全。交通信息管理系统可以提供实时交通信息，帮助人们规划最佳出行路线，提高出行的便利性和效率。

交通信息查询系统是由SpringBoot+vue开发的前后端分离的项目，系统分为管理员、交警和普通用户三种角色。系统为普通用户提供了注册功能，管理员进行数据管理、添加科普知识、录入违章信息，普通用户进行违章缴费等，具体角色及功能如下：

管理员：

- 个人中心
- 用户管理
- 科普知识管理
- 违章制度管理
- 罚单管理
- 工作安排
- 人员调配管理

交警：

- 个人中心
- 工作安排查看
- 人员调配查看

普通用户：

- 用户注册
- 个人中心
- 科普知识学习/点赞
- 违章制度查看
- 罚单缴费

### 二、技术框架

- 后端：SpringBoot，mybatis
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 安装nodejs环境
7. 在idea中用新窗口打开前端项目，使用`npm install`命令，本机测试nodejs版本为（v12.22.12）
8. 下载完成后输入启动命令启动前台项目，`npm run serve`
9. 后台启动运行

>管理员账号密码：system/123456，交警账号密码：jj/123456，普通用户账号密码：wm/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240725111539231](http://image.javatip.cn/bysj/20240725111539.png)

![image-20240725111435267](http://image.javatip.cn/bysj/20240725111435.png)

![image-20240725111503664](http://image.javatip.cn/bysj/20240725111503.png)

![image-20240725111520480](http://image.javatip.cn/bysj/20240725111520.png)

![image-20240725111557279](http://image.javatip.cn/bysj/20240725111557.png)

![image-20240725111616142](http://image.javatip.cn/bysj/20240725111616.png)
