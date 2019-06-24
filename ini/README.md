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
 - 配置github的ssh[a1](https://www.xuanfengge.com/using-ssh-key-link-github-photo-tour.html), [a2](https://ddnode.com/2015/04/14/git-modify-remote-responsity-url.html)
 
## 配置
 - `sh /home/ini/sh/ini.sh`
 
 
## 
 
 - 在/etc/nginx.conf中添加`include /ushio-core/conf/nginx.conf`
