## 325SpringBoot业余足球队评价管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/205.html

业余足球队评价管理系统基于SpringBoot+Mybatis开发，系统分为管理员和球员两种角色。

管理员：

- 球队管理
- 入队审批
- 球员数据查看
- 球员画像
- 对内排行榜

- 球队数据管理

球员：

- 注册登录
- 申请入队
- 比赛数据添加
- 球员画像

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
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456 ，球员账号密码 mx/123456。

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230809164109071](http://image.javatip.cn/bysj/20230809164109.png)

![image-20230809163942950](http://image.javatip.cn/bysj/20230809163943.png)

![image-20230809164012260](http://image.javatip.cn/bysj/20230809164012.png)

![image-20230809164032568](http://image.javatip.cn/bysj/20230809164032.png)

![image-20230809164047027](http://image.javatip.cn/bysj/20230809164047.png)

![image-20230809164137441](http://image.javatip.cn/bysj/20230809164137.png)
