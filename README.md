# Azure Honeypot with Microsoft Sentinel

## Overview
This project documents the deployment of a Windows-based honeypot in Microsoft Azure to observe 
unauthorized access attempts and analyze security events using Log Analytics Workspace (LAW) 
and Microsoft Sentinel.

The goal of this lab is to practice:
- Log collection and forwarding
- SIEM configuration
- KQL querying
- Log enrichment with geographic data
- Visualizing attacks using Sentinel workbooks

## Architecture
- Azure Windows 10 Virtual Machine (Honeypot)
- Network Security Group (NSG) allowing inbound traffic
- Log Analytics Workspace (central log repository)
- Microsoft Sentinel (SIEM)
- Sentinel Watchlist (GeoIP enrichment)
- Sentinel Workbook (Attack Map)

## Skills Demonstrated
- Cloud security fundamentals (Azure)
- SIEM deployment and configuration
- Windows security event analysis
- KQL (Kusto Query Language)
- Log enrichment and visualization
- Incident investigation fundamentals

## Tools & Technologies
- Microsoft Azure
- Windows 10
- Azure Log Analytics Workspace
- Microsoft Sentinel
- KQL
