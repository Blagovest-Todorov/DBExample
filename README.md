# DBExample
tasks from SoftUni
Basic Crud Operations
CREATE, UORADE, DELETE

SELECT 
	FirstName + ' ' + LastName AS 'Full Name',
	Jobtitle, 
	Salary FROM Employees

SELECT * FROM Employees
INSERT INTO Employees 
(FirstName, MiddleName, LastName,Jobtitle,HireDate, Salary)
VALUES('Mi', 'Pet', 'Ivanov','Engineer','2021-05-21',1000),
      ('Mitko', 'Pe


what is normalizerd DB- a DB with no repatings entries.
So to structure the DB , not to have redundant entries.the process of organizing data in a database.
Normalization is the process of organizing data in a database. This includes creating tables and establishing relationships between those tables according to rules designed both to protect the data and to make the database more flexible by eliminating redundancy and inconsistent dependency.
INSERT INTO table_name 
'Row_Name'
VALUES(....); -- We insert into a given table and rowName a given Value;
MULTIPLE INSERT ior BULK INSERT
INSERT INTO table_Name 
(Row1, Row2)
VALUES
(..,..),
(..,..),
(..,..)
--We inserted into the table into two columns three rows of recoreds

SELECT FirstName,LastName, Salary 
		  FROM Employees
		 WHERE Salary > 50000
		 ORDER BY Salary DESC;
		 
		 
SELECT * 
FROM Employees
ORDER BY Salary DESC, FirstName, LastName DESC, MiddleName
