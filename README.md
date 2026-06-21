# AWS Monitoring Lab

Hands-on AWS monitoring and alerting project using EC2, CloudWatch, SNS and IAM.

## Project Overview

This project demonstrates the implementation of a monitoring and alerting solution in AWS.

The objective is to monitor EC2 instances, create CloudWatch alarms and send automated notifications through Amazon SNS whenever predefined thresholds are exceeded.

## Architecture

```text
EC2 Instance
     │
     ▼
CloudWatch Metrics
     │
     ▼
CloudWatch Alarm
     │
     ▼
SNS Topic
     │
     ▼
Email Notification
```

## AWS Services Used

* Amazon EC2
* Amazon CloudWatch
* Amazon SNS
* AWS IAM

## Monitoring Scenarios

### CPU Utilization Alert

* Metric: CPUUtilization
* Threshold: Above 70%
* Evaluation Period: 5 minutes
* Action: Send SNS notification

### Instance Status Check

* Metric: StatusCheckFailed
* Threshold: Greater than 0
* Action: Send SNS notification

## Evidence

Screenshots of the implementation will be stored in the `screenshots` folder.

## Learning Outcomes

* CloudWatch Metrics
* CloudWatch Alarms
* SNS Notifications
* IAM Permissions
* AWS Monitoring Best Practices

## Future Improvements

* Auto Scaling integration
* CloudWatch Dashboard
* Lambda notifications
* Multi-instance monitoring

## Author

Gabriel Paes Cardenette

AWS Certified Cloud Practitioner (CLF-C02)
