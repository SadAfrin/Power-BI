# 📊 Project 1: Sales Data Analysis Dashboard (Power BI)

This is my first Power BI project, built while learning data visualization and dashboard design. It analyzes retail sales data to uncover trends across regions, segments, product categories, and time.

![Dashboard Preview](image.png)

## 🎯 Objective

The goal of this project was to practice:
- Importing and cleaning raw data in Power BI
- Building relationships between multiple tables
- Creating different types of visuals (donut charts, pie charts, funnel charts, line charts, gauge/KPI cards)
- Designing a single-page dashboard that tells a clear story

## 🗂️ Dataset

The dashboard uses a **Superstore-style sales dataset** with two tables:

| Table | Description |
|---|---|
| `Orders` | Order-level transaction data — Order ID, Order Date, Ship Date, Category, Sub-Category, Sales, Quantity, Discount, Profit, etc. |
| `Customer Name` | Customer details — Customer ID, Customer Name, Segment, Region, City, State, Postal Code |

The two tables are connected using the **Customer ID** field.

## 📈 Dashboard Overview

The dashboard, **"Afrin Sales Data"**, includes the following visuals:

- **Sum of Sales by Region** – Donut chart showing sales split across West, East, Central, and South regions
- **Sum of Sales by Segment** – Pie chart comparing Consumer, Corporate, and Home Office segments
- **Sum of Sales by Sub-Category** – Funnel chart ranking product sub-categories (Phones, Chairs, Storage, Tables, etc.) by sales
- **Sum of Sales by Year, Quarter and Month** – Line chart tracking sales trend from 2018–2021
- **KPI Cards** – Gauge visuals summarizing total Sales, Quantity, Profit, and Discount

## 🛠️ Tools Used

- **Power BI Desktop** – for data modeling and dashboard design
- **Excel (.xlsx)** – as the raw data source

## 📁 Files in this Folder

| File | Description |
|---|---|
| `Random_Sales_Data.xlsx` | Raw dataset used to build the dashboard |
| `Sales_Dashboard.pbix` | Power BI project file |
| `image.png` | Screenshot/preview of the final dashboard |
| `notes.md` | My personal learning notes for this project |

## 🧠 What I Learned

- How to build relationships between multiple data tables
- How to choose the right chart type for the right story (donut vs. pie vs. funnel)
- How to use KPI/gauge cards to highlight key metrics at a glance
- How to design a clean, dark-themed dashboard layout

## 🚧 Notes / Known Issues

This is a **learning project**, so a few things are still rough around the edges:
- Some records in the raw data contain placeholder/test values (e.g. region "INDMKB", segment "asa") which slightly skew a couple of charts
- Chart formatting and color consistency can be improved
- Planning to add filters/slicers (e.g. by Year or Region) in a future update

## 🚀 Next Steps

- [ ] Clean up placeholder/test rows in the source data
- [ ] Add slicers for interactive filtering
- [ ] Add a Profit Margin % measure
- [ ] Improve visual consistency (colors, fonts, alignment)

---

*This project is part of my journey learning Power BI and data analytics. Feedback and suggestions are welcome!*
