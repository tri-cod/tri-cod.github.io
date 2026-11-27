---
title: "Week 6 Worklog"
date: 2026-10-26
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Objectives:

- Explore the basic concepts and functionality of Elastic Load Balancing (ELB) in AWS.
- Understand how Amazon EC2 Auto Scaling helps improve application availability and handle changing workloads.
- Gain practical experience in setting up an Application Load Balancer and an Auto Scaling Group.
- Learn how to design an AWS architecture that supports high availability and scalability.

### Tasks to be carried out this week:

| Day | Task                                                                                                                                                                                                                                             | Start Date | Completion Date | Reference Material                                                      |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------------------------------------- |
| 2   | - Review the Amazon RDS knowledge gained during the previous week.<br>- Explore the fundamentals of Elastic Load Balancing (ELB) and the different load balancer types provided by AWS.                                                          | 26/10/2026 | 26/10/2026      | [Introduction to ELB](https://000058.awsstudygroup.com/en/1-introduce/) |
| 3   | - Understand the operating principles of an Application Load Balancer (ALB).<br>- Practice setting up a Target Group and defining Health Checks for EC2 instances.                                                                               | 27/10/2026 | 27/10/2026      | [ELB Prerequisites](https://000058.awsstudygroup.com/en/2-prerequiste/) |
| 4   | - Set up and deploy an Application Load Balancer.<br>- Add multiple EC2 instances to the Target Group.<br>- Test how incoming requests are distributed among the registered EC2 instances.                                                       | 28/10/2026 | 28/10/2026      | [Creating an ALB](https://000058.awsstudygroup.com/en/3-createalb/)     |
| 5   | - Explore the core concepts of Amazon EC2 Auto Scaling.<br>- Configure a Launch Template and create an Auto Scaling Group.<br>- Set up scaling policies using CPU utilization as the scaling metric.                                             | 29/10/2026 | 29/10/2026      | [Creating an ASG](https://000058.awsstudygroup.com/en/4-createasg/)     |
| 6   | - Check the functionality of the Load Balancer and Auto Scaling Group.<br>- Generate simulated application traffic to observe Scale Out and Scale In activities.<br>- Review the topics covered and finish the practical exercises for the week. | 30/10/2026 | 30/10/2026      | [ELB and ASG Cleanup](https://000058.awsstudygroup.com/en/5-cleanup/)   |

### Week 6 Achievements:

- Understood the main purpose of Elastic Load Balancing (ELB) and how it distributes incoming application traffic among multiple EC2 instances.
- Became familiar with the key components of Elastic Load Balancing, such as:
  - Application Load Balancer (ALB)
  - Target Group
  - Listener
  - Health Check
- Successfully deployed an Application Load Balancer and configured a Target Group containing multiple EC2 instances.
- Learned how Health Checks evaluate the availability of EC2 instances and how to monitor their health status through the Load Balancer.
- Gained an understanding of Amazon EC2 Auto Scaling and how it automatically adjusts the number of running EC2 instances according to application workload.
- Successfully created and configured the following resources:
  - Launch Template
  - Auto Scaling Group
  - Scaling Policy
- Simulated changes in application workload and observed Scale Out and Scale In activities, helping clarify how AWS responds to changing demand while maintaining application performance and availability.
- Finished the hands-on exercises covering Elastic Load Balancing and Auto Scaling in the Cloud Journey learning path.
- Established a foundation for designing AWS applications with better scalability, high availability, and fault tolerance.
