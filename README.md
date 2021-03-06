# S3-Object-Lambda
Code to process data retrieved from S3 before returning it to an application. S3 Object Lambda works with your existing applications and uses AWS Lambda functions to automatically process and transform your data as it is being retrieved from S3.

# About
This repository provides use based code to process data retrieved from S3 before returning it to an application. S3 Object Lambda works with your existing applications and uses AWS Lambda functions to automatically process and transform your data as it is being retrieved from S3. The Lambda function is invoked inline with a standard S3 GET request, so you don’t need to change your application code. This repo will provide example code that can be used as is or modified to meet your requirements. 

Some typical use cases that we will try to include is code to: 
- Redact personally identifiable information for analytics or non-production environments. 
- Convert across data formats, such as converting XML to JSON. 
- Augment data with information from other services or databases. 
- Compress or decompress files as they are being downloaded. 
- Resize and watermark images on the fly using caller-specific details, such as the user who requested the object. 
- Implement custom authorization rules to access data. 

(See https://aws.amazon.com/blogs/aws/introducing-amazon-s3-object-lambda-use-your-code-to-process-data-as-it-is-being-retrieved-from-s3/)
