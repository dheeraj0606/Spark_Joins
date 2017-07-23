# Hadoop-Spark-join-datasets
This is a PySpark project on Hadoop platform to join 2 datasets (Coursera project)

The files join1_fileA.txt and join1_fileB.txt contain 2 datasets in form of key-value pairs. join1_fileA.txt contains name(key) and count(value) whereas, join1_fileB has date + name(key) and count(value). Our aim is to join these 2 datasets in form of name(as keys) and date+count(as values).
The spark_map_fns.txt file contains code to be written on Cloudera terminal with PySpark installed.
The final joined RDD will appear in terminal after the final colect() command
