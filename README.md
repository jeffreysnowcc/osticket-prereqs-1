<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/m5kTKQsuC4M)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Department, and Teams
- Creating Agents to work the tickets
- Service Level Agreement in osTicket
- Creating Help Topics


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/skH6nst.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Roles, Departments, and Teams are important in osTicket to determine each action an Agent will have to work a ticket
</p>
<br />

<p>
<img src="https://i.imgur.com/d3wQFul.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Each Agent is given access to the help desk with the intend to respond and resolve tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the tickets/tasks routed to that department.
</p>
<br />

<p>
<img src="https://i.imgur.com/1l9XMH0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.
</p>
<br />
<p>
<img src="https://i.imgur.com/Nj3k75W.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help Topics will determine what Department the ticket is routed to which will determine which Agents have access to the ticket. The Help Topic also can determine other configurations of the ticket, such as the ticket SLA (Service Level Agreement) and priority of a ticket, i.e. Emergency to Low
</p>
<br />                                                                                                 
