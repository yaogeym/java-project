## 125SpringBoot教室预约管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/138.html

教室预约管理系统使用SpringBoot+Mybatis进行开发，系统整体分为前台和后台，后台主要对教室，用户等信息进行管理，前台总共分为学生、教室、辅导员、楼长四种角色，通过预约教室，多层审批完成教室预约功能。系统详细功能如下

后台功能：

- 用户管理
- 教学楼管理
- 教室管理
- 审批查询
- 班级管理

前台功能：

- 学生
    - 教室预约
    - 个人中心
    - 留言

- 教师
    - 教师预约
    - 个人中心
    - 留言
- 辅导员
    - 审批
    - 个人中心
- 楼长
    - 审批
    - 个人中心
    - 留言板

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：jquery

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 启动运行，浏览器输入 `http://localhost:8080` 进行访问。

```
后台管理员账号密码: admin/123456
前台学生账号密码：xx/123456
前台教师账号密码：lyc/123456
前台辅导员账号密码：zs/123456
前台楼长账号密码：wm/123456
```

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230721151012695](http://image.javatip.cn/bysj/20230721151012.png)

![image-20230721151025659](http://image.javatip.cn/bysj/20230721151025.png)

![image-20230721151043270](http://image.javatip.cn/bysj/20230721151043.png)

![image-20230721151127832](http://image.javatip.cn/bysj/20230721151127.png)

![image-20230721151150815](http://image.javatip.cn/bysj/20230721151150.png)

![image-20230721151216050](http://image.javatip.cn/bysj/20230721151216.png)
