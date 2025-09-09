## 101SpringBoot仓库管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/86.html

仓库管理系统基于SpringBoot+Mybatis开发，系统使用shiro框架做权限安全控制，超级管理员登录系统后可根据自己的实际需求配角色，然后新建用户选择角色即可。

超级管理员功能如下：

- 客户管理
- 供应商管理
- 商品管理
- 商品进货
- 商品销售
- 退货查询
- 系统管理
    - 部门管理
    - 菜单管理
    - 角色管理
    - 权限管理
    - 用户管理
- 公告管理
- 系统日志

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
7. 启动运行，访问 http://localhost:8080  , 管理员账号密码 admin/123456 ,普通用户账号密码 user/123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230710112044231](http://image.javatip.cn/bysj/20230710112044.png)

![image-20230710112110485](http://image.javatip.cn/bysj/20230710112110.png)

![image-20230710112126831](http://image.javatip.cn/bysj/20230710112126.png)

![image-20230710112151742](http://image.javatip.cn/bysj/20230710112151.png)

![image-20230710112212479](http://image.javatip.cn/bysj/20230710112212.png)

![image-20230710112228455](http://image.javatip.cn/bysj/20230710112228.png)

![image-20230710112247117](http://image.javatip.cn/bysj/20230710112247.png)
