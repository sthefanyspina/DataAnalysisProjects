# 📊 Sales Dashboard

<img src="sales_dashboard.png" alt="Sales Dashboard">

## 🎯 Dashboard Purpose  
This project was developed to support both theoretical and practical studies on data analysis, data visualization, KPIs, and business performance metrics.  
The dashboard helps identify trends, patterns, and key commercial performance indicators.
This project also focuses on analyzing historical sales data, identifying trends and seasonality, and creating forecasting models to predict future sales.  
It includes exploratory data analysis (EDA), data cleaning, and implementation of multiple time series forecasting models with performance comparison.


---

## 📌 Objectives

- Clean and prepare raw sales data
- Perform exploratory data analysis
- Build a dashboard to visualize the data
- Detect trends and seasonal patterns
- Build sales forecasting models
- Compare forecasting performance using error metrics
- Visualize prediction results

---
## 🛠 Technologies Used

- **ChatGPT** – used to generate the dataset
- **Power Query** – for data cleaning and transformation
- **Power BI** – for building and visualizing the dashboard
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Plotly**
- **Statsmodels**
- **Prophet (Meta)**
- **Scikit-learn**

---

## 🗂 Data Source  
The dataset was created using **SimulaDados**, a tool that generates synthetic data for analytics projects, ensuring volume, variety, and consistency.

---

## 📑 Data Dictionary (Summary)

| Column            | Description                                             | Type       | Examples / Possible Values   |
|-------------------|---------------------------------------------------------|------------|------------------------------|
| Order_id          | Unique identifier for each order                        | Integer    | 1, 2, 3...                   |
| Order_date        | Order creation date                                     | Date       | 01/01/2020 – 12/31/2024      |
| Product           | Product name                                            | Text       | Various                      |
| Category          | Product category                                        | Text       | Electronics, Books...        |
| Sub_Category      | Product subcategory                                     | Text       | Smartphones, Fiction...      |
| Segment           | Product segment                                         | Text       | Technology, Fashion...       |
| Price             | Unit price of the product                               | Integer    | Varies                       |
| Quantity          | Quantity purchased                                      | Integer    | 1, 2, 3, 4, 5, 10            |
| Purchase_Type     | Purchase channel                                        | Text       | Online, App...               |
| Payment_Method    | Payment method                                          | Text       | Credit Card, PayPal...       |
| Shipping_date     | Shipping date                                           | Date       | Order_date + 1 to 3 days     |
| Delivery_date     | Delivery date                                           | Date       | Order_date + 3 to 7 days     |
| Customer_id       | Unique customer identifier                              | Integer    | 1001, 1002...                |
| Customer_gender   | Customer gender                                         | Text       | Female, Male                 |
| Customer_age      | Customer age                                            | Integer    | 18 to 80                     |
| Customer_city     | Customer city                                           | Text       | Various                      |
| Customer_state    | Customer state (USA)                                    | Text       | CA, NY, TX...                |
| Region            | Customer region                                         | Text       | North, South, East, West     |
| Rating            | Product rating                                          | Integer    | 1 to 5                       |

---

## 📊 Exploratory Data Analysis (EDA)

The EDA step includes:

- Time-based grouping (daily, monthly sales)
- Detection of seasonality and trends
- Sales distribution visualization
- Moving averages

---
## 🧹 Data Cleaning Steps

- Parsing dates
- Removing missing and invalid values
- Converting numeric fields
- Sorting by date
- Aggregating daily sales
- Outlier treatment (optional)

---

## 📈 KPIs & Metrics

- **Sales** → Calculated as: `Price * Quantity`
- **Orders** → Total number of orders
- **Quantity Sold** → Total items sold
- **Customers** → Total unique customers
- **Avg Rating** → Average product rating

---

## 🎨 Dashboard Layout & Visuals

Main summary cards:

- **Orders** — total number of orders  
- **Quantity Sold** — total units sold  
- **Total Sales** — total revenue  
- **Customers** — unique customer count  
- **Avg Ratings** — average product rating  

Visual components:

- **Sales by Category** – horizontal bar chart  
- **Sales by Segment** – donut chart  
- **Sales by Sub Category** – vertical bar chart  
- **Sales by Region** – pie chart  
- **Sales by State** – filled map  
- **Sales by Year** – line chart  

---

## 🔍 Key Features

In the **Overview** tab, users can:

- Apply year filters
- View key sales performance indicators
- Analyze sales behavior by segment, category, and region
- Explore geographical sales distribution
- Compare purchase channels and payment methods
- Investigate customer feedback through product ratings

---

## 🔮 Forecasting Models

### 1. **Prophet**
- Seasonal decomposition
- Easy trend detection
- Good for daily/monthly forecasts

### 2. **SARIMA**
- Statistical model
- Accounts for:
  - Autoregression
  - Moving averages
  - Seasonality

---

## 📈 Forecast Visualizations

The project includes:

- Historical sales plot
- Forecast graph (test vs predicted)
- Future trend projection
- Seasonal plots (Prophet)

---

## 📏 Model Evaluation

Metrics used for comparison:

- **MAE** — Mean Absolute Error
- **RMSE** — Root Mean Square Error
- **MAPE** — Mean Absolute Percentage Error

For questions, feedback, or collaboration:  
**Author:** Sthefany Spina  
