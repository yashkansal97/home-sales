# BIG DATA CHALLENGE

In this challenge, we used PySpark to learn how to work with a big dataset. We ran various queries using SparkSQL to better understand the dataset. We further analyzed the power of caching the data and also partitioning it in parquet format. The difference in performance was analyzed by running the same query three (3) times:
1. First was without caching or partitioning
2. Second, we cached the table
3. Third, we partitioned the dataset based on the date_built column in a parquet format

With each step, the time to run the query reduced, with the respective times for each step listed below:
1. 0.7367236614227295 seconds
2. 0.5023884773254395 seconds
3. 0.39278388023376465 seconds
