# BIG DATA CHALLENGE

In this challenge, we used PySpark to learn how to work with a big dataset. We ran various queries using SparkSQL to better understand the dataset. We further analyzed the power of caching the data and also partitioning it in parquet format. The difference in performance was analyzed by running the same query three (3) times:
1. First was without caching or partitioning
2. Second, we cached the table
3. Third, we partitioned the dataset based on the date_built column in a parquet format

With each step, the time to run the query reduced, with the respective times for each step listed below:
1. 1.1564390659332275 seconds
2. 0.5899677276611328 seconds
3. 0.48134422302246094 seconds
