## 208SpringBoot风景推荐系统

### 一、项目介绍

项目地址：http://javatip.cn/store/119.html

风景推荐系统基于SpringBoot+Mybatis进行开发，系统分为前台和后台.

前台功能如下：

- 风景浏览
- 风景搜索
- 收藏
- 点赞
- 我的收藏
- 意见反馈
- 消息通知

后台功能如下：

- 用户管理
- 消息发布
- 意见管理
- 风景分类管理
- 风景管理

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
7. 启动运行，后台访问地址 `http://localhost:8080` 。管理员账号密码 system/123456，前台访问地址 `http://localhost:8080/web`  顾客账号密码 yaoge/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230718144209735](http://image.javatip.cn/bysj/20230718144210.png)

![image-20230718144235856](http://image.javatip.cn/bysj/20230718144235.png)

![image-20230718144253008](http://image.javatip.cn/bysj/20230718144253.png)

![localhost](http://image.javatip.cn/bysj/20230718144344.png)

![image-20230718144437991](http://image.javatip.cn/bysj/20230718144438.png)
