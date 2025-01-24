![Top Kaggle Courses for Data Science](https://raw.githubusercontent.com/SumeyraBayrak/Predictive-Analytics-and-Data-Exploration-Projects/master/Image/Top-Kaggle-Courses-for-Data-Science.png)

# Machine Learning Regression

Machine learning regression is a technique used to analyze the relationship between independent variables (features) and a dependent variable (outcome). It is primarily applied in predictive modeling, where the goal is to predict continuous outcomes. This involves training models on labeled data to understand how features influence the outcome, which allows the model to predict future or missing data.

## Key Points:
- **Purpose**: Predict continuous outcomes and understand relationships between variables.
- **Applications**: Forecasting and decision-making in industries like finance, healthcare, and retail.
- **Examples of Tasks**: Predicting house prices, stock trends, sales figures, etc.
## Types of Regression:
### 1. Simple Linear Regression
- Models the relationship between a single independent variable and the dependent variable.
- Uses a straight line for prediction.

### 2. Multiple Linear Regression
- Involves more than one independent variable to model the relationship with the dependent variable.
- Provides a better fit compared to simple linear regression.

### 3. Logistic Regression
- Used for binary outcomes (e.g., success or failure).
- Predicts the probability of a dependent variable using a sigmoid curve.

# Example :
##  Linear Regression :

```bash
$ python Predictive-Analytics-and-Data-Exploration-Projects/linear_gift.ipynb
```

<p align="center">
  <img src="https://raw.githubusercontent.com/SumeyraBayrak/Predictive-Analytics-and-Data-Exploration-Projects/master/advanced_linear_regression_animation.gif" alt="Project Image">
</p>

<p align="center" style="max-width: 500px; color: #808080; font-size: 5px;">
  Şekil: 2016 yılında İsveç, Linköping'de ölçülen sıcaklık verilerine uyan<br>
  düzenlenmiş bir polinom regresyon modelinin eğitim ilerlemesi.
</p>

<details>
<summary>Click to view regression problems</summary>

| **Project No** | **Project Name**                             | **Description**                                                                 | **Techniques Used**                                               | **Key Libraries**                                            | **Data Source (English)**                                                                 | **Data Source (Turkish)**                                                                 |
|----------------|----------------------------------------------|---------------------------------------------------------------------------------|-------------------------------------------------------------------|-------------------------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------|
| 1              | **Boston Housing Price Prediction**          | Predict housing prices in Boston based on various features like crime rate, number of rooms, etc. | Linear Regression, Decision Trees, Random Forests, Neural Networks | Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn            | [Boston Housing Dataset](https://archive.ics.uci.edu/ml/datasets/housing) | [Boston Konut Fiyatı Verisi](https://archive.ics.uci.edu/ml/datasets/housing) |
| 2              | **Diabetes Progression Prediction**          | Predict the progression of diabetes after one year based on diagnostic measurements. | Logistic Regression, SVM, Random Forests, KNN, Neural Networks    | Scikit-learn, Pandas, NumPy, Matplotlib, Keras/TensorFlow   | [Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) | [Diyabet Verisi](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) |
| 3              | **Car Price Prediction**                     | Predict the market price of a car based on features like age, mileage, and brand. | Linear Regression, Decision Trees, Random Forests, Gradient Boosting | Scikit-learn, Pandas, NumPy, XGBoost, Matplotlib            | [Car Price Dataset](https://www.kaggle.com/datasets/atharvakale/car-price-prediction) | [Araba Fiyatı Verisi](https://www.kaggle.com/datasets/atharvakale/car-price-prediction) |
| 4              | **Stock Price Prediction**                   | Predict the future stock prices of a company based on historical price data. | Time Series Forecasting (ARIMA), LSTM, Random Forests            | Pandas, NumPy, Keras/TensorFlow, Statsmodels, Matplotlib    | [Stock Price Dataset](https://www.kaggle.com/datasets/sbhatti/ultimate-stock-market-data) | [Hisse Senedi Fiyatı Verisi](https://www.kaggle.com/datasets/sbhatti/ultimate-stock-market-data) |
| 5              | **Concrete Compressive Strength Prediction** | Predict the compressive strength of concrete based on its composition. | Linear Regression, Decision Trees, Support Vector Machines        | Scikit-learn, Pandas, NumPy, Matplotlib                     | [Concrete Dataset](https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength) | [Beton Sıkıştırma Dayanımı Verisi](https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength) |
| 6              | **Energy Consumption Forecasting**           | Predict the energy consumption of a building or household based on various parameters like temperature, humidity, etc. | Time Series Forecasting (ARIMA), Random Forests, Neural Networks | Pandas, NumPy, Scikit-learn, Keras/TensorFlow, Matplotlib    | [Energy Consumption Dataset](https://www.kaggle.com/datasets/uciml/individual-household-electric-power-consumption) | [Enerji Tüketimi Verisi](https://www.kaggle.com/datasets/uciml/individual-household-electric-power-consumption) |

</details>
