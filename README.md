# Elastic - SIEM
🔍 Elastic SIEM: Centralized Log Collection & Security Monitoring

This project showcases the setup and configuration of the Elastic Stack (Elasticsearch, Logstash, Kibana) to create a centralized, real-time Security Information and Event Management (SIEM) system. Implemented on a Kali Linux VM, the goal was to collect, analyze, and visualize logs for enhanced threat detection and incident response.

🚀 Project Goals

 ✅ Centralize log collection from multiple endpoints

 ✅ Visualize and analyze logs using Kibana dashboards
 
 ✅ Simulate attack scenarios and validate detection
 
 ✅ Set up alerts for suspicious activity

🛠️ Setup Overview

1. Elastic Stack Installation
	•	Deployed Elasticsearch and Kibana on a Kali Linux VM
	•	Configured Elasticsearch for indexing and storage
	•	Used Kibana for UI-based log search and visualization

2. Elastic Agent Deployment
	•	Installed and configured Elastic Agent on endpoints
	•	Enabled modules to capture system logs, network activity, and security events
	•	Resolved connectivity and firewall issues to ensure seamless data flow

⚙️ Activity Simulation & Analysis

To generate realistic logs:
	•	Ran: nmap -p- localhost
Simulated a full port scan to trigger alerts and validate log ingestion

In Kibana:
	•	Queried logs using KQL, e.g., process.args: "<process_name>"
 	•	Filtered events and monitored specific behaviors

📊 Custom Filters & Log Management
	•	Created custom filters for improved log categorization
	•	Optimized indices and enabled log rotation to manage data volume
	•	Filters accessible via: Security > Rules in Kibana

📩 Alerting Mechanism

Configured email alerts for:
	•	Unauthorized access attempts
	•	Anomalous network traffic patterns
	•	High CPU or memory usage

✅ Outcome

This Elastic SIEM project resulted in:
	•	A functional and scalable centralized logging setup
	•	Real-time visibility into system and network activity
	•	Practical experience with Elastic Stack components
	•	Sharpened skills in incident detection, analysis, and response
