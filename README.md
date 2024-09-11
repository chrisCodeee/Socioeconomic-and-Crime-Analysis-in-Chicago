# Socioeconomic and Crime Analysis in Chicago
**Project Overview**

In this project, I conducted an in-depth analysis of socioeconomic factors and crime data in Chicago, with the goal of understanding the impacts on educational outcomes and community well-being. This analysis was conducted using real-world datasets provided by the Chicago Data Portal, focusing on census data, crime statistics, and public school performance metrics.

**About the Project**
Imagine you have been hired by a non-profit organization dedicated to improving educational outcomes for children and youth in Chicago. Your task is to analyze various datasets related to census data, crime, and school performance for different neighborhoods and districts within the city. The objective is to identify factors that affect school enrollment, safety, health, and environmental ratings, providing insights that can drive effective interventions and policy changes.

**Key Questions Answered**

Throughout the project, I addressed the following critical questions:

**Total Number of Crimes Recorded:**
- Analyzed the CRIME table to determine the total number of recorded crimes.
**Community Areas with Low Per Capita Income:**
- Identified community areas where the per capita income is less than $11,000, highlighting economically disadvantaged neighborhoods.
**Crimes Involving Minors:**
- Listed all case numbers for crimes involving minors (excluding cases where children are not considered minors for crime analysis purposes).
**Kidnapping Crimes Involving Children:**
- Compiled a list of all kidnapping incidents involving children, focusing on this serious crime category.
**Crimes Recorded at Schools:**
- Investigated the types of crimes reported at schools to understand the safety challenges faced by students and staff.
**Average Safety Score for Each Type of School:**
- Calculated the average safety score for different types of schools to assess their security environment.
**Community Areas with Highest Poverty Rates:**
- Identified the top five community areas with the highest percentage of households below the poverty line.
**Most Crime-Prone Community Area:**
- Determined which community area has the highest crime rate, providing insights into areas requiring focused law enforcement efforts.
**Community Area with Highest Hardship Index:**
- Used a sub-query to find the community area with the highest hardship index, indicating severe socioeconomic challenges.
**Community Area with Most Crimes:**
- Used a sub-query to determine the community area with the highest number of recorded crimes, highlighting the areas most affected by criminal activities.

**Data Sources**
The analysis was based on the following datasets, all of which are publicly available on the City of Chicago's Data Portal:

**Socioeconomic Indicators in Chicago:**

This dataset contains six key socioeconomic indicators of public health significance, along with a “hardship index,” for each Chicago community area for the years 2008 – 2012.
Dataset Link: https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2 

**Chicago Public Schools:**
This dataset provides school-level performance data used to create Chicago Public Schools (CPS) Report Cards for the 2011-2012 school year.
Dataset Link: https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t 

**Chicago Crime Data:**
This dataset reflects reported incidents of crime (excluding murders) that occurred in Chicago from 2001 to the present, minus the most recent seven days.
Dataset Link: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2 

**Key Findings**

- Certain community areas exhibit significantly lower per capita income and higher poverty rates, indicating areas in need of targeted economic interventions.
- Specific types of crimes are more prevalent in school environments, necessitating improved security measures.
- Community areas with higher hardship indices and crime rates require focused social services and law enforcement efforts to improve living conditions and safety.

**Technology Stack**
- SQL: For querying and analyzing the data.
- Python: for analysis.
- Jupyter Notebook: For documentation and interactive analysis.
