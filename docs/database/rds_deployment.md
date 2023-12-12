# RDS Deployment Options

## Read Replicas

- Scale the read workload of your DB
- Can create up to 15 Read Replicas
- Data is only written to the main DB

![RDS Read Replicas](../../images/database/rds_read_replica.png)

## Multi-AZ

- Failover in case of AZ outage (hig availability)
- Data in only read/written to the main database
- Can only have 1 other AZ as failover

![RDS Multi AZ](../../images/database/rds_multi_az.png)