# Financial-Reconciliation-Dashboard
An end-to-end data analytics project designed to track and visualize reconciliation status across 20,000+ financial transactions, built from scratch using Excel for data cleaning and Power BI for insightful, executive-ready dashboards.

This dashboard enables teams to:
- Identify mismatches and discrepancies in transaction records
- Track reconciliation trends over time
- Monitor branch-level transaction activities
- Highlight approvals and pending issues

## Tools Used

- **Microsoft Excel** – Initial data cleaning and transformation
- **Power BI** – Data modeling, DAX calculations, and interactive visualizations
- **DAX** – Used for KPI metrics, trends, conditional formatting, and slicers
- **GitHub** – Version control and documentation

---

## Data Cleaning Process (Excel)

- **Handled missing values** in key columns like `Date`, `Currency`, and `Comments`
- Created a `MonthYear` column from `Date` to support trend analysis
- Cleaned and standardized fields like:
  - `Approval Status` → values: Approved, Pending, Rejected, Unknown
  - `Reconciliation Status` → values: Matched, Mismatched, Pending, Unknown
- Used logic to populate empty `Comment` fields based on `Approval Status`
- Replaced blanks in `Currency` based on the most common currency per branch

## Dashboard Highlights

This Power BI dashboard presents a structured view of financial transaction integrity and reconciliation. Key sections include:

### KPI Indicators
- **Total Transactions**
- **Matched Transactions**
- **Mismatched Transactions**
- **Pending Transactions**

### 📈 Visual Elements

- **Approval Status Trend (Bar Chart)**  
  Shows monthly status distribution: Matched, Mismatched, Pending.

- **Transactions over time (Line Chart)**  
  Total transactions evolve.

- **Top 5 Transactions by Branch (Stacked Bar)**  
  Visualizes volume of transactions per branch; highlights volume discrepancies using conditional formatting.

- **Currency Breakdown (Pie Chart)**  
  Distribution of transaction values across multiple currencies.

- **Reconciliation Status Distribution (Donut Chart)**  
  Quick overview of how many transactions are matched, mismatched, pending, or adjusted.

- **Interactive Slicers**  
  Slicers for:
  - Reconciliation Status
  - Approval Status
  - Branch
  - Processed by
  - Date (with MonthYear granularity)



