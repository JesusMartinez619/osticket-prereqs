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

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Create Virtual Machine for OsTicket
- Download osTicket Installation File
- Installing/Enabling IIS
- Installing files from within [osTicket download]
- Unzip osTicket file
- Open osTicket
- Final setup (Helpdesk name/Admin User/Install HeidiSQL)
- Login

<h2>Installation Steps</h2>

- First I created a virtual machine in microsoft azure, the machine that it was built under was (Windows 10 Pro, Version 22H2 - x64 Gen2), I then login to the virtual machine where I will be demonstrating the process of installing osTicket.

![Screenshot 2024-12-23 234214](https://github.com/user-attachments/assets/09282e4b-d76f-4234-ab10-2085dd823396)

- I then proceed to download the osTicket Installation files provided

<img width="789" alt="image" src="https://github.com/user-attachments/assets/41ac96b9-65bf-4b32-92ba-1a344399b3ec" />

- Next I install/enable IIS with CGI, IIS enables a web server that will allow me to run osTicket from the web.

<img width="190" alt="image" src="https://github.com/user-attachments/assets/2d639f11-db61-42d4-ac06-bfb6fdc68824" /> 


- From the [osTicket installation file] I downloaded I start to install the files within. We download PHP manager to allow registration to IIS and allows proper configuration of the other files.

<img width="225" alt="image" src="https://github.com/user-attachments/assets/dcb4b9be-9ee1-4f89-9763-a405864d7b85" />
  <img width="427" alt="image" src="https://github.com/user-attachments/assets/0be14045-2320-4728-a5e1-d1e524a09b74" />
<br />

- I then unzip the osTicket folder where it then starts extrating all its files into a new folder named "upload" I then drag that new folder over to (c:\inetpub\wwwroot) and rename the folder to "osTicket"

<img width="362" alt="image" src="https://github.com/user-attachments/assets/373b8231-453b-4d7c-b089-f7e8c7e63b6f" /> 
<img width="421" alt="image" src="https://github.com/user-attachments/assets/5353607c-d073-4762-ad5c-34d84307b2c8" /> 
<img width="317" alt="image" src="https://github.com/user-attachments/assets/a1b69606-1cda-4c37-8b41-098fe80b3972" />
<img width="311" alt="image" src="https://github.com/user-attachments/assets/551abc44-ac94-439b-b8cd-0903cec47278" />

- I open IIS manager where the osTicket software was installed and open through "Browse 80 (http)", giving us access to the official web page where we will finalize the osTicket installation.

<img width="428" alt="image" src="https://github.com/user-attachments/assets/895f68f1-8294-4f0c-bcd8-4180b0b0d166" /> <img width="389" alt="image" src="https://github.com/user-attachments/assets/b63164e3-a5f1-4317-985a-c476f5a751f2" />

- I first create the Helpdesk name, I then create an Admin user which will be the primary account used to login as an administator. I then install "HeidiSQL" which will allow us connection to our database and configuration power. Now I am finally done installing osTicket and it sends me to the page congradulating me!


<img width="419" alt="image" src="https://github.com/user-attachments/assets/59731bf4-960d-44dd-9d29-d43cffeac3da" /> <img width="311" alt="image" src="https://github.com/user-attachments/assets/94dcfe25-70ba-4367-ba9e-413d28ecddc2" /> <img width="406" alt="image" src="https://github.com/user-attachments/assets/6e324cca-0a1f-439a-a3d6-b93d3fb98eb7" />

- login

<img width="407" alt="image" src="https://github.com/user-attachments/assets/3b40fc8b-27f1-4fec-9a4b-9df227d6bf14" /> <img width="416" alt="image" src="https://github.com/user-attachments/assets/e61b57fd-fc6b-446e-8177-317ac3d22007" />

