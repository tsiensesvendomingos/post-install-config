<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Post-Install Configuration Objectives</h2>

- Configure Agents
- Configure Users
- Configure SLAs
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
After successfully configuring osTicket from scratch, we will now proceed with the post-installation setup. Our first task is to configure new roles within the help desk. To do this, navigate to the Admin Panel, and select Agents, and Roles. We will be creating a new role called "Supreme Admin." Click on 'Add New Role' and provide the role's name. Additionally, you have the option to modify specific role permissions. In the case of the Supreme Admin role, they will have comprehensive access, assuming the role of a versatile expert. However, remember that roles determine an agent's permissions, and not all agents will have unrestricted access. If creating the "Supreme Admin" role is successful, the newly created role should be visible on the roles list like so.
</p>
<p>
<img src="https://i.imgur.com/OFyhMIW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Now we are going to create a new department. Select the 'Departments' button in the agents tab. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. Here in this case we will be creating the "System Administrators" department and this is where the Supreme Admins will be designated. Other specific settings such as SLA's, managers and other email settings can be set up in the Departments tab. 
</p>
<p>
<img src="https://i.imgur.com/9r8QdoW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
After making a new department we will set up a new team. Teams allow you to pull agents from different departments. An example would be that you can create a help topic that correlates with a product you produce and assign it to a team of agents that specialize in that particular product. To create a team go to Agents-->Teams. A Level I Support Team has already been made by default so we'll create a Level II Team. 
</p>
<p>
<img src="https://i.imgur.com/uv5oub9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Now that a new team is set up we will now create a new setting that will allow anyone to create tickets. To do so go to Admin Panel-->Settings-->User Settings. 
</p>
<p>
<img src="https://i.imgur.com/cc1pV2a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
We are now going to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab.
</p>
<p>
<img src="https://i.imgur.com/USyvTNV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/sDcDKat.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
After this we will create users. Users are the customers that create tickets when they are having issues. A user is identified with their email address. To create a user go to the Agent Panel-->Users-->User Directory-->Add User
</p>
<p>
<img src="https://i.imgur.com/UTsbGFZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/8Fiug8V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Service Level Agreement(SLA) Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to the Admin Panel-->Manage-->SLA Plans. Each SLA has a schedule and within that schedule there's a grace period. This screen shows an SLA Plan called "SEV-A" that has a 24/7 schedule and a one hour grace period. Make two others: SEV-B with 24/7 schedule and a four hours grace period and SEV-C with a eight hours grace period and must be solved within business days. 
</p>
<p>
<img src="https://i.imgur.com/ONZJnOp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/GXYY0EM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Help Topics help users categorize their tickets. We are going to create four categories (Business Critical Outage; Personal Computer Issues; Equipment Issues; & Password Reset) for end users to utilize when reporting an issue.
</p>
<p>
<img src="https://i.imgur.com/Td4qd1M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/UdtR1ib.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />
