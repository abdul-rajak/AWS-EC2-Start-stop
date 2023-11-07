
# AWS-EC2-Start-stop
Automate EC2 instance start and stop using Lambda and EventBridge.


# Procedure
To automate the process of stopping and starting EC2 instances periodically using AWS Lambda, follow these steps:

1. Start with a custom Identity and Access Management (IAM) policy and IAM role tailored to your Lambda function's needs.

2. Create Lambda functions.

3. Verify the functionality of your Lambda functions to ensure they perform as expected.

4. Now setup EventBridge schedules that trigger your Lambda function on a predefined timetable.
