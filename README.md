# Spark
General repo for all-things Spark, PySpark and Hadoop

Includes exploratory data analysis using PySpark based on Frank Kane's tutorials.

Further exploration includes setting up a Hadoop cluster on RaspberryPi.


**Basic imports and declarations to get started with PySpark and a SparkContext**

`from pyspark import SparkConf, SparkContext`  
`import collections`  

`conf = SparkConf().setMaster("local").setAppName("RatingsHistogram")`  
`sc = SparkContext(conf = conf)`  