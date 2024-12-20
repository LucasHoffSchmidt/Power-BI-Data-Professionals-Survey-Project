# Power BI Data Professionals Survey Project
In this project we used Power BI to analyse the survey answers of data professionals, to discover key insights about the field of data analytics. 

## Tools and technologies
- **Power BI**: Data cleaning, data exploration and creation of final dashboard

## Project Objectives
- Identify patterns amongst data professionals
- Discover key insights about the field of data analytics

## Data Sources
- [Data Professionals Survey Dataset](data_professionals_survey_dataset.xlsx)

## Analysis steps
- **Data Cleaning in Power Query Editor**:
  - Changed date format from MM/DD/YYYY to DD/MM/YYYY by changing the format to text and then back to date using the USA standard
  - Removed empty columns
  - Consolidated all "Other" responses into a single category using divide column by delimiter
  - Made an average yearly salary by duplicating the salary, using divide column by delimiter, custom column and changed format to decimal
- **Data Exploration**:
  - Made the headline "Data Professionals Survey Breakdown" with a blue background
  - Made a card with the number of survey takers
  - Made a card with the average age of survey takers
  - Made a stacked bar chart with the survey takers title and average salary
  - Made a stacked column chart with the survey takers favorite programming language and number of survey takers 
  - Made a treemap with the survey takers country
  - Made a gauge showing the survey takers average happiness with their work/life balance
  - Made a gauge showing the survey takers average happiness with their salary
  - Made a donut chart showing how difficult it was for survey takers to break into data
  - Combined visuals into a dashboard
  - Made text for visuals concise
  - Updated the theme and colors to make the dashboard more visually appealing

## Key findings
- The average data professional is not happy with their salary and work/life balance
- Data scientists make significantly more than other data positions
- Python is by far the most favored programming language

## Visualizations
**Data Professionals Survey Breakdown**
![Data Professionals Survey Breakdown](data_professionals_survey_breakdown.png)

## Conclusion
Data professionals believe they work too much with too little pay. 
Data scientist is a position worth striving for and python is enjoyed by most data professionals.
