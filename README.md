# 🏠 California House Price Prediction
https://colab.research.google.com/#scrollTo=lIYdn1woOS1n

## 📌 Project Overview
This project is a fundamental implementation of **Supervised Machine Learning**. The goal is to predict house prices in California based on economic and demographic factors using the **Linear Regression** algorithm.

By analyzing the relationship between median income and housing costs, this model provides a mathematical estimation of property value, a technique widely used in real estate tech (PropTech) by companies like Zillow and Redfin.

## 🛠️ Tech Stack
* **Language:** Python 3.13
* **Libraries:** * `NumPy` & `Pandas`: For data manipulation.
  * `Scikit-learn`: For implementing the Linear Regression model.
  * `Matplotlib`: For data visualization and plotting the regression line.

## 📊 Dataset
The project utilizes the **California Housing Dataset** (built-in to Scikit-learn).
* **Target Variable:** Median house value for California districts.
* **Key Feature Used:** `MedInc` (Median income in block group).

## 🚀 How It Works
1. **Data Acquisition:** Loading the dataset directly from Scikit-learn.
2. **Train-Test Split:** Dividing the data (80% Training, 20% Testing) to ensure the model can generalize to new data.
3. **Model Training:** Using the `LinearRegression()` class to find the line of best fit.
4. **Evaluation:** Testing the model accuracy using R2 Score and Mean Squared Error (MSE).

## 📈 Results & Visualizations
The model successfully identifies a positive correlation between income and house prices.

| Metric | Value |
| :--- | :--- |
| **R2 Score** |  0.46 |
| **MSE** |  0.71 |

### Regression Plot
The scatter plot in the notebook visualizes the actual data points (blue) against the model's prediction line (red).

## 👤 Author
**Kushagra Goyal** *B.Tech Computer Science and Engineering (1st Year)* *Registration No: 25BCE11143*

---
*This project was developed as part of my AI-ML learning journey.*
