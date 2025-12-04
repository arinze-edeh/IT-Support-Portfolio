# 🌟 IT Support & Cloud Portfolio — Arinze

Google IT Support • AWS Certified Cloud Practitioner • Azure Data Fundamentals  
WordPress setup • Digital Marketing

This repository showcases hands-on labs and projects demonstrating practical skills in IT support, networking, cloud, WordPress, and automation.

## 📂 Structure
- `1-Active-Directory-Lab/`
- `2-Networking-Lab/`
- `3-Windows-Troubleshooting/`
- `4-Linux-Troubleshooting/`
- `5-Ticketing-System-Projects/`
- `6-AWS-Cloud-Lab/`
- `7-Azure-Cloud-Lab/`
- `8-WordPress-Deployment/`
- `9-Automation-Scripts/`

## 📫 Contact
LinkedIn: [https://linkedin.com/in/yourprofile  ](https://www.linkedin.com/in/arinze-edeh-799359ab/)
Email: edeharinze389@gmail.com
# Active Directory Home Lab

## Overview
This lab builds a small AD domain (`lab.local`) with a Domain Controller and a client. The lab demonstrates user & group management, OU structure, Group Policy basics, and joining a client to the domain.

## Tools
- Windows Server 2019 eval
- Windows 10 client
- VirtualBox (or VMware)
- PowerShell

## Steps (summary)
1. Create two VMs: AD-DC (Windows Server), CLIENT-01 (Windows 10).
2. Set static IP for AD-DC (e.g., 192.168.56.10) and configure DNS to itself.
3. Install AD DS role and promote to DC. Use domain: `lab.local`.
4. Create OUs and users:
   - OU: `IT`, `Staff`
   - Users: `arinze.support`
   - Group: `IT-Support`
5. Create a simple GPO: Set a custom wallpaper via GPO (demonstration).
6. Join CLIENT-01 to `lab.local` and login with `arinze.support`.

## What I learned
- Domain setup & DNS importance
- User/group/GPO basics
- Domain join troubleshooting (time sync, DNS)
