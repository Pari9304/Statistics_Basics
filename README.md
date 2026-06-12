# 📊 Descriptive Statistics - Iris Dataset

This repository contains a simple exploratory data analysis (EDA) project using Python on the famous **Iris dataset**. The goal is to understand basic statistical concepts using Pandas and NumPy.

---

## 📁 Dataset Used

- **Name:** Iris Dataset  
- **Size:** 150 rows × 5 columns  
- **Features:**
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
  - Species

This dataset is widely used for learning classification and statistical analysis in data science.

---

## 📌 Project Overview

This project focuses on **descriptive statistics**, including:

- Loading dataset using Pandas
- Exploring dataset structure
- Computing basic statistical measures

---

## 📊 Key Operations Performed

### 1. Data Inspection
- Viewing first few rows using `head()`
- Viewing last few rows using `tail()`
- Checking dataset shape using `shape`

---

### 2. Statistical Analysis

The following statistical measures were calculated:

- **Mean** → Average value of petal length  
- **Median** → Middle value of petal width  
- **Mode** → Most frequently occurring sepal length  
- **Maximum Value** → Highest petal width in dataset  

---

## 🧮 Example Code Snippet

```python
import pandas as pd
import numpy as np

df = pd.read_csv("IRIS.csv")

mean = df['petal_length'].mean()
median = df['petal_width'].median()
mode = df['sepal_length'].mode()
max_value = df['petal_width'].max()
```

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

- How to load and explore datasets in Python
- Basic descriptive statistics (mean, median, mode)
- How to use Pandas for data analysis
- Fundamentals of Exploratory Data Analysis (EDA)

---

## 📂 Repository Structure

```
stats/
│
├── IRIS.csv
├── iris_statistics.ipynb
└── README.md
```

---

## 📖 About This Project

This is a beginner-level statistics project created as part of my data science learning journey. It helps build a strong foundation in statistical thinking and Python-based data analysis.

---
