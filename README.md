DIVISION OF WORK FOR WEEK :1
HRUSIKESH – Data Gathering & Import
- Collect raw files (POS sales, online orders, customer info).
- Verify file formats (CSV, Excel, JSON).
- Import datasets into Excel/Pandas for inspection.
- Document sources and create a data inventory log (file names, size, columns).
ADITYA – Data Profiling & Quality Checks
- Run initial profiling:
  - Count rows, columns, unique values.
  - Identify missing values, duplicates, and outliers.
- Create a data quality report:
  - % of missing values per column.
  - List of inconsistent date/time formats.
  - Highlight anomalies (e.g., negative revenue).
MANSI  – Data Cleaning & Standardization
- Apply cleaning operations:
  - Handle missing values (drop or impute).
  - Remove duplicates.
  - Standardize date formats (YYYY-MM-DD).
  - Convert currency/revenue fields to numeric.
- Validate data types (transaction ID, product ID, revenue).
SOWMYATI – Documentation & Version Control
- Prepare a data dictionary:
  - Column names, definitions, data types.
- Maintain GitHub repository:
  - Upload raw + cleaned datasets.
 Division of Work for week :2
Mansi – Database Architect & Data Loader
- Schema Design:
  - Create tables (Customers, Products, Orders, Sales).
  - Define primary keys (ORDER ID , CUSTOMER ID , PEODUCT ID )
  - Set foreign keys to link tables (e.g., Orders .Customer ID → Customers .Customer ID).
  - Assign correct data types (DATE, DECIMAL, INT).
- Data Loading:
  - Import the cleaned dataset (cleanedsalesdata.csv) into SQL tables.
  - Validate row counts and check for nulls/mismatches.
  - Run test queries like:
    `SQL
    SELECT COUNT(*) FROM Sales;
    SELECT COUNT(DISTINCT Customer _ID) FROM Customers;
    `
- Deliverables:  
  - schema .SQL file (table creation scripts).  
  - Loaded database with validation notes.

 HRUSIKESH –  – KPI Query Developer
- Business KPI Queries:
  - Write SQL queries for:
    - Total Revenue
    - Best-Selling Products
    - Revenue by City/Region
    - Peak Purchase Times
  - Use GROUP BY, JOIN, and indexing for efficiency.
- Query Optimization:
  - Ensure queries run quickly on large datasets.
  - Test outputs against sample data for accuracy.
- Deliverables:  
  - queries. SQL file with all KPI queries.  
  - Sample query outputs for validation.
Aditya – Documentation & Version Control
- Documentation:
  - Create a data model diagram (tables + relationships).
  - Write explanations for each KPI query (what it calculates, why it matters).
- Version Control:
  - Maintain GitHub repository:
    - Upload schema. SQL, queries. SQL, and validation notes.
    - Commit with semantic messages (“Week 2: Added schema design and KPI queries”).
  - Update README with Week 2 progress summary.
- Deliverables:  
  - README update.  
  - GitHub commits with proper documentation.  
  - ER diagram showing table relations
