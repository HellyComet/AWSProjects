# AWSProjects
I am creating different AWS Projects to investigate and research various AWS services

Power of Math
https://dev.d2c3mks7ohuple.amplifyapp.com/

I have used different AWS services to create this application as mentioned below:

⏩AWS Amplify: I hosted my Front-end HTML and Javascript files here. AWS Amplify lets you host your Full-Stack web application.

⏩API Gateway: API Gateway is a fully managed service that enables developers to create, publish, maintain, monitor and secure APIs.
I created a REST API with POST method that communicates with Lambda function to insert information into the DynamoDB table. I enabled Cross-Origin Resource sharing (CORS).

⏩AWS Lambda: AWS Lambda helps you run serverless event-driven code without provisioning or managing servers. I used Python to code Lambda function. I created the Lambda function to first import JSON utility and AWS SDK package (boto3 for Python), create a DynamoDB object and insert results into the DynamoDB table

⏩DynamoDB: It is a serverless, fully managed NoSQL key-value database. 
I created a table object and invoked it through the Lambda function.

⏩Identity and Access Management(IAM): This is a very important service as it helps us define who and what can access services and resources in AWS. Here I created inline policy for Lambda function in JSON format and gave it the permissions to Put, Delete, Scan ,Query, Get and Update items in the DynamoDB table.
