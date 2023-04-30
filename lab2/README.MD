
# Lab2: Use VPC Reachability Analyzer to analyze traffic reachability from a Source Resource to destination resource in our VPC

Reference : https://docs.aws.amazon.com/vpc/latest/reachability/getting-started.html

We use Reachability Analyzer to determine whether a destination resource in our virtual private cloud (VPC) is reachable from a source resource. 

To get started, we specify a source and a destination. For example, we can run a reachability analysis between 

1. Two network interfaces 
(or)
2. Between a network interface and a gateway. 

If there is a reachable path between the source and destination, Reachability Analyzer displays the details. 
Otherwise, Reachability Analyzer identifies the blocking component.

# Tasks

Step 1: Create and analyze a path

Step 2: View the results of the path analysis

Step 3: Change the network configuration and analyze the path

Step 4: Delete the path


# Example

![image](/lab2/VPCReachabilityAnalyzer.png)

# Lab Instructions

In this lab, we can setup the VPC , Subnets  , SG and EC2 instances and carry out the steps:

Use the Cloudformation Template uploaded in this respository to setup the mentioned resources.

Once you provision the required stack, try to access the Tomcat Web Server running on EC2 instance using EC2 Public IP address.

Troubleshoot and fix the root cause for the access issue.

![image](/lab2/cloudformation-vpc.png)




