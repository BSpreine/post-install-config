<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<!--- <h2>Video Demonstration</h2>(coming soon!) -->

<!--- - ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)(coming soon!) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow ticket creation
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Actions and Observations</h2>

#### Part 1 (Employee Configuration)
- Configure roles
    - Admin Panel --> Agents --> Roles
    - Supreme Admin
- Configure Departments
    - Admin Panel --> Agents --> Departments
    - System Administrators
- Configure Teams
    - Admin Panel --> Agents --> Teams
        - Level I Support
        - Level II Support

</br>

#### Configuring Roles.
<p>
<img src="https://i.imgur.com/ov3rZOI.png" height="50%" width="50%" alt="Role Configuration"/>
</p>

#### Configuring Departments.
<p>
<img src="https://i.imgur.com/Td8HSme.png" height="50%" width="50%" alt="Department Configuration"/>
</p>

#### Configuring Teams.
<p>
<img src="https://i.imgur.com/A6Z5QzH.png" height="50%" width="50%" alt="Team Configuration"/>
</p>

</br>

#### Part 2 (User Configuration)
- Allow anyone to create tickets
    - Admin Panel --> Settings --> User Settings
    - Registration Required: Ensure Require registration and login to create tickets is unchecked.
- Configure Agents
    - Admin Panel --> Users --> Add New
        - Jane
        - John
        - Britani
- Configure Users
    - Agent Panel --> Users --> Add New
        - Karen
        - Ken
        - Oliver

</br>

#### Allowing Anyone to Create Tickets.
<p>
<img src="https://i.imgur.com/5WbjYRU.png" height="50%" width="50%" alt="Ticket Creation"/>
</p>

#### Configuring Agents.
<p>
<img src="https://i.imgur.com/UnlpAGR.png" height="50%" width="50%" alt="Agent Configuration"/>
</p>

#### Configuring Users.
<p>
<img src="https://i.imgur.com/oHmujpS.png" height="50%" width="50%" alt="User Configuration"/>
</p>

</br>

#### Part 3 (Business Configuration)
- Configure SLA
    - Admin Panel --> Manage --> SLA
        - Sev-A (1 hour, 24/7)
        - Sev-B (4 hours, 24/7)
        - Sev-C (8 hours, Business Hours)
- Configure Help Topics
    - Admin Panel --> Manage --> Help Topics
        - Business Critical Outage
        - Personal Computer Issues
        - Equipment Request
        - Password Reset

</br>

#### Configuring SLA.
<p>
<img src="https://i.imgur.com/LXEo34v.png" height="50%" width="50%" alt="SLA Configuration"/>
</p>

#### Configuring Help Topics.
<p>
<img src="https://i.imgur.com/zLhgo2s.png" height="50%" width="50%" alt="Help Topic Configuration"/>
</p>


