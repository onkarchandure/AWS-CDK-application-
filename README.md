# AWS-CDK-application-
AWS CDK application in TypeScript that deploys a static website

To Create an AWS CDK application in TypeScript that deploys a static website using appropriate AWS services for hosting and content delivery follow the 
below step by step guide to achieve the goal.

1. Infrastructure as Code (IaC) Step: Install AWS CDK
Make sure you have Node.js installed, 
then install the AWS CDK globally:


2.Create a New CDK Project & Initialize 
with directory 

Create a new directory for CDK project and initialize it

mkdir static-website-cdk 
cd static-website-cdk 
cdk init app --language typescript

3.Add Dependencies / Packages Install the required AWS CDK packages / 
plugins for S3 and AWS CloudFront service

4.Define the CDK Stack Edit lib/static-website-cdk-stack.ts to define the infrastructure:

5.Create the Website Content <! -- website/index.html -->

Create a directory named website in the 
root of your CDK project and add a simple index.html file:

Deployment Instructions Step by Step guide
Bootstrap CDK Environment
bootstrapped your environment
cdk bootstrap

1.Deploy the Stack Deploy your CDK stack with the below 
command
cdk deploy

2.Verify URL / Validate the Deployment Once done with deployment, check the 
output for the URL of your static website. 
Open this URL in a web browser to verify 

3.validate that the website is accessible
