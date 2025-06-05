# Python Data Project – Luke Barousse Course

This project is part of my learning journey through the Python course by Luke Barousse.  
It's currently a work in progress (WIP), as I continue to apply and expand my Python skills.

The goal of this project is to reinforce key data concepts while building hands-on experience with real Python code.

# 📊 Canadian Data Job Market Analysis

## 📘 Introduction

This project explores demand, trends, salaries, and optimal skills for data roles in Canada, using data from the Luke Barousse Job Dataset. 

Additionally, this repository is part of the capstone project I worked on during the “Python for Data Analytics” course, taught by Luke Barousse.
The project integrates Python programming with data analysis techniques, culminating in a real-world application that demonstrates the skills acquired throughout the course.

---

## 🛠️ Background

The dataset includes 700K+ job postings, focusing on:

- 🇨🇦 Canadian roles
- Job titles, skills, salaries
- Analysis done with Python (pandas, seaborn, matplotlib)

---

## 🧰 Tools Used

`Python`, `pandas`, `seaborn`, `matplotlib`, `adjustText`, `Hugging Face datasets`

---

## 📊 Analysis

*It was noticed that the dataset didn't provide much Canada data, I proceeded with the analysis just for educational purposes*

### 🔹 1. Skill Demand by Role

**Notebook:** `2_skills_project_demand.ipynb`

**Question:** What skills are most in demand for Data Analyst and Data Engineer roles?

✅ Filtered for Canadian roles

✅ Exploded skill lists

✅ Counted frequency and % per job title

**Top 5 Skills by Role (absolute counts)**

*(Bar chart)*

![image](https://github.com/user-attachments/assets/9164cfd9-211a-4d4f-a550-0406c306abd5)


🖼️ Top 5 skills for:

- Data Analyst
- Data Engineer
- Senior Data Engineer

**Top 5 Skills by Role (percent of postings)**

*(Bar chart)*

![image](https://github.com/user-attachments/assets/2787472d-5e74-499a-9fc3-9e7441d230a0)

---

### 🔹 2. Skill Trends Over 2023

**Notebook:** `3_skills_project_trends.ipynb`

**Question:** Which skills became more/less common over time?

✅ Filtered by month

✅ Calculated % of postings per skill per month

**Skill Trends (line plot)**

📎 

![image](https://github.com/user-attachments/assets/a14807c1-14b5-4030-88d1-e2faa2799392)

---

### 🔹 3. Salary by Skill

**Notebook:** `4_salary_project_analysis.ipynb`

**Question:** Which skills lead to higher salaries?

✅ Focused on Data Analyst jobs in Canada

✅ Extracted top-paying and most frequent skills

**Top 10 Highest Paid Skills (bar chart)**

📎 `4_salary_project_analysis_plot_4.py`

![image](https://github.com/user-attachments/assets/ccf6b84d-c8b7-4b6d-a2bc-c8a60e944365)


🖼️ Looker, Snowflake, Spark, AWS, etc.

**Top 10 Most Common Skills (bar chart)**

📎 `4_salary_project_analysis_plot_8.py`

![image](https://github.com/user-attachments/assets/0fc4dae5-777a-4f93-82f4-44534d300a5d)

---

### 🔹 4. Optimal Skills (Demand vs Salary)

**Notebook:** `5_optimal_project_skills.ipynb`

**Question:** Which skills offer both high demand and high salary?

✅ Plotted % of job ads vs. median salary

✅ Annotated high-leverage skills

**Optimal Skill Scatter Plot**

📎 

![image](https://github.com/user-attachments/assets/0bfd8d2e-9ac0-4783-b5be-0fee5dbc4cc5)

🖼️ Shows Python, SQL, Tableau as top options

**Categorized by Technology**

📎 

![image](https://github.com/user-attachments/assets/7c6a3b40-87cf-476b-8f6b-b518ec12e993)


🖼️ Skills grouped by libraries, cloud, analyst tools, etc.

---

## 📚 What I Learned

- Exploding nested skill columns for analysis
- Using `groupby` and joins to calculate demand and salary metrics
- Creating annotated scatter plots with `adjustText`
- How to think analytically about job market datasets

---

## 🔍 Insights

- SQL and Python dominate both in demand and salary
- Tableau and Excel remain essential for analysts
- Spark and Snowflake are high-value for niche roles
- Optimal portfolio = highly demanded + above-median salary skills

---

## 🏁 Conclusion

This project maps the Canadian data job market clearly, showing how specific tools and skills can drive both employability and earnings.
