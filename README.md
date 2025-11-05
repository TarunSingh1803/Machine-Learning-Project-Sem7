# 🌾 Crop Yield Prediction using Machine Learning

## 📘 Project Overview
This project focuses on **predicting agricultural crop yield** based on environmental and agricultural factors such as rainfall, temperature, and pesticide usage.  
By leveraging **machine learning techniques**, the model helps farmers, policymakers, and researchers make data-driven decisions for improving agricultural productivity.

---

## 🧠 Objective
To build a **data-driven model** that predicts crop yield using various independent features from historical datasets — improving forecasting accuracy and aiding sustainable agricultural planning.

---

## 📂 Dataset Description

| File Name | Description |
|------------|-------------|
| `rainfall.csv` | Contains annual/monthly rainfall data for different regions. |
| `temp.csv` | Includes average temperature data over time. |
| `pesticides.csv` | Records the amount of pesticides used per region and year. |
| `yield.csv` | Contains historical crop yield data (target variable). |
| `yield_df.csv` | Final merged dataset used for model training and testing. |

---

## 🧩 Features Used
- **Rainfall (mm)** — Average rainfall for the crop-growing period  
- **Temperature (°C)** — Mean temperature during the season  
- **Pesticide Usage (tons)** — Amount of pesticide applied  
- **Crop Type / Year / State** — Contextual identifiers for yield prediction  
- **Yield (Target Variable)** — Amount of crop produced per hectare  

---

## 🧰 Tech Stack
- **Language:** Python 🐍  
- **Libraries Used:**
  - `pandas`, `numpy` – Data handling and preprocessing  
  - `matplotlib`, `seaborn` – Data visualization  
  - `scikit-learn` – Machine learning modeling and evaluation  
  - `jupyter notebook` – Interactive development environment  

---

## ⚙️ Project Workflow
1. **Data Collection:** Import rainfall, temperature, pesticide, and yield datasets.  
2. **Data Cleaning & Merging:** Handle missing values, normalize units, and merge all CSVs into one DataFrame (`yield_df.csv`).  
3. **Exploratory Data Analysis (EDA):**  
   - Visualize feature distributions  
   - Analyze correlations between environmental factors and yield  
4. **Feature Engineering:** Prepare data for machine learning models.  
5. **Model Training:** Train regression models such as:
   - Linear Regression  
   - Random Forest Regressor  
   - Decision Tree Regressor  
6. **Model Evaluation:** Compare model performance using metrics:
   - R² Score  
   - Mean Squared Error (MSE)  
   - Root Mean Squared Error (RMSE)  
7. **Prediction:** Predict future crop yields based on new rainfall, temperature, and pesticide data.

---

## 📈 Results
- Achieved **high R² score** indicating strong predictive capability.  
- The model effectively identifies relationships between rainfall, temperature, and crop yield.  
- Demonstrates potential for **smart agriculture** and data-based decision-making.

---

## 🚀 Future Improvements
- Integrate **real-time weather APIs** for dynamic yield prediction.  
- Deploy the model using **Flask / Streamlit** for user-friendly web access.  
- Include **soil quality and humidity data** for higher accuracy.  
- Experiment with **deep learning models (LSTM, ANN)** for time-series forecasting.

---

## 🖥️ How to Run the Project

### Prerequisites
Make sure you have Python installed along with these dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```
Clone this repository:
   ```bash
   git clone https://github.com/TarunSingh1803/Machine-Learning-Project-Sem7.git
