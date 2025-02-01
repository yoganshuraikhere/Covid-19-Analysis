# Covid-19-Analysis

**📌 Project Overview**
This project aims to analyze and forecast the impact of COVID-19 to assist authorities and stakeholders in making data-driven decisions. Using PySpark, the dataset is processed to identify trends, assess the spread, and predict future cases.

**Key Objectives:**
* Analyze infection trends across regions.
* Predict future case numbers using time-series forecasting.
* Identify high-risk regions based on active cases and growth rates.
* Evaluate mortality and recovery trends.

**🛠 Technologies Used**
* PySpark – Big data processing and transformations.
* Databricks – Cloud-based data analysis.
* Prophet / ARIMA / LSTM – Time-series forecasting models.
* Matplotlib / Seaborn – Data visualization.

**📂 Dataset Details**

The dataset (covid_19_clean_complete.csv) contains 49,068 rows and 10 columns, covering global COVID-19 cases.

**Column Name	Description**
* Province/State	Specific state or province (if applicable).
* Country/Region	Country or region where data was recorded.
* Lat	Latitude coordinate.
* Long	Longitude coordinate.
* Date	Date of record.
* Confirmed	Number of confirmed cases.
* Deaths	Number of deaths.
* Recovered	Number of recovered cases.
* Active	Number of active cases.
* WHO Region	WHO region categorization.

**🚀 Implementation Steps**

1️⃣ Data Loading & Cleaning

* Load CSV into PySpark DataFrame.
* Handle missing values and inconsistencies.

2️⃣ Exploratory Data Analysis (EDA)

* Identify trends over time (daily, weekly, monthly).
* Compare cases across countries and regions.
* Compute mortality and recovery rates.

3️⃣ Time-Series Forecasting

* Implement Prophet / ARIMA / LSTM models to predict future cases.
* Evaluate forecast accuracy using RMSE and MAPE.

4️⃣ Visualization & Insights

* Plot case progression over time.
* Heatmaps for regional impact analysis.

**📜 Key Takeaways**

✅ PySpark for large-scale data processing.

✅ Time-series forecasting for predicting case growth.

✅ Data visualization to communicate insights.

**👨‍💻 Author**
* Yoganshu Raikhere – Data Engineering Enthusiast

