# HR Data Analysis using MySQL

This project contains SQL queries used to analyze employee data from the `hr_data` database.  
The dataset includes information such as employee age, department, education, job role, job satisfaction, marital status, and attrition.

## Database

```sql
USE hr_data;
SELECT * FROM hrdata;
```
## Analysis Performed

### 1. Count employees in each department
Counts how many employees work in every department.

### 2. Average age per department
Calculates the mean age of employees grouped by department.

### 3. Most common job roles per department
Groups job roles within departments and identifies which roles appear most frequently.

### 4. Average job satisfaction by education level
Shows how job satisfaction varies across different levels of education.

### 5. Average age by job satisfaction level
Compares age differences for employees with different satisfaction levels.

### 6. Attrition rate per age band
Computes the percentage of employees who left the company in each age band.

### 7. Department with highest and lowest job satisfaction
Finds which department has the best average job satisfaction score.

### 8. Highest attrition rate by education level and age band
Identifies the education level and age band combination with the greatest attrition rate.

### 9. Education level with highest job satisfaction among frequent travelers
Focuses on employees with frequent business travel and finds which education group is most satisfied.

### 10. Age band with highest job satisfaction among married employees
Analyzes job satisfaction by age band specifically for married employees.

---

## Purpose of the Project
This project demonstrates fundamental SQL skills for HR analytics, including grouping, aggregation, filtering, and calculating rates.  
It helps understand organizational patterns such as attrition, satisfaction, and demographic structure.

---

## Technologies Used
- MySQL  
- SQL queries for data exploration and analysis

---

## How to Use
1. Import or load the HR dataset into your MySQL database.  
2. Run the provided queries in any MySQL client (MySQL Workbench, phpMyAdmin, command line, etc.).  
3. Review the output to interpret HR trends and insights.


