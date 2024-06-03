<h1>Network Analysis - Web Shell (Easy)</h1>

 <!-- ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)/> -->

<h2>Description</h2>
The SOC received an alert in their SIEM for ‘Local to Local Port Scanning’ where an internal private IP began scanning another internal system. Can you investigate and determine if this activity is malicious or not? You have been provided a PCAP, investigate using any tools you wish.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Wireshark</b> 
- <b>TCPDump</b>

<h2>Environments Used </h2>

- <b>Windows 11</b>

<h2>Program walk-through:</h2>

<p align="center">

<h3>Q1) What is the IP responsible for conducting the port scan activity?</h3>
<b>Investigate conversations </b>
** Looking for IP address scanning ports on another IP address <br />
** Statistics > Conversations > TCP <br />
** Sort on targets (B) port list - See port scanning from 10.251.96.4 <br /> <br />
<img src="https://github.com/nickstrunk/Network-Analysis-Web-Shell-Easy-/assets/165805194/73fb6af0-40a6-4b55-a104-7aacf27c3c45" height="80%" width="80%" alt="Planning Diagram"/>
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
