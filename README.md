# potential-eureka
# 🚀 Machine Learning Projects: Driver Clustering & Salary Prediction

This repository contains two beginner-friendly machine learning projects demonstrating essential ML concepts:

1. **Driver Behavior Clustering (K-Means)**  
2. **Salary Prediction (Linear Regression)**

These projects are designed to showcase both **unsupervised** and **supervised** learning using Python and popular libraries like `pandas`, `scikit-learn`, `matplotlib`, and `seaborn`.

---

## 📁 Project Files


---

## 📌 Project 1: Driver Behavior Clustering (K-Means)

### 🎯 Objective
Group drivers based on:
- `mean_dist_day`: Average distance driven per day
- `mean_over_speed_perc`: Percentage of time over the speed limit

### 📊 Dataset Summary (`driver-data.csv`)
- 4000 entries
- 3 columns: `id`, `mean_dist_day`, `mean_over_speed_perc`

### 🧠 ML Technique
- **K-Means Clustering** (tested with 3 and 4 clusters)
- Visual analysis using `seaborn` and `matplotlib`

### 🔍 Key Outputs
**Cluster Centers (k=3):**

**Cluster Centers (k=4):**

### 📊 Visualizations
- Seaborn `lmplot` used to visualize clusters
- Clear separation between cautious, average, and aggressive drivers

---

## 📌 Project 2: Salary Prediction (Linear Regression)

### 🎯 Objective
Predict an employee's salary based on their years of experience.

### 📊 Dataset Summary (`Salary_Data.csv`)
- 30 records
- Columns: `YearsExperience`, `Salary`

### 🧠 ML Technique
- **Simple Linear Regression** using `scikit-learn`
- Data splitting (2/3 training, 1/3 test)
- Visualization of predictions and model evaluation

### 📈 Predictions
```python
y_pred = lr.predict(x_test)
Mean Absolute Error (MAE): 3426.43
Mean Squared Error (MSE): 21026037.33
Root Mean Squared Error (RMSE): 4585.42
```
pandas
numpy
matplotlib
seaborn
scikit-learn

pip install pandas numpy matplotlib seaborn scikit-learn
git clone https://github.com/kibeert/potential-eureka.git
cd potential-eureka

