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

# Result/Findings:
## 1. Drug Consumption Patterns
### General Statistics:
Total number of incidents analyzed: 20,181.
69% of offenders are male, and 31% are female.
Four drugs consumed: Cocaine, Heroin, Marijuana, and Methamphetamine.

### Drug Consumption by Gender:
- Males:
Cocaine: 3,530 (25.35% of male offenders).
Heroin: 3,475 (24.96%).
Marijuana: 3,530 (25.35%).
Methamphetamine: 3,486 (25.01%).
- Females:
Cocaine: 1,529 (24.43% of female offenders).
Heroin: 1,569 (25.07%).
Marijuana: 1,485 (23.74%).
Methamphetamine: 1,577 (25.21%).

### Drug Consumption by Age Range:

- Middle Age (26–38 years): Heroin (25.40%), Cocaine (25.07%), Marijuana (24.78%), Methamphetamine (24.75%).
- Senior Age (39–59 years): Cocaine (25.46%), Heroin (24.51%), Marijuana (24.57%), Methamphetamine (25.46%).
- Adolescents (18–25 years): Marijuana (25.37%) and Methamphetamine (25.19%) are the most consumed.
- Elderly (60+ years): Heroin consumption dominates (28.71%), followed by Cocaine (24.75%).

## 2. Crime Analysis

### Crime Patterns by Time:
Wednesday witnesses the highest number of crimes, while Thursday sees the lowest.
August experiences the highest crime rate, whereas January has the lowest.

### Types of Crimes:
Theft is the most prevalent crime, followed by Burglary, Vandalism, and Assault.

### Crime Locations:
Urban areas have the highest crime rate, followed by Downtown, Suburbs, and Rural areas.

### Economic Status of Offenders:
Low-income offenders: 10,080 (50% of total).
Middle-income offenders: 5,000 (25% of total).
High-income offenders: 5,100 (25% of total).


# Insights
## Drug-Related Patterns:

Males have higher involvement in drug-related crimes, with Cocaine and Marijuana being the most consumed drugs.
Among females, Methamphetamine has slightly higher consumption, suggesting targeted interventions are needed for specific drugs across genders.
Heroin consumption dominates among the elderly, highlighting potential vulnerabilities in this age group.

## Crime Patterns:
- Theft and burglary are primary crime drivers, likely linked to economic motives, as low-income offenders represent 50% of total offenders.
Urban areas and Downtown regions exhibit the highest crime rates, requiring focused law enforcement efforts.
Seasonal and Weekly Trends:

- Crime rates peak in August, possibly due to increased activity during the summer months.
Wednesdays being the highest crime day may relate to work schedules or social patterns.
Socioeconomic Factors:

- Low-income offenders make up the largest proportion, indicating a potential link between poverty and crime.
Middle- and high-income offenders also contribute significantly, suggesting crime prevention strategies should not exclusively target low-income areas.

# Recommendations 
## Drug Prevention Strategies:

- Focused anti-drug campaigns targeting males, particularly those consuming Cocaine and Marijuana.
Age-specific intervention programs:
- Youth and adolescents: Education programs focusing on the risks of Marijuana and Methamphetamine use.
- Elderly: Rehabilitation programs addressing Heroin addiction.
- Increased monitoring in regions with high Methamphetamine usage, particularly among females.

## Crime Deterrence Measures:

- Urban and downtown areas should receive increased police presence and surveillance, as they experience the highest crime rates.
- Theft and burglary prevention: Community engagement programs to encourage vigilance.
- Deployment of resources to high-theft areas based on urban crime heatmaps.

## Targeting Seasonal Crime Spikes:

- Prepare for a surge in criminal activities in August by allocating additional patrols and resources during this period.
- Engage in public awareness campaigns to encourage crime reporting and discourage theft and burglary during peak months.

## Socioeconomic Interventions:
- Collaborate with community organizations to provide skill-building and employment opportunities for low-income individuals to reduce crime drivers.
- Introduce rehabilitation programs for offenders from middle- and high-income backgrounds, focusing on addressing the causes of their criminal behavior.

## Data-Driven Policing:
- Use predictive analytics tools to map high-crime zones and identify patterns in drug-related offenses.
- Employ geospatial tools for targeted policing in urban and downtown areas.

## Partnerships and Rehabilitation:
- Partner with addiction treatment centers to address the link between drug consumption and crime.
- Implement age-specific rehabilitation programs tailored to address the drug types most consumed by each demographic.

# Conclusions:
The analysis reveals a strong correlation between drug consumption and crime incidents, with distinct patterns based on gender, age, socioeconomic status, and geography. 
Targeted interventions addressing these factors, along with data-driven law enforcement strategies, can help reduce crime rates and drug usage. Focus on vulnerable demographics, 
such as low-income individuals and specific age groups, will be crucial in creating effective policies.


  


