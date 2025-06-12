<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
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
- Windows 10 Pro (22H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Install Active Directory Domain services
- Created Organizational units 
- Connect Patron-1 to the Domain controller

  

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/21UDtRl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I installed Active directory domain services role using server manager on windows server and promoted the server to a domain controller. 
</p>
<br />

<p>
<img src="https://i.imgur.com/RM9Neup.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created two Organizational Units (Associates and Executives), and added a user (Ann Maxwell) with Domain Admin privileges, then i log into my domain as Ann maxwell.
</p>
<br />

<p>
<img src="https://i.imgur.com/okjE6sm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Successfully joined a client machine (Patron-1) to the domain controlled by the server, completing the domain network setup.
</p>
<br />
