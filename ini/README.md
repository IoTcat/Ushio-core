## 步骤



## 用户管理
 - `sudo su` 切换到root
 - `passwd` 设置root密码
 - `adduser yimian`, `passwd yimian` 设置yimian账户，密码
 - `vi /etc/ssh/sshd_config` 更改`PasswordAuthentication`为 `yes`
 - `adduser tomato`, `passwd tomato` 设置tomato账户，密码
 - git同步ushio-core.git到home
 - `git config --global user.name ushio`
 - `git config --global user.email i@iotcat.me`
 
## 
 
 - 在/etc/nginx.conf中添加`include /ushio-core/conf/nginx.conf`
