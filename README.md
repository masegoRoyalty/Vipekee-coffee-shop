# 📊 Project Title

## 🚀 Overview
This project showcases a complete data analysis and visualization solution built using Power BI. The goal of the project is to transform raw data into meaningful insights through data cleaning, modeling, analysis, and interactive dashboard design.

The dashboard is designed to provide stakeholders with clear, actionable insights while maintaining a modern and professional user experience.

---

# 🎯 Project Objectives

- Analyze business performance and trends
- Identify key insights and patterns
- Create interactive visualizations for decision-making
- Build a scalable and optimized data model
- Demonstrate practical Power BI and data analysis skills

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Power BI | Data visualization & dashboard creation |
| Power Query | Data cleaning & transformation |
| DAX | Measures & calculated columns |
| Excel / CSV | Data source |
| Star Schema | Data modeling |

---

# 🧱 Data Modeling

The project follows a **star schema model** for better performance, scalability, and analytical efficiency.

### Fact Table
- Sales / Transactions / Performance metrics

### Dimension Tables
- Date Dimension
- Beverage Dimension
- Time Dimension
- Payment Dimension

---

# 📈 Dashboard Features

## Executive Summary
- High-level KPIs
- Revenue / Sales overview
- Trend analysis

## Performance Analysis
- Top-performing categories
- Seasonal trends
- Time-based analysis

## Interactive Features
- Dynamic filters & slicers
- Drill-through pages
- Tooltips
- Responsive layout

---

# 📊 Key Metrics

- Total Revenue
- Total Orders
- Profit Margin
- Average Transaction Value
- Growth Rate
- Seasonal Performance

---

# 🧠 Key Insights

- Peak sales periods identified through seasonal analysis
- Top-performing products/categories highlighted
- Customer behavior trends discovered
- Business performance fluctuations visualized over time

---

# ⚡ DAX Highlights

Examples of calculations used:

```DAX
Total Sales = SUM(Sales[Revenue])
```

```DAX
Profit Margin = DIVIDE([Profit], [Revenue], 0)
```

```DAX
Season =
SWITCH(
    TRUE(),
    MONTH([Date]) IN {12,1,2}, "Summer",
    MONTH([Date]) IN {3,4,5}, "Autumn",
    MONTH([Date]) IN {6,7,8}, "Winter",
    "Spring"
)
```

---

# 🎨 Dashboard Design Approach

The dashboard was designed with a focus on:

- Clean and modern layout
- Strong visual hierarchy
- Readability and accessibility
- Minimal clutter
- Consistent typography and spacing

---

# 📂 Project Structure

```text
Project Folder
│
├── Data
├── Dashboard
├── Images
├── README.md
└── Documentation

---

# 🔍 Business Questions Answered

- What are the busiest periods?
- Which products/services perform best?
- How does performance change seasonally?
- Which regions/customers generate the most revenue?
- What trends can help improve decision-making?

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Modeling
- DAX Calculations
- Dashboard Design
- Business Intelligence
- Data Visualization
- Analytical Thinking

---

# 🚀 Future Improvements

- Add forecasting models
- Integrate real-time data
- Improve mobile responsiveness
- Add advanced drill-through analytics

---

# 👤 Author

## Otumiseng Masego Sefolo
Aspiring Data Analyst | Power BI Developer | Business Intelligence Enthusiast

- LinkedIn: https://www.linkedin.com/in/otumiseng-masego-sefolo-21352917b/
- Portfolio: https://github.com/masegoRoyalty/Vipekee-coffee-shop
- Email: tumi.sefolo95@gmail.com

---

# ⭐ About This Project

This project was created to strengthen practical skills in:
- Power BI
- Data Analysis
- Dashboard Design
- Business Intelligence
- Storytelling with Data

It also serves as a portfolio project demonstrating the ability to turn raw data into actionable insights.

