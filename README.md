# 🌏 Economic Insights on Asian Countries (2000–2027)

Hi there! 👋  
This project dives deep into the economic landscape of major Asian countries using the **World Economic Outlook (WEO) April 2024** dataset by the IMF. We explore trends, compare economies, forecast the future, and even group similar countries using machine learning — all in a clean, visual, and insightful way.

---

## 🧭 Objectives

Here's what we aimed to do:

1. 📈 **Trend Analysis**  
   - Visualized economic indicators over time (2000–2027) for each country.

2. 🌐 **Country Comparison**  
   - Compared countries side-by-side on key indicators like inflation, import, exports, and more.

3. 💰 **Government Finance Overview**  
   - Analyzed government revenue, expenditure, and net debt to understand fiscal health.

4. 📊 **Correlation Analysis**  
   - Checked relationships between variables — like how inflation relates to investment or exports.

5. 🧠 **Clustering Economies (K-Means)**  
   - Grouped countries based on similar economic behavior to identify patterns using machine learning.

6. 🔮 **Forecasting Key Indicators**  
   - Built simple forecasting models (Linear Regression) to predict future trends like inflation.

---

## 📁 Dataset Used

- **Source**: World Economic Outlook, April 2024 (IMF)
- **Countries**: India, China, Japan, Bangladesh, Indonesia, Pakistan, Bhutan, Russia, Saudi Arabia  
- **Years Covered**: 2000 to 2029  
- **Indicators**:  
  - Population  
  - General government total expenditure  
  - Volume of exports/imports  
  - Inflation (consumer prices)   
  - Government revenue
  - Total investment

---

## ⚙️ Technologies Used

- `Pandas` & `NumPy` – Data cleaning and transformation  
- `Matplotlib` & `Seaborn` – Trend visualization and correlation plots  
- `scikit-learn` – Forecasting (Linear Regression) and Clustering (K-Means)  

---

## 💡 Key Features

- 📊 **Clean trend graphs** by country and indicator  
- 🌍 **Cross-country comparisons**  
- 🔍 **K-Means clustering** to group countries by economic behavior  
- 📉 **Forecasting** using Linear Regression for selected indicators  
- 🧮 **Correlation heatmaps** for understanding variable relationships  

---

## 🔮 Forecasting: How It Works

- We filtered data for a specific indicator (like inflation), ensured values were correct (like using “Percent Change”), and applied a simple **Linear Regression** model to predict values for the next few years.
- While this is a basic model, it gives a general sense of the future direction for economic indicators.

> ✅ Tip: For more accurate forecasting, we can later explore models like ARIMA, Prophet, or LSTM.

---

## 🧠 Clustering (K-Means): What We Did

- We selected the latest year's data and picked economic indicators like:
  - Inflation
  - Investment
  - Exports
  - Government Revenue/Expenditure
  - Unemployment
- Standardized the values, then used the **K-Means algorithm** to group countries with similar economic behavior.
- Used the **Elbow Method** to determine the best number of clusters.

---

## 📌 How to Run This Project

1. Clone the repo or use the code in your Python environment.
2. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
