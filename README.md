# Linear Regression

Welcome to the **Linear Regression** project! This repository contains a simple yet comprehensive implementation of linear regression, one of the most fundamental algorithms in machine learning and statistics.

## 📈 What is Linear Regression?

Linear Regression is a supervised learning algorithm used to model the relationship between a dependent variable and one (simple linear regression) or more (multiple linear regression) independent variables by fitting a linear equation to observed data.

## 🚀 Features

- Implementation of simple linear regression from scratch
- Visualization of data and regression line
- Calculation of error metrics (e.g., Mean Squared Error)
- Well-commented code for easy understanding
- Example dataset included

## 🛠️ Requirements

- Python 3.x
- numpy
- matplotlib

Install dependencies using:

```bash
pip install numpy matplotlib
```

## 📊 Usage

1. **Clone this repository:**
   ```bash
   git clone https://github.com/PRAVITH10HJ/Linear-Regression.git
   cd Linear-Regression
   ```

2. **Run the main script:**
   ```bash
   python linear_regression.py
   ```

3. **Explore the results:**  
   Output graphs and evaluation metrics will be displayed or saved in the `results/` folder.

## 📝 Example

```python
from linear_regression import LinearRegression

# Example data
X = [1, 2, 3, 4, 5]
y = [3, 4, 2, 5, 6]

# Initialize and fit the model
model = LinearRegression()
model.fit(X, y)

# Predict
predictions = model.predict([6, 7])
print(predictions)
```

## 📚 References

- [GeeksforGeeks: Linear Regression](https://www.geeksforgeeks.org/linear-regression-python-implementation/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/linear_model.html#linear-regression)
