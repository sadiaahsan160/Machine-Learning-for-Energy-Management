# Predictive Analysis of Energy Consumption Patterns using Machine Learning

**Project overview:** The objective of this project is to develop a machine learning-based model that predicts household energy consumption over hourly, daily, and weekly intervals.By leveraging historical energy usage data, the goal is to build a predictive model that captures consumption patterns and supports efficient energy management strategies.

**Methodology:**

**Data Collection:** Historical data is collected from individual household smart meters.

**Data Preprocessing:**

- Handling missing values using mean imputation

- Resampling data to hourly, daily, and weekly intervals

- Normalization using Min-Max scaling for uniform feature distribution

**Model Training:**
A machine learning regression model (XGBoost) is trained on preprocessed data to predict consumption patterns.

**Evaluation:**
Model performance is evaluated using RMSE, MSE, and MAE metrics.

**Dataset**

### **Source:** [Individual Household Electric Power Consumption Dataset (UCI Repository)](http://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption)

**Technologies & Frameworks Used**

**Programming Language:** Python 🐍

**Machine Learning Libraries:** scikit-learn, NumPy, Pandas, Matplotlib

**Environment:** Google Colab / Jupyter Notebook
