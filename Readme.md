# Secure Azure Virtual Machine with Monitoring and Backup (AZ-104)

## Overview
This project demonstrates hands-on implementation of core Azure Administrator (AZ-104)
concepts by deploying and managing a secure Azure Virtual Machine.

The project includes configuring Virtual Networks and Network Security Groups (NSGs)
to control inbound traffic, deploying a web server to validate connectivity,
monitoring VM performance using Azure Monitor, creating CPU-based alerts,
and enabling VM-level backups using Recovery Services Vault.

## Azure Services Used
- Azure Virtual Machine
- Virtual Network (VNet)
- Network Security Group (NSG)
- Azure Monitor and Alerts
- Recovery Services Vault (Azure Backup)

## Architecture
- Internet → Public IP  
- Network Security Group (NSG)  
- Virtual Network & Subnet  
- Azure Virtual Machine  
- Monitoring & Backup

## Implementation Steps
1. Created a resource group and virtual network
2. Configured NSG with least-privilege inbound rules
3. Deployed VM inside a secured subnet
4. Installed a web server and verified public access
5. Monitored VM performance using Azure Monitor metrics
6. Configured CPU-based alerts and VM backups

## Key Learnings
- Secure VM deployment using Azure networking
- Traffic control using NSGs
- Monitoring and alerting with Azure Monitor
- Backup and disaster recovery concepts

## Proof of Implementation
Screenshots demonstrating successful configuration and monitoring are included.
