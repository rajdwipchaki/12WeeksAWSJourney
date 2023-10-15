# Connect to an EC2 Linux Instance
There are multiple ways you can connect to an EC2 linux instance.
![alt text](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-connect-to-instance.JPG)

1. In the EC2 instance console, select the instance you want to connect to, and then click the Connect button.
![alt text](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-connect.JPG)


- [Option 1: Connect to your Linux instance using EC2 Instance Connect](#inscon)
- [Option 2: Connect to your Linux instance using SSH Client](#connectec2)(#ssh)
- [Option 3: Connect to your Linux instance using Session Manager](#ssm)

## <a name="inscon">Option 1: Connect to your Linux instance using EC2 Instance Connect</a>
1. Under the EC2 Instance Connect tab, click in the Connect option.
![alt text](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-connect-to-instance.JPG)
2. After connecting successfully, you can check the result as below.
![alt text](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-instance-connect.JPG)

## <a name="ssh">Option 2: Connect to your Linux instance using SSH Client</a>
1. In the Connect to instance page, select SSH client. Follow the instructions below.
![alt text](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-ssh-client.JPG)
2. After connecting continue query to yes, You can check the result as below.
![alt text](https://github.com/rajdwipchaki/12WeeksAWSJourney/blob/main/wk1/ec2/images/ec2-ssh-connect.JPG)

## <a name="ssh">Option 3: Connect to your Linux instance using Session Manager</a>
1. Firstly, create a service role for EC2 to perform AWS system manager service core functionalities (you can do this by attaching 'AmazonSSMManagedInstanceCore' managed policy).
2. Once the role is created, modify the IAM role for the instance by selecting the role that you have created.
3. In the Connect to instance page, select Session Manager. Follow the instructions shown in the screen (wait for a while until the EC2 instance is completely setup for use with Session Manager)
