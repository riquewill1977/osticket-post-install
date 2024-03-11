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
- Configure Agents (help desk professionals)
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

From the Agents tab, click on "Departments"

![Screenshot 2024-03-06 131821](https://github.com/riquewill1977/osticket-post-install/assets/139101776/607ed733-1905-4f9a-8ded-af7949d78a32)

Click on "Add New Department"

![image](https://github.com/riquewill1977/osticket-post-install/assets/139101776/45eeac0e-aa40-47a5-bc75-0de4289ce4eb)

Name the department "System Administrators" and click Create Dept

![image](https://github.com/riquewill1977/osticket-post-install/assets/139101776/7d4ae94f-484c-4624-8ba2-352688537623)

"System Administrators" should be now added to the list of Departments.

![Screenshot 2024-03-06 140413](https://github.com/riquewill1977/osticket-post-install/assets/139101776/8ce34635-c177-46a6-ab7c-65f9990957bf)

<h2>Configure Teams</h2>

Under the Agents tab click on Teams, then "Add New Team"

![Screenshot 2024-03-06 143622](https://github.com/riquewill1977/osticket-post-install/assets/139101776/7351ea27-72fe-412e-9f35-61a0780231e7)

We'll name this Team "Level II Support" and go over to the "Members" tab and add yourself to the team.

![Screenshot 2024-03-06 150412](https://github.com/riquewill1977/osticket-post-install/assets/139101776/5e0321c5-e296-43cb-bc20-3312097bd25d)

![Screenshot 2024-03-06 150439](https://github.com/riquewill1977/osticket-post-install/assets/139101776/e12038b8-7758-42a5-906e-1f780de82240)

<h2>Allow anyone to created tickets</h2>

From the Admins Panel got to the Settings > Users

![Screenshot 2024-03-06 152750](https://github.com/riquewill1977/osticket-post-install/assets/139101776/28dbeddd-7a10-40d0-8e94-f478b24f28ee)

Make sure "Require registration and login to create tickets" is unchecked. 

![image](https://github.com/riquewill1977/osticket-post-install/assets/139101776/74aed40a-5db8-4780-b80f-c4c68aafa8c2)

<h2>Configure Agents (help desk professionals)</h2>

Let's create a coupble agents. From the Admin panel, go to the "Agents" tab and select "Agents". As we did with the others, click "Add New Agent"

![Screenshot 2024-03-06 162912](https://github.com/riquewill1977/osticket-post-install/assets/139101776/b9de0362-324e-4a93-8588-a6ccab3d4505)

Enter a First and Last name, email address and username. Click set password.

![image](https://github.com/riquewill1977/osticket-post-install/assets/139101776/490a070f-e3c5-4a1e-9655-659fc5875b03)

Uncheck "Send the agent a password reset email" and "Require password change at next login" If this were the real-world, we'll leave these checked to allow the user to reset create their password. Click "Set" when done.

![image](https://github.com/riquewill1977/osticket-post-install/assets/139101776/5510a757-026e-40d1-a061-a1108f6021ab)










