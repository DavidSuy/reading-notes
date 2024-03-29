# Readings: AWS: Cloud Servers

## Reading

### [AWS EC2](https://aws.amazon.com/ec2/)

1. What is an EC2 Instance?

An Amazon EC2 instance is a virtual server in Amazon's Elastic Compute Cloud (EC2) for running applications on the Amazon Web Services (AWS) infrastructure.

2. Name 2 use cases for EC2.

- Hosting environments. One of the foremost uses of EC2 is for hosting a variety of applications, software and \* websites on the cloud. ...
- Development and test environments. ...
- Backup and disaster recovery. ...
- Banking and financial sector. ...
- Marketing and advertisement. ...
- High performance computing.

3. Provide 1 reason to use ECS instead of Heroku.

One of the biggest advantages is the flexibility to change underlying EC2 instances. As the traffic or demand increases, we can easily change EC2 instances without any issues.

[EC2 For Humans](https://www.youtube.com/watch?v=lZMkgOMYYIg)

1. Where can we find EC2 on the AWS Console?

   With the EC2 serial console, you have access to your Amazon EC2 instance's serial port, which you can use to troubleshoot boot, network configuration, and other issues. The serial console does not require your instance to have any networking capabilities.

2. Explain the general difference between T2 Micro and XL.

   T2 instances are Burstable Performance Instances that provide a baseline level of CPU performance with the ability to burst above the baseline. The baseline ...

3. Explain a “Compute Cycle” to a non-technical friend.

   A machine cycle consists of the steps that a computer's processor executes whenever it receives a machine language instruction. It is the most basic CPU operation, and modern CPUs are able to perform millions of machine cycles per second. The cycle consists of three standard steps: fetch, decode and execute.

[Elastic Beanstalk](https://www.youtube.com/watch?v=SrwxAScdyT0)

1. What is Elastic Beanstalk?
   What is Elastic Beanstalk and how it works?
   Image result for What is Elastic Beanstalk?

   Elastic Beanstalk reduces management complexity without restricting choice or control. You simply upload your application, and Elastic Beanstalk automatically handles the details of capacity provisioning, load balancing, scaling, and application health monitoring.

2. Describe the relationship between EC2 and Elastic Beanstalk.

   Elastic Beanstalk is one layer of abstraction away from the EC2 layer. Elastic Beanstalk will setup an "environment" for you that can contain a number of EC2 instances, an optional database, as well as a few other AWS components such as a Elastic Load Balancer, Auto-Scaling Group, Security Group

3. Name some benefits of using Elastic Beanstalk.

   Elastic Beanstalk's main benefits include timesaving server configuration, powerful customization, and a cost-effective price point. Elastic Beanstalk automates the setup, configuration, and provisioning of other AWS services like EC2, RDS, and Elastic Load Balancing to create a web service.

## Bookmark and Review

[Virtual Machines](https://www.youtube.com/watch?v=yIVXjl4SwVo)

[VMS and the Cloud](https://www.youtube.com/watch?v=l0DfHUWMjsU)
