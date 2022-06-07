# 100-daysofcode

SELECT Employee. ENO, Employee. ENAME from Employee INNER JOIN Department ON Employee.ENAME = Department.SECTION;

14

15 SELECT * from Employee NATURAL JOIN Department;

16 SELECT ENO, ENAME from Employee LEFT OUTER JOIN Department on Employee.ENAME = Department. DNAME;

17 SELECT ENO, ENAME from Employee RIGHT OUTER JOIN Department on Employee.ENAME = Department.DNAME;

18 SELECT ENO, ENAME from Employee FULL OUTER JOIN Department on Employee.ENAME = Department.DNAME;
