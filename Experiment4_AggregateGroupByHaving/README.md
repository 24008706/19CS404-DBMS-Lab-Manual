# Experiment 4: Aggregate Functions, Group By and Having Clause

## AIM
To study and implement aggregate functions, GROUP BY, and HAVING clause with suitable examples.

## THEORY

### Aggregate Functions
These perform calculations on a set of values and return a single value.

- **MIN()** – Smallest value  
- **MAX()** – Largest value  
- **COUNT()** – Number of rows  
- **SUM()** – Total of values  
- **AVG()** – Average of values

**Syntax:**
```sql
SELECT AGG_FUNC(column_name) FROM table_name WHERE condition;
```
### GROUP BY
Groups records with the same values in specified columns.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name;
```
### HAVING
Filters the grouped records based on aggregate conditions.
**Syntax:**
```sql
SELECT column_name, AGG_FUNC(column_name)
FROM table_name
GROUP BY column_name
HAVING condition;
```

**Question 1**
<img width="992" height="682" alt="image" src="https://github.com/user-attachments/assets/02019d3c-8823-4285-8866-dd2e08c8d017" />



**Output:**

<img width="900" height="431" alt="image" src="https://github.com/user-attachments/assets/83add562-24c6-4243-9861-d352d8d71a78" />


**Question 2**
<img width="742" height="607" alt="image" src="https://github.com/user-attachments/assets/67f4219f-8191-495e-8161-e11423c97c43" />


**Output:**

<img width="571" height="467" alt="image" src="https://github.com/user-attachments/assets/797bf5e1-b804-4d85-87a9-930ffa04499d" />


**Question 3**
<img width="857" height="616" alt="image" src="https://github.com/user-attachments/assets/424e9560-8cbe-4288-924e-3e27eca9ef9e" />


**Output:**

<img width="655" height="447" alt="image" src="https://github.com/user-attachments/assets/fe9e2b82-53d1-46ae-8ea4-61ef844827cd" />


**Question 4**
<img width="1262" height="627" alt="image" src="https://github.com/user-attachments/assets/9894539a-cc8a-4e66-b999-781406e30c50" />


**Output:**

<img width="820" height="530" alt="image" src="https://github.com/user-attachments/assets/0ddf7790-b5d1-4658-9046-c63509805cb1" />

**Question 5**
<img width="1256" height="606" alt="image" src="https://github.com/user-attachments/assets/f42d4b06-8735-4d20-813b-fa5eda8c567d" />


**Output:**

<img width="930" height="550" alt="image" src="https://github.com/user-attachments/assets/7825e7a6-40ac-43c6-b5eb-de657990bbc2" />

**Question 6**
<img width="1152" height="822" alt="image" src="https://github.com/user-attachments/assets/5e68cadd-4041-4509-aea8-793d6eea9102" />


**Output:**

<img width="1212" height="782" alt="image" src="https://github.com/user-attachments/assets/191b17d9-efb0-499e-9595-6c32c2ccdd88" />

**Question 7**
<img width="1262" height="552" alt="image" src="https://github.com/user-attachments/assets/0c71a7c9-9f26-4e79-b13c-286147aff9b3" />


**Output:**

<img width="1072" height="562" alt="image" src="https://github.com/user-attachments/assets/5cd9ac42-f307-4097-a92b-338b21d5917e" />


**Question 8**
<img width="1252" height="492" alt="image" src="https://github.com/user-attachments/assets/6eaf1ba8-4525-4180-b230-d706128184e7" />


**Output:**

<img width="937" height="467" alt="image" src="https://github.com/user-attachments/assets/e64b2d4e-c53a-45d5-b722-9b5417b0ef23" />


**Question 9**
<img width="1257" height="617" alt="image" src="https://github.com/user-attachments/assets/1844f2b9-a462-4d04-b8c4-a68832280288" />


**Output:**

<img width="787" height="532" alt="image" src="https://github.com/user-attachments/assets/fb3f3a5e-af89-42cf-ae04-cb5642873411" />

**Question 10**
<img width="1257" height="596" alt="image" src="https://github.com/user-attachments/assets/5e8718e2-2062-4323-a6f5-178f39b23169" />


**Output:**

<img width="946" height="617" alt="image" src="https://github.com/user-attachments/assets/40b54167-fb53-4c1c-a50d-3bc2f366d025" />



## RESULT
Thus, the SQL queries to implement aggregate functions, GROUP BY, and HAVING clause have been executed successfully.
