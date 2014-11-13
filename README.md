# Code Snippets

Little pieces of code you just can’t remember

Feel free to make suggestions. The rule is that it is something you might use infrequently, that you’d normally Google but it’s often hard to find.

## PHP

### MySQL datetime

For use with [NOW()](http://dev.mysql.com/doc/refman/5.5/en/date-and-time-functions.html#function_now) in MySQL.

```php
date('Y-m-d H:i:s')
```

## MySQL

### Create new database

Create a new database (UTF-8)

```mysql
CREATE DATABASE mydb DEFAULT CHARACTER SET utf8 DEFAULT COLLATE utf8_unicode_ci;
```

Add a user with all privileges

```mysql
GRANT ALL PRIVILEGES ON `database_name`.* To 'user_name'@'localhost' IDENTIFIED BY 'password';
```
