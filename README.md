<h1>SOC Honeynet - Lab</h1>


 
<h2>Description</h2>
Project consists of a lab that walks the user through creating a SOC Honeynet. The lab allows you to follow a step by step guide ......
<br />


<h2>Languages and Utilities Used</h2>

- <b>Microsoft Azure</b> 
- <b>Laptop or PC</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> 
- <b>Remote Desktop</b> 

<h2>Program walk-through:</h2>

<p align="center">
Launch Azure and search Resource Groups: <br/>
<img src="https://i.imgur.com/QGW89IW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Resource Group: Use dashes when naming resource group then choose region  <br/>
<img src="https://i.imgur.com/iFwVGdp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm Resource Group creation: Take note of the location then search virtual machines in search bar <br/>
<img src="https://i.imgur.com/my7nABQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a Virtual Machine: Select the resource group you just created to house your VM  <br/>
<img src="https://i.imgur.com/EDQTbSo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Use dashes when naming your VM (make sure region matches with resource group location)  <br/>
<img src="https://i.imgur.com/ZAicJFN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Image: Use the Windows 10 Pro, version 22H2 - x64 Gen2  <br/>
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
 Paste virtual machines public IP address then click connect  <br/>
<img src="https://i.imgur.com/JcVeodK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Click more choices then enter user name and password you created for VM (use notepad to keep track of username and password)  <br/>
<img src="https://i.imgur.com/stVRH9H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Click yes (let VM connect)  <br/>
<img src=https://i.imgur.com/6zLHZce.png"" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the the virtual machine   <br/>
<img src="https://i.imgur.com/f4iHZG2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

