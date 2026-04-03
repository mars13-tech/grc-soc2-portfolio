# CloudPay India — Protect and Detect Controls
**Date:** 01 April 2026
**NIST CSF Functions:** Protect + Detect
**Written by:** Karthikeyan

## What is a Protect control?
protect control means give a security mechanisms to assests

## What is a Detect control?
Detect control means detect any suspicious activity happen in company

## CloudPay Protect Controls

| Asset ID | Asset Name | Type | Owner | Criticality | control | Risk reduce |
|---|---|---|---|---|---|---|
| A001 | Payment Processing Server | Hardware | IT Team | Critical | Load balancing | unavailable server |
| A002 | Customer Database | Data | Engineering | Critical | Encryption | Data breach |
| A003 | Employee Laptops (x25) | Hardware | IT Team | High | strong passwords | account takeover |
| A004 | Salesforce CRM | SaaS App | Sales | High | MFA | customer data |
| A005 | GitHub Repositories | SaaS App | Engineering | Critical | private repo and MFA | code leak |
| A006 | AWS Production Environment | Cloud Infra | DevOps | Critical | Least privilege | security compromise |
| A007 | Slack | SaaS App | HR/All | Medium | restrict external sharing | internal discussion |
| A008 | Payroll System | SaaS App | HR | High | Employee PII | Cloud |


## CloudPay Detect Controls

| Asset ID | Asset Name | Type | Owner | What is monitored | Alert trigger | Response time |
|---|---|---|---|---|---|---|
| A001 | Payment Processing Server | Hardware | IT Team | CPU usage and uptime | Server down or CPU > 90% | 5 minutes |
| A002 | Customer Database | Data | Engineering | Login attempts | More than 5 failed logins | 10 minutes |
| A003 | Salesforce CRM | SaaS App | Sales | User login location | Login from unusual country | 15 minutes |
| A004 | GitHub Repositories | SaaS App | Engineering | Repository visibility | Private repo becomes public | 10 minutes |
| A005 | AWS Production Environment | Cloud Infra | DevOps | IAM activity | New admin user created | 5 minutes |
| A006 | Slack | SaaS App | HR/All | File sharing | External file shared | 30 minutes |

## Why CloudPay needs both
Protect controls help prevent attacks before they occur.
Detect controls help identify suspicious activity quickly.
Using both controls improves security and reduces business risk.
