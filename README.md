# Salary_decoder
# Bangalore Tech Salary Decoder

## Overview
This project analyzes tech salary data from Bangalore companies. It helps understand how salaries vary based on role, experience, skills, and company type. The goal is to find useful patterns in the data through cleaning and analysis.

## Objective
The main goal is to study:

Salary differences across roles  
Effect of experience on salary  
Impact of skills on pay
Company-wise salary comparison  
Identifying underpaid employees  


## Tools Used
Python  
  Pandas  
  NumPy  
  Jupyter Notebook  

## Dataset
The dataset contains around 1000 employee records with details like role, experience, current CTC, previous CTC, company type, skills, education, and work mode.

---

## Data Cleaning
 Fixed column names  
 Standardized job roles and company types  
 Converted salary values into numeric format (LPA)  
 Handled missing values  
 Removed duplicate records  

## Analysis Done
 Salary comparison by role  
 Experience vs salary trend  
 Skill-based salary difference (AWS, ML, System Design, Kubernetes)  
 Company type comparison (MNC, Unicorn, etc.)  
 Detection of underpaid employees  


## Key Findings
  Product and management roles have higher salaries  
  Cloud and system design skills give better pay
  Unicorn companies generally pay more than MNCs
  Salary increases with experience but not evenly across all roles  
  Some employees are paid below the market median  



## How to Run
```bash
git clone https://github.com/your-username/salary-decoder.git
pip install pandas numpy
jupyter notebook
