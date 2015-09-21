# TechWriting2
Kalan Matthews
To run this Oracle SQL program you will need Oracle SQL developer: http://www.oracle.com/technetwork/developer-tools/sql-developer/overview/index-097090.html

This program is to create and modify tables Named: Department, Project, Employee, WorksOn

-The first table is Department, this table is dropped on line 1 to insure that there will be no problems when creating the table
-Once the table is created the department number, name, and Manager employee number is added. The primary key in this table is the department number.
-The second table is created on line 8, the Project table
-This table is to specify what departments are working on what projects, specified by the project number, name, and the corresponding department number. The primary key in this table is project number
-The Employee and worksOn tables are created in the same fashion as above
-From lines 35-59 the tables are altered to ensure that employee's have a sex of either male or female, specified by "m" or "f" , specify foreign keys, and ensure that the project number cannot be less than or equal to zero.

The queries that exist in lines 68-94 are test queries to ensure that the tables are setup correctly.

-The first querie will count how many of each sex there are in each department
-The second querie will pull up any employee with the position "secretary"
-The third querie will pull up any employee that is a manager
-The fourth querie will pull up anyone that has less than or equal to 1 hour worked or someone that is on payroll but have not worked.
