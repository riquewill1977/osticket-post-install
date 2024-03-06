<p align="center">
<img src="https://github.com/riquewill1977/osticket-post-install/assets/139101776/62d025a5-8c9a-406c-9575-31e63ba18950" alt="osTicket login"/>
</p>

<h1>osticket-post-install</h1>
This tutorial delineates the post-installation configuration procedures for osTicket, an open-source help desk ticketing system. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post Installation Setup</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to creat tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configure Roles</h2>
<p>Log in using your username and password that we created during the intallation process.</p>

![image](https://github.com/riquewill1977/osticket-post-install/assets/139101776/450394b3-a761-4791-9f9a-4b97ba38ba9b)

During this lab, we'll demontrate tasks from an Admin and an Agent. 

When in Admin Panel, the top right should show "Agent Panel". 

![image](https://github.com/riquewill1977/osticket-post-install/assets/139101776/8729be88-8e50-4448-a9eb-c003bd55d7ba)

Click the "Agent Panel" to switch to the Agent Panel which will then display "Admin Panel" to the top right. 

![image](https://github.com/riquewill1977/osticket-post-install/assets/139101776/8516e5bf-4eaa-40c2-bcd6-b29b69586295)

Let's get started and created a Supreme Admin Role

From the Admin Panel click on the "Agents" tab and go to "Roles" as shown in the below image.

![Screenshot 2024-03-05 235246](https://github.com/riquewill1977/osticket-post-install/assets/139101776/d6006cb3-c372-47dd-8e1f-5f6591214e72)

Click on "Add New Role"

![Screenshot 2024-03-06 003359](https://github.com/riquewill1977/osticket-post-install/assets/139101776/1df5acb4-c30c-40c1-b729-f168ad0f2c38)

Name the agent "Supreme Admin"

![Screenshot 2024-03-06 003723](https://github.com/riquewill1977/osticket-post-install/assets/139101776/008f2a6f-dddd-43ad-b914-d357a4de4e57)

Click on the "Permissions" tab and check everything for Tickets, Task and Knowledgebase. Click "add role" once complete.

![Screenshot 2024-03-06 003759](https://github.com/riquewill1977/osticket-post-install/assets/139101776/d90986d0-e3cf-4a35-b6b3-622ea3b86cae)


<h2>Configure Departments</h2>


