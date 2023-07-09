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

- Configure Roles, Departments and Teams
- Configure Agents and Users
- Configure SLA and Help Topics


<h2>Configuration Steps</h2>

<p>

Once osTicket is up and running, we can begin the Post Installation Setup.

**1.) Configuring Roles**

According to the osTicket website, "Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments."

  -To configure roles, first step is to log in and go to Admin Panel

![image](https://github.com/akingsley22/post-install-config/assets/138138839/3f84f598-b837-46e8-8a49-fffa16a9a67f)

  -Then go to Agents -> Roles

![image](https://github.com/akingsley22/post-install-config/assets/138138839/05af669e-a544-45dc-8acb-cac66c64dc56)

  -Click on "Add New Role" and add your role with permissions.

![image](https://github.com/akingsley22/post-install-config/assets/138138839/5642dc30-0a50-494a-b333-dba380fce762)


**2.) Configuring Departments**

  -To configure departments, go to Admin Panel

![image](https://github.com/akingsley22/post-install-config/assets/138138839/3f84f598-b837-46e8-8a49-fffa16a9a67f)

  -Then go to Agents -> Departments

![image](https://github.com/akingsley22/post-install-config/assets/138138839/47e49061-63ff-4b73-87ac-0c975fef6879)

  -Click "Add New Department".

  ![image](https://github.com/akingsley22/post-install-config/assets/138138839/bcf110a6-b13d-4b35-a245-537995ec8833)

**3.) Configuring Teams**

  -To configure Teams, go to Admin panel

![image](https://github.com/akingsley22/post-install-config/assets/138138839/3f84f598-b837-46e8-8a49-fffa16a9a67f)

  -Then go to Agents -> Teams

![image](https://github.com/akingsley22/post-install-config/assets/138138839/e21b537d-4bf4-4c33-b6e8-dcc5f046aba2)


  -Now click "Add New Team" and fill out the appropriate information. After creating teams, you can now add Agents to the teams by clicking their name from your Agents list and clicking the corresponding box next to the team you want them top be in

![image](https://github.com/akingsley22/post-install-config/assets/138138839/16aa317f-23c3-4248-b532-9bdf75609a0c)

![image](https://github.com/akingsley22/post-install-config/assets/138138839/ce5a81b1-fede-4b0b-a6c5-ab2bf18069a8)


**4.) Configuring Agents**

  -To configure Agents, go to Admin panel -> Agents -> Agents -> Add New Agent

  ![image](https://github.com/akingsley22/post-install-config/assets/138138839/e9128043-974a-43a2-bbe8-18450bfd9fcc)

**5.) Configuring SLA**

</p>

<p>
Within the osticket environment, SLA's are seen as a time limit for how long a ticket should be open. To create SLA's we begin at the Admin Panel, then click on Manage and then SLA. Click on "Add New SLA Plan" and proceed according to your company policy.

    Example;
    -Sev-A (1 hour, 24/7)
    -Sev-B (4 hours, 24/7)
    -Sev-C (8 hours, business hours), etc

</p>
<br />

<p>
  
![image](https://github.com/akingsley22/post-install-config/assets/138138839/0e803a25-b14a-4b26-a87f-78c637e801ee)

</p>
<p>  
Lastly I went ahead and created Help Topics that can act as a baseline to help users with Questions
</p>
<br />

<p>
  
![image](https://github.com/akingsley22/post-install-config/assets/138138839/c59778bb-6f6e-4d10-863a-2088f3779acf)

These Topics include:

    -Business Critical Outage
    -Personal Computer Issues
    -Equipment Request
    -Password Reset


</p>

<br />
