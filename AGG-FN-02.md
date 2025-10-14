# SQL Task – COUNT(), SUM(), and AVG() Functions

## Table: Employees

| EmpID | Name   | Department | Salary | City      |
| ----- | ------ | ---------- | ------ | --------- |
| 1     | Ramesh | HR         | 40000  | Delhi     |
| 2     | Priya  | IT         | 55000  | Mumbai    |
| 3     | Anil   | Finance    | 60000  | Bangalore |
| 4     | Neha   | IT         | 45000  | Delhi     |
| 5     | Suresh | HR         | 30000  | Chennai   |
| 6     | Meena  | IT         | 70000  | Pune      |
| 7     | Rajesh | Finance    | 50000  | Hyderabad |
| 8     | Kavita | IT         | 65000  | Chennai   |
| 9     | Arjun  | HR         | 35000  | Delhi     |
| 10    | Simran | Finance    | 72000  | Mumbai    |

---

### **Task 1** - Find the total number of employees in the company.

## Sample Output:

| TotalEmployees |
| -------------- |
| 10             |

---

### **Task 2** - Find the total salary paid to all employees.

## Sample Output:

| TotalSalary |
| ----------- |
| 534000      |

---

### **Task 3** - Find the average salary of all employees.

## Sample Output:

| AverageSalary |
| ------------- |
| 53400         |

---

### **Task 4** - Find the total number of employees in each department.

## Sample Output:

| Department | TotalEmployees |
| ---------- | -------------- |
| Finance    | 3              |
| HR         | 3              |
| IT         | 4              |

---

### **Task 5** - Find the total salary of each department.

## Sample Output:

| Department | TotalDepartmentSalary |
| ---------- | --------------------- |
| Finance    | 182000                |
| HR         | 105000                |
| IT         | 247000                |

---

### **Task 6** - Find the average salary in each city.

## Sample Output:

| City      | AverageSalary |
| --------- | ------------- |
| Bangalore | 60000         |
| Chennai   | 47500         |
| Delhi     | 40000         |
| Hyderabad | 50000         |
| Mumbai    | 63500         |
| Pune      | 70000         |

---

##  Concepts Covered

* `COUNT()` → Counts total rows or items
* `SUM()` → Calculates the total of a numeric column
* `AVG()` → Finds the average (mean) value
* `GROUP BY` → Groups results 
