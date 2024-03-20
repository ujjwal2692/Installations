********************************************
## MONITORING MEMORY UTILIZATION IN CLOUDWATCH
********************************************


1. Create parameter in SSM with name: /alarm/AWS-CWAgentLinConfig

2. User Data section

3. Check if EC2 Instance has CWAgent Installed or not.
sudo /opt/aws/amazon-cloudwatch-agent/bin/amazon-cloudwatch-agent-ctl -m ec2 -a status
