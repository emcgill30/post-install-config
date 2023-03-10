<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2




<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/IaBEj8n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This will be the post-install part of the osticket lab. We're going to configure rolls. Rolls are permissions granted to agents per Department that they have access to. Create roll supreme admin. We will have a roll that can pretty much do everything. Tickets are routed through department. Go to admin panel, agents, departments. By default there is maintenance, and Support. You can come back to this if you want to configure SLA's.
</p>
<br />

<p>
<img src="https://i.imgur.com/Tm1V0rA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we can configure "teams." We can make a new team called, level two support. We're to configure it to where anyone can create tickets even if they're not a user in the system. Admin panel>settings>user settings. Next we're going to configure agents, and how you do that is, go to agents, add new. Add whatever name you want to. SLA's can be configured by going to, Admin Panel, Manage, SLA. You and can configure the the severity and the time in which it needs to be completed
</p>
<br />

