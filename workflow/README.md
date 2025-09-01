# Workflow Design – Okta Offboarding Lab

## Overview
This workflow demonstrates the advantages of **automated documentation** in the offboarding process when IT administrators take direct action in Okta. Once an admin deactivates a user, Okta Workflows automatically updates a Google Sheet and sends a Slack notification.  

This ensures **clear, consistent, and multi-platform documentation** of user lifecycle events. HR is a participant only as a **viewer**, with access to review the spreadsheet for compliance and auditing purposes.

---

## IAM Fundamentals Demonstrated
- **Identity Lifecycle Management (ILM)** – Automates documentation of user offboarding events across systems.  
- **Deprovisioning** – Ensures accounts are deactivated promptly to maintain least privilege.  
- **Auditability & Compliance** – Captures critical information (username, email, timestamp, deactivation date) for audit trails.  
- **Separation of Duties** – IT initiates account deactivation; HR can verify activity without making system changes.  
- **Notification & Visibility** – Slack provides real-time visibility to IT, HR, and Security teams.  

---

## Workflow Steps
1. **IT Admin Deactivates User in Okta**  
   - The admin suspends or deactivates a user.  
   - This serves as the workflow trigger.  

2. **Okta Workflows Automation**  
   - Records the user’s details (username, email, date, timestamp).  
   - Automatically appends this data to the Google Sheet.  

3. **Slack Notification**  
   - Posts a structured alert message in the `#user-lifecycle` channel.  
   - Provides instant visibility across IT and HR stakeholders.  

---
