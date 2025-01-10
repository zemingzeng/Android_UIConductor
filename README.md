# Android_UIConductor
一些杂乱命令
下载：https://github.com/google/android-uiconductor
可用prebuild和自己编译（略微麻烦）
sudo systemctl status mysql.service
sudo systemctl enable mysql
sudo systemctl start mysql
systemctl restart mysql
sudo systemctl stop mysql
harmandb—>1qaz
root---->PKCxZkqBA5ihoIxS
show databases;
show tables;
select user from mysql.user;
sudo mysql -u root -p
alter user ‘harmandb’@‘localhost’ IDENTIFIED By ‘1qaz’;
flush privileges;
use database;
/var/lib/mysql
SHOW GRANTS FOR ‘harmandb’@‘localhost’;
GRANT ALL PRIVILEGES ON . TO ‘harmandb’@‘host’;
CREATE USER ‘newuser’@‘localhost’ IDENTIFIED BY ‘password’;
sudo cat /etc/mysql/mysql.conf.d/mysqld.cnf ====> [mysqld] : grant-tables = ON
select database();
安装mysql:
sudo apt install mysql-client-core-8.0
sudo apt install mariadb-client-core-10.6
sudo apt install mysql-server
