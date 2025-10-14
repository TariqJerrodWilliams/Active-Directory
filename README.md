<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Preparing Active Directory Using Azure</h1>
Here is where I demonstrate how to prepare two virtual machines to deploy Active Directory.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Prepare Active Directory With Azure](https://www.youtube.com/watch?v=EsfFDefAsPU&list=PLJdzXvmqRYWVebeb7-VDhyQAI2VtJyfGW&index=1)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- (<em>Step 1</em>) First, we have to set the Private IP Address of the virtual machine we want, <b>"dc-1"</b>, to be the domain controller to 'Static'. And the other virtual machine's, <b>"client-1"</b>, DNS Server to <b>"dc-1"'s</b> Private IP Address. 
- (<em>Step 2</em>) Next, we need to download Active Directory Domain Services and "promote this server to domain controller". 
- (<em>Step 3</em>) Lastly, we have to sign in to confirm that it has been deployed.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="[https://i.imgur.com/DJmEXEB.png](https://imgur.com/NqgBzAD)" height="80%" width="80%" alt=" Domain Controller And Client Should Be Under The Same Virtual Network."/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
