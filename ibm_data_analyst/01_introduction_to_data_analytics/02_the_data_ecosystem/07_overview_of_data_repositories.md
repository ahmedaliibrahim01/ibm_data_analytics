# Overview of Data Repositories

A data repository is a general term used to refer to data that has been collected, organized, and isolated so that it can be used for business operations or mined for reporting and data analysis. 

It can be a small or large database infrastructure with one or more databases that collect, manage, and store data sets.

In this video, we will provide an overview of the different types of repositories your data might reside in, such as databases, data warehouses, and big data stores, and examine them in greater detail in further videos.

Let’s begin with databases.

A database is a collection of data, or information, designed for the input, storage, search and retrieval, and modification of data.

And a Database Management System, or DBMS, is a set of programs that creates and maintains the database.

It allows you to store, modify, and extract information from the database using a function called querying.

For example, if you want to find customers who have been inactive for six months or more, using the query function, the database management system will retrieve data of all customers from the database that have been inactive for six months and more.

Even though a database and DBMS mean different things the terms are often used interchangeably.

There are different types of databases.

Several factors influence the choice of database, such as the data type and structure, querying mechanisms, latency requirements, transaction speeds, and intended use of the data.

It’s important to mention two main types of databases here—relational and non-relational databases.

Relational databases, also referred to as RDBMSes, build on the organizational principles of flat files, with data organized into a tabular format with rows and columns following a well-defined structure and schema.

However, unlike flat files, RDBMSes are optimized for data operations and querying involving many tables and much larger data volumes.

Structured Query Language, or SQL, is the standard querying language for relational databases.

Then we have non-relational databases, also known as NoSQL, or “Not Only SQL”.

Non-relational databases emerged in response to the volume, diversity, and speed at which data is being generated today, mainly influenced by advances in cloud computing, the Internet of Things, and social media proliferation.

Built for speed, flexibility, and scale, non-relational databases made it possible to store data in a schema-less or free-form fashion.

NoSQL is widely used for processing big data.

A data warehouse works as a central repository that merges information coming from disparate sources and consolidates it through the extract, transform, and load process, also known as the ETL process, into one comprehensive database for analytics and business intelligence.

At a very high-level, the ETL process helps you to extract data from different data sources, transform the data into a clean and usable state, and load the data into the enterprise’s data repository.

Related to Data Warehouses are the concepts of Data Marts and Data Lakes, which we will cover later.

Data Marts and Data Warehouses have historically been relational, since much of the traditional enterprise data has resided in RDBMSes.

However, with the emergence of NoSQL technologies and new sources of data, non-relational data repositories are also now being used for Data Warehousing.

Another category of data repositories are Big Data Stores, that include distributed computational and storage infrastructure to store, scale, and process very large data sets.

Overall, data repositories help to isolate data and make reporting and analytics more efficient and credible while also serving as a data archive.