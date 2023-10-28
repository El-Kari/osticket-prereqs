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

- Enable internet information services
- Install web platform installer
- Install mySQL: Setup username and password
- Configure permissions and install OS ticket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/5o91XTQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I enabled internet information services in order to create a web server that allows the computer to serve up websites. This is essential, it is basically the infrastructure that is required to run OS ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/t1K50nN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The PHP manager is imperative for the OS ticket software to work correctly. Apart of the OS ticket software there is a special configuration that utilizes PHP apart of its installation process, it is a requirement for OS ticket to work. 
</p>
<br />

<p>
<img src="https://i.imgur.com/BVzumZW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When interacting with OS ticket there needs to be a database storage system in place. MySQL server is used to store application data, when an admin is creating and resolving tickets that information needs to be held.
</p>
<br />

<p>
<img src="https://i.imgur.com/dX1XZ86.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
OS Ticket has been successfully installed.  
</p>
<br />

<p>
<img src="https://i.imgur.com/Lt3OIsL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/rxD9UsT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Manipulating the permissions to allow anyone to complete the setup of OS ticket, not only the admin.
</p>
<br />

<p>
<img src="https://i.imgur.com/aru25pp.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installing HeidiSQL in order to actually interact with the MySQL database. After completing this step, the prerequisites for install OS ticket is finally complete.
</p>
<br />
