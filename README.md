# 🏠 Housing Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict house prices using Machine Learning techniques. The dataset contains various house-related features such as area, number of bedrooms, bathrooms, parking spaces, furnishing status, and other amenities. The objective is to analyze the factors affecting house prices and build predictive models that estimate property values accurately.

---

## 🎯 Objectives

* Perform Data Cleaning and Preprocessing
* Conduct Exploratory Data Analysis (EDA)
* Visualize key patterns and relationships in the data
* Build and evaluate Machine Learning models
* Compare Linear Regression and Random Forest Regressor performance
* Identify the most influential factors affecting house prices

---

## 📂 Dataset Information

The dataset contains information about residential properties with the following features:

| Feature          | Description                   |
| ---------------- | ----------------------------- |
| price            | House Price (Target Variable) |
| area             | Area of the house             |
| bedrooms         | Number of bedrooms            |
| bathrooms        | Number of bathrooms           |
| stories          | Number of floors              |
| mainroad         | Access to main road           |
| guestroom        | Availability of guest room    |
| basement         | Availability of basement      |
| hotwaterheating  | Hot water heating facility    |
| airconditioning  | Air conditioning availability |
| parking          | Number of parking spaces      |
| prefarea         | Preferred area                |
| furnishingstatus | Furnishing status             |

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Exploratory Data Analysis

The following visualizations were created:

* House Price Distribution Histogram
* Correlation Heatmap
* Price vs Area Scatter Plot
* Furnishing Status Pie Chart
* Main Road Access Pie Chart
* Price Distribution by Bedrooms
* Actual vs Predicted Price Plot
* Feature Importance Visualization

---

## ⚙️ Data Preprocessing

* Checked for missing values
* Removed duplicate records
* Applied One-Hot Encoding to categorical variables
* Prepared feature matrix and target variable
* Split dataset into training and testing sets (80:20)

---

## 🤖 Machine Learning Models

### 1. Linear Regression

A statistical model used to establish a linear relationship between house features and price.

### 2. Random Forest Regressor

An ensemble learning model that combines multiple decision trees for prediction.

---

## 📈 Model Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### Results Summary

| Model                   | R² Score |
| ----------------------- | -------- |
| Linear Regression       | ~0.65    |
| Random Forest Regressor | ~0.61    |

Linear Regression slightly outperformed Random Forest on this dataset.

---

## 🔍 Key Findings

* House area is the strongest predictor of price.
* Bathrooms and parking availability significantly impact house value.
* Air conditioning and furnishing status contribute to higher prices.
* Larger houses generally have higher market value.
* The relationship between features and price is largely linear.

---

## 💡 Business Recommendation

Real estate companies should focus on properties with larger areas, modern amenities, sufficient parking spaces, and better furnishing, as these features have the greatest influence on house prices and buyer preferences.

---

## 🚀 How to Run the Project

```bash
# Clone Repository
git clone https://github.com/your-username/housing-price-prediction.git

# Navigate to Project Folder
cd housing-price-prediction

# Install Dependencies
pip install -r requirements.txt

# Launch Notebook
jupyter notebook
```

Open the notebook and run all cells sequentially.

---

## 📁 Project Structure

```text
Housing-Price-Prediction/
│
├── Housing.csv
├── Housing_Price_Prediction.ipynb
├── summary.docx
├── plots/
│   ├── chart1_price_distribution.png
│   ├── chart2_correlation_heatmap.png
│   ├── chart3_price_vs_area.png
│   ├── chart4_furnishing_status_pie.png
│   ├── chart8_actual_vs_predicted.png
│   └── chart9_feature_importance.png
│
├── README.md
└── requirements.txt
```

---

## 👨‍💻 Author

**Ankit Agrawal**

MCA (Artificial Intelligence)
Galgotias University

---

## ⭐ Acknowledgements

This project was developed as part of Machine Learning and Data Analytics coursework to demonstrate data preprocessing, visualization, predictive modeling, and model evaluation techniques using Python.
