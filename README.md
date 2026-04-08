<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This screen appears when you first launch the osTicket installer in your browser.

It verifies whether your server meets minimum requirements, such as:
PHP (usually 8.x)
MySQL database
Required PHP extensions (mysqli, XML, JSON, etc.)
Items marked with ✅ mean everything is correctly configured.
If there are ❌ errors, installation cannot proceed until they are fixed.


osTicket automatically checks your environment before installation to prevent failures later.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>This screen (or similar documentation view) shows what you must install before running osTicket.

Typical requirements:

Web server: Apache / IIS
PHP: 8.1–8.4 (modern versions)
Database: MySQL 5.5+
PHP extensions (e.g., IMAP, XML, GD)


These are external dependencies—you must install and configure them manually (e.g., using XAMPP, WAMP, or LAMP stack).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>This screen appears after completing the installation process.

osTicket has successfully:
Created the database
Written the configuration file (ost-config.php)
Installed core components
You click “Finish” to complete setup.



Delete the /setup folder (security step)
Log in to the admin panel
Start configuring your helpdesk system
</p>
<br />
