# EBS Snapshots

A snapshot is a backup of an EBS volume at a point in time. 

It is not necessary to detach the volume prior to doing the backup, but **it is recommended**.

You can copy snapshots across Availability Zones or Regions in order to transfer data in a different region on AWS to leverage the global infrastructure.

![EBS Snapshot](../../images/ec2_storage/ebs_snapshot.png)

## EBS Snapshot Archive

- move a snapshot to an "archive tier" that is 74% cheaper
- takes within 24 to 72 hours for restoring the archive

![EBS Snapshot Archive](../../images/ec2_storage/ebs_snapshot_archive.png)

## EBS Snapshot Recycle Bin

- setup rules to retain deleted snapshots so you can recover them after an accidental deletion
- specify retention (from 1 day to 1 year)

![EBS Snapshots Recycle Bin](../../images/ec2_storage/ebs_snapshot_recycle_bin.png)