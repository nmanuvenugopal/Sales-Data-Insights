# Sales-Data-Insights
Gathering and Visualizing the data with helps of Power BI.

* Once Purpose (goal of the project), Stakeholders (who are involved in the project), End Result (for example, Automate the dashboard to provide the insights to help in data driven decision making), and Success criteria are defind in the AIMS grid (tool used by organization to keep track of goals and track the success/failure rate).

* IT teams (group of software engineers) are responsible for keeping tracks of sale management system. When ever a sale happens it will be registered to the database system they are keeping.

* Next comes the data analysis team and this analysis team will request the IT team for the access of their database to get the data for generating the Insights.

* If we try to establish a connection between database and PowerBI dashboard directly, we should make sure that the query which are trying to execute on the dashboard is not effecting the database. If it effect the database then its is going to effect the busniess, since all the transaction details are ultimately saved to the database. So, in order to assure the smooth business the what they will do is that they will create a DataWarehouse and map the data from Database to this Warehouse.

* There are data engineers and data analyst within the analysis team. What data engineers will do ETL (Extract the data from the database, Transform the data as needed for Power BI dashboard, and Load the data to the Data Warehouse) activities on data stored in the database. These data stored on the Data Ware house is then used by the Data Analyst to visualise it on the dashboard and generate insights.
![image](https://user-images.githubusercontent.com/99719105/219037334-523dd41c-8fe6-4daa-bb8c-c219253fba21.png)



* Ref : Power BI Project For Beginners | Sales Insights Data Analysis Project (by CodeBasics)
