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

- Enable certain extension
- Change Permissions
- Install HeidiSql and set up database
- Finish Setting up osTicket 
  

<h2>Configuration Steps</h2>

<p>
  
![image](https://github.com/user-attachments/assets/18b2c4d4-0b96-4090-ab65-20b22e840928)
![image](https://github.com/user-attachments/assets/cd0076dd-ef16-4d0e-862c-827c38aaf53f)
![image](https://github.com/user-attachments/assets/2d495595-4986-400c-a86b-30740a18c396)
![image](https://github.com/user-attachments/assets/372f81b4-6d76-4417-af18-a699ddd2e379)
![image](https://github.com/user-attachments/assets/46b2b964-14f3-43a7-baab-b8f2054218ab)

<p>
Back inside the IIS we will go to sites to default to osTicket and double-click PHP Manager. Click enable or disable an extension. We will enable php_imap.dll, php_intl.dll, php_opcache.dll. Once this have been enable, refresh the the browser to see the changes take affect.
</p>

![image](https://github.com/user-attachments/assets/cc6eb10f-a24c-49a9-9c00-6cb63e96e375)
<p>
Now rename the ost-sampleconfig.php to ost-config.php. We go to C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php in the folder. Double right click and select rename folder, and change it to ost-config.php. Once this done we will remove all inheritance by double right clicking and going into properties. We set new permission to everyone to all.
</p>

![image](https://github.com/user-attachments/assets/f2103f0e-5edf-4dcd-84d1-5026ddcc4f63)

<p>
Now we will set up the osTicket in the browser.
</p>

![image](https://github.com/user-attachments/assets/5231682a-5662-4200-a54c-ca35d46a1828)
![image](https://github.com/user-attachments/assets/a8d79fb5-a62c-4876-af5e-98c3f6c638ab)
![image](https://github.com/user-attachments/assets/1c32a427-8e51-4962-8946-6e24c6404654)
![image](https://github.com/user-attachments/assets/a4b763d9-b809-4079-93dc-a96c9f312786)
<p>
Finally, we will install HeidiSql. Once install create a new session and connect to the session using the username and password from the mysql we did in the begin. Create a new database name osTicket.
</p>

![image](https://github.com/user-attachments/assets/d9ba0934-838d-4802-9621-d10a3c7cdd26)
<p>
Once HeidiSql is set up. Write the information in the browser for the osTicket to collect information into database. Once completely click Install Now.
</p>

![image](https://github.com/user-attachments/assets/bb5b7c71-8b49-40f3-a1d5-bd3d1808c839)
<p>
Complete and now the osTicket is ready to be use.
</p>
