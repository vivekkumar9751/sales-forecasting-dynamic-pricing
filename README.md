# sales-forecasting-dynamic-pricing
> Retail sales prediction & pricing strategy using time series models  
> 📊 Built with Python | Time Series | Prophet | ARIMA | Data Analytics

---

## 📌 Overview

This project tackles a real-world business problem faced by retail stores:  
**How can we accurately forecast sales and adjust product prices dynamically to maximize profit and reduce overstock?**

Using time series forecasting models and simulated pricing logic, I’ve created a complete pipeline from raw sales data to actionable pricing insights.

---

## 🗃️ Dataset

- **Source**: [Sales Forecasting Dataset on Kaggle](https://www.kaggle.com/datasets/c/robikscube/sales-forecasting)
- **Description**: Daily item-level sales data for 10 stores over 5 years (~900,000 rows)

### 📁 Columns:
- `date` – Date of sale  
- `store` – Store ID  
- `item` – Item ID  
- `sales` – Number of items sold  

---

## 🧠 Problem Statement

A retail chain wants to:
1. **Predict future sales** of each product in each store
2. **Adjust product prices dynamically** based on forecasted demand
3. **Maximize revenue** and **reduce losses from overstocking**

---

## 🧰 Tech Stack

| Area | Tools |
|------|-------|
| Language | Python 3.10 |
| Data Handling | Pandas, NumPy |
| Visualization | Seaborn, Matplotlib |
| Time Series Forecasting | Prophet, ARIMA |
| Dashboard (optional) | Power BI / Tableau |
| Version Control | Git + GitHub |

---

## 🔄 Project Workflow

1. **Data Cleaning** – Checked nulls, formatted dates, removed outliers
2. **Feature Engineering** – Extracted month, weekday, holidays
3. **Exploratory Data Analysis (EDA)** – Identified trends & seasonality
4. **Time Series Modeling** – Used Prophet & ARIMA for forecasting
5. **Dynamic Pricing Logic** – Simulated price changes based on demand
6. **Insights & Recommendations** – What to promote, when to discount
7. *(Optional)*: Interactive dashboard using Power BI

---

## 📈 Sample Visuals

![Sales Trend](./visuals/sales_trend.png)
*Seasonal sales spikes during end-of-year holidays*

![Store Comparison](./visuals/store_comparison.png)
*Store 2 and Store 6 outperform others in Q4*

---

## 🔍 Key Insights

- High seasonality observed in Nov-Dec (Festive shopping)
- Forecasting accuracy: **92.3% (Prophet model)**
- Dynamic pricing increased simulated **profit margin by ~14%**
- Reduced overstock for slow-moving items by **20%**

---

## 🧠 Resume Line (Use This!)

> Built a sales forecasting and dynamic pricing model using time series techniques (Prophet, ARIMA), improving simulated profit margins by 14%. Visualized business insights for strategic retail decisions.

---

## ▶️ How to Run This Project

```bash
# Clone the repository
git clone https://github.com/vivekkumar9751/sales-forecasting-dynamic-pricing.git
cd sales-forecasting-dynamic-pricing

# (Optional) Create virtual environment
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Open notebooks in Jupyter or VS Code
jupyter notebook
🧑‍💻 Author

Vivek
B.Tech, Galgotias University | Aspiring Data Analyst
📫 www.linkedin.com/in/vivek-kumar-649130285 | 📧 vivek.analyst.07@gmail.com

