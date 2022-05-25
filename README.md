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

> Finish the Create topic. The topic details will display, or you can select the newly created topic from the Topics dashboard to create a subscription next.

![image](https://user-images.githubusercontent.com/40290711/170362663-752f9dc8-cce2-4e01-a957-14194362c419.png)

### STEP 2: Subscribe to a Topic
> While you are viewing the details of the newly created topic, start the Create subscription wizard.

![image](https://user-images.githubusercontent.com/40290711/170363593-cf67cf3c-a0b6-4a0d-a733-af642a7d767e.png)

> Use the following details:
>         Field                     Value
>          Protocol                  Amazon SQS
>          Endpoint                  Amazon SQS ARN

![image](https://user-images.githubusercontent.com/40290711/170366759-79a5c033-0013-462e-85ec-49ac2cb4b625.png)

![image](https://user-images.githubusercontent.com/40290711/170368970-51ab7c2f-5813-43e8-8630-6b2773df849a.png)

> In your web browser, a subscription confirmation screen appears

![image](https://user-images.githubusercontent.com/40290711/170369176-4d8c773b-b5de-468b-aa6a-ee8ae8ea85f9.png)

### STEP 3: Publish Message to a Topic
> Go back to the Topics service.
> Select the topic you created earlier and Publish a message with the following details:

![image](https://user-images.githubusercontent.com/40290711/170370467-23600863-9246-4b9c-b533-5398040d24f8.png)

![image](https://user-images.githubusercontent.com/40290711/170371176-5a3838ce-a31b-4d63-bdde-211d99683c0a.png)

![image](https://user-images.githubusercontent.com/40290711/170371310-ce22ff5c-1753-499f-885b-d3b6ef3af916.png)

![image](https://user-images.githubusercontent.com/40290711/170371410-204b496f-c62a-4316-8c24-d0a5b2b40b5f.png)



