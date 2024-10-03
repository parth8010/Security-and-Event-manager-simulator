## Project Objective: 
The focus of this project is on Network Traffic Analysis, which involves monitoring and analyzing data packets flowing through a network to detect malicious activities or vulnerabilities.


## Team Member:
Parth Patil (Solo project)


## Project Summary: 
This project demonstrates the deployment of a Security Information and Event Management (SIEM) solution using Azure services, along with monitoring of security events such as RDP attacks. The setup also incorporates a threat intelligence feed to detect and respond to Indicators of Compromise (IoCs) in real-time.


## Azure Services Used:
List of Azure Services:

-  Azure Virtual Machine (VM)
-  Microsoft Sentinel (SIEM)
-  Log Analytics Workspace
-  Azure Monitor Agent (AMA)


 ## Cost Management:
Resource Costs:
Initial setup was covered by Azure’s free trial credits, with minimal additional costs (e.g., $0.20/hour for the VM).


## Cost-Optimization: 
Used Azure’s free tier and shutdown unused resources when not testing to minimize charges.


## Deployment Steps:
Create an Azure account and start a free trial with $200 credits.
![image](https://github.com/user-attachments/assets/10702ba5-9cb6-450e-ac5d-1cce1c19eebe)

Deploy a Virtual Machine (VM) using a pre-configured Windows server image.
![image](https://github.com/user-attachments/assets/4c0b98a8-e959-4216-949d-b8407c1a20ce)

![image](https://github.com/user-attachments/assets/5238ee8c-6312-4300-9085-05dd0ac08ce0)

![image](https://github.com/user-attachments/assets/1e14eff3-e2bf-4ff9-bb9c-5fda41296cf5)

Deploy Microsoft Sentinel, attaching it to the Log Analytics Workspace.
![image](https://github.com/user-attachments/assets/c207855b-fbf7-4b06-bb38-59686496e126)

Set up a Log Analytics Workspace to store event logs.
![image](https://github.com/user-attachments/assets/4dc1052c-b42d-4d8f-9fbd-74f411575fb2)

![image](https://github.com/user-attachments/assets/f2780fa6-ba5e-4c1d-970c-a6bfd8ac26f4)

Install the Azure Monitor Agent (AMA) to collect security events.
![image](https://github.com/user-attachments/assets/5ae317aa-88f3-47d7-ab7b-9117117ce875)

![image](https://github.com/user-attachments/assets/c17acade-f6f3-4d41-8dac-003586f8637f)

Deploy Microsoft Sentinel, attaching it to the Log Analytics Workspace.
![image](https://github.com/user-attachments/assets/1009516d-5232-4511-9c27-b37a01378bda)

Create an alert rule to detect successful RDP login attempts.

![image](https://github.com/user-attachments/assets/83b11b39-2ad0-484b-84e8-3951d62b4725)

![image](https://github.com/user-attachments/assets/5baadcb3-10de-4bde-a721-936ff2a94f69)

![image](https://github.com/user-attachments/assets/3ea775c2-1c50-405c-9d6c-690ab649635e)


## Now monitor the logs based on threat analysis

![image](https://github.com/user-attachments/assets/e8e03a49-9581-4d7d-9903-1044feef0d35)

![image](https://github.com/user-attachments/assets/ff80acef-fd62-4597-b7ac-87d0e991f85e)

## Conclusion
Key Learnings: Learned how to deploy and configure a basic SIEM solution using Azure Sentinel, gained experience with security event monitoring, and configured data ingestion pipelines.

Future Improvements: The project could be enhanced by adding automated responses to detected threats, expanding the threat intelligence feed, and integrating additional VMs for multi-device monitoring.








