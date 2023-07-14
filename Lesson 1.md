# The MySQL Class - Lesson 1

| Syntax        |  Explain      | example  |
| :------------- |:-------------|:--------
| CREATE DATABASE        | 創建資料庫      | CREATE DATABASE \`資料庫名稱\`;  |
| USE        | 使用資料庫      | USE \`資料庫名稱\`; |
| CREATE TABLE | 創建表格 | CREATE TABLE \`表格名稱\`{  ....   }; |
| DROP TABLE | 刪除表格 | DROP TABLE \`表格名稱\`;|

## Create the Database
```mysql
-- CREATE DATABASE `資料庫名稱`
CREATE DATABASE `Company`;
```

## Use the Database
```mysql
-- USE`資料庫名稱`
USE `Company`;
```
## Create Table
```mysql
-- CREATE TABLE
CREATE TABLE `Exam`
{
  `id` INT,
  `Name` VARCHAR(20),
  `score` INT
};
```
## Delete Table
```mysql
-- CREATE TABLE
DROP TABLE `Exam`;

```
