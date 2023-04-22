# QuestDB Limitations
QuestDB is a column-oriented database designed for time series and event data. While it offers high performance and low latency, it has some limitations that users should be aware of.

## Lack of support for distributed databases
QuestDB runs on a single node and cannot scale horizontally across multiple nodes. This makes it less suitable for large-scale web applications, IoT applications, and financial trading systems that require distributed databases to handle the volume and velocity of data.

## Limited support for data types
QuestDB does not support all data types that are commonly used in other databases, such as the JSON data type. This may make it challenging to work with applications that rely heavily on JSON data, data warehousing applications dealing with complex data types, and geospatial applications.

## Limited support for complex queries
QuestDB does not support all the features of SQL that are available in other databases, such as subqueries and common table expressions (CTEs). This may make it challenging to work with applications that require complex querying, reporting, and analytics, and advanced aggregate functions.

Despite these limitations, QuestDB offers many benefits for time series and event data. Users can use QuestDB in conjunction with other databases to achieve some of the benefits of a distributed database system. Additionally, the lack of support for some data types can be mitigated by using QuestDB in conjunction with other databases that do support those data types.

## Workarounds
Use QuestDB in conjunction with other databases to achieve some of the benefits of a distributed database system.
Use QuestDB in conjunction with other databases that do support data types not supported by QuestDB.
Use other databases for complex queries, reporting, and analytics.