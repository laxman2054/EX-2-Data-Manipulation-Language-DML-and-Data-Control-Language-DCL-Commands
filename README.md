# EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands

# DATE:

# AIM:


To create a manager database and execute DML queries using SQL.




DML(Data Manupulation Language)


The SQL commands that deal with the manipulation of data present in the database belong to DML or Data

Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that

controls access to data and to the database. Basically, DCL statements are grouped with DML statements.

List of DML commands:


INSERT: It is used to insert data into a table.

UPDATE: It is used to update existing data within a table.

DELETE: It is used to delete records from a database table

Create the table as given below:


create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));

insert the following values into the table


insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John'); insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James'); insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL); insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');


Q1) Update all the records of manager table by increasing 10% of their salary as bonus.


QUERY:

![image](https://github.com/laxman2054/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118680826/ddad8475-611d-41c6-b459-a52f9d552f80)

OUTPUT:


![image](https://github.com/laxman2054/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118680826/1f93a274-2f8c-4f89-ab34-9ee71f1645ed)


Q2) Delete the records from manager table where the salary less than 2750.


QUERY:


![image](https://github.com/laxman2054/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118680826/a86a5e66-e8a5-4e5b-90bb-14f1959458cd)



![image](https://github.com/laxman2054/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118680826/a5dee670-fa84-4aa3-87d7-10b8114aa898)


Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


QUERY:


![image](https://github.com/laxman2054/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118680826/3d5bc628-1552-4a37-9b12-bc3c34ac3c44)



OUTPUT:

![image](https://github.com/laxman2054/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118680826/4f101672-281c-4c98-a180-c7b3ad0f7bc8)


Q5) List the names of Clerks from emp table.



QUERY:



![image](https://github.com/laxman2054/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118680826/c380bef5-92f9-4861-94cd-101f3e67f7d7)



Q14) Find maximum, minimum and average salary in EMP table.


QUERY:


![image](https://github.com/laxman2054/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118680826/48fd4a5e-3a78-4861-b725-ec11abf6bb94)




OUTPUT:



![image](https://github.com/laxman2054/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118680826/444ea237-259b-4495-a5d1-6676db449c50)



Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.




QUERY:




![image](https://github.com/laxman2054/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118680826/23e1b6c0-248c-46f9-a91d-9bd3d961bb53)




OUTPUT:



![image](https://github.com/laxman2054/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118680826/3955b2d1-7669-4e8d-aceb-6fa19b2a0ae3)


# RESULT : THUS, THE OUTPUT IS VERIFED SUCCESFULLY.












































