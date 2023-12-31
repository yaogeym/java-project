## 200SpringBoot薪资管理系统

### 一、项目介绍

项目地址：http://javatip.cn/store/105.html

薪资管理系统是一个基于企业与员工关系的信息分享、传播、获取各种信息发布相结合的平台。企业能够通过该平台实现对员工薪酬进行合理的管理。同时，员工通过改平台进行考勤、请假。在工资结算后查看自己的工资情况。
为了数据的安全性考虑，本系统采用shiro安全框架进行数据权限的划分，及数据安全的保护。
本系统分为三个角色，分别为普通用户、财务人员及领导。三种角色分别拥有以下权限

- 领导
    - 部门管理
    - 员工管理
    - 角色管理
    - 岗位管理
    - 通知管理
    - 考勤查看
    - 请假审批
    - 工资条查看
- 财务人员
    - 薪资配置
    - 岗位薪资配置
    - 薪资核算
    - 考勤管理
    - 请假管理
    - 通知查看
    - 工资条查看
- 普通员工
    - 考勤管理
    - 请假管理
    - 通知查看
    - 工资条查看

除了上述功能外，三种角色都拥有更新个人信息及修改密码等系统通用功能。

### 二、技术框架

- 后端：SpringBoot，Mybatis
- 前端：bootstrap

### 三、安装教程

1. 用idea打开项目
2. 在idea中配置jdk环境
3. 配置maven环境并下载依赖
4. 新建数据库，导入数据库文件
5. 在application-druid.yml文件中将数据库账号密码改成自己本地的
6. 启动运行，浏览器输入 `http://localhost:8080` 即可访问。
    系统用户账号密码：
    - 领导： 账号：mayun  密码：123456
    - 财务： 账号：zhaona  密码：123456
    - 普通员工： 账号：liuneng  密码：123456

更多项目请访问 http://javatip.cn

### 四、项目截图

![image-20230712222522571](http://image.javatip.cn/bysj/20230712222523.png)

![image-20230712222814523](http://image.javatip.cn/bysj/20230712222814.png)

![image-20230712222833787](http://image.javatip.cn/bysj/20230712222833.png)

![image-20230712222854946](http://image.javatip.cn/bysj/20230712222855.png)

![image-20230712222612827](http://image.javatip.cn/bysj/20230712222612.png)

![image-20230712222558216](http://image.javatip.cn/bysj/20230712222558.png)

![image-20230712222722654](http://image.javatip.cn/bysj/20230712222722.png)

![image-20230712222745114](http://image.javatip.cn/bysj/20230712222745.png)
