<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Installation of Ticketing System</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket. Once the Ticketing System is installed, I adjust user permissions.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Summary with Images</h2>

- Setup Virtual Machine in Azure
- Log into the VM with Remote Desktop
- Install / Enable IIS -Internet Information Systems in Windows WITH CGI -Common Gateway Interface
- Register PHP -a popular scripting language- from within IIS
- Assign Permissions: ost-config.php


<h2>Installation Steps</h2>

Summary: I log into Azure and setup a vitual machine. Next I setup the osTicket requirments on the VM including a database and web server. I  then download osTicket, install it and explore its interface. I am able to setup and adjsust users permimssions.  

I created a new virtual machine in the Azure cloud.

![Creating a Virtual Machine](https://github.com/user-attachments/assets/64d95edd-83be-42dd-8e1b-8b83e623fa31)
<br />


</p>
<p>

Next I logged into the virtual machine using the remote desktop protocol.

![RDP](https://github.com/user-attachments/assets/4b5ce5a8-2c9f-4be1-9be6-7e6cd063fd66)

![Virtual Machine Desktop](https://github.com/user-attachments/assets/c14578c5-8e69-4d6e-8589-37a22043a3c7)


I installed and enabled IIS - Internet Information Services. This is a web server that allows me to host the Ticketing applicaiton. 

![Setup of IIS](https://github.com/user-attachments/assets/f6cd818f-a10c-463b-9f81-83805030db17)


While installing IIS and also activate CGI - Common Gateway Interface. This interface enables the IIS server to run the ticketing application. 

![Turn on IIS and CGI](https://github.com/user-attachments/assets/2536e671-350d-46a9-8491-a841f49b3a53)


I registered PHP in IIS. This is a scripting language that the ticketing application will use. 

![Registering PHP](https://github.com/user-attachments/assets/c048a0f1-1871-4a7c-9a2c-85759eb0a555)



I assigned permissions for using the ticketing system.

![Setting up permission for help desk](https://github.com/user-attachments/assets/8764f58b-fe74-4074-b6ea-355ffe6c7e9a)


Finally I located osTicket in the IIS interface and was able to launch the appliation.

![Locating osTicket in IIS interface](https://github.com/user-attachments/assets/f30a59ca-5cc1-4077-8323-bd0911bcbb93)


![HelpDesk Ticketing Interface](https://github.com/user-attachments/assets/637a7884-8556-4d31-a059-108b21e4938f)


