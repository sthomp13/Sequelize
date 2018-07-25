# Data-Storage-and-Retrieval

This project uses Station and Measurements CSV files. These files are connected with SQL Alchemy for data analysis. A flask api was designed based on my queries.

#Steps to Run the Project

The database_engineering file in Jupyter notebook will create a sqlite database called hawaii.sqlite and 2 tables will be created (measurement and station). 
These tables are populated based on the data provided in the CSV files. 
All data has been cleaned (by dropping rows that have NaNs) before loading into the tables in the data engineering file.
The climate analysis file file analyses the data, plots graphs and also uses flask to display the data from the database in JSON format. 
Flask runs locally on your machine (127.0.0.1) on port 5000. Please see the images in Flask_Images for an example of what the Flask api will look like.
