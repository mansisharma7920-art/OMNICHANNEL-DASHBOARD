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
    Division of Work for week :3
MANSI  – Dashboard Designer
- Tasks:
  - Import SQL query outputs or Excel dataset into Power BI/Tableau.
  - Design the overall dashboard layout (navigation, filters, slicers).
  - Create visualizations for KPIs:
    - Total Revenue (card/summary view).
    - Best-Selling Products (bar chart).
    - Revenue by City/Region (map or stacked bar).
    - Peak Purchase Times (line chart by hour).
- Deliverables:
  - Draft dashboard with all KPI visuals.
  - Layout template for final presentation.
HRUSIKESH –– Data Visualization Specialist
- Tasks:
  - Refine visuals for clarity and aesthetics (color coding, legends, labels).
  - Add interactive elements (filters by date, product category, city).
  - Ensure consistency in units, formats, and scales.
  - Test dashboard responsiveness with sample queries.
- Deliverables:
  - Polished KPI charts.
  - Interactive dashboard features (slicers, drill-downs).

ADITYA  – Documentation & Integration Lead
- Tasks:
  - Document dashboard components (each KPI → chart type → business meaning).
  - Write a user guide explaining how to navigate and interpret the dashboard.
  - Integrate dashboard files into GitHub repository.
  - Update README with Week 3 progress and screenshots.
- Deliverables:
  - Dashboard documentation (PDF/Markdown).
  - GitHub commits with dashboard files and guide.
Division of Work for week :4
MANSI  – Insight Analyst
- Tasks:
  - Interpret KPIs and dashboard outputs from Week 3.  
  - Identify business trends (e.g., top products, regional performance, peak times).  
  - Highlight anomalies or improvement areas (low-performing categories, inventory gaps).  
  - Draft actionable recommendations (marketing, stocking, pricing strategies).  
- Deliverables:  
  - Insight summary document.  
  - Recommendations section for final report.  
HRUSIKESH – Report Writer
- Tasks:
  - Compile findings into a structured professional report.  
  - Sections: Executive Summary, Methodology, KPIs, Insights, Recommendations.  
  - Include charts and visuals exported from dashboards.  
  - Ensure clarity, conciseness, and professional formatting.  
- Deliverables:  
  - Final written report (Word/PDF).  
  - Polished visuals integrated into the report.  
ADITYA  – Presentation & Documentation Lead
- Tasks:
  - Prepare final presentation slides (PowerPoint/Google Slides).  
  - Summarize Week 1–4 workflow, KPIs, insights, and recommendations.  
  - Add visuals (charts, ER diagram, dashboard screenshots).  
  - Update GitHub repository with final report and presentation files.  
- Deliverables:  
  - Final presentation deck.  
  - Updated GitHub repository with all project artifacts.

