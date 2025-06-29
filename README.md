<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- configure roles to navigate osTicket
- configure departments for types of adminstration 
- configure teams for different work related objectives
- configure agents and users 
- setup SLA 

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In osTicket we need to allow certain permissions to the agents and users so in the agent panel from there we can give access or restrict access to users. from there we can also add roles with a whole list of permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Starting out we can make a supreme admin so we will go the admin panel and go to agents and we can make a new agent Trace and we will make him supreme admin. In the departments this allows us to give access to certain permissions like ticket visibility, sysadmins and networking. Teams allows for easier grouping of agents on projects. We can make users for a certain department like maintenence and support to easier help clients, we'll go to the agent panel- users- add new. We will create Sierra and Rio as users. Like the teams I mentioned earlier we will add Sierra to the online banking team and Rio to the Business team.
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring SLA is very simple. We go the the admin panel- manage- SLA- then click add new SLA plan. There will be differnt kinds of SLA in the workplace so we will do SEV-B. SEV-B is the most common of the SLA you will need to contact the user every 4 hours and it will be on a 24/7 basis. SLA really all comes down to how important or big issue is in the workplace. You can also make help topics for the user if they are having trouble they can click on our tab that we can create, so we will go to admin panel- manage- help topics. We will create tabs that have password reset/ equipment reset/ computer issues/ business critical outages/ other. This way it will give the user some tips while they wait to get in contact with an IT professional.
</p>
<br />
