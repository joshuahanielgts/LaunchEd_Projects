# 🏠 Bangalore House Price Classification

A classification model to predict whether a house in Bangalore is *affordable* or *expensive* based on features like size, location, and price per square foot.

## 🧠 Project Objective

Use machine learning (Logistic Regression, Random Forest, etc.) to classify house listings as *Affordable (0)* or *Expensive (1)* based on the dataset.

## 🧰 Technologies Used

- Python
- Pandas / NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Google Colab

## 📁 Dataset

Dataset: [Bangalore House Price Data (Kaggle)](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

Key features:

- `location`
- `size`
- `total_sqft`
- `bath`
- `balcony`
- `price`
- Custom label: `price_category` → 0: Affordable, 1: Expensive

## 📊 Features Covered

- Missing value handling
- Feature engineering (price per sqft)
- Label encoding of categorical variables
- Correlation analysis and data visualization
- Train-test split
- Model training & evaluation (accuracy, confusion matrix)

## ✅ Classification Models Used

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

## 📌 Key Results

- Random Forest outperformed other models with ~90% accuracy.
- Location and total_sqft were top contributors to classification.

## 🚀 How to Run

1. Clone this repo or open in Google Colab.
2. Upload `Bengaluru_House_Data.csv`.
3. Run the notebook end-to-end.
