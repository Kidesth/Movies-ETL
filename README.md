# Movies-ETL
## Overview

The purpose of this project utilizing python and SQL. To create a refactorable and Intuitive ETL pipeline follows the ETL process: extract, transform the different datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database. This process helps to organize and get a cleaned report from a large set of data.

## Resources
 Python 3.10.5, Jupyterlab 6.4.8
 PostgresSQL, PgAdmin 4
 Movie Data sourced from IMDB Wikipedia and Kaggle, and refractable and Intuitive ETL pipeline. 


## steps to EXTRACT - TRANSFORM - LOAD

 primary steps screenshot.

 #### - Extract:
 This process includes Retrieving and reading the dataset from different formats 
(Json.csv) using python.
![Extracting the data](https://user-images.githubusercontent.com/107454933/185731191-afe44370-d0da-460e-ab62-67178478b305.png)


  #### - Transform:
  cleaning the data assessing the missing values and any corrupt data formatting.
  Transforming: filter the data and classified the datatypes redefined and changed for better interpretation and merge different data.

  ![transform data](https://user-images.githubusercontent.com/107454933/185730995-a40d853c-c760-4669-bc75-49d843fb4b31.png)

 #### - Load 

  These steps connect to the database server from the python environment to load the data to  SQL    PgAdmin into new created database schema /table.

 ![loading to PgAdmin](https://user-images.githubusercontent.com/107454933/185731170-5c095c9a-70d9-4e1b-812b-b0c0dea36f76.png)




