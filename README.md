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

- Configure basic system settings, including helpdesk name, email, and default preferences
- Set up user roles, permissions, and departments for efficient ticket management
- Configure email settings to enable ticket creation and notifications via email
- Customize ticket settings, including SLA plans, priorities, and help topics
- Secure and optimize the system by removing setup files and adjusting access controls

<h2>Configuration Steps</h2>

<p>
<img width="1378" height="1120" alt="image" src="https://github.com/user-attachments/assets/04f5f586-f8fb-4191-a360-2b712417410f" />
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
<img width="2171" height="1009" alt="image" src="https://github.com/user-attachments/assets/29a4b353-3846-41e0-8611-ce9bf1c6a76c" />



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
<img width="939" height="804" alt="image" src="https://github.com/user-attachments/assets/627cb0cc-a06c-4c23-a3b1-663571df657f" />

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
