AWS-IAM-S3-EC2-Access-Security

The best practice of using IAM Roles to provide secure, credential-free access to AWS resources.You will learn how to create an IAM role
with read-only permissions and attach it to an Amazon EC2 instance,allowing it to list and interact with files in an mazon S3 bucket without
storing access keys on the instance.

Architecture Components
**IAM Role: A secure way to delegate permissions that are assumed by an AWS service (EC2).

**Amazon EC2: The compute instance acting as the client to access S3.

**Amazon S3: The object storage service holding the data.

**AWS CloudShell: A browser-based shell used to validate S3 connectivity
