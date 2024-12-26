# Drug-Abuse:Exploring-the-Nexus-between-Substance-Abuse-and-Diverse-Criminal-Activities

## Project Overview:
This project involves a comprehensive analysis to explore the complex relationship between substance abuse and various criminal activities.
Utilizing Data Analytics, I applied both Descriptive and Diagnostic Analytics methodologies to uncover patterns and correlations within real-world healthcare data.
This endeavor not only provided invaluable insights into the impact of substance abuse on criminal behavior but also enhanced my analytical skills and deepened my
understanding of critical social issues.

## Aim of the Project
A. Data Integration and validation: Establish robust data integration processes to compile and validate diverse datasets related to substance abuse and criminal activities,
ensuring data consistency and accuracy.
 
B. Descriptive Analysis: Perform descriptive data analysis to summarize key statistics and metrics related to drug-related crimes.
 
C. Frequencies, location trends, and drug types involved.
 
D. Trend Identification: Identify and document temporal trends in drug-related crimes.
 
E. Location Analysis: Conduct location-based analysis to pinpoint geographical hotspots of drug-related criminal activities, supporting focused law enforcement efforts.
 
F. Data Visualization: Develop clear and intuitive data visualizations, such a charts, graphs, using Excel to present analytical findings for easy interpretation by stakeholders.

# Tools: 
- Excel: for data cleaning and manipulation 
- Power Bi: Visualization
  
# Steps:The steps used in carrying out this analysis is as follows

## Data Importation:
— Imported the dataset by using the Get Data icon in Excel to bring in the xlsx file.

## Data Type Verification:
— Brought the data into Excel Power Query and cross-checked each column to ensure the correct data types for smooth analysis.

## Duplicate Removal:
— Removed duplicates from the dataset to ensure data accuracy and reliability.

## Text to Column Conversion:
— Separated columns with comma-separated values using the Text to Column feature to ensure proper data segmentation.

## Handling Missing Values:
— Replaced NA columns in the dataset to maintain data integrity and accuracy.

## Creating Age Ranges:
— Added a new column to divide “Abuser Age” into age ranges using the formula:
```excel
=IF([@[Abuser_Age]]<=27,”18–25 Adolescent”,IF([@[Abuser_Age]]<=38,”26–38 Middle Age”,IF([@[Abuser_Age]]<=59,”39–59 Senior”,”60 and Above Old”)))
```
— This categorization is important for understanding age-related trends in substance abuse and crime.

## Extracting Crime Day:
— Added a new column to extract the crime day from the crime date using the formula:
```excel
=TEXT([@[Crime_DateTime]],”dddd”)
```
— This helps identify patterns in criminal activity based on days of the week.

## Visualization:
The following visuals were created using clustered column chart, bar chart, line chart and pie chart.
- chart 1: Shows the incident of drug abuse by gender
- chart 2: Drug type consumed by the age range
- chart 3: Proportionate distribution abusers by gender
- chart 4: The prevalence of crime by day
- chart 5: Prevalence of crime type
- chart 6: Crime type by location
- chart 7: Crime by month
- chart 8: Crime by age range
- chart 9: Economic status of the offenders

  # Result:
  


