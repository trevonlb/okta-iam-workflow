# okta-iam-workflow

# Okta Offboarding Automation Lab

## Project Description
This project demonstrates a **user offboarding automation workflow** using **Okta Workflows**, **Google Sheets**, and **Slack**.  
When an IT admin deactivates a user in Okta, the workflow automatically:  
1. Logs the event in a Google Sheet (username, email, timestamp, date).  
2. Sends a Slack alert to the `#user-lifecycle` channel for visibility.  

This lab highlights practical **Identity and Access Management (IAM)** automation skills and shows how organizations can ensure security, auditability, and real-time communication around **Joiner–Mover–Leaver (JML)** processes.  

---

## Software Involved
- **Okta Workflows** → Automation engine for identity lifecycle events.  
- **Google Sheets** → Centralized log for offboarding documentation.  
- **Slack** → Real-time notifications for IT, Security, and HR viewers.  

---

## Key Features
- Admin-driven offboarding (initiated in Okta).  
- Automated multi-platform documentation (Okta → Sheets + Slack).  
- Real-time Slack alerts for improved visibility.  
- Audit-ready with timestamps and termination details. 
