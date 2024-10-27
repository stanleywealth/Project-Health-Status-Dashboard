# Projects Health Status Dashboard for EIFFAGE Construction

### Project Overview

The goal of this dashboard is to show the status or health of the various construction projects awarded to EIFFAGE Construction. The primary purpose is to have a dashboard that shows at a glace the stages of all the projects handle by the company, whether they are ongoing, in need of attention, or completed. It should also show the budget and expenses of the projects at a glance. It will be nice if the dashboard can show the locations of these projects awarded to the conpany.

### Final Dashboard Image

![Project Heealth Status Dashboard - full image](https://github.com/user-attachments/assets/efc1d2bb-c6e5-43f3-bb0a-1be9fc6c9e2d)



### Data Source
Company data

### Tools used for the project

Power Query and PowerBI


### Data Cleaning/Preparation

The data cleaning was done with Power Query in Power BI. The data types was converted to the appropriate type, and date column was formatted correctly using the (dd mmm yy) format.


### Visualization

After preparing the data in Power Query, it was loaded into Power BI for visualiation. Below show each metric and chart in the dashboard with explanation.

1. Cards that shows KPIs for Number of Projects, Budget, Expenses, and Average Project duration where created for easy view.
![Project Heealth Status Dashboard KPIs](https://github.com/user-attachments/assets/29d15059-4346-41a2-a455-5ffd665d15e9)

2. A map visual is used to show the locations of the various projects handled by the conpany in Nigeria. The map also shows the number of projects that are on track, that are completed, and the projects that need attention when filter using the selection horizontal bar with three different colors at the top of the KPI.
![Project Heealth Status Dashboard - location and priority](https://github.com/user-attachments/assets/46edf535-28da-49f5-b520-a300743fd769)

3. This charts shows the number of projects by status, Project details (which shows project name, start date, end date, budject, and percentage completion), Number of project by project type and priority. 
![Project Heealth Status Dashboard - Status and details](https://github.com/user-attachments/assets/9a180c1d-f46d-465f-b6a3-10f51b94bd4e)

4. This chart that shows budget and expense by project manager. This shows the project manager with the highest budget and expenses.
![Project Heealth Status Dashboard - budget and expenses by project managers](https://github.com/user-attachments/assets/1675124b-d76b-45e9-9663-64661d48a9a3)


### Observations/Findings

- According to the chart analysis, 35 projects are on track with the set end date and with a budget of $606k aad expenses of $477k. They all have average completion of 196 days. These projects are spread across 5 different locations.
- However, it also shows that a total of 19 projects needs attention, and all these projects are all in one location.


### Recommendations

From this charts and dashboard I dicovered that the project managers of all the projects that needs attention need to be contacted to acertain what is going on with these projects and what needs to be done. Getting this information will help the company meet the set end dates or deadline for the projects and also contact the appropriate authority if needed for a shift in the end date due to current situations.


### Limitations

This dashboard relies on data supplied by project managers at various locations of the project sites around the country.





