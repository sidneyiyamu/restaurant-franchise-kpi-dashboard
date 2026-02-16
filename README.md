# Restaurant Franchise KPI Dashboard (Power BI)

A Power BI dashboard analysing a multi-branch restaurant franchise across regions (Midlands, North, South).
Built to showcase KPI reporting, targets vs actuals, and interactive filtering by date range and region.

## Dashboard Preview
- File: outputs/dashboard.png

## Key Insights Covered
- Total Revenue (£) and Sales Count
- Top Branch by Revenue
- Revenue by Region
- Daily Revenue Trend by Date & Region
- Revenue Share by Branch
- Target vs Actual with Variance and Status (On Track / Watch / Off Track)

## Files in this Repo
- `dashboard/Restaurant_Franchise_KPI.pbix` – Power BI report file
- `data/` – CSV datasets used in the model
- `notebooks/restaurant_analysis.ipynb` – Python data prep / analysis notebook
- `outputs/` – exported PDF + screenshot preview

## How to Open 
1. Download the repo
2. Open `dashboard/Restaurant_Franchise_KPI.pbix` in Power BI Desktop
3. If prompted, update data source paths to the `data/` folder

## Tools Used
- Power BI Desktop (DAX measures, visuals, slicers)
- Python (Pandas) for data preparation (optional)
- SQL for some reporting tables (e.g. `v_kpi_daily_region.csv`, `v_top_branch_per_region.csv`) were generated from SQL-style views/queries and exported to CSV for Power BI.
  
## Notes
This project uses sample CSV data for portfolio demonstration purposes.

![Dashboard Preview](outputs/dashboard.png)
