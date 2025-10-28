<h1>SOC Honeynet - Lab</h1>


 
<h2>Description</h2>
The goal of this project is to design and deploy a small-scale honeynet to capture and analyze real-world cyberattacks in a controlled environment.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Microsoft Azure</b> 
- <b>Laptop or PC</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> 
- <b>Remote Desktop</b>
- <b>Azure Virtual Network</b>
- <b>Azure Virtual Machine</b>
- <b>Log Analytics Workspace</b>
- <b>Azure Monitoring Agent(AMA)</b>
- <b>Microsoft Sentinel</b>
- <b>Sentinel Watchlist</b>


<h2>Program walk-through:</h2>

<p align="center">
 Setup Azure Enviornment: <br/>
 - Create Resource Group<br/>
 - Deploy Virtual Network<br/>
 - Create virtual Machine (intentionally vulnerable)<br/>
 
<img src="https://i.imgur.com/QGW89IW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/a/aPOmchL"  height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create and configure Log Analytics Workspace:  <br/>
 - Create Log Analytict Workspace in Azure <br/>
  <br/>
 
<img src="https://i.imgur.com/iFwVGdp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Sentinal Instance<br/>
- Link log analyticts workspace to Sentinal
  
<img src="https://i.imgur.com/my7nABQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch Azure Monitoring Agent   <br/>
- Deploy AMA in sentinal<br/>
- located in content hub<br/>
- search security event(download)<br/>
- configure with Windows security event Azure Monitoring Agent(AMA)<br/>
- Open connector page <br/>
- Create data collection rule <br/>
- Select your VM and create (this takes a minute) <br/>
<img src="https://i.imgur.com/EDQTbSo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open Log Analytics Workspace  <br/>
- Click the logs tab <br/>
- Query and filter logs with KQL

<img src="https://i.imgur.com/ZAicJFN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create The Watchlist  <br/>
- The watchlist contains geographical information 
<img src="https://i.imgur.com/Z03QUSn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Size: Use at least 2vcpus  <br/>
<img src="https://i.imgur.com/v3f4bjK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  create your user name and password (take note of it in notepad)  <br/>
<img src="https://i.imgur.com/gTGwIpn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  Check the box under licensing then click 'next' through to Networking  <br/>
<img src="https://i.imgur.com/FMNpIOY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  If 'virtual network' is blank, click create new, name your network (use dashes) then use default settings seen below (click ok, then click review + create)  <br/>
<img src="https://i.imgur.com/SXiDZ7G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Confirm validation passed then click create  <br/>
<img src="https://i.imgur.com/Qlp4RYj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Once deployment is complete type virtual machines in the search bar  <br/>
<img src="https://i.imgur.com/rJAM2uS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Copy your virtual machines public IP address (example below)  <br/>
<img src="https://i.imgur.com/Z5yKllx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Search remote desktop from your computer then double click   <br/>
<img src="https://i.imgur.com/6Ppg4sx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 

