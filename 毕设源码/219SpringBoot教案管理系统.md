## 219SpringBoot教案管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/147.html

教案管理系统基于SpringBoot+Mybatis进行开发，系统通过java爬虫来爬取”数睿思“网站的数据做为基础数据，然后将这些数据归类整理，供老师作为教案使用。系统分为管理员，老师，学生三个角色。。

管理员：

- 用户管理
- 公告管理
- 分类管理
- 资源库管理
- 资源爬取
- 数据统计（饼图、柱状图等）

老师：

- 学生管理
- 分类管理
- 教案选择

学生：

- 教师关注
- 查看教师教案
- 取消关注

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui，jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 默认上传图片在**F:/upload/**，如果没有F盘，则替换项目中的`file.properties` 和 `AppFileUtils.java`文件中的地址
7. 启动运行，浏览器输入 `http://localhost:8080` 进行访问。管理员账号密码 system/123456。老师账号密码 wls/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230724212527055](http://image.javatip.cn/bysj/20230724212527.png)

![image-20230724212850150](http://image.javatip.cn/bysj/20230724212850.png)

![image-20230724212945780](http://image.javatip.cn/bysj/20230724212945.png)

![image-20230724213105591](http://image.javatip.cn/bysj/20230724213105.png)

![管理员](http://image.javatip.cn/bysj/20230724213121.png)

![老师](http://image.javatip.cn/bysj/20230724213132.png)

![学生](http://image.javatip.cn/bysj/20230724213137.png)
