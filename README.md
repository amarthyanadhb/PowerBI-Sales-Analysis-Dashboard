# Power BI Sales and Profit Analysis Dashboard

## 📊 Project Overview

This repository showcases a comprehensive Power BI dashboard project demonstrating advanced data visualization and business intelligence capabilities. The dashboard provides interactive insights into sales performance, profitability metrics, and operational analytics across multiple dimensions.

**Data Last Updated:** November 8, 2025

## ✨ Key Features

### Interactive Visualizations
- **Sales Performance Metrics**: Total Sales (118.73M), Total Profit (16.89M), Total Quality (1.13M)
- **Comprehensive KPIs**: Gross Sales (127.93M), COGS (101.83M), Product Count (700)
- **Multi-dimensional Analysis**: By Product, Segment, Country, Month, and Year

### Advanced Power BI Capabilities
1. **DAX Calculations**: Custom measures for LY Sales, Growth %, and comparative analysis
2. **Waterfall Charts**: Category and year-wise sales progression visualization
3. **Hierarchy Drill-Through**: Country-level data exploration with interactive navigation
4. **Bookmarks**: Dynamic filtering by Day, Year, Quarter, and Month
5. **Donut Charts**: Region-wise profit distribution (Central, East, South, West)
6. **Conditional Formatting**: Color-coded subcategory performance metrics
7. **Interactive Filters**: Year, Month, and Product-based slicers

## 📸 Dashboard Screenshots

### Main Dashboard
![Sales and Profit Report Dashboard](screenshots/dashboard-main.png)
*Comprehensive overview displaying key metrics, product analysis, segment distribution, country-wise sales, and monthly trends*

### DAX Calculations
![DAX Analysis](screenshots/dax-calculations.png)
*Year-over-year sales comparison with LY Sales, Total Sales, and Growth percentage calculations*

### Waterfall Chart Analysis
![Waterfall Chart](screenshots/waterfall-chart.png)
*Sum of Sales by Category and Year showing incremental changes across Furniture, Technology, and Office Supplies*

### Hierarchy Visualization
![Hierarchy Analysis](screenshots/hierarchy.png)
*Country-level sales hierarchy enabling drill-through capabilities*

### Bookmark Functionality
![Bookmarks](screenshots/bookmarks.png)
*Dynamic time-based filtering with Sales, COGS, and Profit analysis by Day, Year, Quarter, Month*

### Regional Analysis
![Donut Chart - Regional Profit](screenshots/donut-chart.png)
*Profit distribution across Central, East, South, and West regions*

### Drill-Through Page
![Drill Through](screenshots/drill-through.png)
*Interactive drill-through functionality for detailed regional analysis*

### Conditional Formatting
![Conditional Formatting](screenshots/conditional-formatting.png)
*Subcategory-wise performance table with color-coded sales, profit, quantity, and discount metrics*

### Navigation Home
![Home Navigation](screenshots/home.png)
*Financial Analysis Dashboard home with navigation buttons to Sales Report and Profit Analysis sections*

## 🛠️ Technical Implementation

### Power BI Components Used
- **Power Query**: Data import and transformation
- **Data Modeling**: Relationships and calculated columns
- **DAX (Data Analysis Expressions)**: Custom measures and KPIs
- **Visualizations**: Bar charts, line charts, donut charts, waterfall charts, tables
- **Interactive Features**: Slicers, filters, drill-through, bookmarks, buttons
- **Formatting**: Conditional formatting, custom themes, responsive design

### Key Metrics & Measures
```dax
// Sample DAX Measures
Total Sales = SUM(Sales[Sales Amount])
Total Profit = SUM(Sales[Profit])
Growth % = DIVIDE([Total Sales] - [LY Sales], [LY Sales], 0)
COGS = SUM(Sales[Cost of Goods Sold])
```

## 📁 Repository Structure
```
PowerBI-Sales-Analysis-Dashboard/
├── screenshots/
│   ├── dashboard-main.png
│   ├── dax-calculations.png
│   ├── waterfall-chart.png
│   ├── hierarchy.png
│   ├── bookmarks.png
│   ├── donut-chart.png
│   ├── drill-through.png
│   ├── conditional-formatting.png
│   └── home.png
└── README.md
```

## 🎯 Business Insights

### Performance Highlights
- **Total Revenue**: $118.73M in sales with $16.89M profit
- **Top Performing Products**: Paseo and VTT leading in sales and profit
- **Geographic Distribution**: United States dominates with 21.98% of total sales
- **Segment Analysis**: Government segment leads with 44.27% of sales
- **Seasonal Trends**: Monthly variations tracked across 2014-2017 period

### Key Findings
- Strong performance in Technology and Office Supplies categories
- Consistent growth trends from 2014 to 2017
- Regional profit distribution shows balanced performance across zones
- Subcategory-level analysis reveals optimization opportunities

## 🚀 Power BI Concepts Demonstrated

### Q1: Power BI Platform
Understanding of Power BI ecosystem including Desktop, Service, and Mobile applications with SaaS capabilities for enterprise analytics.

### Q2: DAX Implementation
Advanced calculated measures for year-over-year comparisons and growth percentage calculations.

### Q4: Waterfall Visualization
Incremental analysis showing category-wise contribution to total sales across multiple years.

### Q5: Hierarchy Implementation
Geographic hierarchy enabling interactive drill-down from country to regional levels.

### Q6: Bookmark Functionality
Dynamic page state management for filtering data by different time dimensions.

### Q7(a): Donut Chart
Regional profit distribution visualization with interactive selections.

### Q7(b): Drill-Through
Detailed analysis capability from summary to granular regional data.

### Q8: Conditional Formatting
Data-driven color coding for immediate identification of performance patterns.

### Q9: Dashboard Integration
Cohesive navigation structure with home page and multiple interconnected reports.

## 📚 Learning Outcomes

This project demonstrates proficiency in:
- Data visualization best practices
- Interactive dashboard design
- DAX formula creation and optimization
- Power BI feature implementation
- Business intelligence storytelling
- User experience design for analytics

## 🔗 Live Dashboard

The dashboard is published on Power BI Service and demonstrates real-time interactivity with filters, drill-through capabilities, and responsive design.

## 👤 Author

**Amarthya Nadhb**
- GitHub: [@amarthyanadhb](https://github.com/amarthyanadhb)

## 📝 License

This project is created for educational and portfolio purposes.

---

*For questions or collaboration opportunities, please feel free to reach out through GitHub.*
