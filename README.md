# 🥑 Avocado Price Forecasting using Facebook Prophet

## 📌 Project Overview

This project focuses on forecasting future avocado prices using historical retail sales data and Facebook Prophet, a powerful time series forecasting library developed by Meta (Facebook).

The dataset contains avocado sales information across multiple regions in the United States, including average prices, sales volumes, product types (organic/conventional), and bag sizes.

The objective is to analyze historical price trends and generate future price forecasts to support data-driven business decisions.

---

## 🎯 Business Problem

Retailers, suppliers, and distributors need accurate forecasts to:

- Optimize inventory management
- Plan procurement strategies
- Reduce overstocking and stockouts
- Improve pricing decisions
- Understand seasonal demand patterns
- Support long-term business planning

Forecasting helps businesses anticipate future market behavior and make proactive decisions.

---

## 📂 Dataset Information

The dataset includes:

| Feature | Description |
|----------|-------------|
| Date | Observation date |
| AveragePrice | Average avocado price |
| Total Volume | Total avocados sold |
| 4046 | Small Hass avocado sales |
| 4225 | Large Hass avocado sales |
| 4770 | Extra-large Hass avocado sales |
| Total Bags | Total bagged avocado sales |
| Small Bags | Small bag sales |
| Large Bags | Large bag sales |
| XLarge Bags | Extra-large bag sales |
| Type | Organic or Conventional |
| Year | Observation year |
| Region | Geographic region |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Prophet (Facebook Prophet)

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset inspection and cleaning
- Date conversion and time-series preparation
- Missing value analysis
- Price trend visualization
- Organic vs Conventional price comparison
- Correlation analysis
- Regional data exploration

---

## 🤖 Forecasting Model

### Facebook Prophet

Prophet is a time series forecasting model designed to handle:

- Trend analysis
- Seasonality detection
- Missing values
- Outliers
- Uncertainty estimation

The model automatically decomposes time series data into:

Forecast = Trend + Seasonality + Error

---

## 🔍 Forecasting Workflow

1. Data Loading
2. Data Cleaning
3. Time Series Preparation
4. Prophet Model Training
5. Future Date Generation
6. Price Forecasting
7. Trend Analysis
8. Seasonality Analysis
9. Forecast Visualization

---

## 📈 Results

The model successfully:

- Learned historical avocado price patterns
- Detected yearly seasonal behavior
- Generated future price forecasts
- Estimated uncertainty intervals
- Visualized long-term trends

Forecast outputs included:

- Predicted Price (`yhat`)
- Lower Confidence Bound (`yhat_lower`)
- Upper Confidence Bound (`yhat_upper`)

---

## 📉 Trend Analysis

The Prophet model identified:

- Long-term price movement
- Seasonal fluctuations
- Future pricing behavior

Trend plots provide insights into how avocado prices evolve over time.

---

## 📅 Seasonality Analysis

Yearly seasonality analysis revealed recurring patterns in avocado pricing throughout the year.

These insights can help businesses understand:

- High-demand periods
- Low-demand periods
- Seasonal pricing effects

---

## 💡 Key Business Insights

- Avocado prices exhibit seasonal behavior.
- Historical trends influence future price forecasts.
- Organic avocados generally have higher prices than conventional avocados.
- Forecasting can improve inventory and pricing decisions.
- Confidence intervals help quantify prediction uncertainty.

---

## 🚀 Future Improvements

Potential enhancements include:

- Region-wise forecasting
- Organic vs Conventional forecasting comparison
- Forecast accuracy evaluation
- ARIMA vs Prophet comparison
- Interactive dashboards using Plotly
- Streamlit deployment
- Holiday effect modeling

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Time Series Forecasting
- Trend Analysis
- Seasonality Detection
- Forecast Interpretation
- Business-Oriented Data Analysis
- Facebook Prophet
- Data Visualization

---

## 📷 Sample Visualizations

### Price Trend Over Time
<img width="942" height="420" alt="av2" src="https://github.com/user-attachments/assets/aacacf60-5579-43d4-b08c-a3d95d8652db" />


### Forecast Output
<img width="753" height="452" alt="av3" src="https://github.com/user-attachments/assets/561f06d7-febc-4de1-a029-726f2dcc3d65" />


### Trend and Seasonality Components
<img width="672" height="451" alt="av4" src="https://github.com/user-attachments/assets/9fce5cf5-8d78-44fd-b008-5fd752c224e0" />


---

## 📖 References

- https://facebook.github.io/prophet/
- https://www.kaggle.com/datasets/neuromusic/avocado-prices

---

## 👨‍💻 Author

Prakriti Anand

Associate Business Analyst | Aspiring AI/ML Engineer

Skills:
Python • SQL • Machine Learning • Statistics • Power BI • Data Analytics • Time Series Forecasting
