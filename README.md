# New York City Shooting and Arrest Data Warehouse 
- author(s): Jiaojiao Li, Jiayang Li, Kelvin Roman, L'Oniele Salim
- date created: 11/24/2022
- class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
1. Data Integration - Python (Jupyter Notebook)
2. Data Warehousing - Google BigQuery
3. Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for project:
Over the pandemic, there was a spike in crime and shooting news all over New York City. Our group is very interested in discovering the shooting and arrest rates in New York City to compare and contrast the results between each borough over periods of time. Furthermore, our group is also curious to see if any of us or someone we know lives in any of these areas and whether the problem is getting better or worse.

Description of the issues or opportunities the project will address:
As a densely populated city, where are New York City’s most dangerous neighborhoods? How can New York City Officials make informed decisions to allocate resources and increase attention or public surveillance for the public welfare? Are there specific time periods with the highest or lowest activities? What are the demographics of perpetrators? How fatal are these incidents?

To answer these questions, the New York City Shooting and Arrest Data Warehouse will combine census, dates, location, victim death rates to uncover insights regarding New York City shootings and arrests. 


Project Business or Organization Value:
Improving dangerous neighborhoods can improve the quality of life and living standards throughout New York City. Socioeconomic status, which consists of income, education levels, and employment, have a negative correlation to crime rate. We predict a decrease in crime rate will lead to an increase in socioeconomic status. These improvements will encourage gentrification and raise the safety and wellness of local residents. 

NYPD would be able to focus resources and manpower on specific hotspots, i.e. increasing patrols, increasing public awareness through news coverage to bring attention to crime hotspots, installing more CCTV to monitor streets and ensuring that immediate action can be taken whenever an incident occurs. 


Data Sources:
NYPD Shooting Incident Data
NYPD Arrest Data

### Business Requirements Definition

1. List of Data Warehouse KPI's:
2. Shooting Occurrences by Location
3. Arrests Occurrences by Location
4. Shooting Occurrences by Month
5. Shooting Occurrences by Day
6. Arrest Occurrences by Month
7. Arrest Occurrences by Day
8. Crime fatality: Number of death from shooting per borough

### Dimensional Model

This project's Dimensional Model consists of 2 Facts and 5 Dimensions

This project's Kimball Bus Matrix:

![Alt text](Kimball_Bus_Matrix.png)

This project's dimensional model: Multi Fact Star Model:

![Alt text](Multi_Fact_Star_Model.png)

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Geography Map - We will be using a Geography Map for Shooting Occurrences by Location and Arrests Occurrences by Location, because it can clearly display the geographic distribution of data by using color or shading. We will use color to show the count of occurrences in each borough. The color will range from light to dark with light depicting a lower rate than dark which will represent a higher value.

2. Line Graph - As for Shooting Occurrences by Month and Arrests Occurrences by Month, we think a line chart will display this data the best, because it was time-series analysis. We will have the months listed along the x - axis and we plan to show both arrests and shooting data within the same chart and have a legend to help distinguish the two.

3. Stacked Bar Chart - Shooting Occurrences by Day and Arrests Occurrences by Day will be demonstrated using a stacked bar chart. We believe that this method would clearly show a comparison between the highest activities amongst the different boroughs effectively by day. 

4. Bubble Chart - As for the final KPI which will show fatality resulting from shootings in each borough, we will be using a bubble chart as a comparative analysis so the users can easily see the scale of which boroughs have the largest number of deaths from shootings and which have the smallest.


BI Application Wireframe design:

Shooting and Arrest Occurrences Dashboard Wireframe:

![Alt text](Shooting_and_Arrest_Occurrences_Dashboard_Wireframe.png)

Death from Shootings Dashboard Wireframe:

![Alt text](Death_from_Shootings_Dashboard_Wireframe.png)

Shooting and Arrest Occurrences Dashboard Wireframe

![Alt text](Dashboard_Arrest.png)
![Alt text](Dashboard_Shooting.png)

### Deployment

The project was deployed on Tableau Public: (link here)
https://public.tableau.com/app/profile/jiaojiao.li/viz/Milestone4_Group13_16691797247710/Story1
