# Crowdfunding_ETL

## Summary

This was a collaborative project to build an ETL (Extract, Transform, Load) pipeline using Python, Pandas, and Python dictionary method to extract and tranform the data.  Four CSV files were then created, and were used to create an Entity Relationship Diagram (ERD) and table schema.  The CSV files were then loaded into a relational database using PostgreSQL.


## Technology Used

* Python
* Pandas
* PostgreSQL
* Jupyter Notebook
* Excel


## Features

### Create the Category and Subcategory DataFrames

We extracted and transformed the 'crowdfunding.xlsx' data and loaded them into the respective 'category' and 'subcategory' DataFrames.  
* This was done by creating a column of unique categories and subcategories and numbered it sequentially.
- The original column 'category & sub-category' was split into category and subcategory columns.
- The unique categories and subcategories were extracted and counted, then entered sequentially from 'cat1-n', and 'subcat1-n'.
- The DataFrames were exported to a CSV file.


### Create the Campaign DataFrame

Extracted and transformed the 'crowdfunding.xlsx' data to create a 'campaign' DataFrame.
* Columns were renamed appropriately and given correct data types.
* Dates were converted datetime format(YYYY-MM-DD).
* The 'category', 'subcategory' and 'campaign' DataFrames were merged into one DataFrame, 'campaign_merged_df'.
* Unwanted columns were dropped from this DataFrame.
* DataFrame was then exported to a CSV file.




