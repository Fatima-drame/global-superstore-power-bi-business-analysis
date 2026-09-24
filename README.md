# Global Superstore Power BI Business Analysis

#### Power BI Data Analytics Project | Sales Performance | Interactive Dashboard

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Preparation](#data-preparation)
- [DAX & Analysis](#dax--analysis)
- [Interactive Dashboard](#interactive-dashboard)
- [Key Analysis Areas](#key-analysis-areas)
- [Business Recommendations](#business-recommendations)
- [Presentation](#presentation)


## Project Overview

The Global Superstore dataset was analysed in Power BI to evaluate sales performance, profitability, customer behaviour and geographic trends.

The project focused on preparing the data, creating calculated columns and DAX measures, applying time intelligence and ranking techniques, and developing an interactive multi page Power BI report.

## Dataset

The analysis used the **Global Superstore dataset** from Kaggle.

| Attribute | Details |
|---|---|
| Records | 51,291 |
| Columns | 21 |
| Key fields | Order ID, Order Date, Ship Date, Ship Mode, Customer, Segment, State, Country, Region, Market, Product, Category, Sub Category, Sales, Quantity, Profit |

## Data Preparation

The dataset was prepared in Power BI before analysis.

Key preparation steps included:

- Converted `Order Date` and `Ship Date` to Date format
- Standardised numeric fields including Sales, Profit and Quantity
- Checked for duplicates and missing values
- Trimmed extra spaces from text fields
- Standardised Region, Category and Sub Category values
- Prepared the data for DAX calculations and interactive reporting

## DAX & Analysis

Calculated columns and measures were created to support the analysis.

**Calculated Columns**

- Total Sales
- Profit Margin
- Shipping Lag
- Sales Category

**Core Measures**

- Total Sales
- Total Profit
- Average Order Value
- Total Quantity Sold
- Distinct Customer Count

**Advanced Analysis**

- `SUMX` for row level sales calculations
- `AVERAGEX` for average sales analysis
- `RANKX` for product ranking
- Filter context for interactive analysis
- Time intelligence for YTD Sales, Prior Year Sales and Month over Month Growth

## Interactive Dashboard

The Power BI report was designed as a multi page interactive dashboard.

### Overview

The overview page provides KPI level visibility into:

- Total Sales
- Total Profit
- Average Order Value
- Total Quantity Sold

It also includes sales trends by Order Date and Ship Date.

<img width="1363" height="757" alt="image" src="https://github.com/user-attachments/assets/9152b594-33b5-41c4-89e4-2e4a2fe5eaa1" />


### Product Analysis

The product analysis page focuses on:

- Sales by Category and Sub Category
- Top 5 Customers
- Top 10 Products by Sales
- Geographic sales performance
- Segment and Ship Mode analysis

Interactive slicers allow users to filter the analysis by:

- Segment
- Ship Mode
- Category

Conditional formatting is used to highlight high profit regions and top selling products.

<img width="1358" height="766" alt="image" src="https://github.com/user-attachments/assets/5c3fdd55-3cfd-4a0b-b563-859ab41620e3" />

## Key Analysis Areas

**Sales Performance**  
Sales increased from **$43K to $60K** between 2011 and 2014.

**Product Performance**  
**Office Supplies generated 93.81% of sales**, with **GBC DocuBind P400** as the top product at approximately **$5.8K**.

**Customer Performance**  
**Andy Reiter** was the top customer at approximately **$5.5K**.

**Geographic Performance**  
The **United States generated approximately $120K** in sales.

## Business Recommendations

1. **Analyse sales growth drivers** and replicate successful strategies.
2. **Keep high demand products well stocked.**
3. **Retain high value customers** through loyalty initiatives.
4. **Prioritise the United States** for marketing and inventory.

## Presentation
[Global Superstore.pdf](https://github.com/user-attachments/files/32613039/Global.Superstore.pdf)

