# Customer Purchase Classification using Logistic Regression

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas" />
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge&logo=plotly" />
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Model-Logistic%20Regression-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Dataset-Social%20Network%20Ads-informational?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Problem-Classification-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Accuracy-82.5%25-brightgreen?style=for-the-badge" />
</p>

***

## 📌 Project Overview
This project focuses on predicting whether a customer will purchase a product based on features like **Gender**, **Age**, and **Estimated Salary**.
The machine learning model used in this project is **Logistic Regression**, which is suitable for binary classification problems.

The complete workflow of this project includes:
- Data loading
- Data exploration
- Data preprocessing
- Data visualization
- Model building
- Prediction and evaluation

***

## 🎯 Objective
The main objective of this project is to build a classification model that can predict customer purchase behavior using customer demographic and salary-related information.

***

## 🗂️ Dataset Information
The dataset used in this project is **Social Network Ads.csv**.

### Features in the dataset:
- **User ID** – Unique identifier for each customer
- **Gender** – Male or Female
- **Age** – Age of the customer
- **EstimatedSalary** – Estimated annual salary of the customer
- **Purchased** – Target variable (0 = Not Purchased, 1 = Purchased)

### Important note:
- `User ID` was removed because it does not contribute to prediction.
- `Purchased` is the dependent variable.

***

## 🛠️ Technologies and Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

***

## 📊 Exploratory Data Analysis
In this project, basic data exploration and visual analysis were performed to better understand the dataset.

### EDA steps covered:
- Checking dataset shape
- Viewing top rows of the dataset
- Checking null values
- Checking duplicate values
- Understanding data types
- Statistical summary of numerical columns
- Visualizing gender distribution
- Visualizing purchase count by gender

### Observations:
- The dataset contains **400 rows** and **5 columns**.
- No missing values were found.
- No duplicate values were found.
- Gender distribution is fairly balanced.
- Purchase behavior varies across customers and can be influenced by age and salary.

***

## 📉 Visualizations Used
This project includes the following visualizations:
- **Gender Count Plot**
- **Purchase Count by Gender**
- **Confusion Matrix Heatmap**

These visualizations help in understanding the distribution of data and the final model performance.

***

## ⚙️ Data Preprocessing
The following preprocessing steps were performed before model training:
- Removed the `User ID` column
- Converted categorical gender values into numerical format using encoding
- Selected important input features
- Split the dataset into training and testing sets

***

## 🤖 Model Building
The model used in this project is:

### Logistic Regression
Logistic Regression is a supervised machine learning algorithm used for binary classification.
Here, it is used to predict whether a customer will purchase a product or not.

***

## 🧪 Model Evaluation
The project evaluates the model using:
- **Accuracy Score**
- **Confusion Matrix**

### Result:
- **Model Accuracy: 82.5%**

### Confusion Matrix:
- True Negatives = 61
- False Positives = 12
- False Negatives = 9
- True Positives = 38

This shows that the model performs well in classifying customer purchase behavior.

***

## 📁 Project Files
- `Customer-Purchase-Classification-using-Logistic-Regression.ipynb` – Main notebook
- `Social_Network_Ads.csv` – Dataset file
- `Gender-Countplot.jpg` – Gender distribution plot
- `Purchase-Countplot.jpg` – Purchase count by gender plot
- `Model-Result.jpg` – Confusion matrix result

***

## 🚀 How to Run This Project
1. Clone this repository.
2. Open the project folder.
3. Install required libraries if not already installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open the Jupyter Notebook.
5. Run all cells step by step.

***

## 📌 Conclusion
This project demonstrates how Logistic Regression can be applied to solve a real-world binary classification problem.
Using customer details like age, gender, and estimated salary, the model predicts whether a customer is likely to purchase a product.

It is a simple and effective beginner-friendly machine learning project that covers the full pipeline from data analysis to model evaluation.

***

## 🔮 Future Improvements
This project can be improved further by:
- Applying feature scaling
- Trying other classification algorithms
- Using cross-validation
- Evaluating with precision, recall, and F1-score
- Building a small deployment app using Flask or Streamlit

***

## 🙌 Learning Outcome
Through this project, the following concepts were practiced:
- Binary classification
- Logistic Regression
- Data preprocessing
- Exploratory Data Analysis
- Data visualization
- Model evaluation

***

## 📎 Author
**Adiratna Kamble**

If you like this project, feel free to star the repository and connect with me on GitHub.
