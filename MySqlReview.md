# MySQL

## 1. Install

### 	Configuration path --> sudo vim ~/.bash_profile 

### 	Add to file --> PATH=$PATH:/usr/local/mysql/bin

### 	Save and start the configuration --> source ~/.bash_profile

## 2. Database

### 	Create database

```mysql
create database test;
```

### 	chose database

```mysql
use test;
```

### 	view database

```mysql
show databases;
```

## 3. SQL command classification

1. DQL

   Data query language (query statement with ```"select"``` keyword)

2. DML

   Data manipulation language (DML is used to add, delete and modify the data in the standard)

   ```mysql
   insert
   delete
   update
   ```

3. DDL

   The language of the data definition (mainly the structure of the operation table, not the data in the table)

   ```mysql
   create
   drop
   alter
   ```

4. TCL

   Transaction control language

   ```mysql
   commit
   rollback
   ```

5. DCL

   Data control language (authorize, revoke authority)

   ```mysql
   grant
   revoke
   ```

   



