# Database Project – SQL Scripts  

## About the Project  
This project contains SQL scripts related to **database schema design, CRUD operations testing, and stress testing** to ensure the database's **functionality, efficiency, and scalability**.  

## Project Objectives  
- **Database Schema Design:** Define tables, relationships, and constraints.  
- **CRUD Operations Testing:** Validate Create, Read, Update, and Delete operations.  
- **Stress Testing:** Analyze performance under high-load conditions.  

## SQL Files Overview  

### 1. **vandana_project.sql**  
- Defines the **database schema**, including table structures, data types, primary keys, and foreign key relationships.  
- Ensures database normalization and integrity.  
- Example tables:  
  - Users  
  - Products  
  - Orders  
  - Transactions  

### 2. **vandana_project_crud_test.sql**  
- Implements **CRUD operations** to validate database functionality.  
- Includes:  
  - **CREATE** – Adding new records to tables.  
  - **READ** – Fetching data using SELECT queries.  
  - **UPDATE** – Modifying existing records.  
  - **DELETE** – Removing data securely.  
- Helps in verifying **data consistency and error handling**.  

### 3. **vandana_stress_testing.sql**  
- Contains queries to **simulate high-load scenarios** and evaluate database performance.  
- Includes:  
  - **Bulk Inserts** – Testing large data ingestion.  
  - **Complex Joins** – Checking query optimization.  
  - **Concurrent Transactions** – Simulating multiple users.  
- Helps assess **query execution time, indexing efficiency, and database bottlenecks**.  

## Technologies Used  
- **SQL Database Management System (DBMS):** MySQL / PostgreSQL / SQL Server (Specify the one used)  
- **Testing Tools:** SQL Benchmarking, Performance Logs  

## Key Takeaways  
- **Well-structured database schema** enhances data integrity.  
- **CRUD validation** ensures smooth user interactions.  
- **Stress testing** highlights performance improvements.  

## How to Use  
1. **Set up the database:** Run `vandana_project.sql` to create tables.  
2. **Test CRUD operations:** Execute `vandana_project_crud_test.sql`.  
3. **Perform stress testing:** Run `vandana_stress_testing.sql` and analyze results.  

## Contributors  
- **Vandana Jain**  
- **Project Type:** Database Development & Testing  
