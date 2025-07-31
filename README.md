# PowerQuery Data Cleaning Project

This project demonstrates how to clean and transform raw retail sales data using **Power Query Editor in Power BI**. The cleaned dataset is now prepared for further analysis or dashboard creation.

---

## Files Included

- `DataCleaning.pbix`: Power BI project file with cleaned and transformed data.
- Raw datasets:
  - `Customers.csv`
  - `Products.csv`
  - `Regions.csv`
  - `Returns_1997-1998.csv`
  - `Stores.csv`
  - `Transactions_1997.csv`
  - `Transactions_1998.csv`

---

## What are the Objectives?

To clean and consolidate transactional retail data for the years 1997–1998 by:
- Removing duplicates and nulls
- Standardizing column formats
- Basic merging operations in PowerQuery
- Making the dataset ready for business analysis

---

## Tools Used:

- **Power BI Desktop**
- **Power Query Editor**
- CSV datasets (loaded as source)

---

## Key Data Cleaning Steps

- Combined `Transactions_1997.csv` and `Transactions_1998.csv` into one dataset
- Removed rows with missing or invalid data (e.g., null product IDs)
- Created relationships between tables using unique keys
- Joined supporting tables
- Transformed data types
- Filtered out test or demo data
- Renamed columns for consistency

---

## How to View the Project

1. Open the `DataCleaning.pbix` file in Power BI Desktop.
2. Go to **Power Query Editor** (Transform Data) to view all steps.
3. Use the cleaned data for visualizations or further modeling.


