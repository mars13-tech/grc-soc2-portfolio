# Asset Inventory — CloudPay India Pvt Ltd
**Framework:** NIST CSF 2.0 — Identify Function  
**Date:** 31 March 2026  
**Prepared by:** Karthikeyan  

## Why This Matters
Asset inventory is the foundation of every compliance 
program. SOC 2, ISO 27001, and PCI DSS all require 
you to know what assets are in scope before any 
control can be designed or tested.

## Asset Register

| Asset ID | Asset Name | Type | Owner | Criticality | Data Handled | Location |
|---|---|---|---|---|---|---|
| A001 | Payment Processing Server | Hardware | IT Team | Critical | Card data, PII | AWS Mumbai |
| A002 | Customer Database | Data | Engineering | Critical | PII, Financial | AWS Mumbai |
| A003 | Employee Laptops (x25) | Hardware | IT Team | High | Internal data | On-premise |
| A004 | Salesforce CRM | SaaS App | Sales | High | Customer PII | Cloud |
| A005 | GitHub Repositories | SaaS App | Engineering | Critical | Source code | Cloud |
| A006 | AWS Production Environment | Cloud Infra | DevOps | Critical | All data | AWS Mumbai |
| A007 | Slack | SaaS App | HR/All | Medium | Internal comms | Cloud |
| A008 | Payroll System | SaaS App | HR | High | Employee PII | Cloud |

## Asset Criticality Definitions
- **Critical** = Business stops if unavailable
- **High** = Significant business impact if unavailable
- **Medium** = Moderate impact, workarounds exist
- **Low** = Minimal impact

## Notes
Asset inventory is important because an organization cannot effectively protect systems and data without knowing what assets exist in its environment.

For a SOC 2 audit, asset inventory is critical as it helps define the scope of systems and resources that are subject to security controls. Auditors rely on this inventory to identify which assets store, process, or transmit sensitive data such as PII.
