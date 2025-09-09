## 316SpringBoot热点新闻监控分析系统

### 一、项目介绍

项目地址：http://javatip.cn/store/193.html

热点新闻监控分析系统基于SpringBoot+Mybatis开发，项目每次启动的时候，爬虫会去爬取网易新闻首页的热点内容，进行解析存库，然后通过标签分析内容种类。

主要功能如下：

- 新闻爬取
- 新闻管理
- 新闻查看
- 新闻分类统计
- 新闻爬取趋势统计

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
7. 启动运行，访问 http://localhost:8080  , 账号密码 system/123456 

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230804152452170](http://image.javatip.cn/bysj/20230804152452.png)

![image-20230804152407241](http://image.javatip.cn/bysj/20230804152407.png)

![image-20230804152419676](http://image.javatip.cn/bysj/20230804152419.png)

![image-20230804152430967](http://image.javatip.cn/bysj/20230804152431.png)
