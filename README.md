# ✈️ Flight Price Prediction - EDA & Data Preparation

This repository contains an end-to-end Exploratory Data Analysis (EDA) and data preprocessing pipeline for a **Flight Price Prediction** problem. The objective is to clean, analyze, and prepare the dataset to make it ready for machine learning model development.

---

## 📌 Project Objective

The goal of this project is to:
- Understand the structure and distribution of the dataset
- Clean and preprocess the raw data
- Perform exploratory data analysis and visualization
- Engineer meaningful features
- Prepare a final dataset suitable for predictive modeling

---

## 🗃️ Dataset

- The dataset used contains information on various flight journeys, including:
  - Airline
  - Date of journey
  - Source & Destination
  - Route & Duration
  - Number of stops
  - Price



---

## 🔧 Tasks Performed

### ✅ Data Cleaning
- Handled missing values and inconsistent data types
- Removed duplicates and outliers

### 📊 Exploratory Data Analysis (EDA)
- Univariate and multivariate analysis
- Visualized trends in pricing based on:
  - Time of travel
  - Airline
  - Number of stops
  - Duration

### 🏗️ Feature Engineering
- Converted date/time columns into datetime format
- Extracted new features: Day, Month, Duration in minutes, etc.
- Encoded categorical variables using Label Encoding / One-Hot Encoding

### 📁 Final Output
- A clean, structured dataset ready for ML algorithms
- Saved as `processed_flight_data.csv` (or similar)

---


---

## 🧠 Future Work

- Train regression models (e.g., Linear Regression, Random Forest, XGBoost)
- Hyperparameter tuning
- Model evaluation using RMSE, MAE, etc.
- Build a simple UI using Streamlit for predictions

---

## 🚀 Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Scikit-learn (for future ML steps)

---

## 📬 Contact

Feel free to connect or reach out if you're interested in collaborating or giving feedback!

🔗 LinkedIn:   www.linkedin.com/in/himanshu-tyagi-30a21128a
🔗 GitHub: https://github.com/Himanshutyagi4348/EDA_flight_price_prediction

---

## 📌 License

This project is open-source and available under the [MIT License](LICENSE).
