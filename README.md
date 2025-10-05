## 🔗 Live Dashboard

<p align="center">
  <a href="https://app.powerbi.com/view?r=https://app.powerbi.com/view?r=eyJrIjoiOWEwYzU4MDEtNzBjOC00NWQxLWI4N2UtOTY1ZTUyNzBjYTc3IiwidCI6ImZkMDIwMmRjLTA0ZjUtNGYxMy04Mzg5LTIyODA5MTliY2ZjNiJ9" target="_blank">
    <img src="https://img.shields.io/badge/View%20Dashboard-PowerBI-yellow?style=for-the-badge&logo=powerbi" alt="Power BI Dashboard"/>
  </a>
</p>


# BlinkIT-Grocery-Sales-Dashboard-Power-BI-Project-
BlinkIT Grocery Sales Dashboard (Power BI Project) A comprehensive Power BI dashboard analyzing BlinkIT’s grocery sales, outlet performance, and customer satisfaction. Built using DAX, Excel data, and Power BI visuals to uncover sales patterns, outlet performance insights, and optimization opportunities.

## 📖 Project Description
This Power BI project provides a comprehensive analysis of **BlinkIT’s grocery sales performance**, **customer satisfaction**, and **inventory distribution**.  
It helps identify **key trends, sales patterns, and optimization opportunities** using interactive Power BI visualizations and DAX measures.

The dashboard gives a 360° view of BlinkIT’s retail performance — covering sales by outlet size, location, fat content, and item type — allowing stakeholders to make data-driven decisions.


## 🎯 Business Objective
To conduct a detailed analysis of BlinkIT’s sales performance and customer satisfaction, enabling better strategic planning and operational improvements.

---

## 🧮 Key Performance Indicators (KPIs)
1. **Total Sales:** Overall revenue generated from all items sold.  
2. **Average Sales:** Average revenue per item sold.  
3. **Number of Items:** Total count of distinct items sold.  
4. **Average Rating:** Average customer rating across products.

---

## 📊 Chart Requirements & Objectives

| S.No | Chart Title | Objective | Chart Type |
|------|--------------|------------|-------------|
| 1 | Total Sales by Fat Content | Analyze the impact of fat content on total sales | Donut Chart |
| 2 | Total Sales by Item Type | Compare performance of different product types | Bar Chart |
| 3 | Fat Content by Outlet for Total Sales | Compare fat type sales across outlets | Stacked Column Chart |
| 4 | Total Sales by Outlet Establishment | Evaluate how outlet type or age influences sales | Line Chart |
| 5 | Sales by Outlet Size | Correlation between outlet size and total sales | Donut Chart |
| 6 | Sales by Outlet Location | Sales distribution across different outlet locations | Funnel Map |
| 7 | All Metrics by Outlet Type | Overview of all KPIs by outlet type | Matrix Card |

---

## 🧠 DAX Measures Used

```DAX
Total Sales = SUM('BlinkIT Grocery Data'[Sales])
Avg Sales = AVERAGE('BlinkIT Grocery Data'[Sales])
No of Items = COUNTROWS('BlinkIT Grocery Data')
Avg Rating = AVERAGE('BlinkIT Grocery Data'[Rating])


