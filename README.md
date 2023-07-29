<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- Internet Information Services (IIS)
- PHP Manager
- VC Redist
- MySql
- Heidi Sql
- osTicket v1.15.8
- Link to downloads:
  https://drive.google.com/drive/u/0/folders/1APMfNzcxZC6EzdaNfdZsUwxWYChf6

<h2>Installation Steps</h2>

<p> 
  In this tutorial I will install osTicket on a Azure VM (Virtual Machine). This tutorial assumes you have already created a VM, are logged in to it, and have installed files for osTicket.

<br />

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1. Install / Enable IIS in Windows with CGI (World Wide Web Services -> Application Devlopment Features -> [X] CGI)
  
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2. From the installation files, install PHP Manager for IIS 
  (PHPManagerForIIS_V1.5.0.msi)
  
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3. From the installation files, install the Rewrite Module (rewrite_amd64_en-US.msi)
  
</p>
<br />
