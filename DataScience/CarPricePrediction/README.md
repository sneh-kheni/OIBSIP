# Car Price Prediction Using Machine Learning

This project was completed as part of my Data Science Internship at Oasis Infobyte.

## Project Overview

The goal of this project is to predict the selling price of used cars using machine learning. The model analyzes different features such as car age, fuel type, transmission, engine size, kilometers driven, owner type, and other vehicle specifications to estimate a car's selling price.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, model evaluation, and prediction.

---

## Objectives

- Analyze the used car dataset
- Clean and preprocess the data
- Perform exploratory data analysis
- Build machine learning models
- Compare model performance
- Predict the selling price of a used car

---

## Dataset

The dataset contains information about used cars, including:

- Car Name
- Manufacturing Year
- Selling Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner Type
- Mileage
- Engine Capacity
- Maximum Power
- Number of Seats

Target Variable:

- Selling Price

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Exploratory Data Analysis

The following analysis was performed:

- Data inspection
- Missing value handling
- Duplicate removal
- Feature engineering
- Correlation analysis
- Distribution plots
- Scatter plots
- Box plots
- Feature importance analysis

---

## Machine Learning Models

The following models were implemented:

- Linear Regression
- Random Forest Regressor

---

## Model Performance

| Model | MAE | RMSE | R² Score |
|------|------------:|------------:|---------:|
| Linear Regression | 168620 | 273335 | 0.6595 |
| Random Forest Regressor | 73116 | 129983 | 0.9230 |

The Random Forest Regressor achieved the best performance with an R² score of 92.30%.

---

## Project Structure

```
Car_Price_Prediction/
│
├── dataset/
│   └── car_data.csv
│
├── images/
│
├── output/
│
├── Car_Price_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone this repository.

```bash
git clone <repository-url>
```

2. Navigate to the project folder.

```bash
cd Car_Price_Prediction
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Open `Car_Price_Prediction.ipynb` and run all cells.

---

## Results

- Cleaned and preprocessed the dataset.
- Performed feature engineering by creating the Car Age feature.
- Built and compared Linear Regression and Random Forest models.
- Random Forest achieved the best prediction accuracy with an R² score of 92.30%.
- Successfully predicted the selling price of used cars based on their specifications.

---

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

---

## Author

**Snehbhai Kheni**

Data Science Internship Project

Oasis Infobyte

---

## License

This project was developed for educational and internship purposes.
