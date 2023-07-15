# The MySQL Class - Lesson 1
## Create at 2023.07.14

## 基本語法
|  Syntax        |  Explain      | example  |
| :------------- |:-------------|:--------
| CREATE DATABASE        | 創建資料庫      | CREATE DATABASE \`資料庫名稱\`;  |
| USE        | 使用資料庫      | USE \`資料庫名稱\`; |
| CREATE TABLE | 創建表格 | CREATE TABLE \`表格名稱\`{  ....   }; |
| DROP TABLE | 刪除表格 | DROP TABLE \`表格名稱\`;|
| ALTER TABLE | 更改表格 | ALTER TABLE \`表格名稱\`... ;|

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

##  ALTER TABLE
### 針對已存在的資料表進行變更

### 增加欄位(ADD COLUMN)
#### 語法
#### ALTER TABLE table_name ADD column_name datatype;
#### 例子:將Exam表格加入type欄位
```mysql
ALTER TABLE `Exam` ADD `type` VARCHAR(20);
```
### 更改欄位資料型別 (ALTER COLUMN TYPE)
#### 語法
#### ALTER TABLE table_name ALTER COLUMN column_name datatype;
#### 例子:將Exam表格type欄位改成INT
```mysql
ALTER TABLE `Exam` ALTER COLUMN `type` INT;
```
### 刪除欄位 (DROP COLUMN)
#### 語法
#### ALTER TABLE table_name DROP COLUMN column_name;
#### 例子:將Exam表格type欄位刪除
```mysql
ALTER TABLE `Exam` DROP COLUMN `type`;
```

