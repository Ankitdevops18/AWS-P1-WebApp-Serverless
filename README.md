# AWS-P1-WebApp-Serverless
Create a web app Connect the web app to a serverless backend Add interactivity to your web app with an API and a database

Ref : https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/

Overview
In this, you will create a simple web application. You will first build a static web app that renders "Hello World." Then you will learn how to add functionality to the web app so the text that displays is based on a custom input you provide.
What you will accomplish
This tutorial will walk you through the steps to create the sample web application discussed above. You will:

Create a web app
Connect the web app to a serverless backend
Add interactivity to your web app with an API and a database
Prerequisites
Before starting this tutorial, you will need:

An AWS account: If you don't already have an account, follow the Setting Up Your Environment getting started guide for a quick overview.
 AWS experience
Beginner
 Minimum time to complete
35 minutes
 Cost to complete
Free Tier eligible
 Requires
AWS account with administrator-level access*
Recommended browser: The latest version of Chrome or Firefox
*Accounts created within the past 24 hours might not yet have access to the services required for this tutorial.
 Services used
AWS Amplify, AWS IAM, Amazon API Gateway, AWS Lambda, and Amazon DynamoDB 
 Last updated
April 4, 2023
Application architecture

The diagram below provides a visual representation of the services used in this tutorial and how they are connected. This application uses AWS Amplify, Amazon API Gateway, AWS Lambda, Amazon DynamoDB, and AWS Identity and Access Management (IAM).

As we go through the tutorial, we will discuss the services in detail and point to resources that will help you get up to speed with them.
Architecture diagram showing how AWS services are used in this tutorial.
Modules

This tutorial is divided into six short modules. You must complete each module in order before moving on to the next one.

Create Web App (5 minutes): Deploy static resources for your web application using the AWS Amplify Console.
Build Serverless Function (5 minutes): Build a serverless function using AWS Lambda.
Link Serverless Function to Web App (5 minutes): Deploy your serverless function with API Gateway.
Create Data Table (10 minutes): Persist data in an Amazon DynamoDB table.
Add Interactivity to Web App (5 minutes): Modify your web app to invoke your API.
Clean Up Resources (5 minutes): Clean up resources used in this tutorial.
You will be building this web application using the AWS Management Console accessible directly from your browser.
