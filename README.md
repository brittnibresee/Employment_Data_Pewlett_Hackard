## Pewlett-Hackard-Analysis
Using SQL- relational databases, QuickDBD and GitHub.
This was a research project done for a fictional company named, Pewlett Hackard.
One major tast was to research about people whom the company employed during the 1980s and 1990s.
I designed the tables to hold the data from the CSV files, imported the CSV files into a SQL database, and then answer questions about the data. Below is the breakdown.


## Data Modeling
For this project, I pulled 6 csv files. Each file contained information on Pewlett Hackard employees. Using QuickDBD I created an Entity Relationship Diagram (ERD).


## Data Engineering
Using PgAdmin, 6 tables were created for each corresponding csv file. These tables were created with the correct corresponding primary and foreign keys and also created in the proper order. Once the tables were created, each csv was imported to said table.


## Data Analysis
Using PgAdmin I analyzed the data by writing a query for parts and segments of the tables. Some tables needed to be merged together. In the end I was able to list the employees with their information and all corresponding details. Doing this I could see there are 20 employees with the first name 'Hercules'.
