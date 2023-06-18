# Building-a-Complex-Data-Pipeline-using-Kafka
The "Building a Complex Data Pipeline with Kafka" project focuses on building a complex data pipeline using Kafka. The pipeline will involve setting up a Kafka cluster, creating multiple topics, writing producers to generate data, writing consumers to process the data, and integrating the pipeline with an external system.

## Operating System: Windows

## Platforms:
- Jupyter Notebook
- MySQL WorkBench
- Terminal
## Dependencies:
- Kafka
- Mysql.connector
- Json
- yfinance

# Yfinance
Install the yfinance library by using the command pip install yfinance.

Note: This library is used to retrieve streamed data for stocks.

## JSON
The data is converted into JSON format using json.encode and json.decode. This conversion simplifies the data into a string format for easy retrieval.

Note: The purpose of this conversion is to send the data to the consumer in a readable format to avoid errors and ambiguities.

# Kafka Setup
Ensure that Kafka is installed on your system.

Set up a Kafka cluster with three brokers by following these steps:

Add paths for three new log files.
Assign three different ports for the topics.
Create three new server files with the updated changes.
Start ZooKeeper.

Start the Kafka server.

Create three topics on the partitions of the brokers.

Run the producer and consumer using the provided topics (test1, test2, and test3) using the relevant commands.

Note: The producer fetches data from the specified topics, and the consumer performs operations on the data stored in the cluster.

# MySQL Workbench 
Install MySQL Workbench by following the tutorial provided.

Install mysql-connector-python by using the command pip install mysql-connector-python in the command prompt.

Install mysql.connector in Jupyter Notebook using the command pip install mysql.connector.
