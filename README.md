# Employee Attrition Analysis & Performance Insights

## **What is Employee Attrition?**

Employee attrition happens when an employee leaves an organization for any reason and is not replaced for a long time, or not ever. It often results in a decrease in the size of an organization's or department's workforce because positions aren't refilled when employees leave.


## **Problem Statement:**

Employee attrition poses a significant challenge for organizations, leading to increased recruitment costs, loss of experienced staff, and disruption in team productivity. Identifying the key factors that influence why employees leave is essential for Human Resource (HR) departments to develop effective retention strategies.


## **Project Overview**

This project analyzes the IBM HR Analytics Employee Attrition & Performance dataset to uncover insights about **employee turnover**, **job satisfaction**, **performance**, and other factors influencing attrition.


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

## **Key Questions**

1. What is the **overall attrition rate** in the company?
2. Which **job roles and departments** have the highest attrition?
3. Is there a **correlation between overtime and attrition**?
4. Does **job satisfaction or work-life balance** influence attrition?
5. How do **income, education, and experience** affect attrition?


## **Data Preprocessing**

* Checked for **missing values** and **inconsistent data**.
* Converted numeric categorical columns to **category datatype**: Education, JobSatisfaction, WorkLifeBalance, EnvironmentSatisfaction, JobInvolvement.
* Binned continuous variables like `TotalWorkingYears`, `YearsAtCompany`, and `MonthlyIncome` for grouped analysis.
* Removed or ignored **redundant columns** such as EmployeeCount, StandardHours, and EmployeeNumber for analysis.


## **Exploratory Data Analysis (EDA)**

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
5. **Satisfaction & Work-Life Balance:** Low satisfaction or poor work-life balance increases attrition.
6. **Income, Education & Experience:** Lower-paid employees and early-career employees have higher attrition.
   * Employees leaving the company tend to have slightly lower median monthly income of 3202 compared with median monthly income of 5204 for employees who continue working at company.
   * Attrition is higher among Bachelor and College level employees.
   * Employees with 0–9 years of experience or short tenure at company are more likely to leave.


## **Recommendation:**

Training, career growth, and incentive programs may reduce attrition. Improving work-life balance, job satisfaction, and compensation can significantly reduce turnover.


## **Future Work**

* Predictive modeling to **forecast employee attrition** using machine learning.



**Priscilla Philby Oommen**
