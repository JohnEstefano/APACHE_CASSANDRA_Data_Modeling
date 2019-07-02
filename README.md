# Project: Data Modeling with Cassandra
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They wanted a data engineer to create an Apache Cassandra database which could create queries on song play data to answer the questions, and brought me on the project. My role was to create a database for this analysis.

# Project Overview
In this project, I modeled my data by creating tables in Apache Cassandra to run queries.

# Project Steps
Below are steps I completed.

# NOTE: CODE LOCATED IN A JUPYTER NOTEBOOK CALLED 'Project_Notebook.ipynb'

## Modeling the Apache Cassandra database
- Tables where designed to answer the queries outlined in the project template.
- Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements were written.
- CREATE statements for each of the tables was written to address each question.
- The data was loaded with INSERT statements for each of the tables.
- IF NOT EXISTS clauses were included in the CREATE statements to create tables only if the tables do not already exist.
- DROP TABLE statements was also written for each table, for the purposes of reseting the database and to test the ETL pipeline
- Database was tested by running the proper select statements with the correct WHERE clauses
