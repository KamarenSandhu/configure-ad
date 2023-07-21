<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines some of the steps needed for the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (22H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Create Virtual Machines
- Step 2: Install Active Directory
- Step 3: Create an Admin and Normal user account in AD

<h2>Deployment and Configuration Steps</h2>

<h3>Create Virtual Machines</h3>
<p>
<img src="https://i.imgur.com/3kOUMl1.png" width="80%" alt="Create Virtual Machines"/>
</p>
<p>
Similar to before you will need to create two virtual machines. One virtual machine will be with Windows 10 and the other will be in the Windows Server. 
</p>
<br />

<h3>Install Active Directory</h3>
<p>
<img src="https://i.imgur.com/CzW7ZoM.png" height="80%" width="80%" alt="Install Active Directory"/>
</p>
<p>
Install Active Directory from the server manager via your remote desktop connection to your virtual machine.
</p>
<br />

<h3>Create Admin and Normal User Account in AD</h3>
<p>
<img src="https://i.imgur.com/CgXnzt2.png" height="80%" width="80%" alt=" Create Admin and Normal User Account in AD"/>
</p>
<p>
Create a User account in the admin folder and adjust the properties to create an admin. Repeat for the user account in the employee folder.
</p>
<br />
