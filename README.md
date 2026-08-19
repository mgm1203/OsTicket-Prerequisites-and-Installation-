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
5. Install PHP Manager for IIS.
6. Create the Directory C\PHP. 
7. Install Microsoft Visual C+ and MySQL.
8. Open IIS as an Admin and Register PHP from within IIS. 
9. Download and extract osTicket.
10. Upload osTicket files to C: Drive. 
11. Access OsTicket Web browser.
12. Configure osTicket files within IIS.
13. Complete the osTicket Installation. 

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


<p align="center">
<img width="974" height="799" alt="image" src="https://github.com/user-attachments/assets/f64122ec-696f-4bd3-ab25-9bb83368c8da" />
</p>

<p align="center">
<img width="966" height="755" alt="image" src="https://github.com/user-attachments/assets/2cf792d0-bf67-42dc-8328-e58c2dfc08fe" />
</p>

Next, we will install PHP manager for IIS by clicking on PHP located in the osTicket Installation files. We will also install the Rewrite Module from the installation files folder. 

<p align="center">
<img width="975" height="514" alt="image" src="https://github.com/user-attachments/assets/25372ee6-336d-4159-8dc3-4cc915c9f77a" />
</p>

<p align="center">
<img width="975" height="816" alt="image" src="https://github.com/user-attachments/assets/4378ba8f-0125-42f6-bc15-86365e04549c" />
</p>

Next, we will create a directory on our C drive called PHP. Navigate to files and head to windows (C:) folder, create a PHP folder within the C: drive. After creating the PHP folder, in the osTicket Installation files folder you will unzip the PHP zip file into the folder that you created. 

<p align="center">
<img width="455" height="551" alt="Information Technology Course - 4 3 2 - osTicket Installation - CourseCareers - Google Chrome 8_19_2026 4_07_51 AM" src="https://github.com/user-attachments/assets/d3d5ebe0-9808-4049-8c87-5138de3667f9" />
</p>

<p align="center">
<img width="938" height="581" alt="image" src="https://github.com/user-attachments/assets/0e853d55-92ce-43de-9bff-3325e5fbad46" />
</p>

Next, you will install Microsoft Visual C++ located in the osTicket Installation folder.

<p align="center">
<img width="966" height="755" alt="image" src="https://github.com/user-attachments/assets/532ec362-2d00-49cd-91f2-e1d3a8bdae38" />
</p>

Following this step, we will also be installing MySQL located in the same installation folder. After installing MySQL Server, launch the configuration wizard of MySQL.

<p align="center">
<img width="975" height="744" alt="image" src="https://github.com/user-attachments/assets/05b30565-441e-4d41-adca-98e8535e53d3" />
</p>

<p align="center">
<img width="975" height="744" alt="image" src="https://github.com/user-attachments/assets/b80cb5e6-2258-4cf9-95bb-2c01cf3a9772" />
</p>

After clicking "Next," click Standard Configuration, shortly after we will be creating a username and password.
##### Note: In this example, I will be using the same word for my username and password (Do not do this in real-life scenario). 

<p align="center">
<img width="975" height="845" alt="image" src="https://github.com/user-attachments/assets/5c98781b-4530-49f8-8635-6e75535f85cb" />
</p>

<p align="center">
<img width="655" height="736" alt="Information Technology Course - 4 3 2 - osTicket Installation - CourseCareers - Google Chrome 8_19_2026 4_25_38 AM" src="https://github.com/user-attachments/assets/ebc4f827-5b79-400d-ab8e-d6ec06da561f" />
</p>

Next, we will be opening IIS as an admin and  Registering PHP from within IIS. Navigate to start menu and after searching IIS, click "Run as Administrator." In "PHP Manager," register a new PHP version, look for "php-cgi.exe," located in the PHP folder on the C: drive.

<p align="center">
<img width="975" height="816" alt="image" src="https://github.com/user-attachments/assets/13002711-ad9b-44e9-89fd-83f49f302431" />
</p>

The next step is to download and extract osTicket located in the installation files.

<p align="center">
<img width="975" height="514" alt="image" src="https://github.com/user-attachments/assets/054e5d40-ca66-4fa2-9285-f4bec3c7fbd9" />
</p>

<p align="center">
<img width="975" height="514" alt="image" src="https://github.com/user-attachments/assets/ee2a670b-468d-4cf8-8038-751f0d87a25a" />
</p>

