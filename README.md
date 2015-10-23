# change-password-of-your-WAMP
how to change password of your WAMP
<br>use your MMC of mysql.
<br>input Ent
<br>input use mysql
<br>input update user set password=PASSWORD('yourpassword') where user='root';
<br>flush privileges;
<br>quit
