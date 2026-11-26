# Healthcare-Data-Analysis-and-Insights
1. Problem Statement

The objective of this project is to analyze healthcare data using Microsoft Excel to understand patient health conditions, medical history, and healthcare expenses.

The project involves combining multiple datasets, performing data preprocessing, exploring relationships between different health indicators, and visualizing insights through charts and an interactive dashboard.

The analysis focuses on understanding:

Cancer history among smokers and non-smokers.

Major surgeries and HbA1C levels based on transplant history.

Healthcare charges across different weight and diabetes statuses.

Average healthcare charges across hospital tiers and states.

Relationships between age, BMI, HbA1C, and healthcare charges.

2. Dataset Description

The dataset contains healthcare-related information about patients, including personal details, medical examinations, hospitalization information, and healthcare expenses.

The original data was provided in three separate tables:

Customer Details: Contains customer identification and personal information.

Medical Examinations: Contains medical indicators such as BMI, HbA1C, heart issues, transplant history, cancer history, major surgeries, and smoking status.

Hospitalization Details: Contains hospitalization-related information such as healthcare charges, hospital tier, city tier, and state ID.

The tables were combined using Customer ID as the common key.

The final consolidated dataset contains the following columns:

Customer ID, First Name, BMI, HBA1C, Heart Issues, Any Transplants, Cancer history, NumberOfMajorSurgeries, smoker, Weight Status, Diabetes Status, Date of Birth, charges, Hospital tier, City tier, State ID, and Age.

3. Data Preprocessing

The following data preparation steps were performed:

Created a new worksheet named Healthcare.

Combined the three original tables into a single dataset.

Used the VLOOKUP function to retrieve data based on Customer ID.

Retained only the required columns for analysis.

Calculated the age of each patient using the Date of Birth.

Created the Weight Status and Diabetes Status fields based on the assignment requirements.

Prepared the consolidated dataset for PivotTable analysis and visualization.

4. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed using PivotTables, PivotCharts, and Scatter Charts.

A. Cancer History Analysis

Analyzed the distribution of cancer history among smokers and non-smokers.

Visualized the comparison using Donut Charts.

B. Transplant and Surgery Analysis

Compared the total number of major surgeries between patients with and without a transplant history.

Compared average HbA1C levels based on transplant history.

Used Donut and Column Charts for visualization.

C. Healthcare Charges Analysis

Analyzed average healthcare charges across different Weight Status and Diabetes Status categories.

Compared average healthcare charges for different hospital tiers across states.

Used Clustered Column and Bar Charts.

D. Correlation Analysis

Explored the relationship between Age and BMI.

Explored the relationship between Age and HbA1C.

Analyzed the relationship between Age and healthcare charges.

Used Scatter Charts with trendlines to visualize the relationships.

E. Dashboard Creation

Created an interactive Excel dashboard to consolidate the key visualizations.

Added slicers for Weight Status and Diabetes Status.

Connected the slicers to the relevant PivotTables and PivotCharts to support interactive filtering.

Tools and Technologies

Microsoft Excel (Excel Web)

VLOOKUP

PivotTables

PivotCharts

Donut Charts

Column and Bar Charts

Scatter Charts

Slicers

Dashboard Design

Learning Outcome

This project helped me gain practical experience in data consolidation, data preprocessing, exploratory data analysis, chart creation, and interactive dashboard development using Excel.

It was a valuable step in my learning journey as an aspiring Data Analyst.
