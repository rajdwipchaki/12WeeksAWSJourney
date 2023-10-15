# Connect to an EC2 Linux Instance
![There are multiple ways you can connect to an EC2 linux instance](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-connect-to-instance.jpg)

1. In the EC2 instance console, select the instance you want to connect to, and then click the Connect button.
![alt text](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-connect.jpg)


- [Option 1: Connect to your Linux instance using EC2 Instance Connect](#inscon)
- [Option 2: Connect to your Linux instance using SSH Client](#connectec2)(#ssh)
- [Option 3: Connect to your Linux instance using Session Manager](#ssm)

## <a name="inscon">Option 1: Connect to your Linux instance using EC2 Instance Connect</a>
1. Under the EC2 Instance Connect tab, click in the Connect option.
![alt text](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-connect-to-instance.jpg)
2. After connecting continue query to yes, You can check the result as below.
![alt text](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-instance-connect.jpg)

## <a name="ssh">Option 2: Connect to your Linux instance using SSH Client</a>
1. In the Connect to instance page, select SSH client. Follow the instructions below.
![alt text](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-ssh-client.jpg)
2. After connecting continue query to yes, You can check the result as below.
![alt text](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-ssh-connect.jpg)

## <a name="ssh">Option 3: Connect to your Linux instance using Session Manager</a>
1. Select the instance under Instances section in the navigation pane.
2. Choose Instance state, Terminate instance.
3. Choose Terminate when prompted for confirmation.
