## 提示
该项目无法正常运行，由于当时数据库部署的机器已经被收回，本地备份也丢失，所以如果要运行可以自己尝试搭一下数据库。
## 项目简介
和朋友一起构思的一个项目，是一个银行管理系统。目前做了用户界面，员工界面与管理员界面这三个部分，实现了基本的银行业务的功能。项目中包含了众多的前后端交互，数据的及时跟新。
## 页面结构
- 登录页面（login.html）
- 员工端界面
 - 注册（register.html）
 - 登录成功后的主页（user_main.html）
    - 电子银行导航栏内容
    - 存款及银行卡导航栏内容
       - 存款业务介绍子页面（storage-server.html）
       - 存款利率子页面（storage-rate.html）
       - 预约开户子页面（open-account.html）
    - 投资理财导航栏内容
    - 信用卡导航栏内容
- 员工端页面（employee_main.html）
 - 贷款业务
    - 贷款审批（loaning-approval.html）
       - 审批页面（audit.html）
    - 贷款产品资料填写（loaning-product.html）
    - 贷款归还业务说明（loaning-back.html）
 - 储存业务
    - 存取钱及转账（save-draw-transfer.html）
    - 账号管理（account-manage.html）
       - 新开卡（open-account.html）
       - 修改密码（modify-password.html）
- 系统管理员
 - 主页（manage_main.html）
    - 角色管理
       - 修改密码（manage-modify-password.html）
       - 添加功能（add-role.html）
    - 储存利率管理子页面（manage-storage-rate.html）
    - 贷款利率管理子页面（manage-loan-rate.html）

## 使用
- 克隆：git clone https://github.com/Mrdouhua/BankSystem016.git
- 使用tomcat运行项目
- 浏览器输入网址：http://localhost:8080/BankSystem_16/
 - 登录客户端，用户名：guess；密码：1234567
 - 登录员工端，用户名：clerk；密码：1234567
 - 登陆管理员端，用户名：admin；密码：1234567
