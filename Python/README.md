## Understanding the Importance of Python ETL

Python is one of the modern world’s most popular & commonly leveraged programming languages, with endless applications in a variety of fields. It has won the prestigious TIOBE Programming Language of the Year 2021 award.

Python’s flexible and dynamic nature makes it ideal for Deployment, Analysis, and Maintenance tasks. Python ETL is one of the crucial skills required in Data Engineering to build Data Pipelines, develop Statistical Models, and perform a thorough analysis on them.

It has become a popular tool for executing ETL processes due to its ease of use and robust libraries for accessing databases and storage systems. Many teams use Python for ETL & Data Engineering rather than an ETL tool as it is more versatile and powerful for these tasks.

The greatest benefit of Python over other programming languages is the simplicity of use in Data Mining, Data Science, Big Data, Artificial Intelligence, and Machine Learning.

Companies around the world use Python for their data to obtain insights, manage their operations, and keep everything running smoothly.

# 2 Easy Steps to Build Python ETL Pipeline
In this part, you’ll learn the essential steps for building an ETL pipeline using Python. You’ll create a basic Data Pipeline that feeds data into a Microsoft SQL Server database from MySQL & Microsoft SQL Server Databases.

In order to set up the Python ETL script, follow the steps below:

## Step 1: Install the Required Modules
To set up the Python ETL Pipeline, you’ll need to install the following modules:

Python to MySQL Connector: mysql-connector-python (Use pip install mysql-connector-python command to install)
Python to Microsoft SQL Server Connector: pyodbc (Use pip install pyodbc command to install)

## Step 2: Set Up the ETL Directory
After installing the above packages, you need to create 4 Python files, mentioned below in your project directory:

## db_credentials.py: 
This file includes code to establish connections with all Databases.

## sql_queries.py: 
This file comprises the commonly used Database queries to extract and load data in string format.

## etl.py: 
This file possesses the necessary operations to connect to the Database and run the required queries.

## main.py: 
This is the primary file that regulates the flow and execution of the Python ETL Pipeline.
