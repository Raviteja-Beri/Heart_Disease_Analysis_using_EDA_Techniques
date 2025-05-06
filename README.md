# ❤️ Heart Disease EDA | Healthcare Data Analysis with Python

This project performs **Exploratory Data Analysis (EDA)** on a heart disease dataset to uncover meaningful health patterns and risk factors associated with cardiovascular disease (CVD). Using tools like **Seaborn**, **Pandas**, and **Matplotlib**, the analysis delivers rich insights via visual storytelling.

---

## 📌 Objective

- Explore trends and distributions in heart disease patient data.
- Understand how demographic and medical features relate to heart disease.
- Generate actionable health insights using visual analytics.

---

## 🧠 Dataset Overview

The dataset includes medical records for patients with and without heart disease, with features such as:

- **Age, Sex, Chest Pain Type (cp), Blood Pressure (trestbps)**
- **Cholesterol (chol), Fasting Blood Sugar (fbs), ECG Results (restecg)**
- **Maximum Heart Rate (thalach), Exercise-induced Angina (exang)**
- **ST Depression (oldpeak), Slope of ST Segment, Number of Major Vessels**
- **Target (1 = heart disease, 0 = no disease)**

---

## 🧪 Key Techniques Used

- Handling and visualizing missing values.
- Analyzing categorical vs. numerical features.
- Statistical correlation matrix & heatmaps.
- Group-based feature comparisons.
- KDE plots, histograms, box plots, pairplots, and count plots.

---

## 📈 Sample Visualizations

- **Distribution of Age and Cholesterol**
- **Heart Disease Frequency by Gender and Chest Pain Type**
- **Correlation Heatmap of All Features**
- **Boxplots by Target Class (disease/no disease)**
- **Pairplots to identify multi-feature trends**

---

## 🔍 Notable Insights

- Certain chest pain types and ECG results show stronger correlation with heart disease.
- Males had a slightly higher frequency of heart disease than females in this dataset.
- High resting blood pressure and cholesterol values tend to be associated with higher risk.
- Exercise-induced angina and peak heart rate are critical indicators.

---

## 💡 Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`

---

## ▶️ How to Run the Notebook

1. **Clone the repository:**

   ```bash
   git clone https://github.com/<your-username>/heart-disease-eda.git
   cd heart-disease-eda
   ```

2. **Install requirements:**

```bash
pip install pandas matplotlib seaborn scipy
```
3. **Launch Jupyter Notebook:**

```bash
jupyter notebook EDA-Heart-Disease-Analysis.ipynb
```
## 🧑‍⚕️ Use Cases
* Healthcare risk profiling

* Preventive analytics for heart disease

* Medical feature correlation studies

* EDA teaching material for data science students
