<p align="center">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/556252cb-981e-4992-9262-305d5013b854">


</p>

<h1>Azure: Create a Virtual Machine and Deploy a Web Server</h1>
In this tutorial, we create a Virtual Machine in Azure to deploy a web server, specifically a Nextcloud server. We will also observe how to use Bastion to connect to the machine via SSH, without exposing an external port to the Internet, and then installing a simple Nextcloud server and make the Virtual Machine available.  <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure VM
- Virtual Network
- Bastion
- Network Protocol (SSH)

<h2>Operating Systems Used </h2>

- Ubuntu Server
- Nextcloud

<h2>High-Level Steps</h2>

-Task 1: Create a Resource Group

-Task 2: Create a Virtual Network and a subnet

-Task 3: Protect a subnet using a Network Security Group

-Task 4: Deploy Bastion to connect to a Virtual Machine

-Task 5: Create an Ubuntu Server Virtual Machine

-Task 6: Install Nextcloud by connecting via SSH using Bastion

-Task 7: Publish an IP

-Task 8: Create a DNS label

<h2>Actions and Observations</h2>

<p>
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/f71be315-3a9c-4d99-b026-840fd326bb64">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/66735504-bc37-435f-8bc4-c0ab5969e242">

</p>
<p>
Task 1.
</p>
<br />

<p>
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/7624304b-3c63-46f0-bc48-4dea52f67de3">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/36a7d2d4-9eb0-4c9a-b0e4-2c2b0c45b20c">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/e66f4f13-5eb4-4296-9a2c-11e823fd1c6e">

  
</p>
<p>
Task 2.
</p>
<br />

<p>
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/d20fd8e1-17a9-4ef9-89b5-e568b3e26947">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/03bf3e9d-f270-4c0a-883d-5b609eb98415">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/b1a0f8e5-bd30-430f-acbf-f58e391f5d53">



</p>
<p>
Task 3.
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


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

