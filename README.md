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

- Microsoft Azure Subscription
- Resource Group
- Virtual Network
- Virtual Machine
- Microsoft Remote Desktop

<h2>Installation Steps</h2>

<p>
<img src= "https://i.imgur.com/W4rZQua.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Upon provisioning a resource group within the Microsoft Azure environment, a virtual network is established as an integral component. Subsequently, the creation of a virtual machine ensues, facilitating remote desktop access as per our operational requirements.
</p>
<br />

<img src= "https://i.imgur.com/sjz9G47.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
</p>  
 To gain access to Remote Desktop for our virtual machine hosted within Azure, it is essential to acquire the public IP address assigned to the virtual machine. This public IP address serves as the endpoint through which remote connections are established. 
 </p> 
 </p>
   
<img src= "https://i.imgur.com/rDCHWvL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  
</p>
<p>
Upon obtaining the public IP address, it can be seamlessly integrated with the Remote Desktop Protocol (RDP), facilitating the initiation of remote desktop sessions. Subsequently, users can utilize their designated credentials, previously established during the virtual machine's configuration, to securely log in and access the system remotely.
</p>
<br />

<p>
  
  <img src= "https://i.imgur.com/Z9cl0LP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To establish a robust environment for hosting osTicket, a comprehensive setup is initiated. This begins with the installation and enabling of Internet Information Services (IIS) on Windows, ensuring that essential features such as CGI and HTTP are enabled to facilitate web application hosting. Additionally, a MySQL database is configured to serve as the backend infrastructure, storing and managing data vital for osTicket's operations. 
</p>
<br />
