# 📊 Sales Prediction Using Python

This project was completed as part of the **Data Science Internship** at **Oasis Infobyte**.

The objective of this project is to predict product sales based on advertising expenditures across different media platforms such as TV, Radio, and Newspaper using Machine Learning.

---

## 📌 Project Overview

Businesses invest heavily in advertising to increase product sales. This project analyzes the relationship between advertising budgets and sales and builds machine learning models to predict future sales based on advertising investments.

The project includes data preprocessing, exploratory data analysis (EDA), model training, performance evaluation, and prediction.

---

## 🎯 Objectives

- Analyze the advertising dataset.
- Understand the relationship between advertising expenditure and sales.
- Perform exploratory data analysis (EDA).
- Build machine learning models for sales prediction.
- Compare model performance using evaluation metrics.

---

## 📂 Dataset

The dataset contains advertising expenditure across three media channels:

- TV Advertising Budget
- Radio Advertising Budget
- Newspaper Advertising Budget

Target Variable:

- Sales

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Data inspection
- Missing value analysis
- Duplicate value check
- Correlation analysis
- Pairplot visualization
- Scatter plots
- Feature relationship analysis

---

## 🤖 Machine Learning Models

The following models were implemented:

1. Linear Regression
2. Random Forest Regressor

---

## 📈 Model Performance

| Model | MAE | RMSE | R² Score |
|-------|------------:|------------:|---------:|
| Linear Regression | 1.4608 | 1.7816 | 0.8994 |
| Random Forest Regressor | 0.6201 | 0.7686 | 0.9813 |

The Random Forest Regressor achieved the best performance with the highest accuracy and lowest prediction error.

---

## 📁 Project Structure

```
Sales_Prediction/
│
├── dataset/
│   └── advertising.csv
│
├── images/
│
├── output/
│
├── Sales_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone <repository-url>
```

2. Navigate to the project folder

```bash
cd Sales_Prediction
```

3. Install the required libraries

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open `Sales_Prediction.ipynb` and run all cells.

---

## 📌 Results

- TV advertising has the strongest positive impact on sales.
- Radio advertising also contributes significantly to sales.
- Newspaper advertising has comparatively less influence.
- Random Forest Regressor produced the most accurate predictions with an R² score of **98.13%**.

---

## 📚 Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

---

## 👨‍💻 Author

**Snehbhai Kheni**

Data Science Internship Project

Oasis Infobyte

---

## 📄 License

This project is developed for educational and internship purposes.
