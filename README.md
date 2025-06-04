### 🏠 House Price Prediction

## 📝 Overview / Objective

The goal of this project is to predict house prices based on various features such as location, area, number of bedrooms, and other property characteristics. This predictive modeling helps homeowners, real estate companies, and investors make data-driven decisions.

## 📂 Dataset Source

* Dataset: Bangalore House Price Data
* Source: [Kaggle - Bangalore House Price Prediction](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

## 🛠️ Tools and Libraries Used

* Python
* Jupyter Notebook
* Libraries:

  * `pandas`, `numpy` (data handling)
  * `matplotlib`, `seaborn` (visualization)
  * `sklearn` (modeling and preprocessing)
  * `joblib` (model serialization)

## 🔍 Steps Followed

1. **Exploratory Data Analysis (EDA)**:

   * Examined missing values, outliers, and data distributions
   * Visualized price trends and feature correlations

2. **Data Cleaning & Preprocessing**:

   * Handled missing values
   * Feature engineering (e.g., deriving `bhk`, extracting numeric values from strings)
   * Removed outliers based on domain knowledge and statistical thresholds
   * One-hot encoding for categorical variables
   * Feature scaling

3. **Model Building**:

   * Split data into training and testing sets
   * Trained Linear Regression model
   * Performed GridSearchCV for model tuning (Ridge, Lasso, DecisionTreeRegressor)

4. **Model Evaluation**:

   * Evaluated using metrics like RMSE and R² score
   * Selected the best-performing model

5. **Prediction and Serialization**:

   * Saved the model using `joblib` for deployment

## 📊 Results

* **Best Model**: Linear Regression
* **R² Score**: \~0.65
* **RMSE**: \~1.22 lakhs

*(Values may slightly vary based on data split)*

*Feature correlation heatmap*

---

Let me know if you'd like me to generate a `requirements.txt` or add code to save plots automatically for the screenshots section.
