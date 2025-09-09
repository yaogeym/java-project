## 220SpringBoot采购管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/149.html

采购管理系统基于SpringBoot+Mybatis开发，系统使用shiro框架做权限安全控制，系统分为管理员，仓库人员，采购人员三种角色。

管理员功能如下：

- 部门管理
- 用户管理

- 供应商管理
- 采购单管理
- 入库管理
- 物料管理
- 库存查询

仓库人员：

- 供应商管理
- 采购单查询
- 入库管理
- 物料查询
- 库存查询

采购人员：

- 供应商管理
- 采购单管理
- 入库查询
- 物料查询
- 库存查询

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：layui

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml文件中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 system/123456 ,仓库人员账号密码 cangguan/123456，采购人员账号密码 caiguan/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230725104437140](http://image.javatip.cn/bysj/20230725104437.png)

![image-20230725104610080](http://image.javatip.cn/bysj/20230725104610.png)

![image-20230725104901901](http://image.javatip.cn/bysj/20230725104902.png)

![image-20230725104917410](http://image.javatip.cn/bysj/20230725104917.png)

![image-20230725104954281](http://image.javatip.cn/bysj/20230725104954.png)
