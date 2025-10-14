# SQL Task – UPDATE 

## Original Table: Employees

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

### **Task 1** -  Update the salary of **Ramesh (EmpID = 1)** to **45,000**

**Updated Row:**

| EmpID | Name   | Department | Salary | City  |
| ----- | ------ | ---------- | ------ | ----- |
| 1     | Ramesh | HR         | 45000  | Delhi |

---

### **Task 2** - Update the **city of all IT department employees** to **"Noida"**

**Updated Rows:**

| EmpID | Name   | Department | Salary | City  |
| ----- | ------ | ---------- | ------ | ----- |
| 2     | Priya  | IT         | 55000  | Noida |
| 4     | Neha   | IT         | 45000  | Noida |
| 6     | Meena  | IT         | 70000  | Noida |
| 8     | Kavita | IT         | 65000  | Noida |

---

### **Task 3** - Increase salary of all employees in the **HR department by 5,000**

**Updated Rows:**

| EmpID | Name   | Department | Salary | City    |
| ----- | ------ | ---------- | ------ | ------- |
| 1     | Ramesh | HR         | 50000  | Delhi   |
| 5     | Suresh | HR         | 35000  | Chennai |
| 9     | Arjun  | HR         | 40000  | Delhi   |

---

### **Task 4** - Change the department of **Simran (EmpID = 10)** from **Finance to IT**

**Updated Row:**

| EmpID | Name   | Department | Salary | City   |
| ----- | ------ | ---------- | ------ | ------ |
| 10    | Simran | IT         | 72000  | Mumbai |
