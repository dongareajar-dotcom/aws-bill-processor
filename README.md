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
<img width="1571" height="828" alt="Screenshot 2026-06-08 145617" src="https://github.com/user-attachments/assets/4f0f84e5-c0d9-4850-9ced-c49754c03406" />



### S3 Bucket
<img width="1596" height="835" alt="Screenshot 2026-06-08 145701" src="https://github.com/user-attachments/assets/8cd0f576-fe59-4dc9-b68a-292b06d45668" />



### DynamoDB Table
<img width="1576" height="841" alt="Screenshot 2026-06-08 145804" src="https://github.com/user-attachments/assets/73725348-9aab-4afe-a0d3-09e97d4f910e" />


## Features

* Automated bill processing
* OCR-based data extraction
* Serverless architecture
* Event-driven workflow
* DynamoDB data storage

## Author

Sahil Donagre
AWS Cloud & Data Engineering Enthusiast

