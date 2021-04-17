# spark_movielens_dataset_analysis 

A movie recommendation system is used by top streaming services like Netflix, Amazon Prime, Hulu, Hotstar etc to recommend movies to their users based on historical viewing patterns.

Before the final recommendation is made, there is a complex data pipeline that brings data from many sources to the recommendation engine. In this project, I have used Databricks Spark on Azure with Spark Sql to build this data pipeline.

The dataset is from GroupLens Research, which is a research group in the Department of Computer Science and Engineering at the University of Minnesota. They operate a movie recommender based on collaborative filtering called MovieLens. This dataset (ml-latest) describes 5-star rating and free-text tagging activity from MovieLens, a movie recommendation service. It contains 22884377 ratings and 586994 tag applications across 34208 movies. These data were created by 247753 users between January 09, 1995 and January 29, 2016. This dataset was generated on January 29, 2016.

Here in the repository I have attached the computation part of the pipline, the computation (processing) is done on Azure Databricks.

## Tech Stack Used:

- Storage: Azure Datalake Storage
- ETL/Data pipline: Azure Datafactory
- Computation: Azure Databricks/ Databricks community Edition

## Steps Involved:

1. Building storage account on Azure.
2. Uploading Raw data in the Azure Datalake storage.
3. Creating a Azure Datafactory instance.
4. Creating a datapipline using Azure Datafactory. (To copy data from 1 location to other)
5. Creating Azure Databricks instance (Databricks community edition can also be used).
6. Creating a databricks cluster.
7. Creating a python notebook and accessing the data either from DBFS/Azure datalakes storage etc.
8. Performing the computation and EDA on the dataset and plotting it.

### You can also view the code directly on Databricks using below link:

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4873749021654053/3608940803493665/4555382193918971/latest.html


### Results (Dashboard/Charts):

1- Genre distribution ie. Which genre has highest number of more than 4 rating across entire Dataset

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4873749021654053/3608940803493665/4555382193918971/latest.html

2- Number of movies for each genre

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4873749021654053/3608940803493665/4555382193918971/latest.html

3- Number of ratings (2,3,4,5 etc.)

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4873749021654053/3608940803493665/4555382193918971/latest.html


