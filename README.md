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

- Microsoft Azure
- Virtual Machine
- osTicket Installation Files

<h2>Installation Steps</h2>

Step 1 - Conect to your Cirtual Machine with Remote Desktop

Step 2 - Install/nable Internet Information Services in Windows

Step 3 - Download, install, and open Web Platorm Installer. Afterwards, download necassary files

Step 4 - Install osTicket v1.15.8

Step 5 - Reload IIS

Step 6 - Enable Extensions in IIS: Some extensions won't be enabled at first
    -double click PHP Manager
    -Click Enable or disable an extension under PHP Extensions
    -Right click
    -php_imap.dii, php_intl.dii, php_opacache.dii

Step 7 - Refresh the osTicket site in your browser, observe the changes

Step 8 - Rename

Step 9 - Assign Permissions: ost-config.php

Step 10 - Continue setting up osTicket in the browser

Step 11 - Download and Install HeidiSQL

Step 12: Go back to the browser and continue setting up osTicket by filling out the fields

Congratulations!!! You have completed the installation of osTicket!

