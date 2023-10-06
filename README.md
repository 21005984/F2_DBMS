# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
# AIM:
To create a student database and execute DDL queries using SQL..
# DDL (Data Definition Language)
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
# List of DDL commands:
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.
# Query:
1) Create a table student with the following fieds rollno,name,age,address,phoneno.
# SQL QUERY:
~~~
create table studenttables1(rollnumber int,name char(30),age int,address char(30),cnumber int);
~~~
# OUTPUT:
![1](https://github.com/21005984/F2_DBMS/assets/94748389/7c46a3d9-3aab-4315-ac33-649b81f9dc1b)

2) Change the above student table by adding another attribute department
SQL QUERY:
~~~
insert into studenttables1 values (1,'MEI',19,'Ambur',8778441834);
insert into studenttables1 values (2,'VAISHU',18,'Banglalore',9994273887);
insert into studenttables1 values (3,'SHIVA',16,'Mumbai',9980796635);
insert into studenttables1 values (4,'DEEKSHA',15,'Delhi',7708224923);
~~~
# OUTPUT:

![2](https://github.com/21005984/F2_DBMS/assets/94748389/38cfe440-b32e-47e0-b9fb-22978c6c99ae)

3) Drop the student table
# SQL QUERY:
~~~
drop table studenttable;
~~~
# OUTPUT:

![3](https://github.com/21005984/F2_DBMS/assets/94748389/34db44d3-0abd-4fff-91d7-5958fda9087e)

4) Delete the student table using truncate keyword
# SQL QUERY:
~~~
truncate table myworld;
~~~
# OUTPUT:

![WhatsApp Image 2023-10-05 at 00 03 34_f4da88fb](https://github.com/21005984/F2_DBMS/assets/94748389/d74f2dc2-3a94-4399-99f9-0d82272ae219)

5) Rename the student table to mystudent
# SQL QUERY:
~~~
rename studenttables1 to myrecord
~~~
# OUTPUT:

![WhatsApp Image 2023-10-05 at 00 02 47_6c8b1c2b](https://github.com/21005984/F2_DBMS/assets/94748389/aa56c486-eece-4e9b-8c7e-284e3cfa974a)

# RESULT:
Creating a student table and executing the DDL queries using SQL was successfully executed.
