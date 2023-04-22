
# Lab1: Analyze VPC Flowlogs using Cloudwatch Insights

Reference : https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html

VPC Flow Logs feature enables us to capture information about the IP traffic going to and from network interfaces in the VPC. 

Flow log data can be published to the following locations: 

1. Amazon CloudWatch Logs
2. Amazon S3 
3. Amazon Kinesis Data Firehose. 

Onece the flow log is created, We can retrieve and view the flow log records in the log group, bucket, or delivery stream that we configured.

Using Flow logs , we can do the below troubleshooting tasks tasks:

1. Diagnosing overly restrictive / blocking security group rules
2. Monitoring the traffic that is reaching instance
3. Determining the direction of the traffic to and from the network interfaces

# Flow logs basics

We can create a flow log for a VPC, a subnet, or a network interface. If you create a flow log for a subnet or VPC, each network interface in that subnet or VPC is monitored.

Flow log data for a monitored network interface is recorded as flow log records, which are log events consisting of fields that describe the traffic flow.

![image](/lab1/flow-logs-diagram-cw.png) ![image](/lab1/vpc-flow-logs.png)

# Example

![image](/lab1/sample-flowlogs.png)

# Lab Instructions

In this lab, we can setup the VPC , Subnets  , SG and EC2 instances and carry out the steps:

Use the Cloudformation Template uploaded in this respository to setup the mentioned resources.

![image](/lab1/cloudformation-vpc.png)




