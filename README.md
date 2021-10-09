# CF_SQL_Rockbuster
**Query-based summary of inventory and revenues of an online video rental store using PostgreSQL** <br>
_Analysis performed for learning purposes with CareerFoundry_

Rockbuster Stealth LLC is a fictive brick and mortar movie rental company with stores around the world. The management plans to use existing movie licenses to launch an online video rental service.

The goal of the project is to acquire a good understanding of the various data points. This has been achived by exploring the inventory and revenues of the stores by using **relational database management system PostgreSQL**. The findings has been communicated and visualized in Tableau and PowerPoint.

The repository contains:
1. Data dictionary
1. Entity relationship diagram
1. Selected PostgreSQL queries
1. Visualizations of queries results in Tableau
1. Presentation of insights in PowerPoint


During this project, I learned the SQL concept from the very begining. The exercises performed in **pgAdmin4** walked me through most important steps in the process of the data analysis.

First, it was important to understand the relationships that exist in the Rockbuster database and get an overview of all the tables. The **snowflake-type entity relationship diagram** was exctracted with DbVisualizer. The list of all the fact and dimension tables along with data types, keys and column descriptions were collected in the **data dictionary.**

Then, by using the basic **CRUD** commands and writing simple queries for ordering, grouping or filtering data, the first business questions were answered. In the next steps, I learned commands for data cleaning process to find inconsitencies, missing values or duplicates. Then, SQL queries were used to calculate **descrpitve statistics** for selected columns. Finally, writing queries and **subqueries** combined with **joins** between tables using their common keys, I was able to find answers for more advanced business questions. Additionally, the same questions were answered using the concept of **CTE** to learn the advantages of common table expressions over subqueries in complex problems. 

Results of the key business questions are visualized in Tableau:
[Top 10 countries by customers](https://public.tableau.com/app/profile/anna.walerys/viz/Top10countries-Task3_10forCF/Top10countriesbycustomers)
[Total payments by country](https://public.tableau.com/app/profile/anna.walerys/viz/Rockbuster_Task3_10_totalpaymentbycountry/Totalpayments)
[Top 10 cities by top customers](https://public.tableau.com/app/profile/anna.walerys/viz/Rockbuster_Task3_10_Top10citiesbycustomer/Top10Cities)
[Top 5 customers by country](https://public.tableau.com/app/profile/anna.walerys/viz/RockbusterTop5Customers_Task3_10/Top5Customers)


