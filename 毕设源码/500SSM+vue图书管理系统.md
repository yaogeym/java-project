## 500SSM+vue图书管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/848.html

图书管理系统是由SSM和vue开发的前后端分离系统，用户在前台进行图书借阅，管理在后台对图书及分类管理。对用户的借阅和归还图书进行审核。

用户：

- 注册登录
- 首页
- 图书查看
- 公告查看
- 个人中i性能
- 图书借阅
- 图书归还

管理员：

- 读者管理
- 公告管理
- 分类管理
- 图书管理
- 借阅管理
- 归还管理
- 图书统计
- 借阅统计

### 二、技术框架

- 后端：Spring，SpringMVC，mybatis
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开项目（前端vue已经打包至项目中，不用单独启动，只需要运行library-system），单独启动也可以（单独运行则三个项目都需要运行）
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 下载Tomcat并在idea中配置Tomcat
5. 新建数据库，导入数据库文件
6. 在application.yml中将数据库账号密码改成自己本地的
7. 找到**FileController**，大概第60行的位置，将 **D:\\ssm1o9rw\\**路径替换为你本地的项目存放**根路径**，路径中不要使用中文
8. 启动后台运行

>前台和后台分别使用两个浏览器进行访问，同一个浏览器访问可能会造成token失效
>
>后台路径地址：http://localhost:8080/ssm1o9rw/admin/dist/index.html  账号密码：admin/123456
>前台路径地址：http://localhost:8080/ssm1o9rw/front/dist/index.html  读者账号密码：1001/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20250110155307587](http://image.javatip.cn/bysj/20250110155315.png)

![image-20250110155337559](http://image.javatip.cn/bysj/20250110155337.png)

![image-20250110155346930](http://image.javatip.cn/bysj/20250110155347.png)

![image-20250110155356729](http://image.javatip.cn/bysj/20250110155356.png)

![image-20250110155437458](http://image.javatip.cn/bysj/20250110155437.png)

![image-20250110155451558](http://image.javatip.cn/bysj/20250110155451.png)

![image-20250110155503253](http://image.javatip.cn/bysj/20250110155503.png)