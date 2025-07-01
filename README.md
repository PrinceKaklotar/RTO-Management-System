# RTO-Database
This project is a PostgreSQL-based relational database system designed to manage and streamline the core operations of an RTO (Regional Transport Office). It handles essential tasks such as vehicle registration, license issuance, ownership records, and officer management through a normalized and scalable schema.

## 📌 Features

- ✅ Vehicle Registration & Management:
  
  Tracks all vehicle details including registration number, owner info, and fitness validity.
- ✅ Driving License Management:
  
  Manages license issuance, renewal, suspension, and validation processes.
- ✅ Owner & Applicant Records:
  
  Maintains personal information, contact details, and ownership history.
- ✅ Normalized schema for minimal redundancy
- ✅ Functional dependencies and relational modeling
- ✅ Optimized SQL queries for real-world use cases and reporting
- ✅ ER Diagram and Relational Model diagrams included

## 🧩 Technologies Used

- **PostgreSQL** – Database system
- **pgAdmin 4** – GUI for managing PostgreSQL databases
- Standard **SQL**
- DBMS concepts (Normalization, Functional Dependencies, Relational Algebra)
- Python (for optional query execution)

## 🛠️ How to Run

1. Install **PostgreSQL** and **pgAdmin 4** if not already installed.
2. Open `pgAdmin 4` and create a new database (e.g., `rto_db`).
3. Use the Query Tool in pgAdmin to:
   - Run `RTO DDL Statements.sql` to create the schema.
   - Run `RTO Data.sql` to insert sample records.
   - Run queries from `RTO Query Statements.sql` to test functionality.
4. (Optional) Use `RTO API (python).py` to interact with the database programmatically via Python.

## 📊 ER & Relational Model

![ER Diagram](./RTO%20ER%20Diagram.png)
![Relational Model](./RTO%20Relational%20model.png)
