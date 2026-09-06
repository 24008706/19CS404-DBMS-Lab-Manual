# Experiment 5: Subqueries and Views

## AIM
To study and implement subqueries and views.

## THEORY

### Subqueries
A subquery is a query inside another SQL query and is embedded in:
- WHERE clause
- HAVING clause
- FROM clause

**Types:**
- **Single-row subquery**:
  Sub queries can also return more than one value. Such results should be made use along with the operators in and any.
- **Multiple-row subquery**:
  Here more than one subquery is used. These multiple sub queries are combined by means of ‘and’ & ‘or’ keywords.
- **Correlated subquery**:
  A subquery is evaluated once for the entire parent statement whereas a correlated Sub query is evaluated once per row processed by the parent statement.

**Example:**
```sql
SELECT * FROM employees
WHERE salary > (SELECT AVG(salary) FROM employees);
```
### Views
A view is a virtual table based on the result of an SQL SELECT query.
**Create View:**
```sql
CREATE VIEW view_name AS
SELECT column1, column2 FROM table_name WHERE condition;
```
**Drop View:**
```sql
DROP VIEW view_name;
```

**Question 1**
<img width="1261" height="762" alt="image" src="https://github.com/user-attachments/assets/12cf33d4-1901-49fc-a562-c8149e5f69bf" />


**Output:**

<img width="1260" height="552" alt="image" src="https://github.com/user-attachments/assets/08a57ca2-35ee-40bf-b018-71b1aafcd99a" />

**Question 2**
<img width="1221" height="587" alt="image" src="https://github.com/user-attachments/assets/c9fe418f-1228-4ae5-bf8a-cdae9bc54b7e" />


**Output:**

<img width="1256" height="417" alt="image" src="https://github.com/user-attachments/assets/3149dad3-727b-47b4-8d25-c8d0794e81a5" />


**Question 3**
<img width="1257" height="682" alt="image" src="https://github.com/user-attachments/assets/fe7d81ae-9508-41ba-b219-2d35f797a86d" />

**Output:**

<img width="942" height="642" alt="image" src="https://github.com/user-attachments/assets/a7ff1cbf-f794-4438-ac17-cd54d3397de1" />


**Question 4**
<img width="1237" height="701" alt="image" src="https://github.com/user-attachments/assets/74aac698-1e30-46a4-abd0-d25f2f0029e2" />


**Output:**

<img width="1242" height="537" alt="image" src="https://github.com/user-attachments/assets/40a02296-81e6-4f1c-8b9d-5a815d35bbbe" />

**Question 5**
<img width="1236" height="867" alt="image" src="https://github.com/user-attachments/assets/46d6443a-edb7-432f-a16b-e2ce6d4ede3b" />


**Output:**

<img width="1260" height="610" alt="image" src="https://github.com/user-attachments/assets/57d0eeb7-df13-42fb-90c4-34eac6b116c0" />

**Question 6**
<img width="1242" height="712" alt="image" src="https://github.com/user-attachments/assets/838eb944-7a06-4623-bd36-c885753ccc97" />


**Output:**

<img width="1260" height="540" alt="image" src="https://github.com/user-attachments/assets/7c6836b1-b8ec-4aac-96df-999ca988d870" />


**Question 7**
<img width="1255" height="547" alt="image" src="https://github.com/user-attachments/assets/eb30a1a4-9fad-49bb-907e-693ad45d73b2" />


**Output:**

<img width="1260" height="555" alt="image" src="https://github.com/user-attachments/assets/34dfa709-52ae-4494-9c3d-5de15aaf0be8" />


**Question 8**
<img width="1125" height="582" alt="image" src="https://github.com/user-attachments/assets/dd0c5a09-b1e9-4d3d-82c9-db33ee1e44fe" />

**Output:**

<img width="1252" height="502" alt="image" src="https://github.com/user-attachments/assets/0cae0ce2-64b8-4389-9376-1d1fb5ae1a1b" />

**Question 9**
<img width="1167" height="922" alt="image" src="https://github.com/user-attachments/assets/9e7c92f4-0992-4eb3-bee3-619d7f2b7c5c" />


**Output:**

<img width="1255" height="612" alt="image" src="https://github.com/user-attachments/assets/43fb245c-84e4-4c0b-9f72-63b39036cf15" />

**Question 10**
<img width="1260" height="767" alt="image" src="https://github.com/user-attachments/assets/6166bde1-6cb7-437b-a149-eef3f7d6ad0d" />


**Output:**

<img width="822" height="677" alt="image" src="https://github.com/user-attachments/assets/7f04c8d7-1946-46d6-85be-1030140cb1fc" />


## RESULT
Thus, the SQL queries to implement subqueries and views have been executed successfully.
