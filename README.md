# Crowdfunding_ETL

For the ETL mini project, we worked as a team of three to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After transforming the data, we created four CSV files and used the CSV file data to create an ERD and a table schema. Finally, we uploaded the CSV file data into a Postgres database.

We did this project in four parts:

1. Category DataFrame is Created

The DataFrame contains a "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories 
The DataFrame has a "category" column that contains only the category titles 
The category DataFrame is exported as category.csv 

2. Subcategory DataFrame is Created 

The DataFrame contains a "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories 
The DataFrame contains a "subcategory" column that contains only the subcategory titles 
The subcategory DataFrame is exported as category.csv 

3. Campaign DataFrame is Created 

The DataFrame has the following columns: 
"cf_id" column
"contact_id" column
"company_name" column
"description" column
"goal" column that is a float data type
"pledged" column that is a float data type
"outcome" column
"backers_count" column
"country" column
"currency" column
"launch_date" with the time formatted as "YYYY-MM-DD"
"end_date" with the time formatted as "YYYY-MM-DD"
"category_id" column that contains the unique identification numbers matching those in the "category_id" column of the category DataFrame
"subcategory_id" column that contains the unique identification numbers matching those in the "subcategory_id" column of the subcategory DataFrame
The campaign DataFrame is exported as campaign.csv

4. Contacts DataFrame is Created 

The DataFrame has the following columns: 
"contact_id" column
"first_name" column
"last_name" column
"email" column
The contacts DataFrame is exported as contacts.csv 
A Crowdfunding Database is Created 

5. A database schema labeled, crowdfunding_db_schema.sql is created
A crowdfunding_db is created using the crowdfunding_db_schema.sql file 
The database has the appropriate primary and foreign keys and relationships 
Each CSV file is imported into the appropriate table without errors 
The data from each table is displayed using a SELECT * statement 
