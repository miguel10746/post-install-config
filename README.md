<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Creating Roles, Departments,Team
- Creating Agents(workers)
- Creating Users(customers)
- Configure SLA
- Create Help Topics
  

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/211956db-c1d8-45dc-8a52-9cf8fbc684e9)
<p>
I log-in as the admin into the osTicket. To create departments, teams, roles.
</p>

![image](https://github.com/user-attachments/assets/2d8ddfd2-4ae8-4df8-af20-b5c8cd0078e4)
<p>
I click on the admin panel then went to agents clicked roles, to add a new role name Supreme Admin.
</p>


![image](https://github.com/user-attachments/assets/f7123f77-c312-4936-bac7-43fe139cd1c4)
<p>
Within the same page I clicked departments. Add new department named SysAdmins.
Then I went to teams to create Online Banking as a new team.
To allow unregistered users to create tickets I went to Admin Panel and settings to User Settings and uncheck unregistered users can create tickes.
</p>

![image](https://github.com/user-attachments/assets/7485cdbf-9911-40c4-923d-a94c02eb19eb)
![image](https://github.com/user-attachments/assets/5b2ba32e-ac07-4a07-bb9e-788f9394dbe9)
![image](https://github.com/user-attachments/assets/98879237-479d-4afe-a426-87c10a65c80f)

<p>
I create a fake worker name Jane and set her role in the organization and her access. After that I create another user name John as a support role.
</p>

![image](https://github.com/user-attachments/assets/1a3069d8-e25d-438c-9293-ad8a8eb8dfa7)
<p>
I created a user to create tickets name Karen.
</p>

![image](https://github.com/user-attachments/assets/276882fc-4714-42cb-8d62-91af062372b5)
![image](https://github.com/user-attachments/assets/357f246a-1b40-46df-b430-c912682fa003)
<p>
I created three levels of Service level agreements each with different grace periods Sev-A 1 Hour, Sev-B 4 Hours, and Sev-C 8 Hours. To defined the response and resolution time expectation for support tickets.
</p>

![image](https://github.com/user-attachments/assets/ab7db7ff-3bf9-4efd-a2c7-1fad3c0f52da)
![image](https://github.com/user-attachments/assets/f9b77b40-192b-46ca-b3aa-a72cc383bd66)
<p>
I finally create Help topic that users can use to create tickets from password resets to Business critical outage.
</p>



