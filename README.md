# 🚲 Bike Sharing Demand Analysis

This project explores bike-sharing usage patterns using Python, focusing on different factors such as hour, day type (weekday/weekend), and holiday status. It includes exploratory data analysis (EDA), data visualization, and a simple predictive model.

---

## 📊 Exploratory Data Analysis

### 1. Total Demand Overview
We started by visualizing the total number of bikes shared across the dataset. This gave us an idea of overall usage and seasonality.

### 2. Usage by Hour
A line chart shows that bike-sharing peaks during commuting hours, especially at 8 AM and 6 PM, indicating a strong workday-related usage pattern.

### 3. Weekend vs Weekday
We observed a high variation in cycling between weekdays and weekends. People tend to use bikes more during weekdays, likely for commuting purposes.

### 4. Holiday vs Non-Holiday
Bike demand is significantly higher on non-holidays, supporting the idea that bike sharing is mostly used for routine travel.

---

## 🤖 Predictive Analysis

We trained a simple **Linear Regression** model to predict the number of bikes shared using the following features:

- Hour of the day  
- Temperature (ºC)  
- Humidity (%)  
- Wind speed (km/h)  
- Weekend/Weekday  
- Holiday/Non-holiday

### 🔍 Model Performance

---

## 📌 Conclusion

The linear regression model explains about **29%** of the variability in bike-sharing demand.

This means that **hour, weather conditions, weekend, and holiday indicators** partially explain the usage patterns.

The RMSE value indicates there’s still significant error, so predictions can be improved.

**Future steps** could include:

- Adding more features (e.g., weather type, events, traffic)
- Trying more complex models (e.g., Random Forests, XGBoost, or Neural Networks)
- Performing feature engineering to capture hidden patterns

---

## 🛠️ Tools Used

- Python  
- Pandas  
- Seaborn  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook
