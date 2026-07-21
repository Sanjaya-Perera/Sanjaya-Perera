<h1 align="center">👔 Garment Demand Forecasting & Sales Dashboard</h1>
<p align="center">
  <b>Predicting monthly product demand to reduce inventory waste in the Garment Industry using Machine Learning</b>
</p>

<p align="center">
  <!-- Badges -->
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--learn-ML-green?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-Dashboard-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/PowerBI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge"/>
</p>

<p align="center">
  <a href="#-key-features">Features</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-dashboard">Dashboard</a> •
  <a href="#-results">Results</a> •
  <a href="#-how-to-run">Run</a> •
  <a href="#-about-me">About Me</a>
</p>

---

### 📌 Project Overview
In the garment industry, overproduction and stockouts cost companies millions.
This project uses historical sales data to **predict next month's product demand** using a `RandomForestRegressor`.

A **Streamlit Web App** and **Power BI Dashboard** were built to help merchandising and production teams make data-driven decisions.

> **Business Impact**: Helped reduce potential inventory waste by ~20% and improve fabric planning accuracy.

---

### ✨ Key Features
- [x] **Data Cleaning & EDA**: Handled missing values, outliers, and seasonality
- [x] **ML Model**: `RandomForestRegressor` with 92% R2 Score
- [x] **Forecasting**: Predict demand for next 3 months per product
- [x] **Interactive Dashboard**: Streamlit app for real-time predictions
- [x] **Executive Report**: Power BI Dashboard with KPI, Trends, and Filters

---

### 🛠️ Tech Stack
| Category | Tools |
| --- | --- |
| **Language** | Python 3.10, SQL |
| **ML / Data** | Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn |
| **Dashboard** | Streamlit, Power BI |
| **Other** | Git, GitHub, Jupyter Notebook |

---

### 📊 Dashboard Preview
<p align="center">
  <img src="notebooks/garment_dashboard.gif" width="800" alt="Power BI Dashboard Demo"/>
  <br>
  <i>Power BI Dashboard showing Sales Trend, Top Products, and KPI Cards</i>
</p>

---

### 📈 Results
| Metric | Score |
| --- | --- |
| **Model R2 Score** | 0.92 |
| **MAE** | 15.4 Units |
| **Key Insight** | T-Shirt demand increases by 33% in March. Recommended early fabric order. |

---

### 🚀 How to Run This Project
1. **Clone the repo**
    ```bash
    git clone https://github.com/Sanjaya-Perera/garment-demand-forecast.git
    cd garment-demand-forecast
