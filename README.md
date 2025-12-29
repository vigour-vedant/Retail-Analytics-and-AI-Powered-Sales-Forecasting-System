# Retail Analytics & AI-Powered Sales Forecasting System

## Project Overview
This project focuses on analyzing retail sales data from multiple stores and product categories to extract meaningful business insights and forecast future sales trends. The system is designed to support data-driven decision-making for retail management through analytics, segmentation, and predictive modeling.

The project simulates the role of a Data Scientist working for a national retail chain.

---

## Objectives
- Analyze historical retail sales data
- Identify sales trends, seasonality, and growth patterns
- Segment stores based on sales performance
- Forecast future sales using time-series modeling
- Present actionable business insights

---

## Dataset Information
- **Dataset Name:** Retail_Sales_Data_Unlox.csv  
- **Time Period:** January 2023 – December 2024  
- **Records:** ~73,000  
- **Data Source:** Provided as part of the project  

---

## Project Structure
Retail Analytics & AI-Powered Sales Forecasting System/
│

├── data/

│└── Retail_Sales_Data_Unlox.csv

│

├── notebooks/

│   └── Retail_Analytics_and_Forecasting.ipynb

│

├── outputs/

│   ├── sales_trends.png

│   ├── category_analysis.png

│   └── forecast_plot.png

│

|─ report/

│   └── Project_Report.pdf

│

└── README.md


---

## Tools & Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Statsmodels (SARIMA)

---

## Key Analysis Performed
### 1. Exploratory Data Analysis (EDA)
- Total sales trends over time
- Monthly and yearly sales patterns
- Category-wise and store-wise sales analysis
- Identification of seasonal demand patterns

### 2. Store Segmentation
- Aggregated store-level performance metrics
- K-Means clustering used to segment stores into performance groups:
  - High-performing
  - Medium-performing
  - Low-performing

### 3. Sales Forecasting
- Monthly sales aggregation
- SARIMA time-series model
- 6-month future sales forecast
- Visualization of actual vs predicted sales

---

## Business Insights
- Sales exhibit strong seasonal patterns, useful for inventory planning
- Certain product categories drive the majority of revenue
- High-performing stores can be used as benchmarks for others
- Forecasting enables proactive demand and inventory management

---

## How to Run the Project
1. Open the Google Colab notebook from the `notebooks` folder
2. Mount Google Drive
3. Ensure dataset path is correctly set
4. Run cells sequentially from top to bottom

---

## Outcome
This project delivers a complete analytics and forecasting solution that transforms raw retail data into actionable insights, enabling informed strategic decisions for retail management.

---

## Author
Vedant Salunkhe  
VIT Bhopal University
