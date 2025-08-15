# DBMS-LAB

## 1 [USE THE ORACLE SQL LOGIN](https://www.oracle.com/database/technologies/oracle-live-sql/)
## 2 [SRIT ORACLE SQL LOGIN SESSION](http://localhost:8080/apex/f?p=4550:1:1238993382107458)


# SQL ETHICS
1. ALL Keywords/Reserved Words must be Capital letters
2. ALL User-Defined Words must be small letters
3. Data Inside the database must be either any case.
4. Data Inside the database must follow business Rules.
   
## List of Experiments
[DBMS LAB_SYLLABUS](DBMS_LAB_SYLLABUS.pdf).

## WEEK1
1. Write SQL queries to CREATE TABLES for various databases using DDL commands (i.e. CREATE, ALTER, DROP, TRUNCATE).
2. Write SQL queries to MANIPULATE TABLES for various databases using DML commands (i.e. INSERT, SELECT, UPDATE, DELETE,).

## Links for Preparations

### DDL COMMANDS

- [CREATE TABLE](https://www.oracletutorial.com/oracle-basics/oracle-create-table/)
- [ALTER TABLE](https://www.oracletutorial.com/oracle-basics/oracle-alter-table/)
- [DROP TABLE](https://www.oracletutorial.com/oracle-basics/oracle-drop-table/)
- [TRUNCATE TABLE](https://www.oracletutorial.com/oracle-basics/oracle-truncate-table/)

### DML COMMANDS

- [INSERT](https://www.oracletutorial.com/oracle-basics/oracle-insert/)
- [SELECT](https://www.oracletutorial.com/oracle-basics/oracle-select/)
- [UPDATE](https://www.oracletutorial.com/oracle-basics/oracle-update/)
- [DELETE](https://www.oracletutorial.com/oracle-basics/oracle-delete/)

# WEEK1: DESIGN THE DATA BASE of the FOLLOWING
![DB1](DBD1.png)
![DB2](DBD3.png)
![DB3](DBD2.png)

## Do the following things for the above data base
1. CREATE TABLES OF THE ABOVE DataBase With Out Constraints [2M]
2. INSERT All Valuses inside the table. [2M]
3. Describe All Tables. [1M]
4. List the Created tables. [1M]
5. Display the Values of each table. [2M]
6. Delete All Tables [2M]
   
## Viva Voce [10 Marks] [Link](https://forms.gle/c6j46VGtdedejy2W9)

# WEEK-1 (COntinuation)
## Constraints for the above Database
1. Primary Key Constraints for the Following Attributes
   1. Student_number for student table
   2. Course_number for course table
   3. Section_idendifier for section table
   4. Student_number, Section_identifier for gradereport table
   5. Course_number, Prerequisite_number for prerequisite table
2. Foriegn Key Constraints for the Following Attributes
   1. Student_number for Grade_report Table
   2. Section_identifier for Grade_reoprt Table
   3. Course_number for prerequisite
3. Not Null Constraints for the following Attributes
   1. Major for Student table
   2. Credit_hrs for Course table
   3. Semester, Section for Section Table
   4. Grade for GradeReport
## Use the above Contraints to implement the following
   1. Implement the tables using above contraints
   2. Display the decription of each table
   3. Insert the values specified by the above database
   4. Display the instances of each table in the database
   5. All **branch** attribute in **student** table and Describe the table
   6. Copy **Major** attribure values into **branch** attribute and display it
   7. Remove the **Major** attribute in **Student**
   8. Change the name of **Course_number** to **cid** in **course** and describe it
   9. change the value of **credit-hrs** of *database* to *4* in **course**
   10. Put **NOT NULL** CONSTRAINT to column **branch** in student
   11. Replace the **student** table name to **pupil**
   12. Remove the **student** table
   13. Remove the rows of 'Fall' Semester in **section**
   14. Remove the row of 'Data_structure' in **Course**
   15. Remove all rows in all tables using **TRUNCATE** table
   16. Remove **pupil, course and section** table so that it exist in recycle bin
   17. Remove **Grade_Report & Prerequisites** table permanently
## VIVA VOCE [10 Marks] 
### ---------------------------------- END OF WEEK-1 LAB ----------------------------
***
# WEEK-2
1.   Queries (along with sub-Queries) using ANY, ALL, IN, EXISTS, NOTEXISTS, UNION, INTERSET, Constraints. Example - Select the roll number and name of the student who secured fourth rank in the class.
2. Queries using Aggregate functions (COUNT, SUM, AVG, MAX and MIN), GROUP BY, HAVING and Creation and dropping of Views.

## Links for Preparations
1. [WHERE CLAUSE](https://www.oracletutorial.com/oracle-basics/oracle-where/)
2. [SUBQUERY](https://www.oracletutorial.com/oracle-basics/oracle-subquery/)
3. [Co-Related SubQuery](https://www.oracletutorial.com/oracle-basics/oracle-correlated-subquery/)
4. [EXISTS](https://www.oracletutorial.com/oracle-basics/oracle-exists/)
5. [NOT EXISTS](https://www.oracletutorial.com/oracle-basics/oracle-not-exists/)
6. [ANY](https://www.oracletutorial.com/oracle-basics/oracle-any/)
7. [ALL](https://www.oracletutorial.com/oracle-basics/oracle-all/)
8. [IN](https://www.oracletutorial.com/oracle-basics/oracle-in/)
9. ### CONSTRAINTS
   1. [PRIMARY KEY](https://www.oracletutorial.com/oracle-basics/oracle-primary-key/)
   2. [FOREIGN KEY](https://www.oracletutorial.com/oracle-basics/oracle-foreign-key/)
   3. [UNIQUE](https://www.oracletutorial.com/oracle-basics/oracle-foreign-key/)
   4. [CHECK](https://www.oracletutorial.com/oracle-basics/oracle-check-constraint/)
   5. [NOT NULL](https://www.oracletutorial.com/oracle-basics/oracle-not-null/)
   6. [DEFAULT](https://www.oracletutorial.com/oracle-basics/oracle-default/)
10. ### SET OPERATIONS
    1. [UNION](https://www.oracletutorial.com/oracle-basics/oracle-union/)
    2. [INTERSECT](https://www.oracletutorial.com/oracle-basics/oracle-intersect/)
    3. [MINUS](https://www.oracletutorial.com/oracle-basics/oracle-minus/)
11. ### Aggregate Functions
    1. [Aggregate Functions](https://www.oracletutorial.com/oracle-aggregate-functions/)
    2. [AVERAGE](https://www.oracletutorial.com/oracle-aggregate-functions/oracle-avg/)
    3. [COUNT](https://www.oracletutorial.com/oracle-aggregate-functions/oracle-count/)
    4. [MAX](https://www.oracletutorial.com/oracle-aggregate-functions/oracle-max/)
    5. [MIN](https://www.oracletutorial.com/oracle-aggregate-functions/oracle-min/)
    6. [SUM](https://www.oracletutorial.com/oracle-aggregate-functions/oracle-sum/)
12. ### Grouping rows
    1. [GROUP BY CLAUSE](https://www.oracletutorial.com/oracle-basics/oracle-group-by/)
    2. [HAVING CLAUSE](https://www.oracletutorial.com/oracle-basics/oracle-having/)
13. ### Creating and Dropping Views
    1. [Introduction to views](https://www.oracletutorial.com/oracle-view/)
    2. [Creating Views](https://www.oracletutorial.com/oracle-view/oracle-create-view/)
    3. [Dropping Views](https://www.oracletutorial.com/oracle-view/oracle-drop-view/)

## USE THE FOLLOWING RELATIONAL SCHEMA and its instances Complete Week-2 Lab Session
<!--
### Company Relatinal Schema 
![COMPANY DATABASE SCHEMA](CompanyDB.png)
### Company Relational Instances
![COMAPANY_INSTANCES1](Company1.png)
![Company_Instances2](company2.png)
## Also Implement the Following Sailors Database
-->
### Sailors Database Schema
![SailorsDB](Salors_DB.png)
### Sailors Instances
![Sailors_INSTANCE](Sailors.png)
### Reserves Instances
![Reserves_InStances](boat.png)
### Boat Instances
![boat_instances](boat1.png)
## Use the above database to Answer the following Questions
1. Find the names and ages of all sailors.[^1]
2. Find all sailors with a rating above 7.[^2]
3. Find the names of sailors who have reserved boat number 103 [^3]
4. Find the sids of sailors who have reserved a red boat. [^4]
5. Find the names of sailors who have reserved a red boat. [^5]
6. Find the colors of boats reserved by Lubber. [^6]
7. Find the names of sailors who have reserved at least one boat. [^7]
8. Compute increments for the ratings of persons who have sailed two different boats on the same day. [^8]
9. Find the ages of sailors whose name begins and ends with B and has at least three characters.[^9]
10. Find the names of Sailors who reserved a red boat or a green boat[^10]
11. Find the names of sailors who have reserved both a red and a green boat.[^11]
12. Find the sids of all sailors who have reserved red boats but not green boats.[^12]
13. Find all sids of sailors who have a rating of 10 or have reserved boat 104[^13]
14.  Find the names of sailors who have reserved boat 103[^14]
15. Find the names of sailors who have reserved a red boat[^15]
16.  Find the names of sailors who have reserved boat number 103 [^16]
17.  Find sailors whose rating is better than some sailor called Horatio. [^17]
18. Find sailors whose rating is better than every sailor called Horatio. [^18]
19. Find the sailors with the highest rating. [^19]
20. Find the names of sailors who have reserved both a red and a green boat. [^20]
21. Find the names of sailors who have reserved all boats. [^21]
22. Find the average age of all sailors. [^22]
23. Find the average age of sailors with a rating of 10. [^23]
24. Find the name and age of the oldest sailor. [^24]
25. Count the number of sailors. [^25]
26. Count the number of different sailor names. [^26]
27. Find the names of sailors who are older than the oldest sailor with a rating of 10. [^27]
28. Find the age of the youngest sailor for each rating level. [^28]
29. Find the age of the youngest sailor who is eligible to vote (i.e., is at least 18 years old) for each rating level with at least two such sailors. [^29]
30.  For each red boat, find the number of reservations for this boat.
31.  Find the average age of sailors for each rating level that has at least two sailors.
32.  Find the average age of sailors who are of voting age (i.e., at least 18 years old) for each rating level that has at least two sailors.
33.  Find the average age of sailors who are of voting age (i.e., at least 18 years old) for each rating level that has at least two such sailors.
34.  Find those ratings for which the average age of sailors is the minimum over all ratings.

    
[^1]:Use **DISTINCT** Keyword to eliminate duplicates
[^2]: Use **WHERE CLAUSE** to Answer the Query.
[^3]: use **WHERE CLAUSE** and DO Cartesian Product to Answer the Query and you have to display names of sailors only
[^4]: use **WHERE CLAUSE** and DO Cartesian Product to Answer the Query and you have to display sids only
[^5]: use **WHERE CLAUSE** and do Cartesian product to answer the Query and display names only
[^6]: use **WHERE CLAUSE** and do Cartesian product to answer the Query and display colors of boat reserved by Lubber.
[^7]: use **WHERE CLAUSE** and do Cartesian product to answer the Query and display names of sailors only.
[^8]: Perform *rating+1* operation in SELECT CLAUSE, use **WHERE CLAUSE** and do Cartesian Product to answer the Query and dispaly names,
[^9]: use Pattern matching techiques in **WHERE CLAUSE** to implement it and ages only.
[^10]: Implement the above Query in two ways. First way perform cartesian and use where clause effectively. second way you can implement **UNION** set Operations.
[^11]:Implement the above Query in two ways. First way perform cartesian and use where clause effectively. second way you can implement **INTERSECT** set Operations.
[^12]:Implement the above Query in two ways. First way perform cartesian and use where clause effectively. second way you can implement **MINUS** set Operations.
[^13]: Perform **UNION** Operation
[^14]: Implement it using nested subqueries and use **IN** Operator
[^15]: implement it using multi nested subqueries and use **IN** Operator
[^16]: Implement co-related subquery method using **EXISTS** operator.
[^17]: use **>ANY** operator to solve the above question.
[^18]: use **>ALL** operator to solve the above question.
[^19]: use **>=ALL** Operator to solve the above question.
[^20]: use **IN** and **Nested Query Method** to solve the above query.
[^21]: Use **NOT EXIST**, **MINUS or Not using also** and **Co-related Nested Query** to solve the above query.
[^22]: use **Aggregate AVG Function** to solve the above query.
[^23]: use **Aggregate AVG Function** and **WHERE CLAUSE** to solve the above query.
[^24]: use **Aggregate MAX Function in nested Query** to solve the above query.
[^25]: use **Aggregate COUNT Function** to solve the above query.
[^26]: use **Aggregate COUNT Function and DISTINCT Keyword** to solve the above query.
[^27]: use **Aggregate AVG Function** and **WHERE CLAUSE** to solve the above query. In Addtion to that Solve the above query using **>ALL operator** to sovle the above query.
[^28]: use **GROUP BY and MIN Function** to solve the above Query
[^29]: use **GROUP BY, HAVING and MIN Function** to solve the above Query.










