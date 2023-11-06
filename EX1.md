# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
##Date:4/8/23 
## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```
### OUTPUT:
![1](https://github.com/selva258963/G2_DBMS/assets/121961701/ac56f450-fb80-489c-95c5-91acad809cb9)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);

```
### OUTPUT:
![2](https://github.com/selva258963/G2_DBMS/assets/121961701/606c80af-32fc-4cb1-9a39-688b122f7a3f)


### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;

```
### OUTPUT:
![3](https://github.com/selva258963/G2_DBMS/assets/121961701/ce472bb5-ffc6-4236-92d3-18b185ac336e)


### 4) Delete the student table using truncate keyword
### SQL QUERY: 
```
truncate table student;

```
### OUTPUT:
![4](https://github.com/selva258963/G2_DBMS/assets/121961701/5467f897-54de-4c66-b3ed-0498eca5cb8f)

### 5) Rename the student table to mystudent
### SQL QUERY: 
```
alter table student rename to mystudent;

```
### OUTPUT:
![5](https://github.com/selva258963/G2_DBMS/assets/121961701/02804182-a0a4-4e90-b77a-d93b425fb35e)

### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
