# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
The Problem at Northstar Medical was that there was no structure with onboarding/offboarding as well as who had access to what privileges and account providing was done manually which made it error prone and impossible to audit. This created a serious HIPPA risk in relation to confidential health information and former employees keeping active accounts. 


## Solution Overview
I built a new Active Directory Domain on windows server and promoted a domain controller to manage it. I designed organizational unit structure that mirrors the companies departments, and created security groups for each job function then assigned permissions to those groups rather than individuals. This RBAC model means access is based on role which limit exposure to employee a patient data which supports HIPPA minimum necessary standard. This made it clear to have a new hire placed in the correct OU which gave them the correct access via the respectable security groups and the inverse as well with offboarding. The result is a documented and auditable structure.



## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Made a clear structure to insure efficient auditing
  
