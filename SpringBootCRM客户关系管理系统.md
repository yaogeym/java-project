## 171SpringBoot客户关系管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/290.html

客户关系管理系统使用SpringBoot+Mybatis进行开发，系统可以分为管理员，经理和销售人员三种角色，用户赋予对应的角色则获得访问对应菜单的权限。

管理员主要功能如下：

- 部门管理
- 销售目录管理
- 用户管理
- 权限管理
- 客户管理
- 订单列表
- 报表统计
- 销售与客户分析
- 销售与失败分析

经理：

- 销售目录管理
- 客户管理
- 订单列表
- 报表统计
- 销售与客户分析
- 销售与失败分析

销售：

- 销售目录管理
- 客户管理
- 订单管理
- 报表统计

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：jquery，layui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 启动运行，前台访问地址 http://localhost:8080  销售人员账号密码：wm/123456，经理账号密码：张富贵/123456，管理员账号密码：admin/123456，

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240102144803341](http://image.javatip.cn/bysj/20240102144844.png)

![image-20240102145231813](http://image.javatip.cn/bysj/20240102145231.png)

![image-20240102145207840](http://image.javatip.cn/bysj/20240102145208.png)

![image-20240102152158550](http://image.javatip.cn/bysj/20240102152158.png)

![image-20240102152141346](http://image.javatip.cn/bysj/20240102152141.png)
