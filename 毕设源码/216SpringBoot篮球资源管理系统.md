## 216SpringBoot篮球资源管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/140.html

篮球资源管理系统基于SpringBoot+Mybatis进行开发，主要用来记录篮球的相关信息。主要功能有：

管理员：

- 用户登录

- 用户管理
- 新闻管理
- 球队管理
- 球馆管理
- 球员管理
- 教练管理

普通用户：

- 新闻查看
- 球队产看
- 球馆查看
- 球员评分
- 教练查看

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 默认上传图片在**F:/upload/**，如果没有F盘，则替换项目中的`file.properties` 和 `AppFileUtils.java`文件中的地址
7. 启动运行，浏览器输入 `http://localhost:8080` 进行访问。管理员账号密码 system/123456。普通用户账号密码 xiaolan/123456

更多项目请访问 http://javatip.cn

### 四、项目项目

![image-20230721163450250](http://image.javatip.cn/bysj/20230721163450.png)

![image-20230721163803338](http://image.javatip.cn/bysj/20230721163803.png)

![image-20230721163821154](http://image.javatip.cn/bysj/20230721163821.png)

![image-20230721163835625](http://image.javatip.cn/bysj/20230721163835.png)

![](http://image.javatip.cn/bysj/20230721163846.png)

![image-20230721163912241](http://image.javatip.cn/bysj/20230721163912.png)
