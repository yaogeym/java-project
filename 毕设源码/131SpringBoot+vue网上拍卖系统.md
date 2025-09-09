## 131SpringBoot+vue网上拍卖系统

### 一、项目介绍

项目地址：http://javatip.cn/store/156.html

网上拍卖系统基于SpringBoot+vue进行开发，系统分为前台和后台，后台主要进行数据管理，总共有三个项目组成，一个后台接口，一个后台的前端页面，一个前台页面。

后台主要功能：

- 拍卖公告管理
- 拍卖会管理
- 标的管理
- 新闻资讯
- 新闻审核
- 用户管理
- 竞买人管理

前台主要功能

- 新闻查看
- 拍卖会
- 拍卖标的
- 竞标
- 拍卖公告
- 我的竞拍

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：vue，elementui

### 三、安装教程

1. 解压目录后，前台项目在front目录中，idea打开front目录，后台项目在back目录中，新开一个idea窗口打开back目录
2. 在后台idea中配置jdk环境
3. 在后台配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的

6. 在application.yml文件中将redis信息修改成自己本地的，redis默认密码为空（需要启动redis）

7. 在idea中进入前台文件夹front。在idea底部打开两个**Terminal**，分别进入两个子文件，然后分别输入命令**npm install** 下载依赖。等到进度条走完后在两个**Terminal**中分别输入命令 **npm run serve**启动前台项目（需要安装node环境，本机测试用的node版本为 v12.22.12）。

8. 后台管理员账号密码 admin/123456。前台账号密码 yao/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230726150817321](http://image.javatip.cn/bysj/20230726150817.png)

![image-20230726150853512](http://image.javatip.cn/bysj/20230726150853.png)

![image-20230726150907442](http://image.javatip.cn/bysj/20230726150907.png)

![image-20230726151027881](http://image.javatip.cn/bysj/20230726151028.png)

![image-20230726151124108](http://image.javatip.cn/bysj/20230726151124.png)
