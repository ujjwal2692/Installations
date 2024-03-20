********************************************
## MONITORING MEMORY UTILIZATION IN CLOUDWATCH
********************************************


## Create parameter in SSM with name: /alarm/AWS-CWAgentLinConfig

## User Data section

## Check if EC2 Instance has CWAgent Installed or not.
sudo /opt/aws/amazon-cloudwatch-agent/bin/amazon-cloudwatch-agent-ctl -m ec2 -a status
