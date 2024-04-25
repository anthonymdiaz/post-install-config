<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Role Configuration
- Department Configuration
- Team Configuration
- Ticket Creation Permissions
- Agent Configuration
- User Configuration
- SLA Configuration
- Help Topics Configuration


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Role Configuration:
Navigate to Admin Panel -> Agents -> Roles.
Establish the "Supreme Admin" role.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Department Configuration:
Go to Admin Panel -> Agents -> Departments.
Configure the "System Administrators" department.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Team Configuration:
Access Admin Panel -> Agents -> Teams.
Create "Level I Support" and "Level II Support" teams.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Ticket Creation Permissions:
Enable ticket creation for all users:
Access Admin Panel -> Settings -> User Settings.
Set "Registration Required" to require registration and login for ticket creation.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Agent Configuration:
Access Admin Panel -> Agents -> Add New.
Add agents "Jane" and "John".</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. User Configuration:
Navigate to Agent Panel -> Users -> Add New.
Add users "Karen" and "Ken".</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. SLA Configuration:
Access Admin Panel -> Manage -> SLA.
Define SLA levels:
Sev-A: 1 hour response time, 24/7 availability.
Sev-B: 4 hours response time, 24/7 availability.
Sev-C: 8 hours response time, business hours availability.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. Help Topics Configuration:
Go to Admin Panel -> Manage -> Help Topics.</p>
<br />
