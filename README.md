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

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (For when users create a ticket)

<h2>Configuration Steps</h2>
<h3>Configure Roles (for grouping permissions)</h3>
<p>
Admin Panel -> Agents -> Roles </br>

We're creating a Supreme Admin that has full ticket and task permissions. 

</p>
<br />

<p>
<img src="https://i.imgur.com/rdGK0QB.png" height="80%" width="80%" alt=""/>
</p>

<h3>Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)</h3>
<p>
Admin Panel -> Agents -> Departments

SysAdmins
</p>
<br />

<p>
<img src="https://i.imgur.com/X1vZczQ.png" height="80%" width="80%" alt=""/>
</p>

<br />

<h3>Configure Teams</h3>
<p>
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)

Online Banking

</p>
<br />

<p>
<img src="https://i.imgur.com/xGD5cA8.png" height="80%" width="80%" alt=""/>
</p>

<br />

<h3>Allow anyone to create tickets</h3>
<p>
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 


</p>
<br />

<p>
<img src="https://i.imgur.com/xGD5cA8.png" height="80%" width="80%" alt=""/>
</p>

<br />

