# aws-champion


𝐀 𝐬𝐢𝐦𝐩𝐥𝐢𝐟𝐢𝐞𝐝 𝐨𝐯𝐞𝐫𝐯𝐢𝐞𝐰 𝐨𝐟 𝐧𝐚𝐭𝐢𝐯𝐞 𝐀𝐖𝐒 𝐬𝐞𝐫𝐯𝐢𝐜𝐞𝐬❗

AWS offers an extended collection of services catering to different functionality and use cases. Below is a condensed summary of some of the main AWS services:

🔶 **Compute:**
Amazon EC2 (Elastic Compute Cloud): Scalable virtual servers for running any application.
AWS Lambda: Serverless computing, allowing code execution without managing servers.
Amazon Lightsail: Simplified virtual servers for basic needs.
AWS Elastic Beanstalk: Effortless deployment and scaling of web applications.

🔶 **Storage:**
Cloud storage that scales with Amazon S3.
Amazon EBS: EC2 instance block storage volumes.
Amazon Glacier: Economical, extended-duration storage.

🔶**Database:**
Managed relational database service provided by Amazon RDS.
The managed NoSQL database service is offered by Amazon DynamoDB.
Scalable, rapid data warehousing offered by Amazon Redshift.
Amazon Aurora: Managed relational database with high performance.

🔶 **Networking & Content Delivery:**
Amazon VPC: Private cloud infrastructure.
Amazon CloudFront: A worldwide network for content delivery (CDN).
AWS Direct Connect: A network connection that is dedicated

🔶**Tools for developers:**
Amazon CodeCommit: A service for managed source control.
AWS CodeBuild: Construct and evaluate code.
Automated code deployments using AWS CodeDeploy.

🔶 **Identity, Security, and Compliance:**
AWS IAM: Controls encryption keys and user access.
User identification and data synchronization using Amazon Cognito.
Amazon KMS: Handles keys for encryption.

🔶 **Machine Learning:**
Create, train, and implement ML models using Amazon SageMaker.
AWS DeepLens: A video camera with deep learning capabilities.
Amazon Rekognition: Video and image processing.

🔶 **Analytics:**
Amazon EMR: Handle massive data volumes.
Amazon Kinesis: Data streaming in real-timeAmazon Glue: Get data ready and loaded for analysis.

🔶**Integration of Applications:**
Coordinate dispersed applications using AWS Step Functions.
Push, email, SMS, and pub/sub notifications using Amazon SNS.
Amazon SQS: Message queue management.


Server Less
	https://aws.amazon.com/serverless/

AWS Lambda
	https://docs.aws.amazon.com/lambda/latest/dg/welcome.html

UseCase
	https://aws.amazon.com/lambda/

AWS Lambda Concept 
	https://docs.aws.amazon.com/lambda/latest/dg/gettingstarted-concepts.html	

For making batch push in SQS queue
	https://www.baeldung.com/aws-queues-java

	Code Github
		https://github.com/awsdocs/aws-doc-sdk-examples/blob/master/java/example_code/sqs/src/main/java/aws/example/sqs/SendReceiveMessages.java

	limitations
		https://stackoverflow.com/questions/40489815/checking-size-of-sqs-message-batches
		https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-limits.html#limits-messages

		10 message limit
		https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-batch-api-actions.html
