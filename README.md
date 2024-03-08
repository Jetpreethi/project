# Data migration and transformation tool for mongodb(nosql) data warehouses

Project Title :Data migration and transformation tool for mongodb(nosql) data warehouses
Technologies used in this project : Python/PySpark,Requests,Zipfile,boto3,pandas,sqlalchemy, Amazon S3, Mongodb.
Problem Statement:
You have a URL that points to a zip file. The zip file contains multiple JSON files. The JSON files contain multiple documents with various data structures. Your goal is to download the zip file from the URL, extract the data from the JSON files, store it in Amazon S3, and load it into Mongodb. You want to use Python or PySpark to perform these tasks. You may use any libraries or tools that are necessary to complete the task.

Approach:
To extract the data from a zip file that is available at a URL and load it into Amazon S3 and mongodb(NoSQL), you can follow these steps: 

1.Use the requests library to download the zip file from the URL.

2.Use the zipfile module to extract the data from the zip file.

3.Use the boto3 library or PySpark to store the data in Amazon S3.

4.Use the pandas library and sqlalchemy or PySpark to load the data from S3 into mongodb (NoSQL).

Result:
The result of following these steps should be that the data from the zip file is extracted and stored in a list of dictionaries (if you are using Python) or a DataFrame (if you are using PySpark). Each dictionary or DataFrame row will represent a document from one of the JSON files in the zip file. 
The data in the list or DataFrame will then be stored in Amazon S3 as JSON files. You will be able to access these JSON files using the boto3 library or the Amazon S3 web interface. 
The data from the JSON files will also be loaded into mongodb (NoSQL). 




