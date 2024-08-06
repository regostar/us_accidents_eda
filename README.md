Quick Links :- 
---------------

https://youtu.be/Ms5TEd0rRdo

US Accidents Dataset
----------------------

This data comprises of data about accidents in US from 2016 to 2023, sourced from Kaggle. This dataset consists of over 7 Billion data points and 46 unique features.​

https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents/data

Features of Project :- 
---------------------

Size of the Dataset – 7B data points​

Pyspark, MLib and custom GCP architecture.​

Multiple integrations with tools like Hive, Solr.​

Highly Scalable with the current allowed infrastructure. (added auto scaling policy on gcp)​

Accuracy of over 94% to predict severity of accident using Random forest Classifier.​

State of the art – business ready architecture and infrastructure utilized.


Architecture:- 
-------------

#### Google Cloud Platform (GCP) Infrastructure​
#### Dataproc Cluster 
The core of the architecture involves utilizing Google Cloud Dataproc to create and manage clusters. Dataproc provides a fully managed Apache Spark and Hadoop service, allowing for scalable and efficient data processing.​

#### PySpark
For distributed data processing, PySpark, the Python API for Apache Spark, is used. It makes it easier to create scalable and parallelized data transformations and analytics that take advantage of the Dataproc cluster's processing capability.​

#### Hive
a Hadoop data warehouse and SQL-like query language, is integrated into the design. It offers organized querying of the dataset, allowing for the creation of tables and the execution of complicated queries, hence improving data retrieval and analysis performance.​

#### Solr 
for Full-Text Search and Indexing

#### Googler Cloud Storage
for storing intermediate results, works in tandem with dataproc for storing the dataset.​

#### Identity and Access Management (IAM)
for providing authorized access to users to manage services.​

#### Autoscaling policy
– set as a policy to scale up VM's by creating new nodes.​

#### Visualizations using Jupyter Notebook
-  this provides a user friendly way to work on the pyspark- python code.​

#### Apache Solr
on GCP DataProc which provides rich indexing and querying capabilities

![image](https://github.com/user-attachments/assets/33389efc-2710-4783-90e4-ba72d6a20877)

Results :- 
-------------

![image](https://github.com/user-attachments/assets/45849ad7-0968-4958-8378-56bae4d2c329)

![image](https://github.com/user-attachments/assets/a34c825b-0e73-429b-a173-ff1677702aa7)

![image](https://github.com/user-attachments/assets/6bbe4df9-9420-4ef1-995d-3d166231270d)

For more stats, please view - https://github.com/regostar/us_accidents_eda/blob/main/eda-latest.pdf



