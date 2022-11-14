Readings: AWS: API, Dynamo and Lambda
=====================================

Reading
-------

[AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)

1. What is Amazon API Gateway?
    * a fully managed service that makes it easy for devs to create, publish, maintain, monitor, and secure APIs at any scale
2. Why is Amazon API Gateway an important part of the Serverless ecosystem?
    * devs can create RESTful APIs and WebSocket APIs that enable real-time two-way communication apps.
3. How does API Gateway integrate with other AWS services?
    * gateway supports containerized and serverless workloads from other services like buckets and lambdas

[AWS API Gateway](https://aws.amazon.com/api-gateway/)

1. What are the some benefits of using Amazon API Gateway?
    * Scale and support with other AWS services; easy monitoring and controls from the console
2. What two API types might you choose from?
    * RESTful and WebSocket

[AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)

1. What is DynamoDB?
    * a hosted NoSQL DB offered by AWS
2. Under what circumstances would you recommend DynamoDB over MongoDB?
    * first, is the rest of your application in AWS? Then use Dynamo. Second, dynamo auto-scales, is stateless, and authenticated through the AWS IAM dashboard

[AWS DynamoDB](https://aws.amazon.com/dynamodb/)

1. Explain to a non-technical friend how DynamoDB works.
    * is a database associated with AWS. AWS takes care of the auth and state so the dev can focus on building other aspects of their app

[Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

1. What is Dynamoose?
    * is a modeling tool inspired by mongoose
2. What are some key features of Dynamoose?
    * dynamoDB Single Table Design Support, ability to transform data before saving or retrieving items, and strict data modeling (validation, required attributes, and more)
