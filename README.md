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
3. Install and configure IIS.
4. Install PHP.
5. Install PHP Manager for IIS.
6. Install the required PHP extensions.
7. Install IIS URL Rewrite.
8. Install and configure MySQL/MariaDB.
9. Download and extract osTicket.
10. Configure osTicket files within IIS.
11. Access the osTicket web installer.
12. Configure the osTicket database connection.
13. Complete the osTicket installation.

# Deployment and Configuration Steps

<p align="center">
<img width="1920" height="1008" alt="Create a virtual machine - Microsoft Azure - Google Chrome 8_19_2026 3_24_31 AM" src="https://github.com/user-attachments/assets/29ea1b6a-91c4-4086-81e5-7de2a8164d8a" />
</p>

The first step is to create a resource group in azure so we can then move to step 2 and deploy a virtual machine. 
##### Note: You can create a virtual machine first while creating a resource group by simply clicking on "Create New," under Resource Group tab. 
This then completes both steps simultaneously and after your group is deployed we can move to step 3. 
