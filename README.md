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

- Install / Enable IIS in Windows with CGI
- Install PHP Manager for IIS
- Install the Rewrite Module
- Create the directory C:\PHP
- Download PHP 7.3.8 and unzip the contents into C:\PHP
- Install Microsoft Visual C++ Redistributable
- IIS Configuration
- Item 8

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/OuF5fYv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This process was done on a Virtual Machine I created through Microsoft Azure. I then connected to my virtual machine through a remote desktop connection.
To install IIS : In the search bar type "control panel" and enter program> Click "program uninstall programs" > click "Turn windows on and off"> Check the box "Internet Information Services" and expand the tab>
search for "World Wide Web Services" and expand the tab> search for "Application Development Features" and expand the tab> Check the "CGI" box> click "ok". 
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
Next, I downloaded and installed the Rewrite Module. This system will properly route the URLs in the OS Ticket web application. The Rewrite Module is required for the OS Ticket to run and function properly. 
</p>
<br />

<p>
<img src="https://i.imgur.com/F0YOTAH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To create the directory C:\PHP : Right click the manila folder on your taskbar > Click "File Explorer"> Open Tab for "This PC"> Click "Window (C:)" > Create a new folder inside "Window (C:) named "PHP"
</p>
<br />

<p>
<img src="https://i.imgur.com/ydgg3WH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, right click on "php 7.3.8-nts-Win32-VC15-x86" zip file > click "Extract All..." > click "browse > click "window (C:)" > click "PHP" folder > click "select folder" > click "Extract". After the extraction is complete, all contents from the zip folder will have successfully been added to the PHP folder that was created in the previous step. 
</p>
<br />

<p>
<img src="https://i.imgur.com/FP87hn8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I downloaded and installed Microsoft Visual C++ Redistributable. Installing this ensures that the OS Ticket system has the necessary libraries to function properly.
</p>
<br />

<p>
<img src="https://i.imgur.com/K3qZcSF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I downloaded and installed My SQL. After it was installed, I set up credentials for future use of MySQL Server. Once I configured MySQL, it created a database that OS ticket will use to store all the data (Example: user accounts, ticketing information, customer information etc.) 
</p>
<br />

<p>
<img src="https://i.imgur.com/jC5VnhB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is the final step before downloading OS Ticket. I had to do some configurations in the IIS as an Admin. Registering PHP within IIS: In the search bar on the taskbar, type "IIS"> right click on "IIS" and choose "Run as administrator"> click "PHP Manager" > click "Register new PHP version" > Click "..." to browse > click "Window (C:)"> click "PHP"> click "php-cgi" > click "ok". I reloaded the IIS after making those changes by stopping and starting the server. 
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
