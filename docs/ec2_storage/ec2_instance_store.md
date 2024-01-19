# EC2 Instance Store

EBS volumes are network drives with good but *limited* performance. If you need a high-performance hardware disk use **EC2 Instance Store**.

EC2 Instance Store is the name of the HW attached to the physical server.

EC2 Instance Store has better I/O performance, **but they lose their storage** if they are stopped or termimated (ephemeral).

EC2 Instance Store can **not** be used as a durable long term place to store your data. Also there is **risk of data loss** if hardware fails.

EC2 Instance Store are good for buffer, cache, scracth data, or temporary content. Backups and Replication are your responsibility.