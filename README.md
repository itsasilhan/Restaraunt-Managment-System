#  Restaurant Management Database System

This project is a fully designed and implemented relational database system for managing restaurant operations. It simulates real-world workflows including customer ordering, menu management, employee tracking, and analytical reporting

---

##  Project Overview

The system is designed to support two main user groups:

###  Customers
- View menu and place orders  
- Add special requests (e.g., vegan, nut-free)  
- Leave reviews with ratings and comments  
- Track order history and spending  

###  Employees / Managers
- Manage menu items (add/update/delete)  
- Process and track orders  
- Update order status (preparing, served, etc.)  
- Analyze customer behavior and preferences  
- Generate reports (sales, top dishes, etc.)  

---

##  Database Design

The database consists of **20+ normalized tables**, including:

- Restaurant  
- Menu  
- Item  
- Ingredient  
- Order  
- Customer  
- Employee  
- Position  
- Review  
- Special Requests  
- Rating  
- Measurement  

All entities are connected using **primary and foreign keys**, ensuring data integrity and consistency

---

##  Normalization

The database follows strict normalization rules:

- **1NF** – Atomic values, no repeating groups  
- **2NF** – Full dependency on primary keys  
- **3NF** – No transitive dependencies  
- **4NF** – No multivalued dependencies  

 Result: clean, scalable, and redundancy-free structure  

---

##  Data Population

- Generated **1000+ realistic records**  
- Data includes:
  - Customers  
  - Orders  
  - Menu items  
  - Reviews  
- No artificial placeholders — all values mimic real-world scenarios  

---

##  SQL Features Implemented

The project includes a rich collection of SQL queries:

###  Basic Queries
- SELECT, WHERE, ORDER BY, LIKE  

###  Aggregations
- COUNT, SUM, AVG, GROUP BY, CASE  

###  Joins
- INNER JOIN, LEFT JOIN, multi-table joins  

###  Subqueries
- IN, NOT IN, correlated subqueries  

###  Window Functions
- RANK()  
- ROW_NUMBER()  
- Running totals  
- Partition-based analysis  

###  Triggers
- Automated actions for INSERT, UPDATE, DELETE  

###  Indexes
- B-tree indexes  
- Composite indexes  
- Bitmap indexes  
- Unique constraints  

---

##  Analytical Capabilities

The system supports real-world analytics such as:

- Ranking restaurants by revenue  
- Tracking customer spending patterns  
- Identifying popular menu items  
- Monitoring price deviations  
- Preventing deletion of reviewed items  

---

##  Performance Optimization

- Indexed all foreign keys for faster joins  
- Used composite indexes for frequent queries  
- Applied bitmap indexes for categorical data  
- Ensured efficient query execution  

---

##  Technologies Used

- SQL  
- PostgreSQL / Oracle / MySQL (depending on implementation)  

---

##  Future Improvements

- Delivery tracking system  
- Loyalty programs  
- Inventory management alerts  
- Real-time analytics dashboards  

---
