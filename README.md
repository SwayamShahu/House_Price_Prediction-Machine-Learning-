# 🏠 House Price Prediction

This project aims to predict house prices using various machine learning regression models. It explores different models and compares their performance on different train-test splits.

## 📂 Files

- `housepriceprediction.py`: The main Python script used for training and evaluating models.
- `Housing.csv`: The dataset used for training/testing (real estate features and prices).

## 📊 Models Used

- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**

Each model is trained and evaluated using two split strategies:
- 80% Training / 20% Testing
- 70% Training / 30% Testing

## 🧪 Evaluation Metrics

Each model is evaluated using the following metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

## ⚙️ Requirements

Make sure the following libraries are installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
