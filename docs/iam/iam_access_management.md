# IAM Access Management

To access AWS you have three options:
- AWS Management Console 
    - protected by password and MFA
- AWS Command Line Interface (CLI) 
    - protected by access keys
- AWS Software Development Kit (SDK) 
    - protected by access keys

Access Keys are generated through the AWS Management Console. Users manage their own access keys.

Access Keys are like user and password:
- access key ID ~= username
- access key secret ~= password

## AWS Command Line Interface (CLI)

AWS CLI is an alternative to using AWS Managment Console.

AWS CLI is a tool that allows you to interact with the AWS services using commands in  your command-line shell.

AWS CLI has direct access to the public API of AWS services. With AWS CLI you can develop script to manage your resource.

AWS CLI is open source and you can find all the source on [GitHub](https://github.com/aws/aws-cli).

## AWS Software Development Kit (SDK)

AWS SDK is a set of language specific libraries that allow you to access and manage your AWS services and APIs programmatically.

AWS SDK is not something that you use within your terminal but it is something you embed within you application.

AWS SDK supports many different programming languages and platforms:
- SDKs (JavaScript, Python, PHP, etc.)
- Mobile SDKs (Android, iOS, etc.)
- IoT Device SDKs (Embedded C, Arduino, etc.)

## AWS CloudShell

AWS CloudShell is an alternative to using the terminal to issue commands against AWS.

Cool things:
- credentials are the same of logged account
- you have a full repository
- you can configure it (e.g. font size, etc.)
- you can download/upload files
- you can open multiple tabs 