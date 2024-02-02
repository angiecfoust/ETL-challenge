# ETL-challenge
Project 2- ETL

## Project overview
The goal of this project was to practice ETL (extract, transform and load) using python, pandas and postgres. We started with multiple crowdfunding data sources (in excel form), cleaned and sorted said data and stored it into a postgres database. 

## Deliverables
	Csv files
- Campaign.csv
- Category.csv
- Contacts.csv
- subcategory.csv
	Postgres schema

## Files
### Resources folder
- **Contents:** All the csv and excel files necessary for creating pandas dataframes in the jupyter notebook file and import data into the postgres database

### ELT_Mini_Project_CSimmons_AFoust.ipynb
- **Overview:** The jupyter notebook file containing all the ‘extract and transform’ steps of the project (creating, cleaning and sorting the dataframes)
- **Transformation techniques used:** altering data-types, splitting text/ strings, changing to date-time format, used unique function to inspect the data, dictionary conversion to dataframe, renaming/ reordering columns, merging dataframes
- **more in depth steps/ methodology are listed within each notebook cell**

### crowdfunding_ERD.png 
- **Overview/methodology:** Using the column names of the csv files created, we created a relationship diagram and identified both primary and foreign keys.

### crowdfundingDB_schema.sql
- **Overview/methodology:** Obtained from the quickDBD export file, this schema was used to create the tables within the postgres database.

### Csv_import_verification.png
- **Overview:** A screenshot from the processes section in postgres, verifying that each csv has been imported correctly into their corresponding tables


### Sql_query_verification.sql
- **Overview/methodology:** After creating the running the schema created in quickDBD, we ran multiple ‘SELECT *’ queries for each table, verifying that each table had been created properly

## Resources
dropping first row of data in pandas: https://sparkbyexamples.com/pandas/pandas-drop-first-row-of-dataframe/#:~:text=Use%20DataFrame.tail()%20Method%20to%20Drop%20First%20Row,the%20first%20row%20of%20DataFrame.



