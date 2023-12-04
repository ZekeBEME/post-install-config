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
- Configure Agents
- Configure Users and SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/a81nYa0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
[Go to Admin Panel -> Agents -> Roles]   Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. 
</p>
<br />

<p>
<img src="https://i.imgur.com/SXoFnhS.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
[Admin Panel -> Agents -> Teams] Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.
</p>
<br />

<p>
<img src="https://i.imgur.com/QuG5nyF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
[Admin Panel -> Agents -> Teams] Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.
</p>
<br />

<p>
<img src="https://i.imgur.com/43CWJXe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
[Admin Panel -> Agents -> Add New] Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department.
</p>
<br />

<p>
<img src="https://i.imgur.com/gkOsP0I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
[Agent Panel -> Users -> Add New] Once a user has activated their account with the help desk, Agents can administratively manage their access to the help desk; including requiring a password reset, locking them from the help desk, and even resetting their password.
</p>
<br />

<p>
<img src="https://i.imgur.com/2zElzIV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
[Admin Panel -> Manage -> SLA] SLA Plans or Service Level Agreements, are unlimited in osTicket. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.
</p>
<br />
