# 🏠 House Price Prediction using Machine Learning

##  Project Overview

This project predicts house prices using **Linear Regression**. The model is trained on house data and estimates the price based on the following features:

* Square Feet Living Area (`sqft_living`)
* Number of Bedrooms (`bedrooms`)
* Number of Bathrooms (`bathrooms`)

The project is built using Python, Pandas, Scikit-learn, and Matplotlib.


##  Features

* Load and preprocess the dataset
* Check for missing values
* Train a Linear Regression model
* Predict house prices
* Evaluate model performance using:

  * Mean Absolute Error (MAE)
  * Mean Squared Error (MSE)
  * R² Score
* Visualize Actual vs Predicted house prices
* Predict house price using user input


## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib



## 📂 Project Structure

House-Price-Prediction/
│── data.csv
│── house_price_prediction.py
│── README.md


## 📊 Dataset

The dataset (`data.csv`) should contain the following columns:

* `sqft_living`
* `bedrooms`
* `bathrooms`
* `price`


## ▶️ How to Run

1. Clone the repository:

   bash
   git clone https://github.com/your-username/House-Price-Prediction.git
   

2. Install the required libraries:

   bash
   pip install pandas scikit-learn matplotlib

3. Run the project:

   bash
   python house_price_prediction.py
   

## 📈 Model Evaluation

The model is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

A scatter plot is also generated to compare actual and predicted house prices.


## 💻 Sample Input
Enter Area (sq.ft): 1800
Enter Number of bedrooms: 3
Enter Number of bathrooms: 2
# Sample Output

Estimated House Price: $425,000.00

## 📌 Future Improvements

* Add more features such as location, year built, and floors.
* Try advanced machine learning models like Random Forest and XGBoost.
* Build a web application using Flask or Streamlit.
* Improve model accuracy with feature engineering.

## 👤 Author

**Vishal Ramraje**

GitHub: https://github.com/your-username
