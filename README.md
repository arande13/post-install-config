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

- Configure Agents and Users
- Configure SLA and Help Topics
- Configure Roles
- Configure Departments
- Configure Teams

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/0ccb17d3-4f9c-4989-a41c-088e57836c0b)

</p>
<p>
Help topics were configured to prepare for the mock ticket scenario. Help topics (Business Critical Outage, Personal Computer Issues, Password Reset, and Equipment Request) were created to reflect real-life scenarios that an agent will encounter in the help desk landscape. I did this by logging in as an admin under labuser1 and adding new help topics and assigning them to a department,so when tickets were eventually created, they could be assigned to the user who was in that respective department.
</p>
<br />

![image](https://github.com/user-attachments/assets/e1c51380-8997-4949-a7d5-b149053c0932)

</p>
<p>
Agents' roles have been configured to allow or restrict their access based on rank in the mock OSTicket lab. The varying levels (Supreme Admin, Expanded Access, and Limited Access) have been added to differentiate what an agent has access to do when it comes to modifying a ticket, working, and ultimately resolving/closing the ticket.
</p>
<br />

![image](https://github.com/user-attachments/assets/7b7a2932-121d-4459-9e24-32edaeadd398)

</p>
<p>
The agent users, Jane and John Doe, have been created as mock agents that have logins. They serve the purpose of allowing me to login from the agent perspective to work tickets created by my admin login labuser1. For example if a ticket with the help topic "Business Critical Outage" was created, then Jane Doe would be the assigned agent because she is apart of the support department that handles those issues. 
</p>
<br /># post-install-config
