# Movies-ETL (Extract, Transform, Load)

The purpose of this challenge was to use the ETL (Extract, Transform, Load) method to clean up messy datasets, and create and save them into an SQL database.  ETL is an important concept to understand, because raw data exists all over, and if one is trying to analyze data that needs to tell a certain story, it makes sense to want to have data that can help tell that story accurately. In ETL, extract refers to reading the data, and extracting that data from multiple sources. Transform involves cleaning and structuring the data in a form that makes it easy to analyze in a meaningful way. Examples of transformation include, parsing and sorting data, summarizing and/or removing duplicate values, or merging and filtering datasets. The final step, load, is where you would write the data into a database for storage, or into a data target, i.e. relational or non-relational databases. For this challenge, a relational database was used, or PostgreSQL, because most databases use SQL-like interfaces, which would make it easier to share the data to anyone, even if they don't use SQL. 

## Resources

* PostgreSQL 13, SQLalchemy
* pgAdmin4 v6.11
* Anaconda (Jupyter Notebook, Pandas, Numpy, JSON)
* files: 
** Kaggle Data: ratings.csv, movies_metadata.csv 
** Wikipedia Data: wikipedia-movies.json


![ETL_image](https://user-images.githubusercontent.com/104864579/183221311-32e1f2a0-a081-427d-8514-02ff22789167.png)
