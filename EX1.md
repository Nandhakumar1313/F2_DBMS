# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

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
```sql
 create table student(
  rollno char(5),
  name varchar(20),
  age char(5),
  address varchar(100),
  phoneno char(15));
```

### OUTPUT:
![dbms 1 1](https://github.com/Nandhakumar1313/F2_DBMS/assets/120230694/a2317095-cb24-4f7c-8400-ead3d22b1455)
### 2) Change the above student table by adding another attribute department


### SQL QUERY: 
```sql
ALTER TABLE student
ADD department varchar(30);
```
### OUTPUT:
![dbms 1 2](https://github.com/Nandhakumar1313/F2_DBMS/assets/120230694/cdebf59a-f67e-44c8-ad5c-b01d67404a98)


### 3) Drop the student table
 
### SQL QUERY: 
```sql
 drop table student;
```
### OUTPUT:
![dbms 1 3](https://github.com/Nandhakumar1313/F2_DBMS/assets/120230694/f30b3fd5-699c-4beb-af66-57b100d10ffc)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
 truncate table student;
```

### OUTPUT:

![dbms 1 4](https://github.com/Nandhakumar1313/F2_DBMS/assets/120230694/d29504ac-69d4-41aa-9051-903ab85de396)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
 ALTER TABLE student
  RENAME to mystudent;
```

### OUTPUT:
![dbms 1 5](https://github.com/Nandhakumar1313/F2_DBMS/assets/120230694/28a9507c-fbf6-4fff-bf7f-692493d3593d)

### RESULT:
hence successfully created a student database and execute DDL queries using SQL.
