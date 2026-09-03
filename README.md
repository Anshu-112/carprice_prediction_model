# 🚗 Ford Car Price Prediction

## 📌 Project Overview

This project focuses on predicting the prices of Ford cars using Machine Learning.

The dataset contains information about Ford vehicles such as their model, year, transmission, mileage, fuel type, tax, MPG, and engine size. The project explores the relationships between these features and car prices and uses them to build a machine learning model for price prediction.

---

## 📊 Dataset

The dataset contains **17,966 records** and **9 columns**.

### Features

| Feature | Description |
|---|---|
| `model` | Ford car model |
| `year` | Year of manufacture |
| `price` | Price of the car |
| `transmission` | Type of transmission |
| `mileage` | Distance travelled by the car |
| `fuelType` | Type of fuel used |
| `tax` | Vehicle tax |
| `mpg` | Miles per gallon |
| `engineSize` | Engine size in litres |

The target variable for this project is:

```text
price

🔍 Project Workflow

The project follows these major steps:

Importing Libraries
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Loading the Dataset
Understanding the Dataset
Checking shape
Viewing the first few records
Understanding data types
Checking missing values
Exploratory Data Analysis (EDA)
Data visualization
Correlation analysis
Understanding relationships between features
Data Preprocessing
Handling categorical variables
One-hot encoding using pd.get_dummies()
Feature scaling using StandardScaler
Machine Learning
Splitting the dataset into training and testing sets
Training a regression model
Making predictions
Model Evaluation
Evaluating the model's performance using appropriate regression metrics
📈 Correlation Analysis

Correlation analysis is used to understand how different numerical features are related to each other and to the car price.

Some important relationships observed in the dataset include:

year and price → positive correlation
mileage and price → negative correlation
year and mileage → strong negative correlation
engineSize and price → positive correlation

These relationships can help understand which factors influence Ford car prices.

🛠️ Technologies Used
Python
Pandas – Data manipulation and analysis
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Statistical visualization
Scikit-learn – Machine Learning
📁 Project Structure
ford-car-price-prediction/
│
├── ford-car-price-prediction.ipynb
├── ford.csv
└── README.md
⚙️ Installation

Clone this repository:

git clone https://github.com/YOUR-USERNAME/ford-car-price-prediction.git

Navigate to the project directory:

cd ford-car-price-prediction

Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn jupyter
▶️ How to Run

Open the Jupyter Notebook:

jupyter notebook

Then open:

ford-car-price-prediction.ipynb

Run the cells sequentially to reproduce the analysis and machine learning workflow.

🎯 Objective

The main objective of this project is to understand how different characteristics of Ford cars affect their prices and to build a machine learning model capable of predicting car prices based on those characteristics.

🚀 Future Improvements

Possible improvements to this project include:

Comparing multiple regression algorithms
Hyperparameter tuning
Improving model performance
Adding more detailed visualizations
Saving the trained model
Building an interactive Streamlit web application
Deploying the prediction model online
👩‍💻 Author

Anshu Varma

This project was developed as part of my Machine Learning and Data Science learning journey.
