# 🏠 House Price Prediction using Linear Regression

This project demonstrates the implementation of Simple & Multiple Linear Regression using the Scikit-learn, Pandas, and Matplotlib libraries in Python. The objective is to predict house prices based on various features such as area, number of bedrooms, and amenities.

## 📌 Objective

- Understand and implement simple and multiple linear regression models.
- Evaluate model performance using appropriate metrics.
- Visualize and interpret regression results.

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 📂 Dataset

The dataset contains 13 features related to housing attributes such as:

- `Price` (Target)
- `Area` (in sq. ft)
- `Bedrooms`, `Bathrooms`, `Stories`
- `Mainroad`, `Guestroom`, `Basement`
- `Hotwaterheating`, `Airconditioning`, `Parking`
- `Prefarea`, `Furnishingstatus`

Note:Categorical features like 'mainroad', 'guestroom', and 'furnishingstatus' are encoded before modeling.

## 📈 Workflow

1. Import and Preprocess the Dataset
   - Clean column names.
   - Encode categorical variables (`Yes`/`No` → 1/0, get_dummies for multi-class).
   - Drop missing values if any.

2. Split Data
   - Training: 80%
   - Testing: 20%

3. Train Linear Regression Model
   - Fit using `LinearRegression()` from `sklearn.linear_model`.

4. Evaluate Model
   - Metrics: MAE, MSE, R² Score.
   - Interpretation of coefficients.

5. Visualize
   - Plot predicted vs actual house prices using `matplotlib`.

## 📊 Evaluation Metrics (example output)

- MAE: Mean Absolute Error
- MSE: Mean Squared Error
- R² Score: Explained variance score (closer to 1 is better)

## 📉 Output Plot

- A scatter plot comparing actual vs predicted house prices.

## 🧠 Learnings

- Gained hands-on experience with linear regression.
- Learned how to preprocess mixed data types.
- Learned how to evaluate and interpret regression models.

