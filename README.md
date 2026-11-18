# Lenskart India Sales Dashboard

An interactive Power BI dashboard for exploring Lenskart India sales performance from 2022 to 2025. It summarizes sales and order metrics, with breakdowns by month, customer age group, sales channel, region, product type, and discount level.

## Project objectives

- Monitor key sales and order performance indicators.
- Compare monthly sales across years.
- Understand sales distribution by age group, channel, region, and product category.
- Explore how order counts vary by discount level.

## Dashboard filters

- **Year:** 2022, 2023, 2024, and 2025
- **Region:** Central, East, North, South, and West

## Key results

| Metric | Result |
|---|---:|
| Total sales | ₹78.4 Cr |
| Units sold | 300K |
| Total orders | 150K |
| Average order value | ₹5K |

### Sales by age group

| Age group | Sales |
|---|---:|
| 18–25 | ₹13.08 Cr |
| 26–35 | ₹16.69 Cr |
| 36–45 | ₹16.69 Cr |
| 46–55 | ₹16.67 Cr |
| 56–64 | ₹15.30 Cr |

### Sales by channel

| Channel | Share |
|---|---:|
| Online | 49.91% |
| Offline | 50.09% |

Online and offline sales are nearly evenly split.

### Sales per city by region

| Region | Sales per city |
|---|---:|
| Central | ₹3.45 Cr |
| East | ₹3.43 Cr |
| South | ₹3.42 Cr |
| West | ₹3.41 Cr |
| North | ₹3.37 Cr |

Sales per city are close across all five regions, at about ₹3.4 Cr each.

### Sales by product type

| Product type | Share |
|---|---:|
| Eyeglasses | 25.23% |
| Contact Lenses | 24.97% |
| Computer Glasses | 24.92% |
| Sunglasses | 24.87% |

Sales are distributed almost equally across the four product categories.

### Orders by discount

| Discount | Orders |
|---|---:|
| 0% | 30K |
| 5% | 30K |
| 10% | 38K |
| 15% | 30K |
| 20% | 15K |
| 25% | 7K |

The 10% discount level has the highest order count among the levels shown. Order counts are lower at the 20% and 25% discount levels.

### Monthly sales trend

The dashboard compares monthly sales from January to December across 2022–2025. Its summary describes sales as steady at approximately ₹19.5 Cr per year.

## Key takeaways

- The report shows total sales of ₹78.4 Cr and 300K units sold.
- The 26–35 and 36–45 age groups have the highest sales, at ₹16.69 Cr each.
- Online and offline channels contribute almost equal shares.
- Central has the highest sales per city and North the lowest, with a small difference between them.
- Product sales are nearly evenly distributed across four categories.
- Orders peak at the 10% discount level and decline at higher discount levels.

## Project file

- `Lenskart-Sales-Analytics.pbix` — Power BI report with the dashboard pages and embedded data model.

## How to open the report

1. Download `Lenskart-Sales-Analytics.pbix` from this repository.
2. Open it in Microsoft Power BI Desktop.
3. Use the Year and Region filters to explore the dashboard.
4. Select chart values to interact with the other visuals.
5. View the second report page for the written findings.

## Tools and techniques

- Microsoft Power BI Desktop
- DAX measures for sales and order metrics
- KPI cards, line chart, bar and column charts, donut charts, and slicers
- Interactive filtering and cross-highlighting

## Data and sharing note

The PBIX contains an embedded data model. The original data source, collection period, and redistribution license are not identified here. Confirm the data’s source and permission to share before making the repository public. If the data is based on a real company or customers, ensure it contains no confidential or personal information. Add the source and attribution here once confirmed.