Following this step, we will upload osTicket files to C: Drive.  After extracting the files, go to C: drive, and go to inetpub--> wwwroot, we will then copy the upload folder into the wwwroot folder.
##### Note: Make sure you rename the folder that was uploaded to exactly, "osTicket."

<p align="center">
<img width="827" height="782" alt="Information Technology Course - 4 3 2 - osTicket Installation - CourseCareers - Google Chrome 8_19_2026 4_45_12 AM" src="https://github.com/user-attachments/assets/36f5460f-4785-4cb0-bb4b-ea89388176bd" />
</p>

<p align="center">
<img width="975" height="524" alt="image" src="https://github.com/user-attachments/assets/30300bf7-b1bf-4d85-804d-3c2cc73a53b7" />
</p>

Next, return to IIS. Go to sites--> Default--> osTicket, towards the right of IIS you will click, ("Browse *80). This should then give you Access to the osTicket web browser.

<p align="center">
<img width="727" height="372" alt="Information Technology Course - 4 3 2 - osTicket Installation - CourseCareers - Google Chrome 8_19_2026 4_55_25 AM" src="https://github.com/user-attachments/assets/c8aa93e2-30cc-431a-8c28-87f5654de0f8" />
</p>

Next, we need to configure osTicket files within IIS correctly which entails installing extensions to ensure osTicket runs correctly. Go back to IIS, in PHP Manager, click "Enable or Disable an Extension". 


<p align="center">
<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/21c8ff08-444f-49c0-b500-ce0e07999db2" />
</p>

<p align="center">
<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/573b4a5e-3f28-4bd4-9c5a-9401e3b2d4c2" />
</p>

<p align="center">
<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/0b9ced77-ca66-4a6d-873e-157ce3eb6eb5" />
</p>

Following this step, Click to Enable: (php_imap.dll), (php_intl.dll), (php_opcache.dll).

<p align="center">
<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/b303adec-9f2f-4eb6-84e8-0ee73a27c653" />
</p>

 Be sure to refresh the osTicket site in your browser after to observe the con figured changes. The next configuration step will be to rename a certain file on the drive which enables osTicket to make configurations.

 <p align="center">
 <img width="975" height="514" alt="image" src="https://github.com/user-attachments/assets/41902bb2-cc24-4f18-8bcb-0fc4d4b8704a" />
</p>

In the C: Drive, inetpub--> wwwroot--> osTicket--> 
 From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php 
 
 <p align="center">
 <img width="975" height="514" alt="image" src="https://github.com/user-attachments/assets/56f5448c-c7ac-43b0-b9d3-097c47d5bfe3" />
</p>

 To: C:\inetpub\wwwroot\osTicket\include\ost-config.php
 
 <p align="center">
 <img width="975" height="610" alt="image" src="https://github.com/user-attachments/assets/775a2395-8958-465b-a8cb-f77909127c82" />
</p>

Following this step, we will assign permissions for osTicket to make changes to this file on the back end. Right click the renamed file and select "Properties".
Secuirty--> Advanced--> Disable inheritance--> Remove all inherited permissions.
 
 <p align="center">
<img width="975" height="610" alt="image" src="https://github.com/user-attachments/assets/8ec9aaf8-4a85-47de-a023-ca7e5d249190" />
</p>

 <p align="center">
<img width="975" height="582" alt="image" src="https://github.com/user-attachments/assets/f96801e3-4eb9-478c-9d9d-6ea7d7081934" />
</p>

Furthermore, click Add, then New Permissions--> Select a Principal. 

 <p align="center">
<img width="950" height="483" alt="image" src="https://github.com/user-attachments/assets/ba94bbb5-1dbd-4c6d-b9d2-acb68ab6dc34" />
</p>

 <p align="center">
<img width="975" height="582" alt="image" src="https://github.com/user-attachments/assets/d790b081-ab12-4dd9-9cd4-02a3d5914e54" />
</p>

Next, type "everyone," in the box granting everyone permission. Followed by this, you will check "Full Control". Be sure to Apply this new setting to the file. This will conclude the configuration steps of osTicket within IIS.
##### Note: This is not realistic to do in a real-world scenario for most ticketing systems. 

 <p align="center">
<img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/2b10b01e-772d-427b-85a9-f6b4072ee473" />
</p>

The next step is to complete the osTicket installation steps by continuing with the setup. After returning to osTicket, click continue to the next portion which will then include all the personal information needed for future users and or people to contact you for help.
##### Note: Make sure to save your username and password for the admin user account. 
