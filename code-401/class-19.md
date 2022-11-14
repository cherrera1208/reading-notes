Readings: AWS: Events
=====================

Reading
-------

[AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

1. What is the difference between SQS and SNS?
    * SNS (simple notification service) is a distributed __publish-subscribe__ service, and SQS (simple queue service) is a distributed __queueing__ service
2. What are some use cases for both SNS and SQS?
    * Choose SNS if:

      * You would like to be able to publish and consume batches of messages.
      * You would like to allow same message to be processed in multiple ways.
      * Multiple subscribers are needed.

    * Choose SQS if:

      * You need a simple queue with no particular additional requirements.
      * Decoupling two applications and allowing parallel asynchronous processing.
      * Only one subscriber is needed.

[AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

1. Describe how to use SQS and SNS in a “fan out” pattern.
    * publishing messages can be delivered to many subscribers
2. Explain how “push notifications” work, using SNS.
    * using the fan out approach, SNS alerts the user by some other service like an email or lambada

[SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

1. How might a large scale, distributed application make use of a Queue system like SQS?
    * AWS SQS is fast, less than 20ms response times from EC2. And, APIs can be batched in queue potentially reducing costs per-request

Bookmark and Review
-------------------

[SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)

[SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)
