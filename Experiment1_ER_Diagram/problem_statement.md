# ER Diagram Workshop – Submission Template

## Objective
To understand and apply ER modeling concepts by creating ER diagrams for real-world applications.

## Purpose
Gain hands-on experience in designing ER diagrams that represent database structure including entities, relationships, attributes, and constraints.

---

# Scenario A: City Fitness Club Management

**Business Context:**  
FlexiFit Gym wants a database to manage its members, trainers, and fitness programs.

**Requirements:**  
- Members register with name, membership type, and start date.  
- Each member can join multiple programs (Yoga, Zumba, Weight Training).  
- Trainers assigned to programs; a program may have multiple trainers.  
- Members may book personal training sessions with trainers.  
- Attendance recorded for each session.  
- Payments tracked for memberships and sessions.

### ER Diagram:
*Paste or attach your diagram here*  
<img width="1161" height="920" alt="image" src="https://github.com/user-attachments/assets/5f640dbf-b49b-4675-bc8c-6f686572c289" />


### Entities and Attributes

<img width="1277" height="480" alt="image" src="https://github.com/user-attachments/assets/3765ed18-95b3-40bc-bdf3-ec193f665cad" />


### Relationships and Constraints

<img width="1237" height="287" alt="image" src="https://github.com/user-attachments/assets/d891a93d-6580-471f-a917-159bc663772a" />


### Assumptions
Each member is enrolled in one membership plan.
A membership plan can be assigned to many members.
A trainer can conduct multiple workout schedules.

# Scenario B: City Library Event & Book Lending System

**Business Context:**  
The Central Library wants to manage book lending and cultural events.

**Requirements:**  
- Members borrow books, with loan and return dates tracked.  
- Each book has title, author, and category.  
- Library organizes events; members can register.  
- Each event has one or more speakers/authors.  
- Rooms are booked for events and study.  
- Overdue fines apply for late returns.

### ER Diagram:
*Paste or attach your diagram here*  
<img width="1182" height="932" alt="image" src="https://github.com/user-attachments/assets/3b98250e-05a3-4d8d-84c8-336970108ce8" />

### Entities and Attributes
<img width="1260" height="295" alt="image" src="https://github.com/user-attachments/assets/cd4a7026-2cfe-4dd0-9370-0f7f141b1a15" />


### Relationships and Constraints

 |<img width="1260" height="295" alt="image" src="https://github.com/user-attachments/assets/eea11e1e-1823-4913-a704-9293a16b8c02" />


### Assumptions
A member can borrow multiple books.
One book copy can be borrowed multiple times over time.
Members can participate in multiple events.

# Scenario C: Restaurant Table Reservation & Ordering

**Business Context:**  
A popular restaurant wants to manage reservations, orders, and billing.

**Requirements:**  
- Customers can reserve tables or walk in.  
- Each reservation includes date, time, and number of guests.  
- Customers place food orders linked to reservations.  
- Each order contains multiple dishes; dishes belong to categories (starter, main, dessert).  
- Bills generated per reservation, including food and service charges.  
- Waiters assigned to serve reservations.

### ER Diagram:
*Paste or attach your diagram here*  
<img width="1167" height="911" alt="image" src="https://github.com/user-attachments/assets/49ef5c95-e9cf-4336-a515-e8bafa7fe84e" />

### Entities and Attributes
<img width="1292" height="442" alt="image" src="https://github.com/user-attachments/assets/a2a9de0b-45e3-427f-a28e-455cb2c32abe" />



### Relationships and Constraints
<img width="1202" height="396" alt="image" src="https://github.com/user-attachments/assets/bdba6ea3-27e3-4af3-b118-36e704c6d2ee" />


### Assumptions
- 
- One guest can make multiple reservations.
One dining table can be reserved many times at di􀆯erent times.
One reservation can include multiple menu items.
One sta􀆯 member can handle multiple reservations.
- 

---

## Instructions for Students

1. Complete **all three scenarios** (A, B, C).  
2. Identify entities, relationships, and attributes for each.  
3. Draw ER diagrams using **draw.io / diagrams.net** or hand-drawn & scanned.  
4. Fill in all tables and assumptions for each scenario.  
5. Export the completed Markdown (with diagrams) as **a single PDF**
