# AWS Bill Processor

Serverless AWS Bill Processing System using Lambda, S3, Textract, DynamoDB, and EventBridge for automated bill data extraction and storage.

## Architecture
<img width="1536" height="1024" alt="ChatGPT Image Jun 21, 2026, 12_20_15 PM" src="https://github.com/user-attachments/assets/69767c7b-e733-4ef1-bce5-25aa90bbcca4" />



## AWS Services Used

* AWS Lambda
* Amazon S3
* Amazon Textract
* Amazon DynamoDB
* Amazon EventBridge

## Workflow

1. Upload bill image to Amazon S3
2. S3 triggers AWS Lambda
3. Lambda invokes Amazon Textract
4. Textract extracts bill information
5. Lambda processes extracted data
6. Data is stored in DynamoDB
7. EventBridge automates scheduled processing

## Screenshots

### Lambda Function



### S3 Bucket

![S3](s3-bucket.png)

### DynamoDB Table

![DynamoDB](dynamodb-table.png)

### EventBridge Rule

![EventBridge](eventbridge-rule.png)

## Features

* Automated bill processing
* OCR-based data extraction
* Serverless architecture
* Event-driven workflow
* DynamoDB data storage

## Author

Sahil Donagre
AWS Cloud & Data Engineering Enthusiast

