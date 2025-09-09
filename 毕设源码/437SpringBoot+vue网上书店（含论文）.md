## 437SpringBoot+vue网上书店（含论文）

### 一、项目介绍

项目地址：http://javatip.cn/store/823.html

图书商城系统是基于SpringBoot+vue开发的前后端分离的项目。后台进行图书数据管理，前台进行书籍购买，同时后台也开通了用户权限，用户可以登录后台进行订单信息的维护。

管理员功能如下：

- 用户管理
- 书籍分类管理
- 书籍管理
- 库存预警
- 轮播图管理
- 新闻资讯管理
- 订单管理
- 发货信息管理

用户功能如下：

- 注册登录
- 书籍浏览
- 书籍查找
- 新闻查看
- 书籍收藏
- 购买
- 评价

### 二、技术框架

- 后端：SpringBoot，mybatis
- 前端：vue，elementui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 将压缩包中的`upload`文件夹移动到F盘下（如果没有F盘，移动到其他盘也可以，需要修改application.yml文件中的上传路径，与你的实际盘符一致）
7. 安装nodejs环境（测试node版本为v12.22.12）
8. 在idea中打开前端项目，使用`npm install`命令，下载依赖
9. 下载完成后输入启动命令启动前台项目，`npm run serve`
10. 后台启动运行

>前台地址：http://localhost:8080/book/index.html，账号密码：wm /123456
>
>后台地址：http://localhost:8081，管理员账号密码：admin / 123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240329113425260](http://image.javatip.cn/bysj/20240329113432.png)

![image-20240329113453226](http://image.javatip.cn/bysj/20240329113453.png)

![image-20240329113507568](http://image.javatip.cn/bysj/20240329113507.png)

![image-20240329113525399](http://image.javatip.cn/bysj/20240329113525.png)

![image-20240329113544055](http://image.javatip.cn/bysj/20240329113544.png)

![image-20240329113620499](http://image.javatip.cn/bysj/20240329113620.png)

![image-20240329113640021](http://image.javatip.cn/bysj/20240329113640.png)

![image-20240329113557256](http://image.javatip.cn/bysj/20240329113557.png)

![image-20240329113654784](http://image.javatip.cn/bysj/20240329113654.png)