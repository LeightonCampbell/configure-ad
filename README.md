<p align="center">
<img src="https://i.imgur.com/0Kivhof.png" alt="osTicket logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Resource Group, Vnet with associated subnet, Virtual Machine running Windows Server OS
- Create second Virtual Machine that will interact with Domain Controller
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/5vAUgui.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setting the IP Address of the Domain Controller PC to static IP
</p>
<br />

<p>
<img src="https://i.imgur.com/o5XCMTi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installing Active Directory roles and services.
</p>
<br />

<p>
<img src="https://i.imgur.com/o5XCMTi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Promoting Server to a Domain Controller</h2>
</p>
<br />

<p>
<img src="https://i.imgur.com/RKc4Juj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<h2>Adding a New Forest</h2>
<img src="https://i.imgur.com/QiEeg95.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Promoting Server to a Domain Controller and adding a new forest
</p>
<br />
