# S3 Website

S3 can be used to create **static** websites accessible on the internet.

The website URL will be (depending on the AWS region):

    http://<bucket-name>.s3-website-<aws-region>.amazonaws.com
    http://<bucket-name>.s3-website.<aws-region>.amazonaws.com

Examples:

    http://demo-bucket.s3-website-us_west-2.amazonaws.com
    http://demo-bucket.s3-website.us_west-2.amazonaws.com

**NOTE**. If you get a **403 Forbidden error** make sure the bucket policiy allow public reads. You must attach an S3 bucket policy that allows the S3 bucket to be public.