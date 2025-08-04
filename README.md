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
3. [Co-Related SubQuery](https://www.oracletutorial.com/oracle-basics/oracle-subquery/)
4. [EXISTS](https://www.oracletutorial.com/oracle-basics/oracle-exists/)
5. [NOT EXISTS](https://www.oracletutorial.com/oracle-basics/oracle-not-exists/)
6. [ANY](https://www.oracletutorial.com/oracle-basics/oracle-any/)
7. [ALL](https://www.oracletutorial.com/oracle-basics/oracle-any/)
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





