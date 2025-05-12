# Product Profitability & Inventory Dashboard

This Power BI dashboard was created as a portfolio project to simulate retail analytics across product performance, returns, and inventory management.

## Table of Contents
- [Overview](#overview)
- [Dashboards](#dashboards)
  - [1. Product Profitability Dashboard](#1-product-profitability-dashboard)
  - [2. Returns & Regional Dashboard](#2-returns--regional-dashboard)
  - [3. Inventory Efficiency Dashboard](#3-inventory-efficiency-dashboard)
  - [4. Product Detail Dashboard (Drill-through)](#4-product-detail-dashboard-drill-through)
- [Data Model](#data-model)
- [Key Measures](#key-measures)
- [Files Included](#files-included)
- [Tools Used](#tools-used)
- [How to Open](#how-to-open)

## Overview

The dashboard addresses the following questions:
- Which products generate the highest and lowest profit?
- What percentage of inventory is tied up in low-performing products?
- What are the return rates by product and reason?
- Are certain regions overstocked or understocked?
- How do profit and return metrics trend over time?

## Dashboards

### 1. Product Profitability Dashboard
- Total Sales, Total Profit, Profit Margin
- Profit trend over time
- Return Rate by Product

### 2. Returns & Regional Dashboard
- Return Count, Return Rate, Inventory Turnover
- Return reasons breakdown
- Total Profit by Region (map visual)

### 3. Inventory Efficiency Dashboard
- Inventory Value, Stock Cover (days)
- Inventory Value by Product (treemap)
- Inventory table with average cost, stock quantity, and inventory value

### 4. Product Detail Dashboard (Drill-through)
- Total Sales, Profit, Return Rate for a selected product
- Profit trend and return reason breakdown
- Product-specific inventory value

## Data Model

The model includes four main tables:
- **Sales**: Order ID, Product, Sales, Quantity, Profit, Date, Region
- **Returns**: Order ID, Product, Return Date, Reason
- **Inventory**: Product ID, Product Name, Stock Quantity, Reorder Point, Inventory Cost
- **Customers** (optional): Customer ID, Segment, Region

## Key Measures

- Total Sales ($)
- Total Profit ($)
- Profit Margin (%)
- Inventory Value ($)
- Return Rate (%)
- Inventory Turnover (x)
- Stock Cover (days)

## Files Included

- `product-profitability-inventory-dashboard.pbix` – Power BI file
- `product-profitability-inventory-dashboard.pdf` – Exported PDF of the dashboard visuals

## Tools Used

- Power BI Desktop
- DAX for calculated measures
- Relationships, model design, bookmarks, slicers, and drill-throughs

## How to Open

1. Download the `.pbix` file from this repository
2. Open it using **Power BI Desktop**
   - [Download Power BI Desktop](https://powerbi.microsoft.com/desktop/)
