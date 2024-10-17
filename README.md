This ETL project aims to integrate a sales dataset from Kaggle into a MySQL database via Jupyter Notebook. The project involves several steps, from cloning the dataset to cleaning it in Python, and finally, loading it into MySQL for querying and analysis. Here's an overview of the key steps involved in the process:

- Extract: Cloning the Dataset from Kaggle
The first step is to extract the data by cloning the required dataset from Kaggle. Kaggle provides a rich repository of datasets, and for this project, we are working with a sales dataset containing columns like order_id, order_date, ship_mode, segment, product_id, sale_price, profit, and more.

- Transform: Cleaning the Data in Python
Once the dataset is downloaded, the next step is to clean and prepare the data using Python. Data from external sources often contains missing values, inconsistencies, or erroneous entries that need to be addressed before it can be loaded into a database.
Eg: Handling missing balues, Data type conversion & Data validation

- Load: Connecting to MySQL and Importing Data
After the data is cleaned, it is ready to be loaded into the MySQL database. This involves setting up a MySQL database, creating the necessary table, and inserting the cleaned data.
Connect to MySQL: Use mysql-connector-python to establish a connection between Python and MySQL.

- Querying the Data in MySQL
With the data successfully loaded into MySQL, you can now run SQL queries to analyze and retrieve insights. This could involve running aggregate functions, calculating sales performance metrics, or filtering data based on certain criteria (e.g., sales by region or product category).

- This ETL project demonstrates the full data pipeline: Extracting data from Kaggle, Transforming it using Python for data cleaning and preparation, and Loading it into MySQL for analysis. This allows you to run SQL queries and derive business insights from the data efficiently. The project showcases how powerful open data sources like Kaggle can be integrated with industry-standard databases for advanced analytics.
