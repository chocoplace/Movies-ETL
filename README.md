# **Movies-ETL**

## Overview of the analysis: 

The goal is to help the Amazing_Prime_Video team develop an algorithm to help predict popular pictures for future campaigns using the ETL process.The analysis will be used in a hackathon event where participants will have access to clean datasets to predict the trend on pictures. 

The analysis follows the ETL process: Extract the Wikipedia and Kaggle data from their respective files, Transform the datasets by cleaning them up and joining them together, and Load the cleaned dataset into a SQL database.

### Resources

Software: PostgreSQL, pgAdmin and Jupyter Notebook. 

Data Source: Wikipedia data, Kaggle metadata, and the MovieLens rating data. Fomd the data here: [Data](https://github.com/chocoplace/Movies-ETL/tree/main/Resources) 

### Results:

The results of this project is a robust and clean DataFrames with good quality data ready to be used in the hackathon. For all the steps on this analysis we had to utilize our knowledge on Python, Pandas, the ETL process and code refactoring.  

 - Deliverable 1. Write an ETL Function to Read Three Data Files and create three separate DataFrames. This first step was the baseline for the other deliverables, which can be reused for future projects. Find the code here: [Deliverable 1.](https://github.com/chocoplace/Movies-ETL/blob/main/ETL_function_test.ipynb)
 
 - Deliverable 2.  Extract and Transform the Wikipedia Data to merge it with the Kaggle metadata. The focus was on identifying errors and duplicates for cleaning. Find the code here: [Deliverable 2.](https://github.com/chocoplace/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb)
 
 - Deliverable 3. Extract and Transform the Kaggle Data and MovieLens rating data. The focus was to convert the transformed data into separate DataFrames. Find the code here: [Deliverable 3.](https://github.com/chocoplace/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb)
 
 - Deliverable 4.Create the Movie Database. Add the DataFrame and MovieLens rating CSV data to a SQL database. Finally, we refactored the code to create the last part of the analysis. Find the code here: [Deliverable 4.](https://github.com/chocoplace/Movies-ETL/blob/main/ETL_create_database.ipynb)

