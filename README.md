# CT08SVF-Cloud-Computing-TASK2

COMPANY: CODTECH IT SOLUTIONS

NAME: ARYA RANI

INTERN ID: CT08SVF

DOMAIN: CLOUD COMPUTING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

This repository contains all files and documentation related to the completion of the 1st task of the cloud computing internship at CODTECH IT SOLUTIONS PVT. LTD., submitted by ARYA RANI (Intern ID: CT08SVF).

DESCRIPTION OF 2nd TASK

Steps for AWS CloudWatch
1. Log in to the AWS Management Console
  •	Go to the AWS Management Console.
  •	Log in with your credentials.

2. Launch an EC2 Instance (if you don’t have one)
  1.	Go to the EC2 service.
  2.	Click Launch Instance.
  3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux 2).
  4.	Select an instance type (e.g., t2.micro).
  5.	Configure instance details (leave defaults if unsure).
  6.	Add storage (default is usually sufficient).
  7.	Add tags (optional).
  8.	Configure security groups to allow SSH (port 22) and HTTP (port 80) traffic.
  9.	Launch the instance and download the key pair.

3. Enable CloudWatch Monitoring for the EC2 Instance
  1.	Go to the EC2 Dashboard.
  2.	Select your instance.
  3.	Click Actions > Monitor and troubleshoot > Manage CloudWatch monitoring.
  4.	Enable Detailed Monitoring (optional but recommended for more granular metrics).
  5.	Click Save.

4. Create a CloudWatch Dashboard
  1.	Go to the CloudWatch service.
  2.	In the left sidebar, click Dashboards.
  3.	Click Create dashboard.
  4.	Enter a dashboard name (e.g., Codtech-Monitoring-Dashboard).
  5.	Click Create dashboard.
  6.	Add widgets to the dashboard:
      o	Click Add widget.
      o	Choose a widget type (e.g., Line, Stacked Area, Number).
      o	Select the metric you want to monitor (e.g., CPUUtilization, NetworkIn, NetworkOut).
      o	Configure the widget and click Create widget.
  7.	Repeat to add more widgets for other metrics (e.g., Memory Usage, Disk I/O).

5. Create CloudWatch Alarms
  1.	In the CloudWatch console, go to Alarms in the left sidebar.
  2.	Click Create alarm.
  3.	Click Select metric.
  4.	Choose a metric (e.g., EC2 > Per-Instance Metrics > CPUUtilization).
  5.	Set the conditions for the alarm:
       o	Threshold type: Static.
       o	Define the threshold (e.g., CPUUtilization > 80%).
       o	Set the alarm to trigger when the threshold is breached for 1 consecutive period.
  6.	Configure actions:
       o	Send a notification to an SNS topic (create an SNS topic if you don’t have one).
       o	Add an email address to the SNS topic to receive notifications.
  7.	Enter an alarm name (e.g., High-CPU-Utilization-Alarm).
  8.	Click Create alarm.

6. Verify Alarms and Dashboard
  1.	Go to the CloudWatch Dashboard to view the metrics in real-time.
  2.	Simulate high CPU usage on your EC2 instance (e.g., run a stress test).
  3.	Check if the alarm triggers and you receive an email notification.


**Output:**
![Image](https://github.com/user-attachments/assets/4ce45d4e-825a-4341-9564-4570f8980f38)

![Image](https://github.com/user-attachments/assets/b05c31d8-0965-48ef-a879-ffb7e2414e9e)

![Image](https://github.com/user-attachments/assets/4335a661-67b1-47de-b27c-be0c1a0aa92a)

![Image](https://github.com/user-attachments/assets/7706ee7c-cca2-457a-811e-28fd0b3e935d)

![Image](https://github.com/user-attachments/assets/4f08662f-4872-418c-ae4e-e174e674c8d9)

![Image](https://github.com/user-attachments/assets/70413408-b643-427f-b4f5-9da3bee89fd6)

![Image](https://github.com/user-attachments/assets/d1a2b66c-71a8-4417-a4ea-a710adbae4d9)

  




Intern ID: CT08SVF Cloud Computing Task2
