# Database Basics

Databases are **optmized for a purpose** and come with different features, shapes and constraints.

Databases types:
- **Relational Databases**
    - can use the SQL language to perform queries/lookups
    - "engineered" for vertical scaling
- **NoSQL Datatabases**
    - NoSQL = non-SQL = non relational databases
    - built for specific data models
    - flexible schema for modern applications
    - benefits: 
        - flexibility: easy to evolve the data model
        - scalability: designed to scale-out by using distributed clusters
        - high-performance: optimized for a specific data model
        - high-functional: types optimized for the data model
    - examples:
        - key-value
        - document
        - graph
        - in-memory
        - search databases

## NoSQL data example: JSON

- JSON = JavaScript Object Notation
- JSON is a common form of data that fits into a NoSQL model
- Data can be **nested**
- Fields can change over time
- Support for new type: arrays, etc.

~~~
    {
        "name" : "John",
        "age" : 30,
        "cars" : ["Ford", "BMW", "Fiat"],
        "address" : {
            "type" : "house",
            "number" : 23,
            "street": "South Road"
        }
    }
~~~

## Database & Shared Responsibility on AWS

AWS offers use to **manage** different databases.

Benefits include:
- quick provisioning
- high availability
- vertical/horizontal scaling
- automated backup & restore
- operations
- upgrades
- OS patching is handled by AWS
- monitoring & alerting

**NOTE**. Many database technologies could be run on EC2, but you must handle yourself the resiliency, backup, patching, high availability, fault tolerance, scaling, ...