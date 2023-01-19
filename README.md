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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents and Users
- Configure SLA and Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/V4SRxc1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First we are going to configure our first role. From the Admin Panel, select "Agents", and then "Roles". Select "Add New Role" and type the name you want the role to be. I named mine "Supreme Admin" and gave him full access under the permissions tab.
</p>
<br />

<p>
<img src="https://i.imgur.com/8pte2xq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we are going to configure our first department. From the Admin Panel, select Agents->Departments->Add new department. I named my department "System Administrators". Here you can input department information, change email and autoresponder settings and add who has access to the department.
</p>
<br />

<p>
<img src="https://i.imgur.com/g3HbUFf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we are going to configure our first Team. From the Admin Panel, select Agents->Teams. There is already one team made by default called "Level I Support". We are going to select "Add New Team" and create "Level II Support". Here you can select team status, who the team lead is, and add members.
</p>
<br />
<p>
<img src="https://i.imgur.com/sOxlW4U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Next we are going to configure user settings so that anyone can submit tickets. From the Admin  Panel, select Settings->Users. At "Authentication Settings" uncheck "registration and login to create tickets box" and set the registration method to public.
</p>
<br />
<p>
<img src="https://i.imgur.com/XH022GT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Next, we are going to configure new Agents. From the Admin Panel, select Agents->Add new Agent. Enter the agents Name, Email, Username, and Password. Then, select their primary department, permissions, and team.
</p>
<br />
<p>
<img src="https://i.imgur.com/l8eHBED.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
After creating our Agents we will create our users. From the Agent panel, select users->Add New User. Here, input the users email, full name, and any internal notes that are necessary. 
</p>
<br />
<p>
<img src="https://i.imgur.com/Sugal1O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Once our Users are created, we will create our Service Level Agreements. From the Admin Panel, select Manage->SLA->Add New SLA Plan. Here we can name our new SLA, determine the grace period and the schedule. I created three SLA's
  
- Sev-A (1 hour 24/7)
- Sev-B (4 hours 24/7)
- Sev-C (8 hours 24/5)
  
 
</p>
<br />
<p>




