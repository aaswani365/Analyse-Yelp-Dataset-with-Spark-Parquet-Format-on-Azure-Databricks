# Analyse-Yelp-Dataset-with-Spark-Parquet-Format-on-Azure-Databricks


# Business Overview ⁉️

Azure Databricks is a data analytics tool tailored for the Microsoft Azure cloud services platform. In massive data pipelines, raw and structured data is imported into Azure in batches via Azure Data Factory or streamed near real-time via Apache Kafka, Event Hub, or IoT Hub. This data is stored in a data lake for long-term sustained storage, either in Azure Blob Storage or Azure Data Lake Storage. Azure Databricks is utilized to read data from different data sources and transform it into breakthrough insights using Spark as part of the analytics workflow.


# Data Pipeline 🖇️

A data pipeline is a technique for transferring data from one system to another. The data may or may not be updated, and it may be handled in real-time (or streaming) rather than in batches. The data pipeline encompasses everything from harvesting or acquiring data using various methods to storing raw data, cleaning, validating, and transforming data into a query-worthy format, displaying KPIs, and managing the above process.

 
# Approach 🏃‍♂️

-   Read yelp datasets in ADLS and convert JSON to parquet for better performance.

-   Convert JSON to Delta Format.

-   Total records in each dataset.

-   Partition tip dataset tip by a date column.

-   repartition() and coalesce()

-   Find the top 3 users based on their total number of reviews.

-   Find the top 10 users with the most fans

-   Analyse the top 10 categories by a number of reviews.

-   Analyse top businesses which have over 900 reviews.

-   Analyse Business Data: Number of restaurants per state.

-   Analyze the top 3 restaurants in each state.

-   List the top restaurants in a state by the number of reviews.

-   Numbers of restaurants in Arizona state per city.

-   Broadcast Join: restaurants as per review ratings in Pheonix city.

-   Most rated Italian restaurant in Tucson.

 

# Tech Stack

➔ Language: PySpark

➔ Services: Azure Data factory, Azure Databricks, ADLS
