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

📎 

![skills_demand_by_role.png](attachment:648636ec-a7f9-446d-96a4-42c3a6032158:skills_demand_by_role.png)

🖼️ Top 5 skills for:

- Data Analyst
- Data Engineer
- Senior Data Engineer

**Top 5 Skills by Role (percent of postings)**

*(Bar chart)*

📎 

![skills_demand_percentage_by_role.png](attachment:78535416-7f21-48e6-b299-2ef582b33121:skills_demand_percentage_by_role.png)

---

### 🔹 2. Skill Trends Over 2023

**Notebook:** `3_skills_project_trends.ipynb`

**Question:** Which skills became more/less common over time?

✅ Filtered by month

✅ Calculated % of postings per skill per month

**Skill Trends (line plot)**

📎 

![trending_skills_percentage_data_analysts_CA.png](attachment:fd37ff0d-e92c-4bbd-970e-2d7ac3e49170:trending_skills_percentage_data_analysts_CA.png)

![trending_skills_data_analysts_CA.png](attachment:936b5854-1389-421e-a533-68f654c2e66f:trending_skills_data_analysts_CA.png)

---

### 🔹 3. Salary by Skill

**Notebook:** `4_salary_project_analysis.ipynb`

**Question:** Which skills lead to higher salaries?

✅ Focused on Data Analyst jobs in Canada

✅ Extracted top-paying and most frequent skills

**Top 10 Highest Paid Skills (bar chart)**

📎 `4_salary_project_analysis_plot_4.py`

![highest_vs_most_demanded_skills_data_analysts_CA.png](attachment:92b5e6ba-64af-44b9-80d6-78cac1e0acef:highest_vs_most_demanded_skills_data_analysts_CA.png)

🖼️ Looker, Snowflake, Spark, AWS, etc.

**Top 10 Most Common Skills (bar chart)**

📎 `4_salary_project_analysis_plot_8.py`

![salary_distribution_data_jobs_CA.png](attachment:24c20ec7-1e1c-4bb1-ab93-a0b4d65a0f90:salary_distribution_data_jobs_CA.png)

---

### 🔹 4. Optimal Skills (Demand vs Salary)

**Notebook:** `5_optimal_project_skills.ipynb`

**Question:** Which skills offer both high demand and high salary?

✅ Plotted % of job ads vs. median salary

✅ Annotated high-leverage skills

**Optimal Skill Scatter Plot**

📎 

![optimal_skills_data_analysts_CA.png](attachment:6f9c0d5d-f395-4fa8-ab01-0e501d097ba3:optimal_skills_data_analysts_CA.png)

🖼️ Shows Python, SQL, Tableau as top options

**Categorized by Technology**

📎 

![optimal_skills_by_technology_data_analysts_CA.png](attachment:d68ec3b5-1f26-4210-a296-14c2e8852af7:optimal_skills_by_technology_data_analysts_CA.png)

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
