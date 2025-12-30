# Check-AWS-Resources-in-Trusted-Advisor
📌 Introduction  AWS Trusted Advisor is an automated cloud service provided by Amazon Web Services (AWS). It offers real-time guidance and recommendations to help customers optimize their AWS infrastructure by following AWS best practices.
Trusted Advisor continuously analyzes your AWS environment and provides actionable insights to improve:

🔐 Security

⚡ Performance

💰 Cost Optimization

🛠 Fault Tolerance

📈 Service Limits

This project demonstrates how to use AWS Trusted Advisor to identify security risks such as unrestricted security groups and public S3 buckets, and validate them through the Trusted Advisor dashboard.

--------------------------------------------------------------------------------------------------------

🧠 What is AWS Trusted Advisor?

AWS Trusted Advisor:

Analyzes AWS resources and configurations in real time

Compares resources against AWS best practices and industry standards

Identifies idle resources, underutilized instances, and security vulnerabilities

Sends proactive alerts and notifications

Provides personalized recommendations based on your AWS setup

Integrates with other AWS services and third-party tools

Is accessible via the AWS Management Console

Is available at no additional cost with an Enterprise-level AWS Support Plan

--------------------------------------------------------------------------------------------------------------

📜 S3 Bucket Policy


Replace replace-this-string-with-your-bucket-arn with your actual bucket ARN.
{
  "Id": "Policy1",
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Stmt1",
      "Effect": "Allow",
      "Principal": "*",
      "Action": [
      
        "s3:GetObject"
],
      "Resource": "replace-this-string-with-your-bucket-arn/*"
    }
  ]
}






