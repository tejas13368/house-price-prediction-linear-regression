# house-price-prediction-linear-regression
.

## 🏡 Activity Overview
This project involves building, training, and evaluating a **Simple Linear Regression** model to predict house prices based on a single key feature from the Boston Housing dataset. It was developed as part of the Machine Learning CIE 2 practical activity.

## 📊 Dataset Source & Description
* **Dataset:** Boston Housing Dataset
* **Target Variable (`MEDV`):** Median value of owner-occupied homes (in $1000s).
* **Feature Variable (`RM`):** Average number of rooms per dwelling.
* **Objective:** Understand the linear relationship between the number of rooms (`RM`) and the house price (`MEDV`) using machine learning.

## 🛠️ Work Completed (Workflow)
1. **Data Loading & Inspection:** Imported necessary libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`) and inspected dataset structure and summary statistics.
2. **Exploratory Data Analysis (EDA) & Cleaning:** Checked for missing values and selected the feature (`RM`) and target (`MEDV`).
3. **Train-Test Split:** Divided the dataset into training (80%) and testing (20%) sets using `train_test_split`.
4. **Model Training:** Fitted a Linear Regression model using `scikit-learn` on the training data.
5. **Evaluation Metrics:** Evaluated model performance using:
   * **Mean Absolute Error (MAE)**
   * **Mean Squared Error (MSE)**
   * **R-Squared ($R^2$) Score**
6. **Visualizations:** Generated scatter plots showing the regression line fitted against the data points and residual plots.

## 🚀 How to Run the Code
1. Open the Jupyter Notebook (`.ipynb`) file in Google Colab or Jupyter Lab.
2. Run the cells sequentially to reproduce the data analysis, model training, and evaluation visualizations.

## 📝 Acknowledgements & Faculty Reference
This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: [Princy2129](https://github.com/Princy2129).
