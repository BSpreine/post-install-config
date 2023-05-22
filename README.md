<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

## Configuration Steps

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

#### Configure role
- Admin Panel -> Agents -> Roles
    - Supreme Admin
#### Configure Departments
- Admin Panel -> Agents -> Departments
    - System Administrators
#### Configure Teams
- Admin Panel -> Agents -> Teams
    - Level I Support
    - Level II Support

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

#### Allow anyone to create tickets
- Admin Panel -> Settings -> User Settings
    - Registration Required: Require registration and login to create tickets 
#### Configure Agents (workers)
- Admin Panel -> Agents -> Add New
    - Jane
    - John
    - Bryant
#### Configure Users (customers)
- Agent Panel -> Users -> Add New
    - Karen
    - Ken
    - Britani
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

#### Configure SLA
- Admin Panel -> Manage -> SLA
    - Sev-A (1 hour, 24/7)
    - Sev-B (4 hours, 24/7)
    - Sev-C (8 hours, business hours)
#### Configure Help Topics
- Admin Panel -> Manage -> Help Topics
    - Business Critical Outage
    - Personal Computer Issues
    - Equipment Request
    - Password Reset
<br />
