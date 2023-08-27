<p align="center">
<img src="https://i.imgur.com/jw8VmsV.jpg" alt="wazuh logo"/>
</p>

<h1>Wazuh - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source SIEM, Wazuh.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: you need this FREE CyberSecurity tool (https://www.youtube.com/watch?v=3CaG2GI1kn0)

<h2>Environments and Technologies Used</h2>

- Linode (Virtual Machines/Compute)
- Docker
- CLI

<h2>Operating Systems Used </h2>

- Ubuntu 22.04 LTS</b> (21H2)

<h2>List of Prerequisites</h2>

- Linode Account

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/bk4qP9E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/kdI77px.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/dR9NKJS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Linode and make a free account. Free account will give you $100 credit for 60 days. Once that is created you will then go to create Linode. Go to marketplace. Search and select Wazuh. After selected you will configure the linode. Use Ubuntu 22.04 LTS. As for plan select anywhere from 2GB to 8GB I run it with 2GB just fine. 
</p>
<br />

<p>
<img src="https://i.imgur.com/SsVlBIG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/W8bLh5n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/zskAsXH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that you've created the linode. You are going to open your terminal and sign into the ssh shown. After in you are going to put in the command ls -al. input the next command cat .deployment-secrets.txt and look for admin username and password. copy and paste that information into a text format. You will need it later. You will go back to the linode dashboard and grab the reverse DNS from the network tab at the bottom. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/chyaFyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/chyaFyl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With the reverse DNS you will copy and paste it into a new tab using https://*insert reverse dns*. Insert the Admin user and password from the terminal to get in. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
