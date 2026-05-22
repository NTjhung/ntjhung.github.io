# Microsoft Graph IAM Reporting Automation

## Project Summary

This project demonstrates IAM reporting automation using Microsoft Graph and PowerShell. The lab simulates how an IAM team can export users, groups, group memberships, and access evidence from Microsoft Entra ID.

The goal is to show how automation can support audit readiness, access reviews, identity governance, and IAM operations.

## Business Problem

IAM teams often need to provide reports for audits, access reviews, security investigations, and user lifecycle management. Manually collecting this information can be slow and error-prone. Automation helps standardize reporting and improves evidence collection.

## What I Built

- Created IAM reporting scripts
- Exported Microsoft Entra ID users
- Exported Microsoft Entra ID groups
- Exported group membership reports
- Generated CSV reports
- Created a reporting plan
- Collected screenshots as audit evidence
- Used a REST-based Microsoft Graph approach to work around module issues

## Screenshots

### Microsoft Graph REST Script Success

<img src="../assets/graph-reporting/graph-rest-script-success.png" alt="Microsoft Graph REST script success screenshot" width="800">

### All Users Report Preview

<img src="../assets/graph-reporting/all-users-report-preview.png" alt="All users report preview screenshot" width="800">

### Group Membership Report Preview

<img src="../assets/graph-reporting/group-membership-report-preview.png" alt="Group membership report preview screenshot" width="800">

## Documentation Summary

### IAM Reporting

IAM reporting helps security and IT teams understand users, groups, and access assignments.

### Audit Evidence

CSV reports and screenshots can be used as evidence during access reviews, audits, and compliance checks.

### Group Membership Review

Exporting group membership helps IAM teams validate whether users still need assigned access.

### Automation

PowerShell automation reduces manual work and makes IAM reporting more repeatable.

### Microsoft Graph

Microsoft Graph can be used to query Microsoft Entra ID user, group, and membership data for reporting and audit purposes.

## Lab Note

The original Microsoft Graph PowerShell cmdlet approach ran into module loading issues in Azure Cloud Shell. To complete the project cleanly, a REST-based Microsoft Graph PowerShell script was created using Invoke-RestMethod and an Azure Cloud Shell access token.

This demonstrates practical troubleshooting and an alternate automation method when module dependencies cause issues.

## Skills Demonstrated

- Microsoft Graph
- PowerShell
- REST API
- IAM reporting automation
- CSV reporting
- Group membership review
- Audit evidence collection
- Troubleshooting

## Resume Bullet

Built a Microsoft Graph IAM reporting automation project using PowerShell and REST API calls to export Microsoft Entra ID users, groups, group memberships, and audit evidence reports for access review support.

[Back to Home](../index.md)
