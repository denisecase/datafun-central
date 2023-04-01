+++
tags = ["data"]
title = "Data at Rest"
weight = 10
+++

Data at rest refers to data that is stored and not actively being processed or transmitted. This includes data stored in databases, data warehouses, data lakes, and other storage systems.

## Data Lakes

A data lake is a centralized repository that allows organizations to store and manage large amounts of structured and unstructured data at scale. Data lakes provide a cost-effective and flexible way to store data from various sources and formats, and can support a wide range of data processing and analytics tools.

### Delta Lake

Delta Lake is an open-source data storage and management system that is designed for large-scale data lakes. It was developed by Databricks, and it provides a number of advanced features, including ACID transactions, version control, and schema enforcement, that make it easier to manage large and complex data sets. 

Delta Lake is built on top of Apache Spark, and it provides a unified platform for managing structured, semi-structured, and unstructured data in a single system. With Delta Lake, data analysts and engineers can  build and manage data lakes and ensure their data is accurate, consistent, and reliable.

## Lake House Architecture

Lake house architecture is an emerging approach to data storage and management that combines the benefits of data lakes and traditional data warehouses. It provides a scalable and flexible platform for storing and processing data, while also providing strong data governance and security controls.

## SQL Databases

SQL databases are a popular type of relational database that use Structured Query Language (SQL) to manage and retrieve data. SQL databases are widely used for a range of applications, including transaction processing, data warehousing, and analytics.

Some popular SQL databases include:

- MySQL
- PostgreSQL
- Microsoft SQL Server
- Oracle Database

## NoSQL Databases

NoSQL databases are non-relational databases that can handle large volumes of unstructured and semi-structured data. They are often used for applications that require high scalability and performance, such as real-time data processing and analytics.

Some popular NoSQL databases include:

- MongoDB
- Cassandra
- Couchbase
- Amazon DynamoDB

## Graph Databases

Graph databases are specialized databases designed to store and manage graph data structures. They are often used for applications that involve complex relationships and dependencies, such as social networks and recommendation systems.

Some popular graph databases include:

- ArangoDB
- Neo4j
- OrientDB

## Data Warehouses

Data warehouses are specialized databases designed for storing and analyzing large volumes of structured data. They are often used for business intelligence and analytics applications, and typically support complex queries and reporting.

Some popular data warehouses include:

- Snowflake
- Amazon Redshift
- Google BigQuery
- Microsoft Azure SQL Data Warehouse

### Snowflake (Commerical)

Snowflake is a cloud-based data warehousing platform that allows organizations to store, manage, and analyze large volumes of structured and semi-structured data in real-time. Snowflake's architecture is designed to separate storage and compute, allowing users to scale each independently and pay only for what they use. This makes it a popular choice for data-intensive workloads that require fast and flexible access to data. Additionally, Snowflake provides a range of tools and features for data management, such as data sharing, secure data exchange, and automated data governance, which can help organizations simplify their data operations and reduce costs. Snowflake is a powerful and flexible data warehousing platform gaining popularity among organizations of all sizes and industries.

### Open-Source Options

There are several open source alternatives to Snowflake that offer similar functionality, including:

#### Apache Druid

A high-performance, column-oriented, distributed data store designed for real-time analytics. Druid is optimized for OLAP queries on large-scale datasets and offers sub-second query response times.

#### Apache Pinot

Another high-performance, distributed data store designed for OLAP queries. Pinot is optimized for handling large-scale datasets and supports real-time ingestion and querying of data.

#### ClickHouse

A high-performance column-oriented database management system designed for OLAP queries. ClickHouse is optimized for handling large-scale datasets and provides sub-second query response times. It also supports real-time data ingestion and offers a variety of storage formats and compression algorithms.

#### Presto

A distributed SQL query engine designed for querying large-scale datasets stored in a variety of data sources, including Hadoop, HDFS, Amazon S3, and more. Presto is optimized for ad hoc querying and provides fast query response times.

#### Apache Arrow

A columnar in-memory data structure and computation framework designed for high-performance data processing. Arrow is optimized for efficient data sharing and serialization across different programming languages and systems.

## See Also

- [Data-in-Motion]({{< relref "in-motion" >}})

