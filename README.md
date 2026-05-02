# 🐍 Employee Data Analysis — Python Project

A Python-based data analysis project using Google Colab to explore and analyze employee demographic and health datasets. The project applies data wrangling, exploration, and visualization techniques to uncover workforce trends and patterns.

---

## 📁 Repository Structure

```
Employee-Python-Analysis/
│
├── Python-2.ipynb                 # Main Colab notebook
├── Data/
│   ├── employee_details.csv       # Employee demographic & work data
│   └── employee_health.csv        # Employee health & wellness data
└── README.md                      # Project documentation
```

---

## 📌 Project Overview

| Detail | Info |
|---|---|
| **Tool** | Python (Google Colab) |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn |
| **Datasets** | employee_details.csv, employee_health.csv |
| **Focus** | Employee demographics, performance, and health trends |

---

## 📂 Datasets

### 1. `employee_details.csv`
Contains demographic and employment information for each employee.

| Field | Type | Description |
|---|---|---|
| EmployeeID | Integer | Unique employee identifier |
| Name | String | Employee name |
| Age | Integer | Employee age |
| Gender | String | Gender (Male/Female) |
| Department | String | Department (HR, Finance, IT, Sales, etc.) |
| JobRole | String | Role/position title |
| JobLevel | Integer | Seniority level |
| YearsAtCompany | Integer | Tenure at the company |
| MonthlyIncome | Integer | Monthly salary |
| PerformanceRating | Integer | Performance rating (1–4) |
| Attrition | String | Whether the employee left (Yes/No) |
| OverTime | String | Overtime status (Yes/No) |
| WorkLifeBalance | Integer | Work-life balance score (1–4) |

### 2. `employee_health.csv`
Contains health and wellness data linked to employees.

| Field | Type | Description |
|---|---|---|
| EmployeeID | Integer | Unique employee identifier |
| BMI | Float | Body Mass Index |
| BloodPressure | String | Blood pressure reading |
| PhysicalActivity | String | Activity level (Low/Medium/High) |
| StressLevel | Integer | Stress score (1–5) |
| SleepHours | Float | Average daily sleep hours |
| HealthStatus | String | Overall health status |
| SickDaysPerYear | Integer | Number of sick days taken annually |

---

## 🔍 Analysis Performed

### Data Cleaning & Preparation
- Loaded and inspected both datasets using Pandas
- Handled missing values and data type conversions
- Merged employee_details and employee_health on `EmployeeID`

### Exploratory Data Analysis (EDA)
- Distribution of age, income, and tenure across departments
- Gender and department breakdowns
- Attrition rate analysis by job role and department
- Correlation between performance rating and monthly income

### Health & Workforce Insights
- Relationship between stress level and work-life balance
- Impact of overtime on health status and sick days
- Physical activity levels across departments
- Sleep hours vs. performance rating comparison

### Visualizations
- Bar charts for department-wise headcount and attrition
- Histograms for age and income distributions
- Heatmap of correlations between numerical features
- Scatter plots for health vs. performance metrics

---

## 🛠 Tools & Libraries

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, and manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Base plotting and charting |
| `seaborn` | Statistical visualizations |

---

## 🚀 How to Run

1. Clone or download this repository.
2. Upload `Python-2.ipynb` to [Google Colab](https://colab.research.google.com/).
3. Upload `employee_details.csv` and `employee_health.csv` to the Colab session storage or mount Google Drive.
4. Run all cells from top to bottom (`Runtime → Run all`).

---

## 💡 Key Insights

- Employees with **high overtime** showed significantly higher stress levels and more sick days annually.
- **Sales and HR** departments had the highest attrition rates.
- A positive correlation was found between **physical activity level** and overall performance rating.
- Employees with **low work-life balance** scores tended to have higher BMI and lower sleep hours.

---

## 👤 Author

**Imtiaz Ahmed**
Data Analyst | Business Analyst
📧 imtiazahmadriyan@gmail.com
🔗 [linkedin.com/in/imtiaz-ahmad-49b5043b9](https://linkedin.com/in/imtiaz-ahmad-49b5043b9)
