# 🔢 Numerical Missing Value Handling

A hands-on Machine Learning preprocessing project focused on handling missing values in numerical features using Mean and Median Imputation techniques.

---

## 🚀 Project Overview

Missing values are one of the most common challenges in real-world datasets. In this project, I explored different strategies for handling missing numerical data and analyzed how these techniques affect data distribution and statistical properties.

Using the Titanic dataset, I compared Mean and Median Imputation methods and visualized their impact on the dataset.

---

## 📚 Concepts Covered

### 🔍 Missing Value Analysis
✔️ Detecting missing values

✔️ Calculating missing value percentages

✔️ Understanding missing data patterns

### 🛠️ Imputation Techniques
✔️ Mean Imputation

✔️ Median Imputation

✔️ SimpleImputer (Scikit-Learn)

### 📊 Statistical Analysis
✔️ Distribution Comparison

✔️ Covariance Analysis

✔️ Correlation Analysis

✔️ Outlier Impact Assessment

### 📈 Visualization
✔️ KDE Plots

✔️ Histograms

✔️ Boxplots

✔️ Distribution Comparison Charts

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Scikit-Learn | Imputation & Preprocessing |
| Jupyter Notebook | Development Environment |

---

## 📂 Dataset

**Titanic Dataset**

Features used for numerical missing value handling:

- Age
- Fare

Target Variable:

- Survived

---

## 🔥 Key Techniques Implemented

```python
SimpleImputer(strategy='mean')
SimpleImputer(strategy='median')
train_test_split()
ColumnTransformer()
fit()
transform()
```

---

## 🎯 Learning Outcomes

Through this project, I learned:

- How to identify missing numerical values
- When to use Mean Imputation
- When to use Median Imputation
- The effect of outliers on imputation techniques
- How imputation changes data distributions
- Building preprocessing pipelines using Scikit-Learn

---

## 📁 Project Structure

```text
📦 numerical-missing-value-handling
 ┣ 📓 Day_36.ipynb
 ┣ 📄 README.md
 ┗ 📊 Titanic Dataset
```

---

## 💡 Key Insight

Mean Imputation works well when data is normally distributed and contains fewer outliers.

Median Imputation is generally more robust when the dataset contains significant outliers or skewed distributions.

---

## 👨‍💻 Author

**Raj Kumar**
B.Tech CSE (AI & ML)

> Good models start with good data preprocessing.
