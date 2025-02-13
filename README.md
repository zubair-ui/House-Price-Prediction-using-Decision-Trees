# House Price Prediction using XGBoost

This project uses **XGBoost** to predict house prices based on various features like crime rate, number of rooms, tax rates, etc.

## 📂 Dataset

The dataset contains the following features:

| Feature | Description                                                         |
| ------- | ------------------------------------------------------------------- |
| CRIM    | Per capita crime rate by town                                       |
| ZN      | Proportion of residential land zoned for large lots                 |
| INDUS   | Proportion of non-retail business acres per town                    |
| CHAS    | Charles River dummy variable (1 if tract bounds river; 0 otherwise) |
| NOX     | Nitrogen oxide concentration (parts per 10 million)                 |
| RM      | Average number of rooms per dwelling                                |
| AGE     | Proportion of owner-occupied units built before 1940                |
| DIS     | Weighted distance to employment centers                             |
| RAD     | Index of accessibility to radial highways                           |
| TAX     | Property tax rate per $10,000                                       |
| PTRATIO | Pupil-teacher ratio by town                                         |
| B       | Proportion of African-American residents                            |
| LSTAT   | % lower status population                                           |
| MEDV    | Median home value (Target Variable)                                 |

## 🚀 Installation

Make sure you have **Python 3.x** installed along with the required libraries.  
You can install dependencies using:

```bash
pip install xgboost pandas numpy scikit-learn
```

## 🔧 Usage

1. **Clone the repository (if applicable)**
   ```bash
   git clone https://github.com/yourusername/house-price-xgboost.git
   cd house-price-xgboost
   ```

## 📊 Model Performance

- **RMSE:** 2.47
- **R² Score:** 0.92
  > The model performs well, explaining **92% of the variance** in house prices.
