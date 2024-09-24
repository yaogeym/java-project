## 409SpringBoot客户管理系统（含论文）

### 一、项目介绍

项目地址：http://javatip.cn/store/342.html

客户作为企业发展的核心资源，其管理和维护成为企业能否在市场中保持竞争力的关键因素之一。传统的客户管理方式，如纸质档案记录、人工跟踪等，已难以满足现代企业对于高效、精准、实时性的需求。因此，开发一套科学、系统、自动化的客户管理系统显得尤为重要。

客户管理系统是基于SpringBoot开发的，系统分为管理员和销售员两种角色，销售员负责跟进客户，管理员负责数据统计分析。具体角色功能如下：

管理员：

- 用户管理
- 客户管理
- 跟进信息管理
- 企业成交统计
- 个人成交统计
- 跟进阶段统计
- 跟进客户统计
- 跟进记录统计

销售员：

- 客户管理
- 客户跟进

### 二、技术框架

- 后端：SpringBoot，mybatis
- 前端：layui，jquery，thymeleaf

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application.yml中将数据库账号密码改成自己本地的
6. 系统的静态资源存储在F盘，如果你的电脑没有F盘，则需要改成其他盘，具体位置在file.properties和FileConfig.java两个文件，将文件里面的F:/upload 改成你本地的即可。
7. 后台启动运行

>访问地址：http://localhost:8080，管理员账号密码：system/123456，普通用户账号密码：15000000000/123456


更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20240726151554729](http://image.javatip.cn/bysj/20240726151554.png)

![image-20240726151134242](http://image.javatip.cn/bysj/20240726151134.png)

![image-20240726151328291](http://image.javatip.cn/bysj/20240726151328.png)

![image-20240726151207333](http://image.javatip.cn/bysj/20240726151207.png)

![image-20240726151150241](http://image.javatip.cn/bysj/20240726151150.png)

![image-20240726151226526](http://image.javatip.cn/bysj/20240726151226.png)
