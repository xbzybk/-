# **鲨鱼云网盘系统**<br>
## 使用PHP搭建，不是基于thinkphp搭建的，纯手工打造<br>
## 第一版即为最后一版，后期不更新，测试过了没有BUG<br>
## BUG联系邮箱：sy@itsha.xyz<br>
### 搭建教程及建议：<br>
#### ①解压源码，将根目录下的“数据库.sql”导入进数据库<br>
#### ②更改根目录下“includes/db.php”文件中的数据库的信息<br>
#### ③更改根目录下“public/includes/db.php”文件中的数据库的信息<br>
#### ④PHP7.3<br>
#### ⑤直接访问网站注册一个自己的账号，注册完后进入数据库，在数据库中找到表users，并找到直接账号的那条数据，把is_admin原本的0改成1，改的那个用户就是管理员了，访问你的域名/admin进入后台输入管理员的账号和密码就可以了<br>
#### ⑥可以在后台更改网站配置<br>
#### ⑦可以更改管理员的文件夹名称，例如admin改成Shark，增强安全性<br>
