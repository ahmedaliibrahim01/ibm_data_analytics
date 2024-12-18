# How to Gather and Import Data

In this video, we will learn about the different methods and tools available for gathering data from the data sources discussed earlier in the course—such as databases, the web, sensor data, data exchanges, and several other sources leveraged for specific data needs.

We will also learn about importing data into different types of data repositories.

SQL, or Structured Query Language, is a querying language used for extracting information from relational databases.

SQL offers simple commands to specify what is to be retrieved from the database, the table from which it needs to be extracted, grouping records with matching values, dictating the sequence in which the query results are displayed, and limiting the number of results that can be returned by the query, amongst a host of other features and functionalities. 

Non-relational databases can be queried using SQL or SQL-like query tools.

Some non-relational databases come with their own querying tools such as CQL for Cassandra and GraphQL for Neo4J. 

Application Programming Interfaces (or APIs) are also popularly used for extracting data from a variety of data sources. 

APIs are invoked from applications that require the data and access an end-point containing the data.

End-points can include databases, web services, and data marketplaces.

APIs are also used for data validation. 

For example, a data analyst may utilize an API to validate postal addresses and zip codes.

Web scraping, also known as screen scraping or web harvesting, is used for downloading specific data from web pages based on defined parameters.

Among other things, web scraping is used to extract data such as text, contact information, images, videos, podcasts, and product items from a web property.

RSS feeds are another source typically used for capturing updated data from online forums and news sites where data is refreshed on an ongoing basis.

Data streams are a popular source for aggregating constant streams of data flowing from sources such as instruments, IoT devices and applications, and GPS data from cars.

Data streams and feeds are also used for extracting data from social media sites and interactive platforms.

Data Exchange platforms allow the exchange of data between data providers and data consumers.

Data Exchanges have a set of well-defined exchange standards, protocols, and formats relevant for exchanging data.

These platforms not only facilitate the exchange of data, they also ensure that security and governance are maintained. 

They provide data licensing workflows, de-identification and protection of personal information, legal frameworks, and a quarantined analytics environment.

Examples of popular data exchange platforms include AWS Data Exchange, Crunchbase, Lotame, and Snowflake.

Numerous other data sources can be tapped into for specific data needs.

For marketing trends and ad spending, for example, research firms like Forrester and Business Insider are known to provide reliable data.

Research and advisory firms such as Gartner and Forrester are widely trusted sources for strategic and operational guidance.

Similarly, there are many trusted names in the areas of user behavior data, mobile and web usage, market surveys, and demographic studies.

Data that has been identified and gathered from the various data sources now needs to be loaded or imported into a data repository before it can be wrangled, mined, and analyzed.

The importing process involves combining data from different sources to provide a combined view and a single interface using which you can query and manipulate the data.

Depending on the data type, the volume of data, and the type of destination repository, you may need varying tools and methods.

Specific data repositories are optimized for certain types of data.

Relational databases store structured data with a well-defined schema. 

If you’re using a relational database as the destination system, you will only be able to store structured data, such as data from OLTP systems, spreadsheets, online forms, sensors, network and web logs. 

Structured data can also be stored in NoSQL. 

Semi-structured data is data that has some organizational properties but not a rigid schema, such as, data from emails, XML, zipped files, binary executables, and TCP/IP protocols. 

Semi-structured can be stored in NoSQL clusters. 

XML and JSON are commonly used for storing and exchanging semi-structured data. 

JSON is also the preferred data type for web services. 

Unstructured data is data that does not have a structure and cannot be organized into a schema, such as data from web pages, social media feeds, images, videos, documents, media logs, and surveys. 

NoSQL databases and Data Lakes provide a good option to store and manipulate large volumes of unstructured data. 

Data lakes can accommodate all data types and schema. 

ETL tools and data pipelines provide automated functions that facilitate the process of importing data. 

Tools such as Talend and Informatica, and programming languages such as Python and R, and their libraries, are widely used for importing data.