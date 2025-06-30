# EC2 Web Server with CloudWatch Monitoring

This project creates an EC2 instance with a web server (Apache) and sets up CloudWatch for monitoring CPU and logging system activity. IAM roles are used for secure communication between services without hardcoding credentials.

## Skills Demonstrated
- EC2 instance setup and SSH access
- IAM Role creation and attachment
- Apache web server installation
- CloudWatch Agent installation
- Log stream configuration
- Metrics dashboard creation

## Commands Used
- chmod 400 ec2key.pem
- ssh -i ec2key.pem ec2-user@IP_ADDRESS
- yum install httpd
- sudo systemctl start httpd
- sudo systemctl enable httpd

## Demo

![CloudWatch Dashboard](screenshots/cloudwatch-dashboard.png)
