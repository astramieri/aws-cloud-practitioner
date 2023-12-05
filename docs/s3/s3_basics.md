# S3 Basics

Amazon Simple Storage Service (S3) is one of the main building blocks of AWS. It's advertised as *infinitely scaling* storage.

Many websistes use Amazon S3 as a backbone.

Many AWS services use Amzon S3 as an integration as well.

Amazon S3 use cases:
- Backup and Storage
- Disaster Recovery
- Archive
- Hybrid Cloud Storage
- Application Hosting
- Media Hosting
- Data Lakes & Big Data Analytics
- Software Delivery
- Static Websiste

## S3 Buckets

Amazon S3 allows people to store objects (files) in **buckets** (top-level directories).

Buckets must have a **globally unique** name across all regions all accounts. This means that the name must be unique across all the regions you have it in your accounts, but also all the accounts that exist out there on AWS. This is the only thing that must be globally unique in AWS.

Even though the name of the bucket is unique across all regions and all the accounts, **the buckets must be defined in a specific AWS regions**.

**NOTE**. S3 looks like a global service but buckets are created in a region.

S3 Naming Convention:
- no uppercase
- no underscore
- 3-63 characters long
- not an IP
- must start with lowercase letter or number
- must not start with the prefix xn--
- must not end with the suffix -s3alias

## S3 Objects

All the objects (files) contained in a bucket have a **key**. 

The key is the **full path**.

- s3://my-bucket/**my_file.txt**
- s3://my-bucket/**my_folder/my_file.txt**

The key is composed of **prefix** + **object_name**.

    s3://my-bucket/my_folder/my_file.txt

    PREFIX: my_folder/
    OBJECT NAME: my_file.txt

**NOTE**. There is no concept of *directories* within buckets (although the UI will trick you to think otherwise). Keys are just very long names that cointains slashes ("/").

Object values are the content of the body:
- max objects size is 5 TB (5000 GB)
- if uploading more than 5 GB, must be uses "multi-part upload"

Objects can also have **metadata**:
- list of text key/value pairs
- can be set by the system or by the user

Objects can also have **tags**:
- unicode key/value pairs (up to 10)
- useful for security and life cycle

Objects can also have a **version ID** is versioning is enabled.
