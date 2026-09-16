# event-driven-pipeline-project

## Event-Driven Pipeline (CSV parsing)
Brief:
- S3 upload triggers a Lambda Function
- Processes CSV file
- Writes metadata to DynamoDB
  - SNS Notification
- Add SQS between stages for decoupling

Project covers:
- S3 events
- SQS vs SNS
- Dead Letter Queues
