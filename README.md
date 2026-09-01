# Business Data Analysis Portfolio

## Project Overview
This portfolio showcases end-to-end business and market data analysis skills applied to two real-world datasets:

1. **Adidas Sales Analysis** – Retail performance analysis of footwear and apparel sales (2020–2021) using Excel.
2. **German Cars Market Analysis** – Exploratory and statistical analysis of the German used/new car market (AutoScout24 data, 2011–2021) using Python.

Both projects demonstrate data cleaning, exploratory analysis, KPI/insight generation, visualization, and actionable business recommendations.

---

## 1. Adidas Sales Analysis (Excel)

### Overview
Analysis of Adidas footwear and apparel sales data to identify performance trends across retailers, product categories, regions, sales methods, and time periods.

### Dataset
- ~9,650 transactional records  
- Key fields: Retailer, Date, Region, State, City, Product, Price, Units Sold, Total Sales, Operating Profit, Margin, Sales Method, Gender, Category  
- Time period: 2020–2021 (note: 2020 geographic coverage is limited)

### Tools Used
- Microsoft Excel
- Native Pivot Tables
- SUMIF / ranking formulas
- Calculated fields and percentage shares

### Analysis Performed
- Data preparation and calculated metrics
- Multi-dimensional Pivot Table analysis (Retailer, Product, Region, Method, Year)
- KPI calculation (Sales, Units, Profit, Avg Price, Avg Margin)
- Ranking & Top-N analysis
- Year-over-year comparison (with data completeness caveats)
- Segmentation by Sales Method and Gender
- Retailer and Product scorecards + written insights

### Key Insights (Summary)
- Men’s Street Footwear was the top product category
- West Gear led overall sales; Foot Locker performed strongly in 2021
- Online became the dominant sales method in 2021
- West region and states such as New York, California, Florida, and Texas drove the highest volume

---

## 2. German Cars Market Analysis (Python)

### Overview
Exploratory and statistical analysis of the German car market using AutoScout24 listings (2011–2021). Focused on understanding pricing drivers, vehicle characteristics, fuel/transmission trends, and market composition.

### Dataset
- Source: AutoScout24 (scraped data available on Kaggle)  
- Original size: 46,405 rows × 9 columns  
- Fields: Make, Model, Price, Offer Type, Mileage, Fuel Type, Gear Type, Horsepower, Production Year  
- Link: [Kaggle – Cars Germany](https://www.kaggle.com/datasets/ander289386/cars-germany)

### Tools Used
- Python
- Pandas & NumPy (data cleaning and analysis)
- Matplotlib (visualizations)
- Jupyter Notebook

### Analysis Performed
- Data cleaning (null handling, data type conversion, outlier/incorrect value treatment)
- Descriptive statistics and correlation analysis
- Distribution analysis (horsepower, price, fuel type, transmission, new vs used)
- Trend analysis over production years (especially fuel type shifts)
- Relationship exploration (Price vs Horsepower)
- Insight discovery and graphical representation

### Key Insights (Summary)
- Strong positive correlation between horsepower and price
- ~90% of offers had less than 200 hp
- Manual transmission dominated (~66%), followed by automatic
- Gasoline was the most common fuel type; electric/hybrid vehicles increased over time
- Vast majority of listings were used cars
- Clear price concentration: most vehicles under €20,000–€50,000
- Notable 2017 anomaly in gasoline vs diesel volumes

---

## Skills Demonstrated Across Both Projects
- Data cleaning and validation
- Exploratory data analysis (EDA)
- KPI and metric calculation
- Segmentation and ranking
- Correlation and statistical analysis
- Data visualization (Excel Pivot Tables + Python Matplotlib)
- Insight generation and business storytelling
- Handling real-world data limitations

## Tools Summary
| Tool              | Used In                  |
|-------------------|--------------------------|
| Excel + Pivot Tables | Adidas Sales Analysis   |
| Python (Pandas, NumPy, Matplotlib) | German Cars Analysis |
| Jupyter Notebook  | German Cars Analysis     |
| Kaggle            | Data source (Cars)       |

## How to Explore
- **Adidas project**: Open the Excel workbook and start with the Pivot Table sheets and the Retailer/Products Analysis tabs.
- **German Cars project**: Review the presentation PDF and the accompanying Jupyter notebook on GitHub for full code and detailed steps.

## Limitations
- Adidas 2020 data has limited geographic coverage
- Cars dataset reflects listings on one platform (AutoScout24) and may not represent the entire market

## Author
[Your Name]  
GitHub: [link]  
LinkedIn: [link]  
Portfolio: [link]
