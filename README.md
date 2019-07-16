

The code should be read in conjunction with the following medium post:
https://medium.com/@singhsa3/spark-in-action-to-predict-customer-churn-rate-on-a-real-dataset-75ffabb1332c# SparkChurnRate

Libraries used:
We have used mainly pyspark and sklearn. To run this notebook you will need to have pyspark installed and configured.
With pyspark, we have used SparkSQL among others.
Pyspark in turn has dependancy on Java 8.
The location of dataset is on S3 and is publicly available.

Files in the repository:
There are two files in the repository, one is the Jupyter notebook and other is html version of it.

Results:
Spark is great for very large dataset. However, if you can fit your data on a single node, having lot of CPU. It is advisable to use Sklearn. However, this project does showcase how to effectively use Spark.
In our case, we are able to , with fair amount of accuracy, predict the churn rate using lositics regression , using both Spark and Sklear,


