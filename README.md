# 3 Databases Compared
The model of a database is the underlying structure for how data is stored in each database system. For my CMSI 402 capstone project, I will be importing data into 3 different databases each with a different model and evaluating their performance. The goal of this project will be to examine the differences and witness firsthand the advantages and disadvantages of each database model. I will using a traditional relational database, a NoSQL database, and a graph database. 

A relational database uses the relational model that is reliant upon first-order predicate logic. Some of the advantages of using the relational model are simplicity, easy of use, and normalization. All relational databases models use the Structured Query Language (SQL) to access the database. 

  In contrast, sometimes a relational model may not be the best tool to solve the problem. NoSQL databases do not have fixed table structures; thus, they have a simple more flexible structure. The downside to NoSQL's flexibility is that they are not as reliable as relational databases and do not support atomicity, consistency, isolation, and durability (ACID) properties. The NoSQL branch of databases offers many different data models to choose from like column, document, key-value, and graph databases.
 

# Key criteria: 
* Ease at which database was set up
* Speed at which queries get results
* Simplicity of query language

# Databases Used:
I will be using PostgreSQL as my standard SQL database engine. 

I am using Apache Cassandra as a wide-column store NoSQL database. 

I am using ElasticSearch as a search engine model. 

The dataset for the project will be a movie dataset that has metadata on 45,000 movies and 26 million ratings. 


Sources:
https://en.wikipedia.org/wiki/Relational_database

https://www.toptal.com/database/the-definitive-guide-to-nosql-databases

https://datajobs.com/what-is-hadoop-and-nosql

https://www.kaggle.com/rounakbanik/the-movies-dataset/home
