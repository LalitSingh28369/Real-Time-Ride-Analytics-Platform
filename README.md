
This project demonstrates a complete end-to-end data engineering pipeline built using modern cloud and big data technologies. It simulates a real-world, event-driven system where data is generated from a web application and processed in near real-time for analytics and reporting.

The pipeline begins with event ingestion through Azure Event Hub (Kafka-based streaming), where streaming data is captured efficiently. Azure Data Factory is used to orchestrate and manage data ingestion workflows, moving data into Azure Data Lake Storage for scalable and reliable storage. Databricks is then leveraged to process the data using PySpark and Spark Structured Streaming, enabling real-time transformations and processing.

A key highlight of this project is the implementation of metadata-driven pipelines, which improve scalability and reusability by dynamically handling data processing logic. Additionally, Slowly Changing Dimensions (SCD) are implemented to manage historical data effectively, ensuring accurate tracking of changes over time.

The processed data is stored in Delta Lake format, providing features such as ACID transactions, schema enforcement, and improved performance. Finally, a STAR schema data model is designed to support efficient querying and analytics, making the data ready for downstream reporting tools.

This project covers essential data engineering concepts including real-time streaming, ETL/ELT pipelines, cloud data architecture, and data modeling. It is designed to be beginner-friendly while still reflecting industry best practices.

By working through this project, you will gain hands-on experience in building scalable, production-ready data pipelines using Azure and Databricks, and develop a strong foundation in modern data engineering workflows.


