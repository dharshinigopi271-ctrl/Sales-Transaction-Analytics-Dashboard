# 💰 Sales Transaction Analytics Dashboard

## 📌 Overview

The **Sales Transaction Analytics Dashboard** is a Power BI project developed to analyze sales performance and transaction activity using interactive KPIs, sales trends, voucher-type analysis, and time-based visualizations.

## 📊 Key KPIs

* Total Sales
* Total Transactions
* Average Sales
* Minimum Sale
* Maximum Sale

## 📈 Dashboard Analysis

The dashboard provides analysis of:

* Monthly sales trends
* Sales by voucher type
* Quarter-wise sales distribution
* Year-wise sales performance
* Transactions by voucher type
* Date-based sales trends

## 🎛️ Interactive Filters

The dashboard includes slicers for:

* Year
* Month
* Quarter
* Voucher Type

## 🗂️ Data Model

The project uses a single table:

* **SalesData** – Main sales transaction table

The dataset contains fields such as Date, Month, Quarter, Year, and Voucher Type.

## ⚠️ Data Quality Consideration

The Month, Quarter, and Year fields should be validated against the main **Date** field before reporting.

For accurate time-based analysis, Year, Quarter, Month, and Month Number can be derived directly from the verified Date field or generated through a dedicated Calendar table.

## 🛠️ Tools Used

* Microsoft Power BI
* DAX
* Power Query
* Data Visualization
* Data Analysis

## 🎯 Project Objectives

* Analyze overall sales performance
* Monitor transaction volume
* Identify monthly and yearly trends
* Analyze voucher types
* Compare quarterly sales distribution
* Provide interactive business intelligence reporting

## 📁 Files

* `Sales_Transaction.xlsx`
* `Sales_Transaction_Dashboard.pbix`

## 📌 Conclusion

This project demonstrates practical Power BI skills in sales analytics, KPI development, interactive visualization, time-based analysis, and business intelligence reporting.
