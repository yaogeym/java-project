## 207SpringBoot车牌识别系统

### 一、项目介绍

项目地址：http://javatip.cn/store/118.html

车牌识别基于SpringBoot+Mybatis进行开发，通过ocr技术将车牌照片识别出车牌号码及颜色，功能分别如下：

管理员：

- 登录
- 车牌上传
- 车牌识别

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 默认上传图片在**F:/upload/**，如果没有F盘，则替换项目中的`file.properties` 和 `AppFileUtils.java` 和 `PlateController.java`文件中的地址
7. 启动运行，浏览器输入 `http://localhost:8080` 进行访问。管理员账号密码 system/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230718140523732](http://image.javatip.cn/bysj/20230718140524.png)

![image-20230718140545974](http://image.javatip.cn/bysj/20230718140546.png)

![image-20230718140559703](http://image.javatip.cn/bysj/20230718140559.png)
