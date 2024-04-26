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

  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/0ed28e1b-d0c8-46fa-8aab-5cf38170b797)
  
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/9a072198-d243-4c74-b0fc-5c585ad3a64d)
  
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/aa39b982-b705-40ce-bafc-5d3a0d4fb7b6)

![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/44defb31-98f6-45fb-ba4f-7b35307c18e4)


  

</p>
<p>
1. Role Configuration:
Navigate to Admin Panel -> Agents -> Roles.
Establish the "Supreme Admin" role.</p>
<br />

<p>

  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/27a3894f-de78-4833-ac7a-5c34eb7f28b3)

  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/6b71c273-a861-44c4-af5b-5c7c25692d12)

  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/abccbafe-a733-4f33-ad64-877fa81b1d72)



</p>
<p>
2. Department Configuration:
Go to Admin Panel -> Agents -> Departments.
Configure the "System Administrators" department.</p>
<br />

<p>

  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/dd224f58-ae48-48b2-817b-efa80e94c3f0)
![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/c6ff32da-95a5-4c2b-8a32-93398ac92785)
![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/986645dc-2aaf-4e42-9d23-a58865229c2d)



</p>
<p>
3. Team Configuration:
Access Admin Panel -> Agents -> Teams.
Create "Level I Support" and "Level II Support" teams.</p>
<br />

<p>

  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/5452cf5f-d83e-4d22-b526-44edc7550b84)

</p>
<p>
4. Ticket Creation Permissions:
Enable ticket creation for all users:
Access Admin Panel -> Settings -> User Settings.
Set "Registration Required" to require registration and login for ticket creation.</p>
<br />

<p>

  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/b0cd953d-48a0-42b6-9349-84f509a843cf)
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/8bddeb61-6b7f-4fd5-aa2a-f10e3eb84c9a)
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/bed3780a-0f27-470f-a4f3-6780a1551862)
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/402f8cf9-72da-4b62-a72e-cf72b4ebb9a7)
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/2c726ea9-a120-476f-a4b5-e8025bd8ceda)
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/847da692-225e-4a86-9cff-528070cf12a4)



</p>
<p>
5. Agent Configuration:
Access Admin Panel -> Agents -> Add New.
Add agents "Jane" and "John".</p>
<br />

<p>

  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/c4920d01-6aa4-4437-83f7-91532e32a427)
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/a972d97f-c377-427d-a5f3-035b441a911c)
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/5abc2a1f-7cd2-405b-b4b3-306b55d0aa43)



</p>
<p>
6. User Configuration:
Navigate to Agent Panel -> Users -> Add New.
Add users "Karen" and "Ken".</p>
<br />

<p>

  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/f37be153-df3a-4a04-b78a-c7ae065dca0f)
  
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/eda03e54-0261-4690-ac23-d3a2d446df74)
  
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/c493d9ba-c498-4c13-98e1-420ecc310e64)
  
  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/60730c6b-b4c8-4d2e-8f79-2a21aa96a547)


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

  ![image](https://github.com/anthonymdiaz/post-install-config/assets/167942930/3cf50890-3105-4494-a745-8e26e61d88a5)


</p>
<p>
8. Help Topics Configuration:
Go to Admin Panel -> Manage -> Help Topics.</p>

- Add more Help Topics as needed


- Example of Help Topics to add


1. Business Critical Outage


2. Personal Computer Issues


3. Equipment Request


4. Password Reset

<br />
