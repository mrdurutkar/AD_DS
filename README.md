<h1>Creating 1k+ users on Windos Server 2019 through Active Directory</h1>


<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through the accessing windows server 2019 as a domain controller. This utility allow you to create multiple users saved in the text file and common passsword (Password1) is given for simplicity. The whole local server will be configured to give access to multiple users through single client which has been granted access to connect to the server in internal network. This project make the use of different aspects to make process autonomous though Powershell script and DHCP server. Moreover, you will learn how to give administrative access to specific user and create users with limited access to resources.

- Active Directory Users and Computers
- Remote Access
- Routing and Networking
- Server Lease
- Server Manager
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Virtual Box</b>


<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows Server 2019</b> 

<h2>Program walk-through:</h2>

<p align="center">
Launch the Windows server 2019: <br/>
<img src="https://imgur.com/jfYyUjI.png" height="80%" width="80%" alt=""/>
<br />
<br />
Add Active Directory Domain Services:  <br/>
<img src="https://imgur.com/lDuL258.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Deploy AD: <br/>
<img src="https://imgur.com/vwJPJhN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure DHCP server:  <br/>
<img src="https://imgur.com/gF1GKY3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run PowerShell Code in that folder:  <br/>
<img src="https://imgur.com/XcEPx5B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creation of multiple users:  <br/>
<img src="https://imgur.com/bmyuYej.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
around 1k users are created:  <br/>
<img src="https://imgur.com/HGch6hM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Clients Ip address in internal network:  <br/>
<img src="https://imgur.com/AgJfK1P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Client can ping internet:  <br/>
<img src="https://imgur.com/AogpSCj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Tracerout on client PC:  <br/>
<img src="https://imgur.com/MIUOHDs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Tracerout on domain controller:  <br/>
<img src="https://imgur.com/2EtlF9I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
User: sdilon logged in to the DC through Client1 computer:  <br/>
<img src="https://imgur.com/rzslCmF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Another User: kpopek logged in to the DC through Client1 computer:  <br/>
<img src="https://imgur.com/aaWVExq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
AD Uers and Computer Pannel:  <br/>
<img src="https://imgur.com/v7Bbdal.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Admin logged in to Client1:  <br/>
<img src="https://imgur.com/QcBgPCG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Server Manager presenting different resources:  <br/>
<img src="https://imgur.com/sIoXPOz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
