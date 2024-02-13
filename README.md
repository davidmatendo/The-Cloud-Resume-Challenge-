# Cloud Resume Challenge - AWS Edition

## Overview
Welcome to my Cloud Resume Challenge - AWS Edition project! This repository showcases my skills in AWS, web development, and best practices through the completion of the Cloud Resume Challenge. Follow the steps below to explore the details of the project.

## Project Structure

- **`/html`**: Contains the HTML code for the resume.
- **`/css`**: Includes the CSS styles for enhancing the resume presentation.
- **`/lambda`**: Contains the Python code for the Lambda function handling the visitor counter.
- **`/sam`**: Contains the AWS SAM (Serverless Application Model) template for defining and deploying API resources.
- **`/tests`**: Includes tests for the Python code in the Lambda function.
- **`/diagram`**: This directory holds the AWS architectural diagram.

## Steps to Replicate

1. **HTML and CSS**: Write your resume in HTML and style it with CSS.
2. **Static Website**: Deploy your HTML resume on Amazon S3.
3. **HTTPS and DNS**: Enable HTTPS using Amazon CloudFront and point a custom DNS domain name to the CloudFront distribution.
4. **JavaScript and Visitor Counter**: Implement a visitor counter using JavaScript on your resume webpage.
5. **Database and API**: Utilize Amazon DynamoDB for the visitor counter, and create an API using AWS API Gateway and Lambda functions for communication.
6. **Python and Tests**: Write Python code for the Lambda function using the boto3 library. Include tests for your Python code.
7. **Infrastructure as Code (IaC)**: Define API resources, DynamoDB table, API Gateway, and Lambda function in the AWS SAM template. Deploy using the AWS SAM CLI.
8. **Source Control and CI/CD**: Create GitHub repositories for backend and website code. Implement CI/CD using GitHub Actions for automatic updates.

## Continuous Integration and Deployment (CI/CD)
- **Backend (AWS SAM)**: GitHub Actions are set up to run Python tests and deploy the AWS SAM application when pushing updates.
- **Frontend (Website)**: GitHub Actions automatically update the S3 bucket when new website code is pushed. Note: Avoid committing AWS credentials to source control.

## AWS Architectural Diagram
Explore the [AWS architectural diagram](/diagram/placeholder.png) to visualize the components and interactions of the project.

## Blog Post
Check out my [blog post](link-to-blog-post) to learn about the insights and lessons I gained while working on this project. The post is published on [Dev.to](https://dev.to/) (or [Hashnode](https://hashnode.com/)).

## Further Resources
For additional strategies, tools, and challenges in the cloud, refer to the AWS edition of the Cloud Resume Challenge book.

Happy exploring, and feel free to reach out if you have any questions or feedback!
