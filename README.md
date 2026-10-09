# 🌍 Predicting Urban Air Quality Using Machine Learning
*A Data-Driven Approach to Sustainable City Planning*

---

## 🧠 Overview
This project applies **Machine Learning** to analyze and predict the **Air Quality Index (AQI)** across major Indian cities.  
By studying pollutants such as PM2.5, PM10, NO₂, CO, and SO₂, the model identifies the major contributors to air pollution and predicts AQI levels to support sustainable urban planning.

---

## 🎯 Objectives
- Predict AQI using historical pollutant data.
- Identify which pollutants most strongly affect air quality.
- Visualize pollutant trends and model performance.
- Demonstrate a full machine learning workflow from data collection to model saving.

---

## 🇮🇳 Context: India’s Air Quality Crisis
- 🌫️ 14 of the world’s 20 most polluted cities are in India.  
  *(IQAir, 2023)*  
- 💨 AQI in Delhi, Lucknow, and Kanpur often exceeds **300–400** (Severe).  
  *(CPCB, 2023; Times of India, 2023)*  
- 🧍‍♀️ Over **1.6 million premature deaths** per year in India are linked to poor air quality.  
  *(Health Effects Institute, 2020)*  
- 🏙️ Air pollution costs India **~5.4% of GDP** annually.  
  *(World Bank, 2023)*

---

## 🧩 Workflow

1. **Data Collection** → *city_day.csv* from CPCB  
2. **Data Exploration** → Visualized pollutant trends & correlations  
3. **Data Cleaning** → Removed missing values, fixed data types  
4. **Model Building** → Trained a Linear Regression model  
5. **Evaluation** → Calculated MAE (31.2) and R² (0.81)  
6. **Visualization** → Feature importance and prediction plots  
7. **Model Saving** → Exported as `linear_regression_model.pkl`  

---

## 🧠 Technologies Used
- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (Linear Regression)  
- Jupyter Notebook  
- Git & GitHub  

---

## 📊 Results
- **Mean Absolute Error (MAE):** 31.21  
- **R² Score:** 0.81  
- **Top Pollutants:** PM2.5, PM10, NO₂  
- **Visual Outputs:**  
  - `feature_importance.png` – pollutant impact  
  - `actual_vs_predicted.png` – model accuracy  

---

## 💬 Key Insights
- Particulate matter (PM2.5 and PM10) are the strongest AQI drivers.  
- The model can predict AQI trends with high reliability.  
- These insights can support data-driven decisions for cleaner cities.

---

## 🚀 Future Scope
- Integrate **weather and traffic data** for better accuracy.  
- Deploy as a **web dashboard** to display live AQI predictions.  
- Expand dataset to cover more Indian cities and years.

---

## 🧾 Citation Sources
- IQAir (2023) – *World Air Quality Report 2023*  
- World Bank (2023) – *The Global Burden of Air Pollution*  
- Health Effects Institute (2020) – *State of Global Air 2020*  
---

## 👩‍💻 Author
Lithika Jadav Malothu 
Honors Seminar Capstone Project — November 2025  


---

## 🪄 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/aqi-ml-honors-project.git
   ```

---

## 📄 License
This project is licensed under the [MIT License](LICENSE) © 2025 Lithika Jadav Malothu.
