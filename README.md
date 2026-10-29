# Pizza Sales Dashboard — Microsoft Excel

An interactive Excel dashboard built to explore pizza sales performance, order volume, pizza-size distribution, and monthly trends.

## Dashboard Preview

Open `images/dashboard_preview.png` to see the dashboard screenshot, if included in this repository.

## Project Objectives

- Summarize overall sales and order volume.
- Compare sales across pizza sizes/categories.
- Explore monthly sales trends.
- Compare order counts by month.
- Provide an interactive month filter for exploring the data.

## Key Metrics

- **Total Sales:** 817,860.05 (currency not specified in the workbook)
- **Unique Orders:** 21,350
- **Order-detail rows:** 48,620

> Note: Confirm the currency and metric definitions before using the figures in a formal business report. The workbook's dashboard labels the second KPI as “Total Count”; the source `orders` table contains 21,350 order records.

## Tools and Excel Features

- Microsoft Excel
- Pivot tables / summarized tables
- Pivot charts and standard charts
- Month slicer / interactive filtering
- KPI cards
- Dashboard layout and formatting

## Workbook Contents

The workbook contains these sheets:

| Sheet | Purpose |
|---|---|
| `pizza_types` | Pizza names, categories, and ingredients |
| `pizzas` | Pizza identifiers, sizes, and prices |
| `order_details` | Order line items, quantities, pizza attributes, and sales values |
| `orders` | Order dates, times, hours, and month fields |
| `Sheet3` | Summary tables used for dashboard analysis |
| `Sheet1` | Dashboard canvas |
| Other sheets | Additional source/export or summary sheets retained from the original workbook |

## Analysis Workflow

1. **Inspect the source tables** to understand pizza types, sizes, prices, orders, and line items.
2. **Prepare and organize fields** used for analysis, including dates/months, quantities, prices, and total sales.
3. **Summarize the data** using Excel summary/PivotTable-style tables.
4. **Build charts** for sales distribution, order count by pizza size, monthly sales, and monthly order count.
5. **Add a month slicer** so viewers can interact with the dashboard.
6. **Present key metrics** in KPI cards and format the dashboard for readability.

## How to Use

1. Download or clone this repository.
2. Open `data/pizza_sales_dashboard.xlsx` in Microsoft Excel (desktop Excel is recommended).
3. Go to the `Sheet1` tab to view the dashboard.
4. Use the month slicer to filter the dashboard, if slicer connections are supported by your Excel version.
5. Explore the source tables to inspect the underlying data.

Some Excel-specific interactive objects may not work in alternative spreadsheet applications. For best results, use Microsoft Excel.

## Repository Structure

```text
pizza-sales-excel-dashboard/
├── data/
│   └── pizza_sales_dashboard.xlsx
├── documentation/
│   └── project_documentation.pdf
├── images/
│   └── dashboard_preview.png
├── DATA_DICTIONARY.md
├── README.md
├── LICENSE
└── .gitignore
```

## Notes and Limitations

- The workbook's dashboard shows sales as `817860.05`; the currency is not explicitly confirmed in the workbook.
- Validate chart totals and filter behavior in Excel before presenting results.
- If the dataset came from a third-party source, add its original source link and required attribution here.
- This repository is an Excel analytics project; it does not contain a separate application or executable code.

## Author

Add your name and LinkedIn/GitHub profile here before publishing.
