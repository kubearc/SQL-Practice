## SQL ALTER TABLE practice task.

### Given Table: `Persons`

| ID | LastName  | FirstName | Address      | City      |
| -- | --------- | --------- | ------------ | --------- |
| 1  | Hansen    | Ola       | Timoteivn 10 | Sandnes   |
| 2  | Svendson  | Tove      | Borgvn 23    | Sandnes   |
| 3  | Pettersen | Kari      | Storgt 20    | Stavanger |

---

### Task: Practice SQL `ALTER TABLE`

Write SQL queries to make the following changes to the `Persons` table:

1. **Add a new column** named `DateOfBirth` of type `DATE`.
2. **Rename** the column `Address` to `HomeAddress`.
3. **Modify** the column `City` to increase its size to `VARCHAR(100)`.
4. **Add a new column** `Email` that must be **unique**.
5. **Delete** the column `Email` from the table.
6. **Drop** the column `DateOfBirth`.
7. **Add** a new column `Age` with default value `18`.

---
