# book-recommendation
#### Link For Video Presentation #####

https://youtu.be/oU51P9YNuVk

#### Jupyter Notebook ####

The jupyter notebook has the code for data visualisation.
A spark session is created to use the spark in memory computing operations. 
The data is first loaded from hdfs into the jupyter notebook.
Stored it as a dataframe and generated visualisations to get overview of the data. 
RDDs from the data are created. The data is manipulated according to the need by using map-reduce, filter, repartition functions.
Spark Mllib library is used for the ALS algorithm to generate recommendations. 

#### Cluster Env ####

A cluster environment with One master and two slave nodes is used to deploy the application over the cloud. //Provided by prof
HDFS storage system is used to store the book data, ratings data etc.

pyspark, pydoop, pyhdfs, and subprocess python libraries are used to form the communication between spark, hdfs and python. 

#### References ######
1. Dataset and KNN algorithm
https://www.kaggle.com/zygmunt/goodbooks-10k

2. Running subprocess commands
https://community.cloudera.com/t5/Community-Articles/Interacting-with-Hadoop-HDFS-using-Python-codes/ta-p/245163
