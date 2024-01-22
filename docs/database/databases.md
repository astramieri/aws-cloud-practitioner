# Databases

Databases are **optmized for a purpose** and come with different features, shapes and constraints.

Databases types:
- **Relational Databases**
    - Can use the SQL language to perform queries/lookups
    - "Engineered" for vertical scaling
- **NoSQL Datatabases**
    - NoSQL = non-SQL = non-relational databases
    - Built for specific data models
    - Flexible schema for modern applications
    - Benefits: 
        - Flexibility: easy to evolve the data model
        - Scalability: designed to scale-out by using distributed clusters
        - High-performance: optimized for a specific data model
        - High-functional: types optimized for the data model
    - Examples:
        - Key-Value
        - Document
        - Graph
        - In-Memory
        - Search Databases

## NoSQL Data Example: JSON

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
- Quick Provisioning
- High Availability
- Vertical/Horizontal Scaling
- Automated Backup & Restore
- Operations
- Upgrades
- OS patching
- Monitoring & Alerting

**NOTE**. Many database technologies could be run on EC2, but you must handle yourself the resiliency, backup, patching, high availability, fault tolerance, scaling, etc.