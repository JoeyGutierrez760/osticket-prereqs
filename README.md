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

- Item 1 : Virtual Machine in Azure
- Item 2 : Installing ISS with CGI and HTTP Features
- Item 3 : Running Internet Information Services
- Item 4 : Setting Up MySQL Wizard

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/JoeyGutierrez760/osticket-prereqs/assets/41347751/3a0f59eb-e08e-495d-8ad8-5f20bc6d4bbb" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Creating Virtual Machine in Azure by creating resource group, windows 10 virtual machine with in 2-4 virtual CPUs & Vnet. 
</p>
<br />

<p>
<img src="https://github.com/JoeyGutierrez760/osticket-prereqs/assets/41347751/a9ef3f88-f70a-46ac-b3e2-83f08b1a10ae" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I will use these files to instill osTicket by installing and enable IIS in Windows with CGI & Common HTTP Features by selecting the files to select the each ones with be active to launch osTicket in my Azure Vitual Machine.
</p>
<br />

<p>
<img src="https://github.com/JoeyGutierrez760/osticket-prereqs/assets/41347751/5ba2f8d4-152d-4ee9-95a3-05e1265483f8" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Getting it up running to make sure its correct by checking 127.0.0.1 to make sure Internet Information Services is working to start the next progress.
</p>
<br />

<p>
<img src="https://github.com/JoeyGutierrez760/osticket-prereqs/assets/41347751/41431051-d69c-4a10-aff6-75467de26daa" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After downloading and installing PHP 7.3.8 for PHPManagerForIIS to start the process of MYSQL 5.5.62 with step by step. Typical Setup, Launch Configuration Wizard, Standard Configuration & setup with a password for the open IIS as An Admin to register PHP from with IIS.
</p>
<br />
