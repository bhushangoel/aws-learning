# Databases

They are an organized collection of data, which is stored electronically and accessed from a computer system.

AWS has different types of database systems

* Relational : \
  Relational databases are those where the data stored is related to each other.
  * Amazon Aurora - mySQL and PosrgreSQL compatible database built for the cloud
  * Amazon RDS (Relational Database Service)
  * Amazon Redshift
* Key-value
  * Amazon DynamoDB - fast and flexible no SQL database.
* In-memory
  * Amazon ElastiCache - in memory data store service for Redis and Memcached. Used for caching, session management, gaming leaderboards and geospatial apps
* Document
  * Amazon DocumentDB - For Content management, catalogues and user profiles. It is mongoDB compatible
* Graph
* Time Series
* Wide column
* Ledger

### Amazon Elasticache

* It is a fully managed in-memory data store. In-memory data store refers to storing things that you have previously requested from your database.
* While accessing, you access elasticache first intead of the database.
* Elasticache has two engines that you can use, which are twi different in-memory data stores.
  * Redis
  * Memcached
* It is fully scalable&#x20;

