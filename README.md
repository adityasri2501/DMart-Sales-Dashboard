# DMart Sales Dashboard

This repository contains a retail sales analytics dashboard built around DMart grocery order data. The project combines real-world sales records with a Power BI report to help analyze sales trends, category performance, regional variations, and profitability.

## Project Overview

The dataset includes transaction-level order records for grocery and retail categories such as:

- Food Grains
- Fruits & Veggies
- Beverages
- Bakery
- Oil & Masala
- Snacks
- Eggs, Meat & Fish

The dashboard is designed to support business analysis around:

- total sales and profit trends
- category-wise performance
- sub-category contribution
- region and city comparisons
- discount vs. profit analysis
- customer purchasing patterns

## Repository Contents

```text
DMart-Sales-Dashboard/
├── Dataset/
│   ├── DMart.csv
│   └── DMart_Grocery_Sales_-_Retail_Analytics_Dataset.csv
├── DMart Sales Dashboard.pbix
├── README.md
└── .gitignore
```

### Files

- `DMart Sales Dashboard.pbix` — Power BI report/dashboard file
- `Dataset/DMart.csv` — DMart sales dataset
- `Dataset/DMart_Grocery_Sales_-_Retail_Analytics_Dataset.csv` — main retail analytics dataset used for sales analysis

## Dataset Schema

The retail dataset contains the following columns:

| Column | Description |
| --- | --- |
| Order ID | Unique order identifier |
| Customer Name | Name of the customer |
| Category | Main product category |
| Sub Category | Specific product sub-category |
| City | City where the order was placed |
| Order Date | Date of purchase |
| Region | Region classification (North, South, East, West, Central) |
| Sales | Revenue generated from the order |
| Discount | Discount percentage applied |
| Profit | Profit earned from the order |
| State | State associated with the order |

The data appears to represent Indian retail transactions, predominantly from Tamil Nadu, with orders spanning several years and multiple regions.

## Business Use Cases

This repository can be used to answer questions such as:

- Which category contributes the most revenue?
- Which sub-category has the highest profit margin?
- Which regions generate the strongest sales?
- How do discounts influence profit?
- Are sales increasing or declining over time?
- Which cities or customer segments drive the most value?

## Dashboard Features

The Power BI dashboard is intended to visualize:

- revenue and profit trends over time
- category and sub-category sales distribution
- regional performance comparison
- city-level sales insights
- discount impact on profitability
- top-selling product segments

## How to Use

1. Open `DMart Sales Dashboard.pbix` in Power BI Desktop.
2. Confirm the dataset file path points to the CSV data in the `Dataset/` folder.
3. Refresh the data model if prompted.
4. Use the dashboard visuals to explore sales, profit, and category performance.

## Data Notes

- The project is focused on grocery and retail sales analytics.
- The data contains sales, discount, and profit fields, making it suitable for exploratory analysis and KPI reporting.
- The dataset can be used for both descriptive analytics and dashboard-based storytelling.

## Requirements

- Power BI Desktop
- CSV files from the `Dataset/` folder
- Basic understanding of retail analytics/reporting concepts

## License

This repository does not currently include a license file. If you plan to publish or distribute it publicly, consider adding an appropriate open-source license.

## Contact

For questions or collaboration, please use the repository owner profile on GitHub.
