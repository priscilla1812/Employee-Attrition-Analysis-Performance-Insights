# Employee Attrition Analysis & Performance Insights

## **What is Employee Attrition?**

Employee attrition happens when an employee leaves an organization for any reason and is not replaced for a long time, or not ever. It often results in a decrease in the size of an organization's or department's workforce because positions aren't refilled when employees leave.


## **Problem Statement:**

Employee attrition poses a significant challenge for organizations, leading to increased recruitment costs, loss of experienced staff, and disruption in team productivity. Identifying the key factors that influence why employees leave is essential for Human Resource (HR) departments to develop effective retention strategies.


## **Project Overview**

This project focuses on analyzing employee attrition patterns and uncovering the key factors that drive employees to leave or stay in a company. The analysis provides actionable insights for HR and management teams to improve employee retention and workplace satisfaction.


## **Tools & Libraries**

* Python 3
* Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
* Environment: Google Colab / Jupyter Notebook


## **Dataset**

* **Source:** IBM HR Analytics Employee Attrition & Performance dataset (Kaggle)
* **Number of Records:** 1470 employees
* **Features:**

  * Employee information: Age, Gender, Marital Status, Education, JobRole, Department
  * Work data: YearsAtCompany, TotalWorkingYears, MonthlyIncome, OverTime
  * Satisfaction & Performance: JobSatisfaction, WorkLifeBalance, EnvironmentSatisfaction, JobInvolvement, PerformanceRating
  * Attrition: Yes / No

## **Key Objectives**

1. Identify the overall attrition rate in the company.
2. Explore which job roles, departments, and demographics have the highest attrition.
3. Analyze the relationship between overtime, work-life balance, and job satisfaction with attrition.
4. Understand how income, education, and experience influence employee turnover.
5. Provide data-driven recommendations for reducing attrition.


## **Data Preprocessing**

* Checked for **missing values** and **inconsistent data**.
* Converted numeric categorical columns to **category datatype**: Education, JobSatisfaction, WorkLifeBalance, EnvironmentSatisfaction, JobInvolvement.
* Binned continuous variables like `TotalWorkingYears`, `YearsAtCompany`, and `MonthlyIncome` for grouped analysis.
* Removed or ignored **redundant columns** such as EmployeeCount, StandardHours, and EmployeeNumber for analysis.


## **Exploratory Data Analysis (EDA)**

1. Attrition breakdown by Age Group, Income, Education, and Job Roles
2. Impact of Overtime on attrition
3. Correlation between Work-Life Balance, Job Satisfaction, and Attrition
4. Salary insights across Marital Status & Education Fields
5. Effect of Promotions (YearsSinceLastPromotion) and PercentSalaryHike on attrition

* Visualizations include:

  * **Overall Attrition Rate** (pie chart)
  * **Attrition by JobRole & Department** (countplots / bar charts)
  * **Attrition vs Overtime** (countplots)
  * **Attrition vs Job Satisfaction, Work-Life Balance, Environment Satisfaction, Job Involvement, Relationship Satisfaction** (countplots)
  * **Attrition vs Income, Education, Total Working Years** (boxplots, grouped bar charts)


## **Insights**

1. **Overall attrition rate:** 16.12% (237 employees left).
2. **High attrition departments:** Sales and Research & Development.
3. **High attrition roles:** Laboratory Technician, Sales Executive, Research Scientist and Sales Representative
4. **Overtime effect:** Employees with overtime have significantly higher attrition.
5. **Satisfaction & Work-Life Balance:** Low satisfaction or poor work-life balance increases attrition. Job Satisfaction is a major driver of retention.
6. **Income, Education & Experience:** Lower-paid employees and early-career employees have higher attrition.
   * Employees leaving the company tend to have slightly lower median monthly income of 3202 compared with median monthly income of 5204 for employees who continue working at company.
   * Attrition is higher among Bachelor and College level employees.
   * Employees with 0–9 years of experience or short tenure at company are more likely to leave.
   * Recent promotions correlate with lower attrition risk.


## **Recommendation:**

1. Reduce excessive overtime workloads.
2. Improve career growth opportunities through timely promotions.
3. Strengthen employee engagement programs to improve job satisfaction.
4. Review compensation structures to ensure fair pay across roles and education levels.
5. Focus retention strategies on high-risk groups (younger employees, singles, frequent overtime workers).

## **Future Work**

* Predictive modeling to **forecast employee attrition** using machine learning.



**Priscilla Philby Oommen**
