# CODETECH – TASK 4  
## Exploratory Data Analysis & Pattern Discovery

**Intern:** Abhii Parihar  
**Domain:** Data Science / Machine Learning  
**Company:** CODETECH IT SOLUTIONS  

---

## 📌 Objective

The objective of this task is to explore the cleaned suicide dataset and identify patterns, trends, and relationships using data visualization techniques. This helps in understanding the data better before applying any advanced analysis or machine learning.

---

## 🛠 Tools Used

- Python  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 📂 Dataset

- Dataset: Suicide Data (Cleaned)  
- Source:  
  https://raw.githubusercontent.com/MainakRepositor/Datasets/master/Suicide%20data.csv  

---

## 🔍 Exploratory Data Analysis (EDA)

In this task, I performed exploratory data analysis on the cleaned dataset to understand the distribution of variables and relationships between different features.

---

### 📊 1. Distribution of Suicide Numbers

```python
sns.histplot(df['suicides_no'])
