# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
DATE: 11/8/23
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![loke2 update](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/6cef14f9-2824-434c-96fd-b0cc5d645f4d)


### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/f3713fce-4d6a-46b8-a109-f10cf900e828)


### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/ed7d9a09-680a-4459-9bc5-89436cf9a418)



### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/4ba227a7-4c8b-496b-9442-16f9278bbceb)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/e8193d45-0079-4d0c-abad-7f0d16d51698)


### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/5c8feb88-78b1-4671-b74f-3af978794aee)

### Q5)	List the names of Clerks from emp table.

### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/bf38d77e-b82c-4e1d-b075-4940c3daf35b)

### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/bf66448b-9acc-4af0-accd-6994d9d5e1a2)


### Q6)	List the names of employee who are not Managers.

### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/f4257de5-b998-42ab-983c-46c08150d40f)

### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/a3ea1628-607b-41df-b019-044b6a6a9108)

### Q7)	List the names of employees not eligible for commission.

### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/05a980e2-536b-459f-9072-5eb08c286f2f)

### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/5876441b-46c5-45e8-b65b-4bc4dd5417c8)

### Q8)	List employees whose name either start or end with ‘s’.
### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/94aef40f-1491-46d6-9942-af92f0f468b9)

### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/6e830eda-e9f7-42f8-9fbe-1b5d5e058c85)

### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.

### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/50460906-2d86-42c5-8aad-18f7fdd51c4f)

### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/c08ce8f6-586d-472e-9e9e-47c909a08fa0)


### Q10) List the Details of Employees who have joined before 30 Sept 81.

### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/1238c540-c727-4c2e-a741-b6d97be2a717)

### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/6b8dd390-75ba-4315-8c4f-266d8e9e1a14)


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.

### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/dfc0b7ba-9122-4286-a0bb-b554ad1fe028)

### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/7783c715-01da-4c19-ab74-1e9580259878)


### Q12) List the names of employees not belonging to dept no 30,40 & 10

### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/9941465d-2e79-4f29-9156-a3b95d3c7f95)

### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/bca28540-59ec-4578-a665-c81610c0bb18)

### Q13) Find number of rows in the table EMP

### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/0cc8cb19-20b3-45c3-8db3-a7831535e3cf)

### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/9d327e4a-abca-42ab-9bc7-acc3a860cf11)

### Q14) Find maximum, minimum and average salary in EMP table.
### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/565d7274-ed20-40ce-b5ff-e422e69e8497)
### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/65864b84-9045-454c-9dab-88939d4007f6)

### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.
### QUERY:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/0c6de8bd-fbbe-485b-b872-43292eae78a6)

### OUTPUT:
![image](https://github.com/lokesh-khanna/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119606216/92de47bd-8661-4c33-810a-1ae3ecb102ea)

### RESULT:
Executing DML queries using SQL was executed successfully.
