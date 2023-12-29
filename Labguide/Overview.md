# Threat Protection with XDR

## Overview

Threat Protection with Extended Detection and Response (XDR) is a game-changing paradigm in cybersecurity, providing an unparalleled shield against modern threats. Unlike conventional security measures, XDR doesn’t just stop at surface-level defense; it orchestrates a symphony of security layers, unifying disparate tools and technologies to create an impenetrable fortress for organization.

### Key features of Threat Protection with XDR

- Integration of Security Tools: XDR integrates multiple security tools and technologies such as endpoint security (EPP/EDR), network security, email security, cloud security, and more into a unified platform.
- Centralized Visibility and Analytics: XDR collects and aggregates data from diverse security sources, creating a comprehensive and unified view of the organization's security posture.
- Automated Threat Detection: XDR leverages its analytical capabilities to detect sophisticated threats, including zero-day exploits, malware, ransomware, phishing attacks, and other advanced threats that might evade traditional security measures.
- Contextualized Insights: XDR provides contextualized insights into detected threats, offering detailed information about the attack chain, affected systems, and the severity of the threat.
- Response and Remediation: When a threat is identified, XDR facilitates a swift response by automating threat containment, isolation, and remediation actions.

## Sandbox Scenario
Contoso is a global organization with a complex IT infrastructure that includes a combination of on-premises data centers and cloud-based resources. They are looking to enhance their security posture by deploying Azure Sentinel, Microsoft's cloud-native security information and event management (SIEM) and security orchestration automation and response (SOAR) solution. Additionally, Contoso aims to onboard its cloud resources and servers to Azure Sentinel to gain better visibility and proactive threat detection and response capabilities.

By implementing a robust log analytics and threat detection program, Contoso aims to proactively identify and mitigate threats, reduce the risk of security breaches, and maintain a strong security posture in an ever-evolving threat landscape. This approach will enable Contoso to stay ahead of potential threats and protect its digital assets effectively.

## About the Sandbox

Using this environment, You'll be able to explore complete features and offerings offered by Microsoft Sentinel. Please find the detailed overview about the sandbox environemnt below.

### Pre-provisioned resources

#### **Virtual Machines**: 

- 2 *Windows Server 2019 Datacenter* Virtual machines, virtual machine related resources like Virtual network, Network security groups, managed disks, Network interface card, and IP addresses are deployed as part of the automation.

  You are recommended to use the same virtual machine through the lab for the best experience through out the lab.

#### **License and subscription**: 

- You'll have access to a pre-confgured Microsoft user accountt with an active Azure subscription, a tenant, and a Microsoft 365 E5 license assigned to the user. 
   
  User account has assigned as Owner at subscription and Global administrator at tenant level. You need to user the same user account through out the lab to get most out of the lab. 

#### **Azure Credits**: 

- You have given a quota of **$83 USD** which includes runnning cost of Pre-deployed resources, license cost, and other resources deployed while running through the lab.

  You will receive **cost alerts** to your registered email address at **50%/75%/90%/95%/100%** of the alloted Azure Credit is spent.

  You can visit the Azure Subscription page to check the current Azure credit spend and Analysis on **Cost analysis** tab under Cost Management option.

  ![Picture 1](./media/o1.jpg)

#### **Duration and Deletion of sandbox**:  

- The sandbox enviornment will be active for 30 days/730 hours from the time of registration. 

  when 100% of Azure credits are spent, the sandbox environment will get automatically deleted without any prior notification. In order to retain the environment for longer period of time and to get most out the enviornment, please follow the best practices mentioned below.

#### **Best practices**: 

- **Resources usage**: Please stop the virtual machines and other resources when not in use in order to minimize the Azure spend.

- **Azure Cost Analysis**: Maintain a pratice of checking the Cost Analysis report of the assigned Azure subscription oftenly in check the Azure spend so that enviornment for a longer duration of time.

- **Alert notifications**: Make sure check your registered email's inbox for any alerts related mails. Alerts gives you can head start to keep your Azure spend in control and to plan out the remaining credits in the best way possible.

## Lab guide Content:

You will access to a lab guide which is a reference material to assist you in getting started with the exploration. You are encouraged to explore Microsoft Purview further based on your interests and preferences.

- Lab 01 - Review and explore sentinel workspace
- Lab 02 - Create queries for Microsoft Sentinel using Kusto Query Language (KQL)
- Lab 03 - Understand Detection Modeling
- Lab 04 - Conduct attacks
- Lab 05 - Create Detections
- Lab 06 - Investigate an Incident
- Lab 07 - Create workbooks
- Lab 08 - Use Repositories in Microsoft Sentinel
- Lab 09 - Threat Hunting using Notebooks with Microsoft Sentinel
- Lab 10 - Mitigate threats using Microsoft Defender for Cloud
- Lab 11 - Integrate Logic App with Threat Protection and XDR

### Azure services and related products

- Log Analytics Workspace
- Microsoft Defender for Cloud
- Microsoft Defender for Endpoint
- Microsoft Entra ID
- Microsoft Sentinel
