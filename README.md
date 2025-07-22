# AWS S3 + Lambda CSV Uploader (Spring Boot)

This project demonstrates a basic AWS-based data ingestion pipeline using Java Spring Boot. The system uploads a CSV file to an S3 bucket, triggers a Lambda function, and logs file ingestion activity using CloudWatch.

## 📌 Features

- Upload CSV to Amazon S3
- Trigger AWS Lambda on file upload
- Log events using CloudWatch
- Java Spring Boot backend
- IAM roles for secure access
- GitHub-ready Maven project

## 🛠️ Technologies Used

- Java 17 (Spring Boot)
- AWS S3
- AWS Lambda
- AWS CloudWatch
- IAM (for permissions)
- GitHub (for version control)

## 🔧 Architecture
aws-s3-lambda-csv-uploader/
├── src/main/java/com/example/uploader/
│   └── controller/UploadController.java
│   └── service/S3Service.java
├── src/main/resources/application.properties
├── pom.xml
└── README.md
License

MIT License — Feel free to use, fork, and contribute.

Author: [Your Name]
GitHub: https://github.com/saurabhmittall/aws-s3-lambda-csv-uploader
