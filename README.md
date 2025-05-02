# guvi-zenclass-aws-task1
aws creation of windows VM 

Step 1: Launch a Windows EC2 Instance
Log in to AWS Console:
Go to https://console.aws.amazon.com/

Navigate to EC2 Dashboard:
Services → EC2 → Instances → Launch instance

Configure the instance:

Name: MyWindowsVM

AMI: Choose a Windows AMI like:

Microsoft Windows Datacenter 2022 Base

Instance Type: t2.micro (Free tier eligible)

Key Pair: Create/download a new key pair (.pem)

Networking:

Allow RDP (port 3389) in the Security Group

Launch the instance.
![aws VM creation](https://github.com/ranju386/guvi-zenclass-aws-task1/blob/main/guvi-aws-a-task1.jpg)

 Step 2: Connect via RDP
Wait for the instance to show Running and get the Public IPv4 address.

Click Connect → RDP Client.

Download remote desktop file and note the username (usually Administrator).

Click Get Password → Upload your .pem file to decrypt the password.

Open the .rdp file and log in using:

Username: Administrator

Password: (decrypted one)

![VM creation](https://github.com/ranju386/guvi-zenclass-aws-task1/blob/main/guvi-aws-b-task1.jpg)

Step 3: Open CMD and Check System Info
After logging in, press Windows + R, type cmd, and press Enter.

In the Command Prompt, type: systeminfo
![VM creation](https://github.com/ranju386/guvi-zenclass-aws-task1/blob/main/guvi-aws-c-task1.jpg)
