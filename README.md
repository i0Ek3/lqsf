# lqsf

> Please read it in reverse.

Use SQL easily after learning it.

## Install & Run SQL

- Download MySQL and install it, link: [https://dev.mysql.com/downloads/mysql/](https://dev.mysql.com/downloads/mysql/)
- or use command: `brew install mysql`
- Run it: `sudo mysql -u root -p`

## Usage


```
$ mysql -uroot -p < init-test-data.sql

mysql> show databases;
mysql> show tables from test;

```

## YSK

- Do not use business related fields as primary key
    - Use BIGINT or GUID type
- Use `ADD INDEX index_name (name)` to create index for colunm name
    - Use `ADD UNIQUE INDEX uni_name (name)` or `ADD CONSTRAINT uni_name UNIQUE (name)` 

## Credit

[https://www.liaoxuefeng.com](https://www.liaoxuefeng.com).
