# Topic: AWS-SNS

### Overview:
> Amazon Simple Notification Service (Amazon SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication.

> The A2A pub/sub functionality provides topics for high-throughput, push-based, many-to-many messaging between distributed systems, microservices, and event-driven serverless applications. Using Amazon SNS topics, your publisher systems can fanout messages to a large number of subscriber systems, including Amazon SQS queues, AWS Lambda functions, HTTPS endpoints, and Amazon Kinesis Data Firehose, for parallel processing. The A2P functionality enables you to send messages to users at scale via SMS, mobile push, and email.

### Prerequisites
> 1. AWS Account

### Tasks:
> 1. Create a topic
> 2. Subscribe to a topic
> 3. Publish a message to a topic


### STEP 1: Create a Topic
> From the AWS Management Console page, select the SNS service:

![image](https://user-images.githubusercontent.com/40290711/170359592-dc876bd3-9ea1-4365-ac6d-5b0d49fc6cd7.png)

> On the left-hand navigation pane, click on the ***Topics*** service, and start the ***Create topic*** wizard.

![image](https://user-images.githubusercontent.com/40290711/170360438-39456545-6f0b-4bf8-909d-e7117ac025fd.png)

> In the Details section, enter a topic name of your choice

![image](https://user-images.githubusercontent.com/40290711/170361932-51a7578c-f87a-4fd1-a498-83283686d000.png)

> In the Access policy - optional section, use the following configuration to create the topic:

![image](https://user-images.githubusercontent.com/40290711/170362242-e906f61e-e773-4fb1-8bd4-eb774ead7966.png)

![image](https://user-images.githubusercontent.com/40290711/170362349-c03dabf0-c980-45e6-a7cb-53405ebc12c9.png)

