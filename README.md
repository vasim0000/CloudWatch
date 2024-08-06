# CloudWatch
As part of my DevOps learning journey, I worked with CloudWatch, a service provided by AWS that collects, monitors, and analyzes metrics, logs, and events from your AWS resources.

I used Cloudwatch to monitor the CPU utilization metric of an EC2 instance and created an alarm to notify the end user using SNS (Simple Notification Service).

Steps I took:
 -> Set Up CloudWatch Alarms: To monitor the CPU utilization metric of my EC2 instance.
 
 -> Create an Alarm: Configured the alarm to trigger if the CPU utilization exceeds 60%.
 
 ->Integrate with SNS: Set up an SNS topic to send a notification whenever the alarm is triggered.

explanation of images attached below:

1-> Shows different metrics of an EC2 instance.

2,3,4,5-> Creating alarm on the CPU utilization metric of instance.

6-> Using Stress to create dummy processes to increase the load on the CPU.

7-> Shows the created alarm on the metric.

![Screenshot (187)](https://github.com/user-attachments/assets/5338849c-a633-4a3c-8c12-661dc77f3c7e)

![Screenshot (182)](https://github.com/user-attachments/assets/eac2f21e-e81c-4f8d-8de2-18c7cb9ab0ad)
   
![Screenshot (183)](https://github.com/user-attachments/assets/1dbc9889-bae4-442a-ba0d-b486db592312)

![Screenshot (184)](https://github.com/user-attachments/assets/9304869a-1bd6-4dac-9e6e-db48f1e426a4)

![Screenshot (185)](https://github.com/user-attachments/assets/d9226f34-549c-4551-9383-9e1664c45985)

![Screenshot (186)](https://github.com/user-attachments/assets/26ca1a75-5ff3-4147-8855-771f12afaa5f)

![Screenshot (188)](https://github.com/user-attachments/assets/75ff3aef-6a9f-498a-8346-df74aef98272)






