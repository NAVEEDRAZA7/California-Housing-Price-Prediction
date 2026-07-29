# 🏠 California Housing Price Prediction

An end-to-end Machine Learning project that predicts median house prices using the California Housing dataset. The project demonstrates the complete Machine Learning workflow, including data loading, exploratory data analysis (EDA), data preprocessing, feature engineering, model training, and evaluation using Scikit-learn.

---

## 📌 Project Overview

The objective of this project is to build a Machine Learning model that predicts the **median house value** of a California district based on demographic and housing-related features.

This project is implemented as part of learning **End-to-End Machine Learning** using Python and Scikit-learn.

---

## 🚀 Features

- Data loading and exploration
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature engineering
- Stratified Train-Test Split
- Linear Regression model
- Model evaluation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

The project uses the **California Housing Dataset**.

The dataset is included in this repository:

```
data/
└── housing.csv
```

It contains information about California districts, including:

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity
- Median House Value (Target)

**Original Dataset Source:**

https://github.com/ageron/data

---

## 📁 Project Structure

```
California-Housing-Price-Prediction/
│
├── data/
│   └── housing.csv
│
├── notebooks/
│   └── California_Housing_Price_Prediction.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/California-Housing-Price-Prediction.git
```

Move into the project directory:

```bash
cd California-Housing-Price-Prediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
notebooks/California_Housing_Price_Prediction.ipynb
```

---

## 📈 Machine Learning Model

Current implementation:

- ✅ Linear Regression

Evaluation includes:

- RMSE (Root Mean Squared Error)

Future improvements:

- Decision Tree Regression
- Random Forest Regression
- Hyperparameter Tuning
- Cross Validation
- Model Comparison
- Model Deployment using FastAPI

---

## 🎯 Learning Outcomes

Through this project, I learned:

- End-to-End Machine Learning workflow
- Data preprocessing techniques
- Exploratory Data Analysis (EDA)
- Feature engineering
- Stratified sampling
- Training and evaluating regression models
- Building reproducible ML pipelines

---

## 📜 License

This project is intended for learning and educational purposes.
