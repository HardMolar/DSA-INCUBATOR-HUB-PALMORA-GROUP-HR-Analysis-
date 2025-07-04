# PALMORA GROUP HR ANALYSIS- GENDER PAY GAP.

## 📌Case Study Overview
Palmora Group Manufacturing Company is a big manufacturing hub in Nigeria faced with allegations of gender inequality across its three operating regions. Media criticism and internal leadership concern have prompted an urgent HR data review to identify, assess, and recommend actions for equity, especially regarding pay gaps and performance-based bonus allocation.
As the HR Analytics Consultant, I’ve been tasked with performing a comprehensive analysis to uncover critical gender-based insights and salary disparities within departments and regions.

## 🎯Objectives
  * Analyze gender distribution by department and region
  * Identify disparities in performance ratings based on gender
  * Evaluate the company’s salary structure for gender pay gaps
  * Assess compliance with salary legislation (minimum of $90,000)
  * Visualize salary band distributions by $10,000 ranges
  * Allocate bonuses based on performance ratings
  * Provide total payout insights by region and overall
    
## 🗃️ Data Sources
  * CSV file of the companies data which include employee details: Names, Gender, Departments, Location and Performance rating.
  * Excel file that contains departments and general ratinngs of each department, which is to be used to calculate bonus for individual staffs based on work rating.

## 🧰Tools and Technology
  * Microsoft Power BI: For data exploriation
  * DAX: Bonus Calculatins, Conditional logic

# 🧬Project Structure

## 🚧Data Exploratory Analysis
### 🧹Data Cleaning
Before analysis, the following data preparation steps were required:
  * Missing Gender:Assign a generic gender status for employees who did not disclose their gender.
  * Missing Salary:Exclude employees with no salary (likely no longer with the company).
  * Missing Department:Remove employees tagged with "NULL" departments.

## 📌Case Scenario
  * Determine the gender distribution by region and department
  * Show insights based on gender.
  * Analyse the company's salary structure so as to identify the salary pay.   gap as regards departments and region, which management should focus on.
  * Minimum salary compliance (>=90,000).
    ** Show pay distribution table of employees grouped by a band of $10,000.
    ** Visualization of the salary band by region.
  * Bonus amount to be paid to individual employee.
  * Total amount(Salary+Bonus) to be paid to individual employee.
  * Total amount to be paid per region and worldwide

## 🧠Insights Generated
1. Gender Distribution by region and department
Visualized by department and region using bar (stacked column chat) for gender distribution by department and donut charts for overall gender distribution by region.

  **Gender distribution across all region**
  Overall Staffs: 946
  Female: 441
  Male: 465
  Neutral: 40
  
  **Staff distribution across all region**
  
  Lagos: 250(26.43%)
  Abuja: 335(35.41%)
  Kaduna: 361(38.16%)
  
  **Gender distribution across all departments**
    
    | Department                  | Neutral | Male   | Female  |
    |-----------------------------|---------|--------|---------|
    | Product Management          | 1       | 47     | 41      |
    | Legal                       | 5       | 49     | 34      |
    | Human Resource              | 3       | 38     | 41      |
    | Services                    | 3       | 37     | 42      |
    | Business Development        | 3       | 37     | 41      |
    | Support                     | 4       | 42     | 35      |
    | Engineering                 | 6       | 36     | 38      |
    | Sales                       | 4       | 40     | 36      | 
    | Training                    | 3       | 38     | 36      |
    | Research and Develpment     | 5       | 31     | 38      |
    | Accounting                  | 2       | 37     | 28      |
    | Marketing                   | 1       | 33     | 31      |
    
2.	Ratings based on Gender
    * Clustered chattered chat shows performance trends by gender and Lime chat to show rating comparison by gender

3.	Salary Structure Analysis across all departments and region
	  * Detected gender pay gaps across certain departments/regions
    * Highlighted departments and regions for leadership focus

4.	Minimum Salary Compliance

○	Analyzed employees earning below the $90,000 threshold

○	Generated compliance statistics and flagged issues

4b. Salary Bands Distribution across all region

○	Salary grouped in $10,000 bands (e.g., $10k–$20k, $20k–$30k)

○	Visualized by gender and region for comparative analysis

5.	Bonus Allocation

○	Calculated bonus per employee based on performance criteria

○	Computed:

■	Bonus amount per employee

■	Total salary + bonus

■	Regional and company-wide bonus payout totals
![image](https://github.com/user-attachments/assets/2677e5a7-bd9c-4195-bfbe-b856c2e9bb42)

  



