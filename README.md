# California Housing Price Prediction - Linear Regression

## 📌 Project Overview
This project applies **Linear Regression** to predict house prices using the **California Housing dataset**.  
It explores:
- Feature engineering
- Model evaluation (MSE, MAE, R²)
- Handling multicollinearity
- Polynomial regression for non-linearity

## 📊 Dataset
- Source: `fetch_california_housing()` from `sklearn.datasets`
- Features include median income, house age, population, and location-based attributes.
- Target variable: **Median house value**

## 🔧 Steps in the Notebook
1. **Data Exploration**: Checking missing values & statistics.
2. **Feature Engineering**: Handling multicollinearity, removing redundant features.
3. **Linear Regression Model**: Training and evaluating performance.
4. **Polynomial Regression**: Testing non-linear relationships for better accuracy.

## 📈 Model Performance
| Model                 | MSE   | MAE  | R² Score |
|----------------------|------|------|---------|
| Linear Regression   | 0.556 | 0.556 | 0.576   |
| After Feature Engineering | 0.650 | 0.600 | 0.504   |
| Polynomial Regression | TBD  | TBD  | TBD     |

## 📂 How to Run the Notebook
1. Install dependencies:  
pip install -r requirements.txt

2. Open Jupyter Notebook:
jupyter notebook

3. Run `California_Housing_Prediction.ipynb`

## 🚀 Next Steps
- Explore feature scaling
- Test alternative regression models (e.g., Ridge, Lasso)
- Deploy model using Flask or FastAPI