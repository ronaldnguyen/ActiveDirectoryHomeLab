<h1><p align="center">Active Directory Home Lab  <p align="left"><img src="https://user-images.githubusercontent.com/114441952/192990608-e244e216-063e-4d33-acea-bbcb7dbedf09.png" width="100"></h1>

<h2>Description</h2>
In this project, I created an Active Directory Home Lab environment through the use of Virtual Machines, to enable client users to access the internet via the virtual private network. I created one Virtual Machine to install Active Directory and to create a domain. Then I setup a NAT/RAS so clients on the private network can access the Internet through the domain controller. Then I setup a DHCP server so new users will automatically be leased an IP address when creating a Windows 10 machine. Then ran a Powershell scipt to create 1000 users in Active Directory. I created another Virtual Machine to install Windows 10, connected this machine to the domain, logged into one of the generated user accounts to test if domain controlled properly leased an IP address so that the clients can access the Internet. This project can simulate a corporate network where new hires are given domain credentials to login into a corporate computer. Another scenario that this lab can be applied is for students that given a unique student ID to login into the school's computer, accessing the private virtual network. 

<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell
- Active Directory
- CMD

</b> 

<h2>Environments Used </h2>

- <b>Windows 10
- Microsoft Server
- VirtualBox

</b> 

<h2>Lab walk-through:</h2>

<p align="center">
Creating the VM (Server and Client): <br>
<img src="https://i.imgur.com/4td0nIX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p align="center">
Rename Ethernet Adapters and Set Internal NIC to desired IP,Mask,Gateway,DNS
<img src="https://i.imgur.com/0s4KQAR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p align="center">
Configure Local Server to install Active Directory Domain Services, Remote Access, DHCP Server
<img src="https://i.imgur.com/ioQ1laD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p align="center">
Run Powershell script to create over 1000 user accounts
<img src="https://i.imgur.com/KAuFuUi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   
<p align="center">
Created second VM and gave it admin access, seeing if the domain controller properly leased an IP address
<img src="https://i.imgur.com/K1EPzvP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   
<p align="center">
Confirmed the created users and see that client computer is being properly recognized in Active Directory
<img src="https://i.imgur.com/BJH4xKP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    
<p align="center">
Confirmed the connectivity of the client computer to the Internet
<img src="https://i.imgur.com/rifKXG5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
