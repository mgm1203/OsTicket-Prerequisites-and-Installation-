<img width="700" height="200" alt="image" src="https://github.com/user-attachments/assets/1f991eb1-6421-47e5-92d3-b5abb18ac1ac" />

# OsTicket-Prerequisites-and-Installation-
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.

# Goal: 
The goal of this project is to gain hands-on experience deploying an IT help desk ticketing system and understanding the software prerequisites required for osTicket to operate successfully.

# Environments and Technologies Used
* Microsoft Azure (Virtual Machines/Compute)
* Internet Information Services (IIS)
* Azure Virtual Machines
* Azure Resource Groups
* Azure Virtual Network
* Windows Server
* PHP
* PHP Manager for IIS
* MySQL
* osTicket
* Remote Desktop Protocol (RDP)
* Web Browser

# Operating Systems Used
* Windows Server — Azure Virtual Machine used to host osTicket
* Windows 10/11 — Local computer used to remotely access and manage the server

# High-Level Deployment and Configuration Steps
1. Create an Azure Resource Group.
2. Deploy a Windows Server Virtual Machine.
3. Download osTicket Installation Files.
4. Enable IIS in Windows with CGI.
5. Install PHP.
6. Install PHP Manager for IIS.
7. Install the required PHP extensions.
8. Install IIS URL Rewrite.
9. Install and configure MySQL/MariaDB.
10. Download and extract osTicket.
11. Configure osTicket files within IIS.
12. Access the osTicket web installer.
13. Configure the osTicket database connection.
14. Complete the osTicket installation.

# Deployment and Configuration Steps

<p align="center">
<img width="1920" height="1008" alt="Create a virtual machine - Microsoft Azure - Google Chrome 8_19_2026 3_24_31 AM" src="https://github.com/user-attachments/assets/29ea1b6a-91c4-4086-81e5-7de2a8164d8a" />
</p>

The first step is to create a resource group in azure so we can then move to step 2 and deploy a virtual machine. 
##### Note: You can create a virtual machine first while creating a resource group by simply clicking on "Create New," under Resource Group tab. 
This then completes both steps simultaneously and after your group is deployed we can move to step 3.

<p align="center">
<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/13ad4603-c1ba-43c8-96c2-c25df2dfd995" />
</p>

<p align="center">
<img width="975" height="816" alt="image" src="https://github.com/user-attachments/assets/c797c8f6-ec36-416c-9806-f75875a1f431" />
</p>

Next, after connecting to your Remote Desktop, download the OsTicket Installation files and extract the file to your desktop.

<p align="center">
<img width="630" height="505" alt="Information Technology Course - 4 3 2 - osTicket Installation - CourseCareers - Google Chrome 8_19_2026 3_44_42 AM" src="https://github.com/user-attachments/assets/c032a57a-aff0-4003-9ab7-32f1b7abbf65" />
</p>

<p align="center">
<img width="975" height="281" alt="image" src="https://github.com/user-attachments/assets/a2bf7c90-d182-4ac9-948a-7faa8adcec3f" />
</p>

Next, we will enable IIS in windows with CGI. Navigate to control panel through windows start menu and select "Programs." You will then click, "Turn Windows Features On or Off," through there you will see IIS (Internet Information Services). Through this tab continue to enable CGI, (World Wide Web Services--> Application Development Features--> CGI). Install CGI, after you will be able to view IIS by typing your virtual machine's IP Address in the web browser. 



