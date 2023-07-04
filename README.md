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
- Configure Agents (workers)
- Configure Users (customers)
- Configure Service Level Agreements (SLAs)
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
After successfully configuring osTicket from scratch in our Azure virtual machine, we will proceed with the post-installation setup. Our first task is to configure new roles within the help desk. To do this, navigate to the Admin Panel, and select Agents, and Roles. We will be creating a new role called "Supreme Admin." Click on 'Add New Role' and provide the role's name. Additionally, you have the option to modify specific role permissions. In the case of the Supreme Admin role, they will have complete access, assuming the role of a versatile expert. However, remember that roles determine an agent's permissions, and not all agents will have unrestricted access. If creating the "Supreme Admin" role is successful, the newly created role should be visible on the roles list like so.
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/post-install-config/assets/138411730/434783c8-af61-4c97-b41d-aeb19318a7b1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next up, we will establish a new department. Click on the 'Departments' button located in the agent's tab. Every agent will be allocated to a particular department based on their assigned role in the helpdesk. In this scenario, we will create a department named "System Administrators," which will serve as the designated area for the Supreme Admins. Additional configurations like SLAs, managers, and email settings can be configured within the Departments tab.
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/post-install-config/assets/138411730/cc9ed856-447f-40d5-ac56-40d96d3fa7b9" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Once a new department is established, we will establish a fresh team. Teams enable the inclusion of agents from various departments, such as creating a help topic related to a specific product and assigning it to a team of specialized agents handling that particular product. To form a team, navigate to the "Agents" section and select "Teams." A Level I Support Team is already in place by default, so we will generate a Level II Team.
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/post-install-config/assets/138411730/c2e971c8-9e31-4065-afc9-bae65d2b63e1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Our next step involves creating Agents, the staff members responsible for resolving helpdesk tickets. Agents are designated to specific departments and assume primary roles in handling tickets related to their assigned departments. Moreover, Agents may be granted access to additional departments beyond their own, with varying roles based on the department they belong to. The assignment of permissions, access, and team affiliations will be carried out within the Agents tab.
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/post-install-config/assets/138411730/1396a32f-ca2d-42e2-b452-452b02486ce4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://github.com/tsiensesvendomingos/post-install-config/assets/138411730/950b5625-2274-4400-acb5-17b6b7fa436f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Following that, we will proceed with user creation. Users refer to customers who generate tickets when encountering problems. Each user is recognized by their unique email address. To create a user, navigate to the Agent Panel, select "Users," access the "User Directory," and finally click on "Add User."
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/post-install-config/assets/138411730/e1780f16-ad93-4bca-bff1-2a2316c9f5f5" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/post-install-config/assets/138411730/a70dff75-e0d0-4694-835b-2c814028649c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
The Service Level Agreement (SLA) Plans establish the timeframe for the help desk to resolve individual tickets. To create SLA Plans, navigate to the Admin Panel and access the "Manage" section, specifically the "SLA Plans" option. Each SLA Plan consists of a predefined schedule and a designated grace period. The first picture below is an example of an SLA Plan named "SEV-A," featuring a 24/7 schedule and a one-hour grace period. Two additional SLA Plans can be created to expand the available options: "SEV-B" with a 24/7 schedule and a grace period of four hours, and "SEV-C" with an eight-hour grace period that applies exclusively to business days.
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/post-install-config/assets/138411730/4d3377d5-4860-45d0-9fe0-c3bd41039a1e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/post-install-config/assets/138411730/5fcb4d8d-64fe-4cf7-8e00-fbc76a570b1a" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
The purpose of Help Topics is to assist users in organizing their tickets. We plan to establish four distinct categories (Business Critical Outage, Personal Computer Issues, Equipment Issues, and Password Reset) in addition to the default topics, from which end users can choose when submitting a problem report.
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/post-install-config/assets/138411730/d89dc7f2-cedd-43c6-b3dd-6885429bb6ce" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/tsiensesvendomingos/post-install-config/assets/138411730/507539db-6315-4d3a-a18a-acbdb367242c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<br />
