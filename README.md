# 🐍 Python Fundamentals – Capstone Project

## 📌 Project Overview
This capstone project demonstrates the application of **Python fundamentals** using **NumPy** and **Pandas** to solve real-world data manipulation and analysis problems. The project focuses on data cleaning, transformation, joining datasets, and applying business logic using Python.

---

## 🎯 Objectives
- Work with multiple datasets using Pandas DataFrames
- Perform data cleaning and preprocessing
- Apply conditional logic and loops
- Merge and transform datasets
- Generate insights from structured data

---

## 📂 Dataset Description

### Employee Data
- ID  
- Name  
- Gender  
- City  
- Age  

### Seniority Level Data
- ID  
- Designation Level  

### Project Data
- ID  
- Project Name  
- Project Cost  
- Project Status  

---

## 📋 Tasks Performed

### Task 1: DataFrame Creation
- Created three DataFrames from given tables  
- Saved each DataFrame as a `.csv` file  

### Task 2: Handle Missing Values
- Identified missing values in **Project Cost**  
- Replaced missing values using **running average** with a `for` loop  

### Task 3: Name Column Split
- Split `Name` into **First Name** and **Last Name**  
- Removed original `Name` column  

### Task 4: DataFrame Merge
- Joined all three DataFrames into a single DataFrame named **Final**

### Task 5: Bonus Calculation
- Added a **Bonus** column  
- Assigned **5% bonus** based on project cost for completed projects  

### Task 6: Designation Update
- Demoted designation level by 1 for failed projects  
- Removed employees with designation level greater than 4  

### Task 7: Title Assignment
- Added **Mr. / Mrs.** prefix to first names  
- Dropped the gender column  

### Task 8: Promotion Logic
- Promoted designation level by 1 for employees aged above 29  

### Task 9: Total Project Cost
- Calculated total project cost per employee  
- Created a new DataFrame **TotalProjCost** with:
  - ID  
  - First Name  
  - Total Project Cost  

### Task 10: City-based Filtering
- Displayed employee records whose city name contains the letter **"o"**

---

## 🛠️ Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy

---


## ✅ Key Learnings
- Hands-on experience with Pandas DataFrames
- Data cleaning and transformation techniques
- Applying business rules using Python logic
- Combining multiple datasets for analysis
- Writing readable and well-commented Python code

---

⭐ *If you find this project helpful, feel free to star the repository!*

