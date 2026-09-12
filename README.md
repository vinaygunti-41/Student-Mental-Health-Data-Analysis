<div align="center">

# 🧠 Student Mental Health Data Analysis

### 📊 Exploring Stress, Academic Pressure & Student Well-being using Python

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&weight=600&size=24&duration=3500&pause=1000&color=00FF88&center=true&vCenter=true&width=700&lines=Python+%7C+Pandas+%7C+NumPy;Matplotlib+%7C+Seaborn+Visualization;Data+Cleaning+%26+Exploratory+Data+Analysis;Student+Mental+Health+Insights"/>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas"/>
  <img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=for-the-badge&logo=numpy"/>
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-43B02A?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter"/>
</p>

</div>

---

# 📌 Project Overview

Mental health has become one of the biggest challenges faced by students across universities and colleges. This project analyzes a **Student Mental Health** dataset to discover patterns related to **stress, anxiety, depression, academic pressure, demographics, and lifestyle factors**.

Using **Python** and **Exploratory Data Analysis (EDA)** techniques, this project transforms raw survey data into meaningful insights through data cleaning, statistical summaries, and visual storytelling.

> 🎯 **Goal:** Help educators and policymakers understand factors influencing student mental health and support better decision-making.

---

# 🎯 Objectives

- 📖 Understand students' mental health conditions.
- 🎓 Analyze the impact of academic pressure on well-being.
- 👨‍🎓 Explore demographic trends (Age, Gender, Course, Year of Study).
- 📊 Identify relationships between mental health indicators.
- 💡 Generate actionable insights using visual analytics.

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| 🐍 Python | Data Analysis |
| 📒 Jupyter Notebook | Interactive Analysis |
| 🐼 Pandas | Data Cleaning & Manipulation |
| 🔢 NumPy | Numerical Operations |
| 📈 Matplotlib | Charts & Graphs |
| 🌊 Seaborn | Statistical Visualization |

---

# 📂 Dataset Information

| Feature | Description |
|---------|-------------|
| **Dataset** | Student Mental Health CSV |
| **Format** | CSV |
| **Records** | Student Survey Responses |
| **Domain** | Education & Mental Health |

### Dataset Includes

- 👤 Gender
- 🎂 Age
- 🎓 Course
- 📚 Year of Study
- 😰 Stress Level
- 😟 Anxiety
- 💙 Depression
- 😴 Sleep Quality
- ❤️ Mental Health Treatment
- 📍 Other psychological indicators

---

# 📁 Project Workflow

```text
Student Mental Health Dataset
            │
            ▼
     📥 Data Loading
            │
            ▼
     🧹 Data Cleaning
            │
            ▼
 🔍 Exploratory Data Analysis
            │
            ▼
 📊 Data Visualization
            │
            ▼
 💡 Insights & Conclusions
```

---

# 🔎 Exploratory Data Analysis

The notebook performs multiple stages of EDA.

## 📌 Data Inspection

- Dataset Shape
- Column Information
- Data Types
- Missing Values
- Duplicate Records
- Summary Statistics

## 📌 Categorical Analysis

- Gender Distribution
- Age Distribution
- Course Frequency
- Year of Study
- Mental Health Status

## 📌 Numerical Analysis

- Descriptive Statistics
- Correlation Matrix
- Distribution Analysis
- Value Counts

---

# 📊 Visualizations Included

This project uses beautiful statistical visualizations to understand student well-being.

### 📈 Analysis Dashboard Includes

- 📊 Bar Charts
- 🥧 Pie Charts
- 📉 Count Plots
- 🌡️ Correlation Heatmap
- 📦 Box Plots
- 📍 Distribution Plots
- 📊 Histogram Analysis

Example insights visualized through Python libraries.

---

# ✨ Key Insights

- 📚 Academic pressure is strongly associated with higher stress levels.
- 😴 Students with poor sleep quality report increased anxiety.
- 👩‍🎓 Mental health trends vary across courses and years of study.
- 💙 A significant number of students hesitate to seek treatment.
- 📈 Visualizations highlight demographic groups with higher mental health risks.

---

# 📁 Project Structure

```bash
Student-Mental-Health-Analysis/
│── Student Mental health.csv
│── Student_Mental_Health_Analysis.ipynb
│── README.md
│── images/
│     ├── heatmap.png
│     ├── age_distribution.png
│     ├── gender_chart.png
│     └── stress_analysis.png
```

---

# 🚀 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/vinaygunti-41/Student-Mental-Health-Analysis.git
```

## 2️⃣ Navigate to Project

```bash
cd Student-Mental-Health-Analysis
```

## 3️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn notebook
```

## 4️⃣ Launch Notebook

```bash
jupyter notebook
```

Open:

```text
Student_Mental_Health_Analysis.ipynb
```

---

# 📌 Python Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

# 📈 Sample Analysis Performed

### Missing Value Detection

```python
dataset.isnull().sum()
```

### Correlation Heatmap

```python
corr = dataset.corr(numeric_only=True)

sns.heatmap(corr,
            annot=True,
            cmap="coolwarm",
            linewidths=0.5)

plt.title("Student Mental Health Correlation Matrix")
plt.show()
```

### Frequency Distribution

```python
dataset['Age'].value_counts()
dataset['Course'].value_counts()
dataset['Gender'].value_counts()
```

---

# 💡 Business / Educational Impact

This analysis can help:

- 🏫 Universities identify high-risk student groups.
- 👨‍⚕️ Counselors understand stress-related patterns.
- 📚 Education policymakers improve mental health programs.
- 🤖 Researchers build predictive mental health models.

---

# 📊 Future Improvements

- ✅ Interactive Power BI Dashboard
- ✅ Predict Mental Health Risk using Machine Learning
- ✅ Student Stress Prediction Model
- ✅ Sentiment Analysis on Student Feedback
- ✅ Streamlit Web App for Mental Health Analytics

---

# 📸 Project Preview

> Add screenshots inside the `images/` folder and display them below.

```md
## Dashboard Preview

![Heatmap](images/heatmap.png)

![Age Distribution](images/age_distribution.png)

![Stress Analysis](images/stress_analysis.png)
```

---

# 📚 Learning Outcomes

Through this project, I practiced:

- ✔️ Data Cleaning
- ✔️ Exploratory Data Analysis (EDA)
- ✔️ Correlation Analysis
- ✔️ Data Visualization
- ✔️ Statistical Interpretation
- ✔️ Python Data Analytics Workflow

---

# 👨‍💻 Author

<div align="center">

## Gunti Vinay

**Aspiring Data Analyst | Python • SQL • Power BI • Tableau**

<p align="center">
  <a href="https://github.com/vinaygunti-41">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/>
  </a>

  <a href="https://linkedin.com/in/vinaygunti-dataanalyst">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin"/>
  </a>

  <a href="https://devoted-jade-0of9azstaa.edgeone.app/">
    <img src="https://img.shields.io/badge/Portfolio-00C853?style=for-the-badge&logo=google-chrome"/>
  </a>
</p>

</div>

---

<div align="center">

### ⭐ If you found this project useful, don't forget to Star the Repository!

<img src="https://capsule-render.vercel.app/api?type=waving&color=00FF88&height=120&section=footer"/>

</div>
