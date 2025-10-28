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
 
<img src="https://i.imgur.com/vVdHptw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create and configure Log Analytics Workspace:  <br/>
 - Create Log Analytict Workspace in Azure <br/>
  <br/>
 <img src="https://i.imgur.com/kF8iDNZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
Create Sentinal Instance<br/>

  
<img src="https://i.imgur.com/MzOV5Ff.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch Azure Monitoring Agent   <br/>
- Deploy AMA in sentinal<br/>
- click content hub<br/>
- search security events(download)<br/>
- configure with Windows security event Azure Monitoring Agent(AMA)<br/>
- Open connector page <br/>
- Create data collection rule <br/>
- Select your VM and create (this takes a minute) <br/>
<img src="https://i.imgur.com/ojrq2pz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open Log Analytics Workspace  <br/>
- Click the logs tab <br/>
- Query and filter logs with KQL

<img src="https://i.imgur.com/Y9p5SPx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create The Watchlist  <br/>
- The watchlist contains geographical information of where attackers are located.
<img src="https://i.imgur.com/W4LGOMs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Create Workbook  <br/>
 - Create workbook to ultimatley view attacker information plotted on a map in realtime.<br/>
 - I recommend leaving virtual machine runnung for at least 12-18 hours before reviewing results.
<img src="https://i.imgur.com/Rzfsvii.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 
