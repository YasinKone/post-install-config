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

- Item 1: A VM from Microsoft Azure
- Item 2: Osticket Installed
- Item 3: Acoount made on Osticket


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/ScpK8SQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Make roles (I did Supreme Admin) by going to Admin Panel -> Agents -> Roles, then make a department (I did system administartors) by going to Admin Panel -> Agents -> Departments, make teams by going to Admin Panel -> Agents -> Teams
</p>
<br />

<p>
<img src="https://i.imgur.com/WuAnQcR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone who is registered to create tickets by going to Admin Panel -> Settings -> User Settings (check the Require registration and login to create tickets box), Make agents (I did Jane and John) by going to Admin Panel -> Agents -> Add New, and then make users (I did Karen and Ken) by going to Agent Panel -> Users -> Add New.


</p>
<br />

<p>
<img src="https://i.imgur.com/2oCanAt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Make three SLAs with their respective attributes Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours) by going to Admin Panel -> Manage -> SLA and then make tickets (I did Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset) by going to Admin Panel -> Manage -> Help Topics




</p>
<br />
