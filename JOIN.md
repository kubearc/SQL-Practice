# SQL Task – JOIN Operations

## Table 1: Employees

| EmpID | Name   | DepartmentID | Salary |
| ----- | ------ | ------------- | ------ |
| 1     | Ramesh | 101           | 40000  |
| 2     | Priya  | 102           | 55000  |
| 3     | Anil   | 103           | 60000  |
| 4     | Neha   | 102           | 45000  |
| 5     | Suresh | 101           | 30000  |
| 6     | Meena  | 102           | 70000  |

---

## Table 2: Departments

| DepartmentID | DepartmentName |
| ------------- | --------------- |
| 101           | HR              |
| 102           | IT              |
| 103           | Finance         |
| 104           | Marketing       |

---
### **Task 1**
**Display all employees along with their department names using INNER JOIN.**

## Sample Output:

| Name   | DepartmentName | Salary |
| ------ | -------------- | ------ |
| Ramesh | HR             | 40000  |
| Priya  | IT             | 55000  |
| Anil   | Finance        | 60000  |
| Neha   | IT             | 45000  |
| Suresh | HR             | 30000  |
| Meena  | IT             | 70000  |

---

### **Task 2**

**Show all employees and their department names, including employees without a matching department (LEFT JOIN).**

## Sample Output:

| Name   | DepartmentName |
| ------ | -------------- |
| Ramesh | HR             |
| Priya  | IT             |
| Anil   | Finance        |
| Neha   | IT             |
| Suresh | HR             |
| Meena  | IT             |

*(All employees have a matching department in this case)*

---

### **Task 3**

**Show all departments and their employees, including departments that have no employees (RIGHT JOIN).**

## Sample Output:

| DepartmentName | Name   |
| -------------- | ------ |
| HR             | Ramesh |
| HR             | Suresh |
| IT             | Priya  |
| IT             | Neha   |
| IT             | Meena  |
| Finance        | Anil   |
| Marketing      | NULL   |

---

### **Task 4**

**Display all employees and departments (FULL JOIN simulation using UNION).**

## Sample Output:

| Name   | DepartmentName |
| ------ | -------------- |
| Ramesh | HR             |
| Priya  | IT             |
| Anil   | Finance        |
| Neha   | IT             |
| Suresh | HR             |
| Meena  | IT             |
| NULL   | Marketing      |

---

### **Task 5**

**Find employees working in the IT department using JOIN and WHERE clause.**

## Sample Output:

| Name  | DepartmentName |
| ----- | -------------- |
| Priya | IT             |
| Neha  | IT             |
| Meena | IT             |

---

### **Task 6**

**Display department names along with the total salary of employees in each department.**

## Sample Output:

| DepartmentName | TotalSalary |
| -------------- | ----------- |
| HR             | 70000       |
| IT             | 170000      |
| Finance        | 60000       |

---

## Concepts Covered

* `INNER JOIN`
* `LEFT JOIN`
* `RIGHT JOIN`
* `FULL JOIN` (using `UNION`)
* `JOIN` with `WHERE`
* Aggregation with `JOIN`
