# 🍫 Chocolate Sales Dashboard — Power BI

An interactive Business Intelligence dashboard built with Power BI to analyze chocolate sales performance across countries, products, and sales representatives.

This project demonstrates data modeling, KPI design, DAX measures, and user-centric dashboard development.

---

## 📊 Dashboard Overview

![Dashboard Overview](images/dashboard_overview.png)

---

## 🎯 Business Objectives

The dashboard was designed to:

- Monitor overall revenue performance  
- Track Year-over-Year growth  
- Analyze average sales and seasonality  
- Identify top-performing products  
- Highlight best sales representatives  
- Visualize sales trends using moving averages  

---

## 📐 Key KPIs Implemented

- Total Sales  
- Average Sales  
- YoY Sales Growth %  
- MoM Growth %  
- 3-Month Moving Average  
- Top 5 Products by Sales  
- Best Sales Person  
- Performance Indicators with Conditional Formatting  

---

## 🧠 Example DAX Measure

### 3-Month Moving Average

\`\`\`DAX
3 Month Moving Average =
AVERAGEX(
    DATESINPERIOD(
        'Calendar'[Date],
        MAX('Calendar'[Date]),
        -3,
        MONTH
    ),
    SUM('Chocolate Sales'[Amount])
)
\`\`\`

---

## 🛠 Technical Stack

- Power BI Desktop  
- DAX  
- Data Modeling  
- Time Intelligence Functions  
- Interactive Filtering  

---

## 📂 Repository Structure

\`\`\`
├── data/
│   └── Chocolate Sales.csv
├── reports/
│   ├── ChocolateSales.pbix
│   └── ChocolateSales.pbit
├── images/
│   ├── dashboard_overview.png
│   └── ChocolateSales.pdf
└── README.md
\`\`\`

---

## 📦 File Explanation

ChocolateSales.pbix  
Full Power BI report including model, DAX measures, relationships, and visuals.

ChocolateSales.pbit  
Power BI template version (without embedded data).

Chocolate Sales.csv  
Source dataset used for analysis.

---

## 🚀 How to Use

1. Download the .pbix file  
2. Open it using Power BI Desktop  
3. Explore filters and interactive visuals  

---

## 📈 What This Project Demonstrates

- End-to-end BI workflow  
- Data preparation & modeling  
- Advanced DAX (time intelligence)  
- KPI-driven dashboard design  
- Business-oriented storytelling  

---

## 👤 Author

Ismael Fofana  
GitHub: https://github.com/Kismaelo-datahub  
LinkedIn: https://www.linkedin.com/in/ismael-fofana-77a258259/

