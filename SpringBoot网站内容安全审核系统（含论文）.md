## 421SpringBoot网站内容安全审核系统（含论文）

### 一、项目介绍

项目地址：http://javatip.cn/store/809.html

网站内容安全审核系统是基于SpringBoot开发的，拟采用基于百度人工智能的文本内容安全审核技术，利用Java语言和MySQL数据库技术，实现网络文本内容的自动审核。本系统通过爬取网易新闻的内容做为基础数据，系统每次启动时将去爬取网易新闻数据进行存库。主要包括如下功能：

#### 第一

开发一个社交网络平台的网络爬虫和社区文本采集系统，利用数据库技术实现网页和信息的存储和查询。

#### 第二

完成基于百度人工智能技术的文本内容审核SDK的调用和集成，实现准确快速输出各种文本属于迷信、色情、暴力、反动和其他非法信息的概率，有效鉴别不良信息。

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

>访问地址：http://localhost:8080，管理员账号密码：system/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240807143658943](http://image.javatip.cn/bysj/20240807143659.png)

![image-20240807142117645](http://image.javatip.cn/bysj/20240807142117.png)

![image-20240807142134230](http://image.javatip.cn/bysj/20240807142134.png)
