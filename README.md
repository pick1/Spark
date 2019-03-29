# Spark

***
<a href='https://github.com/pick1'> <img src='sparkjupyter.png' /></a>
***
General repo for all-things Spark, PySpark and Hadoop

Includes exploratory data analysis using PySpark based on Frank Kane's tutorials.

Further exploration includes setting up a Hadoop cluster on RaspberryPi.

### Installation
**Java**  
Use Java8  
`sudo apt-get install oracle-java8-jdk`  
Check java  
`java -version`  
Should ouput something like:  
`java version "1.8.0_65"`  
`Java(TM) SE Runtime Environment (build 1.8.0_65-b17)`  
`Java HotSpot(TM) Client VM (build 25.65-b01, mixed mode)`   
**Scala**  
`sudo apt-get install scala`  

**Hadoop/Spark/PySpark**
Get hadoop/Spark tar
`wget https://www-us.apache.org/dist/spark/spark-2.4.0/spark-2.4.0-bin-hadoop2.7.tgz`  
Untar  
`tar -zxvf spark-2.4.0-bin-hadoop2.7.tgz`  
**PySpark**
cd into untarred directory/python and run python install setup.py  
`sudo python setup.py install`

**Basic imports and declarations to get started with PySpark and a SparkContext**

`from pyspark import SparkConf, SparkContext`  
`import collections`  

