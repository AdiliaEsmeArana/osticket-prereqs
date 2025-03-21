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

- Install / Enable IIS in Windows wit CGI
- Install PHP Manager for IIS
- Install the Rewrite Module
- Create the directory C:\PHP
- Download PHP 7.3.8 and unzip the contents into C:\PHP
- Item 6
- Item 7
- Item 8

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/OuF5fYv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This process was done on a Virtual Machine I created through Microsoft Azure. I then connected to my virtual machine through a remote desktop connection.
To install IIS:  
In the search bar type "control panel" and enter program. Click "program uninstall programs" > click "Turn windows on and off" Check the box "Internet Information Services" and expand the tab.
Search for "World Wide Web Services" and expand the tab. Search for "Application Development Features" and expand the tab. Check the "CGI" box and click "ok". 
The changes applied will begin to load and IIS will be successfully installed. 
</p>
<br />

<p>
<img src="https://i.imgur.com/bl6ilwQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I downloaded and installed PHP Manager for IIS. 
</p>
<br />

<p>
<img src="https://i.imgur.com/71on3qz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I downloaded and installed the Rewrite Module. This system will properly route the URLs in the OS Ticket web application. The rewrite module is required for the OS Ticket to run and function properly. 
</p>
<br />

<p>
<img src="https://i.imgur.com/F0YOTAH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To create the directory C:\PHP: Right click the manila folder on your taskbar > Click "File Explorer"> Open Tab for "This PC"> Click "Window (C:)" > Create a new folder inside "Window (C:) named "PHP"
</p>
<br />

<p>
<img src="https://i.imgur.com/ydgg3WH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, extract all files from "php 7.3.8-nts-Win32-VC15-x86" zip file > click "browse > click "window (C:)" > click "PHP" folder > click "select folder" > click "Extract". After the extraction is complete, all contents from the zip folder will have successfully been added to the PHP folder that was created in the previous step. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
