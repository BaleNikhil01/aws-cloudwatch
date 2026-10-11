Configured Cloud Watch to monitor cpu utilization metric on an EC2 instance by sending alerts through SNS topics. 
The program when run spikes the cpu utilization of the instance which in turn sends notification via mail. 


<img width="600" height="300" alt="Screenshot From 2026-06-20 01-25-34" src="https://github.com/user-attachments/assets/215da9e7-c80e-4e46-b1c2-e052520f06d7" />

Configured an Amazon CloudWatch CPU utilization alarm with a threshold of 30% for 1 minute.


<img width="700" height="300" alt="Screenshot From 2026-06-20 01-25-07" src="https://github.com/user-attachments/assets/19d63034-7755-423e-aac2-b521a70c8e83" />

 Integration with Amazon SNS email notifications to receive alerts when the alarm enters the ALARM state.

 <img width="300" height="500" alt="Screenshot_2026-10-11-11-58-02-04_e307a3f9df9f380ebaf106e1dc980bb6" src="https://github.com/user-attachments/assets/4448a02d-683a-42fc-a13d-71125e8699f5" />

 Email notification recieved when cpu utilization crossed threshold of 30%


 Cloud Watch can be used in:
--> Auto Scaling 
--> Log Analysis and Troubleshooting
--> Cost Monitoring
--> Resource Monitoring
--> Proactive Monitoring 
