# Retail Sales & Inventory Power BI Dashboard

An interactive Power BI dashboard analyzing retail sales performance and inventory health across a multi-store bicycle retail business, covering 2016–2018.

## 📊 Overview

This project provides a 360° view of sales performance, brand/category trends, regional distribution, staff productivity, and inventory stock levels for three bike retail stores. It's designed to help business stakeholders quickly spot trends, identify top performers, and flag inventory items that need reordering.

**Key Metrics Tracked:**
- 💰 Total Sales: **$6.66M**
- 📦 Quantity Sold: **6,318**
- 🧮 Quantity on Hand: **13.5K**
- 🏬 Inventory Value: **$19.82M**

## 🏪 Stores Covered

| Store | State | Total Sales |
|---|---|---|
| Baldwin Bikes | NY | $4.7M |
| Santa Cruz Bikes | CA | $1.26M |
| Rowlett Bikes | TX | $0.71M |

## 🖥️ Dashboard Pages

### 1. Executive Summary
- Total sales, quantity sold, quantity in hand, and inventory value KPI cards
- Top selling brands (Electra, Trek, Surly, Sun Bicycles, Pure Cycles, Haro, Heller, Ritchey, Strider)
- Total sales by store
- Sales & quantity trends by year (2016–2018)
- Monthly sales & quantity sold trend
- Sales by customer segment (Low / Medium / High value)
- Sales by state (NY, CA, TX)
- Sales & quantity by product category (Mountain, Road, Cruiser, Electric, Cyclocross, Comfort, Children's bikes)
- Quantity sold by staff member

### 2. Detailed Data View
- **Inventory table** — Store, Product ID, Total Quantity, and Stock Level (Available / Reorder) flags
- **Brand performance table** — Store, Brand, State, and Quantity Sold breakdown
- **Monthly sales trend table** — Year, Quarter, Month, Total Sales, and Month-over-Month % change

## 🔍 Key Insights

- **Baldwin Bikes (NY)** is the dominant store, contributing ~70% of total sales.
- **Electra and Trek** are the top-performing brands by units sold across all stores.
- Sales show a general upward trend from 2016 to 2018, with **June 2017** and **January 2018** as standout months.
- A significant share of products are flagged **"Reorder"**, indicating stock levels below threshold and a need for inventory replenishment.
- **Mountain Bikes** lead the category-wise sales, followed by Road Bikes and Cruisers.

## 🛠️ Tools & Techniques Used

- **Power BI Desktop** — report design and data modeling
- **DAX** — calculated measures (e.g., Total Sales MoM%, KPI cards)
- **Power Query** — data cleaning and transformation
- **Data Modeling** — relationships across Sales, Inventory, Product, Store, and Staff tables
- **Slicers & Filters** — Year, Month, and Store Name for interactive exploration
- **Conditional Formatting** — color-coded Stock Level indicators (Available/Reorder)

## 📁 Repository Contents
- **Retail_Sales_Inventory.pbix     # Power BI project file
- **README.md                        # Project documentation
- **screenshots/                     # Dashboard preview images
- **PDF                              #Project PDF
