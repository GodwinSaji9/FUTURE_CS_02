# SIEM Log Analysis & Incident Response

# Task Overview
This project simulates the real-world responsibilities of a Security Operations Center (SOC) Analyst. The objective of this task is to gain hands-on experience with a
Security Information and Event Management (SIEM) platform by ingesting, analyzing, and responding to security events using simulated log data.

The task focuses on detecting suspicious activities, classifying security alerts, and drafting a structured incident response report, mirroring how SOC teams operate in enterprise environments.

# Objective
•	Set up and use a SIEM tool to monitor security logs
•	Identify malicious activities such as malware infections and authentication abuse
•	Classify alerts based on severity and impact
•	Perform basic incident investigation and correlation
•	Document findings in a professional incident response report

# Tools & Technologies Used
•	Elastic Stack (ELK)
• Elasticsearch – Log storage and search
•	Logstash – Log ingestion and parsing
•	Kibana – Log visualization and analysis
•	Simulated SOC Logs
•	Windows Environment
•	Word for documentation

# Data Description
The provided dataset (SOC_Task2_Sample_Logs) contains simulated security logs, including:
•	System event logs
•	Authentication logs (successful and failed logins)
•	Network activity logs with source IP addresses
•	Malware detection alerts (Trojan, Worm, Rootkit, Ransomware)
These logs are designed to represent typical alerts investigated by SOC analysts during daily operations.

# Task Workflow
1.	Log Ingestion
•	Ingested the provided log file into Elasticsearch using Logstash
•	Verified data ingestion using Kibana Discover
2.	Threat Detection & Analysis
•	Analyzed logs to identify malware-related events
•	Investigated repeated failed login attempts
•	Identified suspicious IP addresses involved in multiple alerts
3.	Alert Classification
•	Categorized alerts into High, Medium, and Low severity
•	Prioritized incidents based on potential impact
4.	Incident Investigation
•	Correlated authentication events with malware detections
•	Built a timeline of suspicious activity
•	Assessed the scope and potential impact
5.	Incident Response Simulation
•	Simulated containment, eradication, and recovery actions
•	Documented recommended security improvements
6.	Reporting
•	Created a structured incident response report
•	Captured SIEM screenshots as supporting evidence

# Key Findings
•	Multiple high-severity malware alerts across different systems
•	Repeated failed login attempts indicating credential abuse
•	Suspicious IP addresses associated with multiple attack vectors
•	Indicators of potential system compromise and lateral movement
