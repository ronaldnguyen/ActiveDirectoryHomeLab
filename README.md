<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
In this project, I created an Active Directory Home Lab environment throught the use of Virtual Machines. Using Orcale VM VirtualBox, I created 2 VMs to host the Microsoft Server and to configure my Active Directory Network as well as one VM for an example Microsoft client. After setting up the network environment I ran a Powershell scrip to generate over 1000 users and logged into one of these users on my client VM, giving myself user access to resources on the network. This lab can simulate a business onboarding process which can automatically create a unique user access and give permitted access to resources to the business domain upon hiring.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell
- Active Directory
- CMD</b> 

<h2>Environments Used </h2>

- <b>Windows 10
- Microsoft Server
- VirtualBox</b> 

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
  Confirmed the connectivity of the client computer
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
