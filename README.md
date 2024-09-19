# Employee-Project-Performance-Data-Analysis

## Overview
This data analysis project involves employee performance and project management using Python, Pandas, and NumPy. Tasks include data cleaning, handling missing values, merging datasets, and analyzing project outcomes. The project demonstrates key data manipulation techniques and performance evaluations.

## Project Description
Conducted a comprehensive analysis of employee and project performance using Python to evaluate employee designations, project outcomes, and task assignments. This project illustrates how data cleaning, manipulation, and analysis can drive performance insights and inform decision-making.

## About the Dataset
The dataset consists of three key tables, each providing essential data for the analysis:

- **Employee Data**: Contains employee details including ID, Name, Gender, City, and Age.
- **Seniority Level Data**: Provides information on the employee’s current designation level.
- **Project Data**: Includes project details such as cost, status (e.g., ongoing, finished, failed), and the employee responsible for the project.

## Tasks Performed
- **Task 1: DataFrame Creation and CSV Export**
  - Created three separate DataFrames from the Employee, Seniority Level, and Project tables.
  - Exported the DataFrames into CSV files for further manipulation.

- **Task 2: Handling Missing Values in Project Cost**
  - Replaced missing values in the Project Cost column using a running average computed through a for loop.

- **Task 3: Splitting Employee Names**
  - Split the Name column from the Employee table into two new columns: First Name and Last Name, and removed the original Name column.

- **Task 4: Merging DataFrames**
  - Merged the Employee, Seniority Level, and Project tables into a single DataFrame called Final to streamline data manipulation.

- **Task 5: Adding Bonus Column**
  - Created a new Bonus column for employees who completed their projects, awarding a 5% bonus based on the project cost.

- **Task 6: Adjusting Designation Levels**
  - Demoted employees whose projects failed by 1 designation level.
  - Removed any employee whose Designation Level exceeded 4 as they became ineligible to head projects.

- **Task 7: Adding Titles and Removing Gender**
  - Updated the First Name column to include "Mr." or "Mrs." based on the employee’s gender, and removed the Gender column to simplify the data.

- **Task 8: Promoting Based on Age**
  - Promoted employees over the age of 29 by increasing their Designation Level by 1.

- **Task 9: Calculating Total Project Cost**
  - Created a new DataFrame called TotalProjCost, which aggregated the total project cost for each employee.

- **Task 10: Filtering Employees by City Name**
  - Filtered and printed employee details for those whose city name contains the letter "o."

## Tools and Libraries
- **Pandas**: Used for data manipulation, cleaning, merging, and analysis.
- **NumPy**: Applied for numerical operations and conditional logic.
- **Python**: The primary language used for loops, conditions, and various other operations.
