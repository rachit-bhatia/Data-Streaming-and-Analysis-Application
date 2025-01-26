# Data-Streaming-and-Analysis-Application
The project involves building a data pipeline and application to analyze climate data using MongoDB, Apache Kafka, and Apache Spark Structured Streaming. The goal is to handle real-time and static data using big data technologies to process, analyze, and visualize fire and climate datasets.

Tasks done:
- Designed a NoSQL data model.
- Implemented real-time data streaming and processing pipelines.
- Stored processed data in MongoDB.
- Visualized results for actionable insights.

### Usage Guide
1. Run the MongoDB setup and querying tasks:
   
    Open and execute the Data Model_MongoDB Queries.ipynb notebook to:
  	- Study the designe data model.
    - Load the historic data into MongoDB.
  	- Run analytical queries on the database.

2.	Stream data using Kafka producers:

    Execute the following notebooks to start the Kafka producers:
    - Kafka Data Producer 1.ipynb
    - Kafka Data Producer 2.ipynb
    - Kafka Data Producer 3.ipynb

4.	Process streaming data with Spark:

    Run Spark Streaming Application.ipynb to process the data streams, merge duplicate records, and store the results in MongoDB.

5.	Visualize the data:

    Use Streaming Data Visualiser.ipynb to generate:
     - Line graphs of climate data over time.
     - Bar charts and maps for fire data analysis.

### Dependencies
The project relies on the following technologies:
- Python
- MongoDB
- Apache Kafka
- Apache Spark Structured Streaming
- Python libraries: pymongo, pyspark, kafka-python3, pandas, python-geohash, folium, matplotlib

Make sure these dependencies are installed and configured before running the notebooks
