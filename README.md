# Retail Store Sales Analysis Dashboard

## Overview
This Power BI dashboard provides a comprehensive view of retail performance across store locations, types, and categories. It integrates sales, cost, and profitability metrics to support strategic decision-making.

## Key Features
- **Sales Summary**: 
<img width="1920" height="1080" alt="Screenshot (1562)" src="https://github.com/user-attachments/assets/48486f00-a82a-4b53-a8ae-c6addc7af811" />

  - Total Sales: £4bn
  - Gross Margin: £2bn
  - YTD Sales: £1.39bn

- **Visualizations**:
  - **Geo Map**: Bubble size proportional to store sales volume across U.S. regions.
  - **Sales by Store Type**: Breakdown across Digital, Core, and Local formats.
  - **Sales by Department**: Comparative analysis across Clothing, Electronics, Grocery, etc.

- **Retail Cost & KPI Slide**:
<img width="1920" height="1080" alt="Screenshot (1563)" src="https://github.com/user-attachments/assets/3584d603-3c10-4ee2-910b-15897efb6f12" />

  - Tabular view with conditional formatting for metrics like wages, sales targets, and goal achievement.
  - Line chart tracking sales target progress.
  - Bubble chart showing rent impact vs. store size, segmented by store type.

## Data Model
<img width="1920" height="1080" alt="Screenshot (1564)" src="https://github.com/user-attachments/assets/43b31fe3-c538-436a-b4cc-6fbd604e16e8" />

- **Star Schema** with two fact tables:
  - `Retail Sales`
  - `Retail Cost`
- Dimension tables:
  - `Date`, `Store Details`, `Categories`
- Relationships carefully designed with correct cardinality and filter direction to ensure data integrity.

## Usage
Ideal for retail stakeholders, finance teams, and operations managers seeking insights into store-level performance, cost efficiency, and strategic planning.

## Author
Sidharth — Freelance Data Analyst | Retail & Finance Analytics | Power BI | SQL | Python
