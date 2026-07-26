# 💼 Employee Salary Analysis

## 1. Background and Overview

### Background

There are many influencing factors that impact the salaries of employees; such factors include the employee position, experience, educational background, organization size, and location among others. It will be important for an organization to understand these factors to help in benchmarking salaries and making HR decisions based on evidence.

### Objective

This project aims to perform an end-to-end analysis of an employee salary dataset using statistical analysis and data visualization. Specifically, the study seeks to identify the factors most strongly associated with employee salaries and quantify their relationships using Multiple Linear Regression. The findings are presented through an interactive Power BI dashboard.

### Tools Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, SciPy, Statsmodels, Pingouin, Matplotlib
- **Visualization:** Power BI
- **Environment:** Jupyter Notebook

---

## 2. Project Files
### Dashboard
- 📊 [Power BI Dashboard (.pbix)](Employee_salary_dashboard.pbix)

### Dataset
- 💰 [job_salary_prediction_dataset.csv](job_salary_prediction_dataset.csv)

### Python script
- 🗄️ [Employee_salary_analysis.ipynb](Employee_salary_analysis.ipynb)

### Images
- 📊 [Employee Salary Analysis Dashboard](dashboard.png)

---

## 3. Dataset Overview

### Dataset Information

| Item | Description |
|------|-------------|
| Source | Kaggle |
| Records | 250,000 |
| Variables | 10 |
| Target Variable | Salary |
| Dataset Type | Synthetic dataset |

### Dataset Features

| Variable | Data Type |
|----------|-----------|
| Salary | Numerical |
| Experience Years | Numerical |
| Skills Count | Numerical |
| Certifications | Numerical |
| Education Level | Ordinal |
| Company Size | Ordinal |
| Job Title | Categorical |
| Location | Categorical |
| Industry | Categorical |
| Remote Work | Categorical |

### Project Workflow

```text
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Statistical Analysis
(Correlation + ANOVA + Regression)
    │
    ▼
Business Insights
    │
    ▼
Power BI Dashboard
```

---

## 4. Key Insights

### Salary Distribution

- AI Engineer (\$171K), Machine Learning Engineer (\$161K), and Product Manager (\$156K) have the highest median salaries.
  
- Employees located in the USA, Canada, and the UK receive the highest median salaries.
  
- Employees with higher education levels and those working in larger companies tend to earn higher salaries.

### Statistical Findings

- "Experience Years" shows the strongest positive association among numerical variables.
  
- "Location" has the largest effect size among categorical variables.
  
- "Industry" shows negligible practical influence on salary.

### Multiple Linear Regression Findings

After controlling for other variables:

- "Experience Years" remains the strongest numerical factor associated with salary.
  
- Employees with a Diploma earn approximately \$5,330 less than those holding a Bachelor's degree, on average, while keeping other variables constant.

---

## 5. Recommendations

Based on the findings, HR teams should:

- Benchmark compensation primarily by job title and location rather than industry.
  
- Review salary structures for highly competitive positions such as AI Engineer and Machine Learning Engineer.
  
- Incorporate experience and education level into salary band design and promotion planning.
  
- Apply location-specific compensation strategies to remain competitive across different labor markets.

---

## 6. Limitations

This project has several limitations that should be considered when interpreting the results:

- The dataset is synthetic, so the high R² value (0.963) reflects its structured nature and should not be directly generalized to real-world labor market data.
  
- The analysis identifies statistical associations rather than causal relationships.

