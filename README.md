<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

![osticket-installation](https://github.com/user-attachments/assets/4ea8ebfa-ec6a-4873-a9d1-7055ccea910b)
![osticket-installed](https://github.com/user-attachments/assets/2e3a6780-eb5f-430c-bc63-4c58ad9fc890)


<p>

</p>
<p>
Downloading the osTicket-installation zip file so that we can install the program and its prerequisits.
</p>
<br />

<p

  
  
  ![iis prerequisit](https://github.com/user-attachments/assets/62063041-30da-4726-a66a-a53413c24fff)
![iis with cgi](https://github.com/user-attachments/assets/5870b35e-dc62-402a-b6cc-371c20bc9352)


>
</p>
IIS (Internet Information Services) is required to install osTicket because it acts as the web server that serves the application’s files to users over the internet. osTicket is a PHP-based web application, and IIS can be configured to process PHP code and handle HTTP requests. It provides the necessary environment to run the PHP scripts and deliver dynamic content such as ticketing data. Additionally, IIS helps manage security features like authentication and encryption, ensuring secure communication between users and the application. Without a web server like IIS, osTicket would not be able to function properly on a Windows server.osTicket requires IIS with CGI (Common Gateway Interface) because IIS, by default, doesn’t support PHP directly. CGI allows IIS to process PHP scripts and interact with the web server, enabling osTicket to function properly. By using IIS with CGI, PHP code can be executed on the server, generating dynamic content like ticket data and user interactions. CGI is a bridge between IIS and PHP, ensuring smooth communication between the web server and the PHP interpreter. Without CGI, IIS would not be able to execute the PHP scripts needed for osTicket to operate.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
