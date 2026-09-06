# Experiment 7: PL/SQL – Variables, Control Structures and Loops

## AIM
To write and execute simple PL/SQL programs using variables, loops, and conditional statements.


## THEORY

PL/SQL, which stands for Procedural Language extensions to the Structured Query Language (SQL). It is a combination of SQL along with the procedural features of programming languages.

**Syntax:**
```sql
DECLARE 
   <declarations section> 
BEGIN 
   <executable command(s)>
EXCEPTION 
   <exception handling> 
END;
```

### Basic Components of PL/SQL Block:
- DECLARE: Section to declare variables and constants.
- BEGIN: The execution section that contains PL/SQL statements.
- EXCEPTION: Handles errors or exceptions that occur in the program.
- END: Marks the end of the PL/SQL block.

# PL/SQL Programs – Steps and Expected Output

## 1. Write a PL/SQL program to find the Greatest of Two Numbers

### Steps:
- Declare two numeric variables and initialize them.
- Use an `IF` statement to compare the values.
- Display the greater number using `DBMS_OUTPUT.PUT_LINE`.
- 
- ## program##
- ```
- DECLARE
    num1 NUMBER := 80;   -- First number
    num2 NUMBER := 40;   -- Second number
BEGIN
    IF num1 > num2 THEN
        DBMS_OUTPUT.PUT_LINE('Greatest number is: ' || num1);
    ELSE
        DBMS_OUTPUT.PUT_LINE('Greatest number is: ' || num2);
    END IF;
END;

/```

**Expected Output:**  
Greater number is: 80

---
## output##
<img width="575" height="202" alt="image" src="https://github.com/user-attachments/assets/3f55081e-3f67-4837-9dea-5d598c71c9d7" />

## 2. Write a PL/SQL program to Calculate Sum of First N Natural Numbers

### Steps:
- Declare a variable `n` and assign a value (e.g., 10).
- Initialize a `sum` variable to 0.
- Use a `WHILE` loop to iterate from 1 to `n`, adding each number to the sum.
- Display the result using `DBMS_OUTPUT.PUT_LINE`.

**Expected Output:**  
Sum of first 10 natural numbers is: 55

---
## program ##
```
DECLARE
    n NUMBER := 10;     -- Value of N
    i NUMBER := 1;      -- Counter variable
    sum NUMBER := 0;    -- Initialize sum
BEGIN
    WHILE i <= n LOOP
        sum := sum + i; -- Add current number to sum
        i := i + 1;     -- Increment counter
    END LOOP;

    DBMS_OUTPUT.PUT_LINE('Sum of first ' || n || ' natural numbers is: ' || sum);
END;
```
## output##
<img width="442" height="190" alt="image" src="https://github.com/user-attachments/assets/4887f336-80e2-4588-ad38-2f86a621900f" />

## 3. Write a PL/SQL program to generate Fibonacci series

### Steps:
- Declare the variable `n` to indicate how many terms to generate.
- Initialize the first two Fibonacci numbers (0 and 1).
- Use a loop to generate the next terms using the formula `c = a + b`.
- Print each term in the series.

**Expected Output:**  
n = 7  
Fibonacci sequence: 0, 1, 1, 2, 3, 5, 8

## program ##
```
SET SERVEROUTPUT ON;
DECLARE
    num NUMBER := &n;
    a NUMBER := 0;
    b NUMBER := 1;
    c NUMBER;
    i NUMBER := 3;
BEGIN
    DBMS_OUTPUT.PUT_LINE('n = ' || num);
    DBMS_OUTPUT.PUT('Fibonacci sequence: ' || a || ', ' || b);

    WHILE i <= num LOOP
        c := a + b;
        DBMS_OUTPUT.PUT(', ' || c);
        a := b;
        b := c;
        i := i + 1;
    END LOOP;

    DBMS_OUTPUT.NEW_LINE;
END;
```

## output ##
<img width="466" height="215" alt="image" src="https://github.com/user-attachments/assets/5c26de5e-9fd9-45db-9fa0-dfff320e076e" />


## 4. Write a PL/SQL Program to display the number in Reverse Order

### Steps:
- Declare a variable `n` and assign a value (e.g., 1535).
- Use a loop to extract each digit using modulo and reverse the number.
- Display the reversed number.

**Expected Output:**  
n = 1535  
Reversed number is 5351
## program ##
```
DECLARE
    a NUMBER := 10;
    b NUMBER := 9;
    c NUMBER := 15;
BEGIN
    IF a > b AND a > c THEN
        DBMS_OUTPUT.PUT_LINE('Largest number is ' || a);
    ELSIF b > a AND b > c THEN
        DBMS_OUTPUT.PUT_LINE('Largest number is ' || b);
    ELSE
        DBMS_OUTPUT.PUT_LINE('Largest number is ' || c);
    END IF;
END;
```
## output ##
<img width="437" height="186" alt="image" src="https://github.com/user-attachments/assets/b3719b76-bea1-4aa8-bcf4-3ffd918daac4" />


## 5. Write a PL/SQL program to find the largest of three numbers

### Steps:
- Declare three numeric variables `a`, `b`, and `c`.
- Use nested `IF-ELSIF-ELSE` conditions to find the largest among the three.
- Display the largest number.

**Expected Output:**  
a = 10, b = 9, c = 15  
Largest of three number is 15
## program ##
```
DECLARE
    a NUMBER := 10;
    b NUMBER := 9;
    c NUMBER := 15;
BEGIN
    IF a > b AND a > c THEN
        DBMS_OUTPUT.PUT_LINE('Largest number is ' || a);
    ELSIF b > a AND b > c THEN
        DBMS_OUTPUT.PUT_LINE('Largest number is ' || b);
    ELSE
        DBMS_OUTPUT.PUT_LINE('Largest number is ' || c);
    END IF;
END;
```
## output##
<img width="501" height="172" alt="image" src="https://github.com/user-attachments/assets/e691e323-517a-4f6e-a46b-c3e6d6c736f1" />


## RESULT
Thus, the PL/SQL programs using variables, conditionals, and loops were executed successfully.
