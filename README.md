# Database-Management-Systems

Project:
Restructure a flattened and/or denormalized dataset so it can be loaded into a SQL or Graph database. Identify and demonstrate a form of analysis that is made easier by restructuring the data.

Dataset:
Yelp Dataset(https://www.kaggle.com/yelp-dataset/yelp-dataset)

For this project, I'll utilize a combination of Python for data preprocessing and transformation, and DBeaver for database design, management, and analysis. Python offers powerful libraries for data manipulation and preprocessing, while DBeaver provides a user-friendly interface for working with SQL databases. The primary data source is the Yelp Dataset, which contains information about businesses, users, and reviews. This dataset provides a rich source of information for analysis, including sentiment analysis, user behavior analysis, and more. I'll initially work with a flattened or denormalized version of this dataset, and the goal is to restructure it into a normalized form suitable for loading into a SQL database.

The tasks include:
1. Loading the Yelp dataset into Python.
2. Performing data cleaning and preprocessing, such as handling missing values, removing duplicates, and converting data types.
3. Normalizing the dataset by splitting it into multiple tables based on entities like businesses, users, and reviews.
4. Saving the normalized tables into CSV or JSON files for further processing and loading into the database.
5. Designing a normalized database schema that represents the entities from the Yelp dataset, including tables for businesses, users, and reviews.
6. Creating tables in DBeaver based on the defined schema, specifying primary keys, foreign keys, and constraints.
7. Loading data from the preprocessed CSV or JSON files into the respective tables in the SQL database using DBeaver's import data feature or SQL scripts.
8. Ensuring data integrity and consistency during the loading process and optimizing database performance by indexing frequently queried columns and optimizing queries.
