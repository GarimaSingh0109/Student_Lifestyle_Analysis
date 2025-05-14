# 📊 Student Lifestyle & Stress Analysis Dashboard

This project analyzes the impact of lifestyle factors on student stress levels using **data analytics techniques** and interactive dashboards built in **Power BI** and **Tableau**. It includes **EDA, data visualization, descriptive statistics, predictive modeling**, and **correlation analysis**.

---

## 📁 Dataset Overview

- **File:** `student_lifestyle_dataset.csv` (unzipped from StudentLifeStyle.zip)
- **Records:** Each row represents a student with lifestyle attributes and their stress level.
- **Features Include:**
  - `Gender`
  - `Age`
  - `GPA`
  - `Sleep_Hours`
  - `Study_Hours`
  - `Physical_Activity`
  - `Internet_Usage`
  - `Stress_Level` (target variable)

---

## 🧪 Steps & Techniques

### 1. 📊 Exploratory Data Analysis (EDA) - Python
- Handled missing values and checked for duplicates.
- Visualized distributions using:
  - Countplots (`Stress_Level`)
  - Boxplots (`GPA`, `Sleep_Hours`)
  - Histograms (`Internet_Usage`)
- Categorical encoding for modeling.

### 2. 📈 Correlation Analysis
- Pearson correlation for numerical features.
- Heatmaps to identify correlated features with `Stress_Level`.

### 3. 📋 Descriptive Statistics
- Used `.describe()` and groupby aggregation.
- Summarized mean, median, std by stress levels.

### 4. 🧠 Predictive Modeling
- Logistic Regression, Random Forest Classifier.
- Train-test split (80-20).
- Evaluation using accuracy, precision, recall, and confusion matrix.

---

## 📊 Tableau Dashboard

### Features:
- **Treemap**: Stress Level segmented by GPA Category.
- **Bar Chart**: Sleep Hours by Stress Level.
- **Scatter Plot**: GPA vs. Internet Usage with Stress Level as color.
- Filters for Gender and Physical Activity.

### Instructions:
1. Connect Tableau to the CSV file.
2. Create calculated fields (e.g., `GPA Category`).
3. Use "Show Me" panel to build visuals.
4. Add sheets to a single dashboard view.

---

## 📊 Tableau Visualizations

### 🟦 Treemap: Stress Level Distribution
![Treemap](images/stress_treemap.png)

### 🟪 GPA Category vs. Stress Level
![GPA vs Sleep_Hours_per_Day]()

### 🟧 Bar Chart: Sleep Hours by Stress
![Sleep Bar](images/sleep_stress_bar.png)


### Dashboard
[![Dashboard Preview](https://github.com/GarimaSingh0109/Student_Lifestyle_Analysis/blob/main/Dashboard%201.png)]([https://public.tableau.com/views/YourDashboardName/YourSheet](https://public.tableau.com/app/profile/garima.singh7972/viz/Student_lifestyle/Dashboard1?publish=yes))


