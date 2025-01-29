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

- Internet Information Services
- PHP(7.4 or 8.0 recommended)
- MySQL Database
- OsTicket Files


<h2>Installation Steps</h2>

<p>
<img width="1680" alt="Screenshot 2025-01-26 at 12 21 00 PM" src="https://github.com/user-attachments/assets/76e44414-cde8-4a7a-a655-de8e26431efe" />
</p>
<p>
Install / Enable IIS in Windows WITH CGI
World Wide Web Services -> Application Development Features -> [X] CGI
</p>
<br />

<p>
<img width="1680" alt="Screenshot 2025-01-26 at 12 16 15 PM" src="https://github.com/user-attachments/assets/cd28d4b3-61ce-4ddc-899d-dce1b4ba6047" />
</p>
<p>
From the “osTicket-Installation-Files” folder, install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)
From the “osTicket-Installation-Files” folder install the Rewrite Module (rewrite_amd64_en-US.msi)

</p>
<br />

<p>
<img width="1680" alt="Screenshot 2025-01-26 at 12 31 10 PM" src="https://github.com/user-attachments/assets/3bf683fc-7630-46cc-9202-74a911c1a5be" />
</p>
<p>
Create the directory C:\PHP

From the “osTicket-Installation-Files” folder, unzip PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into the “C:\PHP” folder

From the “osTicket-Installation-Files” folder, install VC_redist.x86.exe.

From the “osTicket-Installation-Files” folder, install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
</p>
<br />

<p>
https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.oreilly.com%2Flibrary%2Fview%2Fmicrosoft-iis-100%2F9781787126671%2Fad0ff9a5-87cf-4d97-8824-93001f965081.xhtml&psig=AOvVaw0P8-lJDwjZPBpAHdeaUHvA&ust=1738210934315000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCODk7L6KmosDFQAAAAAdAAAAABAE![image](https://github.com/user-attachments/assets/6c12d27d-0335-4849-a7b2-54140a6995d4)
</p>
<p>
From the “osTicket-Installation-Files” folder, unzip “osTicket-v1.15.8.zip” and copy the “upload” folder into “c:\inetpub\wwwroot”
Within “c:\inetpub\wwwroot”, Rename “upload” to “osTicket”
</p>
<br />
