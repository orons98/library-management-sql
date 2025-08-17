# Library Management System – SQL and Data Simulation

This project simulates a relational database for a library management system, designed as part of an academic assignment. It includes realistic, randomly generated data covering books, members, and book condition histories, and demonstrates key SQL database design principles.

This assignment involved database creation, schema design, and data generation using Python. It was built to reflect real-world business logic, with ethical and structural considerations in mind.

---

## Database Overview
The system models:
- **Books** with metadata, pricing, and condition
- **Memberships** with join/expiration dates and membership tiers
- **Book Conditions** over time to track inventory status

All data types were represented:
- **Nominal:** Genre, Author, Publisher  
- **Ordinal:** Book Condition, Membership Type  
- **Interval:** Join/Expiration Dates, Published Year  
- **Ratio:** Book Price, Number of Pages

---

## Tools and Methods
- **SQLite** – for schema definition and data handling  
- **Python (Pandas, NumPy, Matplotlib)** – for realistic data simulation  
- **ERD schema diagrams** – for normalisation and design logic

---

## Key Features
- Over **1,000 rows of generated data**
- Use of **foreign and composite keys** to maintain integrity
- Simulated **missing values** to reflect real-world datasets
- Designed for **normalisation**, scalability, and practical queries
- Clean separation of concerns across **Books**, **Memberships**, and **Book Conditions** tables

---

## Ethical and Privacy Considerations
- No personally identifiable information (PII) was used  
- All names and categories are synthetic but realistic  
- Distribution of values (e.g. membership tiers, book conditions) was probability-weighted to match real-world trends  
- Missing data was intentionally introduced to simulate imperfect records
