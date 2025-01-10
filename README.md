# Android_UIConductor
一些杂乱命令
1. 下载：https://github.com/google/android-uiconductor
2. 可用prebuild和自己编译（略微麻烦）
3. sudo systemctl status mysql.service
4. sudo systemctl enable mysql
5. sudo systemctl start mysql
6. systemctl restart mysql
7. sudo systemctl stop mysql
8. harmandb—>1qaz
9. root---->PKCxZkqBA5ihoIxS
10. show databases;
11. show tables;
12. select user from mysql.user;
13. sudo mysql -u root -p
14. alter user ‘harmandb’@‘localhost’ IDENTIFIED By ‘1qaz’;
15. flush privileges;
16. use database;
17. /var/lib/mysql
18. SHOW GRANTS FOR ‘harmandb’@‘localhost’;
19. GRANT ALL PRIVILEGES ON . TO ‘harmandb’@‘host’;
20. CREATE USER ‘newuser’@‘localhost’ IDENTIFIED BY ‘password’;
21. sudo cat /etc/mysql/mysql.conf.d/mysqld.cnf ====> [mysqld] : grant-tables = ON
22. select database();
23. 安装mysql:
24. sudo apt install mysql-client-core-8.0
25. sudo apt install mariadb-client-core-10.6
26. sudo apt install mysql-server
