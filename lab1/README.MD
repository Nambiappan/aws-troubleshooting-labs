
Analyze VPC Flowlogs using Cloudwatch Insights

Reference : https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html

VPC Flow Logs feature enables us to capture information about the IP traffic going to and from network interfaces in the VPC. 

Flow log data can be published to the following locations: 

1. Amazon CloudWatch Logs
2. Amazon S3 
3. Amazon Kinesis Data Firehose. 

Onece the flow log is created, We can retrieve and view the flow log records in the log group, bucket, or delivery stream that we configured.

Using Flow logs , we do the below troubleshooting tasks tasks, such as:

Diagnosing overly restrictive / blocking security group rules
Monitoring the traffic that is reaching instance
Determining the direction of the traffic to and from the network interfaces
