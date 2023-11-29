## EC2 Instance

Amazon EC2 provides a wide selection of instance types optimized to fit different use cases. 

Instance types comprise varying combinations of CPU, memory, storage, and networking capacity and give you the flexibility to choose the appropriate mix of resources for your applications. 

Each instance type includes one or more instance sizes, allowing you to scale your resources to the requirements of your target workload.

## EC2 Instance Types

- **General Purpose** (m/t)
    - great for a diversity of workloads (web servers or code repositories)
    - balance between compute, memory and networking
- **Compute Optimized** (c)
    - great for compute-intensive tasks that require high performance processors
        - batch processing workloads
        - media trascoding
        - high performance web servers
        - high performance computing
        - scientific modeling & machine learning
        - dedicated gaming servers
- **Memory Optimized** (r/x/z)
    - fast performance for workloads that process large data sets in memory
        - high performance, relational/non-relational databases
        - distributed web scale cache stores
        - in-memory databases optimized for BI
        - applications performing real-time processing of big unstructured data
- **Storage Optimized** (i/d/h)
    - great for storage-intensive tasks that require high, sequential read and write access to large data sets on local storage
        - high frequency online transaction processing (OLTP)
        - relational and nosql databases
        - cache for in-memory database (e.g. Redis)
        - data warehousing applications
        - distributed file systems
- **HPC Optimized** (h)
- **Accelerated Computing** (p)

## EC2 Instance Naming Convention

    m5.2xlarge
    
    m = instance class
    5 = generation (AWS improves them over time)
    2xlarge = size within the instance class

## Resources

- [AWS EC2 Instance](https://aws.amazon.com/ec2/instance-types/)
- [EC2 instance compare](https://instances.vantage.sh/)