# 🔍 Customer Churn Insight Analyzer

This project explores customer churn behavior in a telecom dataset and offers visual and predictive insights. It uses Python libraries like `pandas`, `matplotlib`, and `scikit-learn` to perform EDA (Exploratory Data Analysis), data filtering, and regression-based prediction.

---

## 📁 Project Description

Customer churn is when a client stops doing business with a company. Preventing churn is key to a successful business, especially in competitive industries like telecom. This notebook helps:
- Understand customer behavior
- Identify churn-prone segments
- Predict patterns like monthly charges based on tenure

---

## 🧰 Tools & Libraries

- **Pandas** & **NumPy** – Data manipulation
- **Matplotlib** – Visualization
- **Scikit-learn** – Regression modeling and evaluation

---

## 🔍 Exploratory Data Analysis

The notebook answers business-specific questions such as:
- Who are senior male customers using electronic checks?
- How many customers have over 70 months of tenure or high monthly charges?
- What patterns exist among churners using mailed checks with two-year contracts?

### 📊 Visualizations:
- Bar plot of Internet Service types
- Histogram of Customer Tenure
- Scatter plot: Tenure vs Monthly Charges
- Boxplot: Tenure by Contract type

---

## 🤖 Machine Learning

### 🔧 Model Used:  
- **Linear Regression** to predict `MonthlyCharges` based on `tenure`.

### 📈 Performance:
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**  
Used to evaluate prediction performance.

---

## 📌 Insights

- **Contract Type** strongly influences churn behavior.
- **Tenure & Monthly Charges** have a clear correlation.
- Customers on longer contracts churn less.
- Visual storytelling greatly supports business understanding.

---

## 🏁 Getting Started

1. Clone this repo or download the notebook
2. Ensure required libraries are installed:
```bash
pip install pandas numpy matplotlib scikit-learn
```
3. Open the notebook in Jupyter or VS Code and run all cells.

---

## 🙋‍♀️ Note

This notebook is part of an ongoing effort to dive deeper into customer behavior analytics. It's simple, visual, and built to be beginner-friendly.

Feel free to fork, experiment, and enhance it with classification models in future versions!

