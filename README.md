# Dallas-Police-Incidents

CSV file link
https://www.dallasopendata.com/Public-Safety/Police-Incidents/qv6i-rri7

Goal:
The goal of this project was to analyze a large dataset of Dallas Police incidents, which contained over 1 million rows and 86 columns. (Incident id, time, date, victim, gender, 911, etc). The goal was to gain valuable insights from the data and support data-driven decision-making.


Task:

Data profiling and Cleaning: First, I needed to profile the data to understand its characteristics and identify any potential issues. I utilized Python and a library called "ydata-profiling" to conduct data profiling. This library generates a very detailed report and it shows the total number of rows, columns, missing values, duplicates, size of dataset and data type of columns. It also shows details about each column like missing values, distinct values and memory size. This involved examining data quality, statistics, and the overall structure of the dataset. Cleaned the dataset using python. Renamed the columns according to the business requirements. Handled null, missing values, inconsistencies in the data. Date format. 
Used pandas functions like rename, is null.sum, duplicated, replace, fillna, to date time etc

Graph data model: I aimed to create an efficient graph data model for this dataset. This required meticulous data mapping and integration into a Neo4j database. The goal was to represent the relationships between different data points, such as incidents, locations, and involved parties, in a way that facilitates efficient querying and analysis. Wrote cypher script to load data from csv to neo4j database.

Data validation :  conducted thorough data validation to ensure the accuracy and integrity of the data stored in Neo4j. This involved comparing the row count in the cleaned dataset with the row count in the Neo4j node data to confirm that all the data had been successfully loaded without any data loss.

Data visualization: I leveraged Tableau to create data visualizations. These visualizations were designed to provide valuable insights and support effective decision-making based on the analyzed data.

Result:

As a result of this project, we were able to gain deep insights into the Dallas Police incidents dataset, enabling data-driven decision-making.
