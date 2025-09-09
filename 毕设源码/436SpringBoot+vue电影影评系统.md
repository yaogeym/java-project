## 436SpringBoot+vue电影影评网站

### 一、项目介绍

项目地址：http://javatip.cn/store/840.html

电影影评网站是由SpringBoot开发的电影推荐评价系统，系统分为用户前台和管理员后台。

前台：

- 注册登录
- 首页
- 电影查看
- 电影评论
- 电影评分
- 电影收藏
- 资讯查看
- 个人中心

后台：

- 用户管理
- 电影分类管理
- 电影管理
- 电影评分管理
- 资讯管理
- 系统管理

### 二、技术框架

- 后端：SpringBoot，mybatis
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开项目（前端vue已经打包至项目中，不用单独启动）
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 找到**FileController**，大概第75行的位置，将 **D:\\springboot6n498\\**路径替换为你本地的项目存放**根路径**，路径中不要使用中文
7. 启动后台运行

>前台和后台分别使用两个浏览器进行访问，同一个浏览器访问可能会造成token失效
>
>后台路径地址：http://localhost:8080/springboot6n498/admin/dist/index.html  账号密码：admin/123456
>前台路径地址：http://localhost:8080/springboot6n498/front/dist/index.html  员工账号密码：ym/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20241016165232892](http://image.javatip.cn/bysj/20241016165233.png)

![image-20241016165224589](http://image.javatip.cn/bysj/20241016165224.png)

![image-20241016165211522](http://image.javatip.cn/bysj/20241016165211.png)

![image-20241016165258398](http://image.javatip.cn/bysj/20241016165259.png)

![image-20241016165311671](http://image.javatip.cn/bysj/20241016165311.png)