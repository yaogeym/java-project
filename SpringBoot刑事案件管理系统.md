## 225SpringBoot刑事案件管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/161.html

刑事案件管理系统基于SpringBoot+Mybatis开发，系统分为管理员，普通用户，公安，检察院，法院五种角色。公安人员发布案件，将案件交给检察院，检察院审核认为构成犯罪的移交给法院，不构成犯罪的退回公安。法院公布最终案件结果。过程中公安、检察院和法院可以发布案件动态。

管理员功能如下：

- 用户管理
- 案件查看

公安：

- 案件动态管理
- 添加案件
- 发送案件

检察院：

- 案件动态管理
- 案件处理

法院：

- 案件动态管理
- 案件结果公布

普通用户

- 注册登录
- 案件查看

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456，公安账号密码 xiaogong/123456，检察院账号密码：xiaojian/123456，法院账号密码：xiaofa/123456，普通用户账号密码：xiaowang/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230727103251209](http://image.javatip.cn/bysj/20230727103251.png)

![image-20230727103227565](http://image.javatip.cn/bysj/20230727103234.png)

![image-20230727103346559](http://image.javatip.cn/bysj/20230727103346.png)

![image-20230727103557250](http://image.javatip.cn/bysj/20230727103557.png)

![image-20230727103614333](http://image.javatip.cn/bysj/20230727103614.png)
