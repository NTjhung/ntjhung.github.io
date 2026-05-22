# Conditional Access Security Baseline Design

## Project Summary

This project demonstrates a Microsoft Entra Conditional Access security baseline design. The lab focuses on MFA enforcement strategy, admin protection, legacy authentication blocking, break-glass account planning, report-only rollout planning, rollback documentation, and limitation evidence.

Live Conditional Access policy creation was limited by lab tenant licensing and billing profile setup, so this project is documented as a Conditional Access design and rollout plan instead of a live deployment.

## Business Problem

Organizations need to protect user identities without accidentally locking out users or administrators. Conditional Access policies help enforce security controls such as MFA and access restrictions, but they must be planned, tested, and documented carefully.

## What I Built

- Designed a Conditional Access policy matrix
- Documented MFA enforcement strategy
- Created a break-glass account plan
- Created a rollback plan
- Created a testing results document
- Documented licensing and support limitations
- Collected screenshots as evidence

## Screenshots

### Conditional Access License Warning

<img src="../assets/conditional-access/ca-license-warning.png" alt="Conditional Access license warning screenshot" width="800">

### Billing Profile Error

<img src="../assets/conditional-access/billing-profile-error.png" alt="Billing profile error screenshot" width="800">

### Support Request Permission Error

<img src="../assets/conditional-access/support-request-permission-error.png" alt="Support request permission error screenshot" width="800">

## Documentation Summary

### Planned Policy 1: Require MFA for Administrators

This policy would require privileged/admin users to complete MFA before accessing cloud resources.

### Planned Policy 2: Require MFA for All Users

This policy would require standard users to complete MFA when accessing cloud applications.

### Planned Policy 3: Block Legacy Authentication

This policy would block older authentication methods that do not support modern security controls.

### Planned Policy 4: Require MFA for Sensitive Groups

This policy would apply stronger access requirements to sensitive groups such as Finance, HR, IT Admins, and Contractors.

### Planned Policy 5: Break-Glass Account Exclusion

This policy would document emergency admin account exclusions to reduce the risk of total tenant lockout.

## Skills Demonstrated

- Conditional Access planning
- MFA strategy
- Break-glass account planning
- Rollback planning
- IAM policy design
- Security documentation
- Evidence collection
- Limitation documentation

## Resume Bullet

Designed a Microsoft Entra Conditional Access security baseline with MFA enforcement strategy, admin protection, legacy authentication blocking, break-glass planning, report-only rollout strategy, rollback documentation, and licensing limitation evidence.

[Back to Home](../index.md)
