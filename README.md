<h1>Network Analysis - Web Shell (Easy)</h1>

 <!-- ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)/> -->

<h2>Description</h2>
In this lab we're going to walk through how to create an Active Directory home lab environment using
Oracle Virtual Box. Configuring and running this lab will definitely help your understanding of how 
active directory and windows networking works, so I'd highly recommend running through it a couple times,
ask questions where stuff is unclear, and eventually try to build your own without watching. Please let
me know if you have any questions!
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
 
<b>Preplanning of Project:</b> <br/>
<img src="https://github.com/nickstrunk/ActiveDirectoryLab/assets/165805194/b7fdcb80-8215-4dc0-97c4-d26252a353cb" height="80%" width="80%" alt="Planning Diagram"/>
<br />
<br />
 
<b>DC Installation (Server ISO):</b>  <br/>
<img src="https://github.com/nickstrunk/ActiveDirectoryLab/assets/165805194/8679325e-bd56-47df-b4cc-43c1231c8c47" height="80%" width="80%" alt="DC Installation"/>
<br />
<br />
 
<b>Set Up IP Addressing:</b> <br/>
<img src="https://github.com/nickstrunk/ActiveDirectoryLab/assets/165805194/0e89e34f-1e39-4e07-a98b-c96f3da20198" height="80%" width="80%" alt="Network Interface Cards"/>
<br />
<br />
* No default gateway because the domain controller serves as the default gateway
<br />
* Active directory automatically installs DNS, so there server will use itself as the DNS server. Can use either its own IP address (172.16.0.1) or loopback address (127.0.0.1)
<br />
<br />
<img src="https://github.com/nickstrunk/ActiveDirectoryLab/assets/165805194/1914bbad-8393-437e-ad44-ef71e65595b2" height="80%" width="80%" alt="Internal Addressing"/>
<br />
<br />

<b>Renamed PC:</b>  <br/>
<img src="https://github.com/nickstrunk/ActiveDirectoryLab/assets/165805194/d73f7998-b974-4930-93da-c0924a72847d" height="80%" width="80%" alt="Renamed PC"/>
<br />
<br />

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
