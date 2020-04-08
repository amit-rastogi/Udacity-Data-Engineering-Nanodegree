Data Engineering Capstone Project

The project builds a data warehouse in AWS Redshift from the Movielens dataset. This data warehouse could be used by the data analysts and machine learning engineers to perform data analysis using OLAP cubes or build a movie recommendation system.

The Movielens dataset would be written to AWS S3 in parquet format which would be ingested by the ETL step to load the parquet files to staging tables in Redshift. The ETL step would then use the staging tables to populate the fact and dimensional tables of the star schema in Redshift.
