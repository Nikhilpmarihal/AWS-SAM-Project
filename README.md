# AWS SAM Project

This repository contains a collection of AWS serverless application examples and exercises, demonstrating various AWS services and patterns.

## Project Structure

The project is organized into the following components:

### Serverless Application (`AWS/serverless-app`)

A complete serverless application utilizing a REST API architecture. Key components include:

- **AWS Lambda Functions**:
  - `SubmitOrderFunction`: Handles incoming order submissions.
  - `ProcessOrderFunction`: Processes orders from the queue.
- **Amazon SQS**: Decouples the submission and processing logic.
- **Amazon DynamoDB**: Stores order information.
- **Amazon API Gateway**: Exposes the application via a REST API.
- **Frontend**: A static `index.html` file to interact with the API.

### AWS Lambda Examples (`AWS/aws-lambda`)

Contains examples and documentation for working with AWS Lambda, including:

- Basic function setup and execution.
- logging to Amazon CloudWatch.
- Handling S3 upload events.

### Amazon EventBridge (`AWS/amazon-eventbridge`)

Resources and examples related to Amazon EventBridge integrations.

## Getting Started

Refer to the Markdown documentation files within each subdirectory for specific instructions on deploying and testing each component.

- [Serverless App Instructions](AWS/serverless-app/serverless-app-instructions.md)
- [Working with Lambda](AWS/aws-lambda/working-with-lambda.md)
