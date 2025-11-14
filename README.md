# code-pipeline1
This project implements a serverless, Infrastructure-as-Code (IaC) solution for automated language translation on AWS. 
The system integrates Amazon S3, AWS Lambda (Python/Boto3), and Amazon Translate to automatically process translation requests. 
Terraform provisions the infrastructure, ensuring repeatable deployments. 
JSON request files uploaded to S3 trigger a Lambda function that translates the text and stores results in another S3 bucket.
