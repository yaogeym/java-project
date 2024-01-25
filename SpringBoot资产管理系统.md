## 162SpringBoot资产管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/281.html

资产管理系统使用SpringBoot+Mybatis进行开发，系统分为管理员、经理和员工三种角色，管理员和经理数据权限一样。

经理主要功能如下：

- 用户管理
- 用户注册审批
- 资产管理
- 资产分类管理
- 资产申请审批
- 申请人一览
- 资产报废
- 不可用资产一览
- 各种资产占比
- 个人资产

员工：

- 用户查询
- 资产申请
- 资产归还
- 资产分类查询
- 申请人一览
- 资产报废
- 不可用资产一览
- 各种资产占比
- 个人资产

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：jquery，elementui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 启动redis服务，在application.yml文件中将redis相关信息改成本地的
7. 启动运行，浏览器输入 http://localhost:8080 进行访问，管理员账号密码：admin/123456，经理账号密码：zhangsan/123456，普通用户账号密码：guanyu/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20231221114037612](http://image.javatip.cn/bysj/20231221114037.png)

![image-20231221113836330](http://image.javatip.cn/bysj/20231221113836.png)

![image-20231221113804726](http://image.javatip.cn/bysj/20231221113804.png)

![image-20231221113749754](http://image.javatip.cn/bysj/20231221113749.png)

![image-20231221113553481](http://image.javatip.cn/bysj/20231231171025.png)
