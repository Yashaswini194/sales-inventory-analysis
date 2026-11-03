# Sales and Inventory Analysis Dashboard

https://yashaswini194.github.io/sales-inventory-analysis/dashboard/

An analysis of retail sales and inventory data, built to show total sales, stock levels, pricing and where inventory is piling up or running out.

## Dataset

`data/data.xlsx` has 876 records with these columns:

| Column | Meaning |
| --- | --- |
| Price | Price of the item |
| Sales | Units sold |
| Stock | Units in stock |
| Price_Sales_Ratio | Price divided by sales |
| Sales_Stock_Ratio | Sales divided by stock |

The `Summary` sheet in the workbook holds the headline totals.

## Key figures

- Total sales: 84,830 units
- Total stock: 1,478,875 units
- Average price: 1.61
- Estimated revenue (price × sales): about 138,888
- Records with no stock: 16
- Records with stock but no sales: 50

## What I did

- Organised the sales and inventory data in Excel and used formulas and PivotTables to summarise sales and stock performance.
- Built a Power BI dashboard with KPI cards and charts for sales and stock.
- Built an interactive web version of the dashboard (`dashboard/index.html`) with a price-band filter, distribution charts, a stock vs sales scatter plot and a top 10 table.

## Tools

Excel, Power BI, HTML, CSS and JavaScript.

## View the dashboard

Download this repository and open `dashboard/index.html` in any browser. No installation is needed.

## Notes

- Estimated revenue assumes the Sales column is units sold.
- The dataset has no dates or product names, so there is no time trend and records are identified by row number.

## Files

- `data/data.xlsx`: the dataset
- `dashboard/index.html`: the interactive dashboard
- `SalesInventory.pbix`: the Power BI report: \SalesInventory.pbix':the Power BI report'
