# Azure---VM---Webserver

Azure - Create a Virtual Machine and Deploy a Web Server

## Introduction

<b>Create a Virtual Machine in Azure to deploy a web server, specifically a Nextcloud server. Instead of using just the presets, you will explore how the basic architecture of Azure works, by creating a Virtual Machine, connecting it to a subnet, protected by inbound and outbound rules thanks to Network Security Groups, in a Virtual Network. You'll also learn how to use Bastion to connect to the machine via SSH, without exposing an external port to the Internet, and then installing a simple Nextcloud server and make the Virtual Machine available to you by opening a public IP and a DNS label.
</b>



# Create a Virtual Machine and Deploy a Web Server



## Steps

<br/>

- Create a Resource Group

<img src="https://i.imgur.com/WsRCtCR.png">
  
- Create a Virtual Network and a subnet

<img src="https://i.imgur.com/LuHhr21.png">
  
- Protect a subnet using a Network Security Group

<img src="https://i.imgur.com/TDccB3l.png">

- Deploy Bastion to connect to a Virtual Machine

<img src="https://i.imgur.com/WiH7Rx2.png">
  
- Create an Ubuntu Server Virtual Machine

<img src="https://i.imgur.com/hTpltO4.png">

- Install Nextcloud by connecting via SSH using Bastion

<img src="https://i.imgur.com/M1YVTMK.png">
  
- Publish an IP

<img src="https://i.imgur.com/JtDWqcj.png">
  
- Create a DNS label

<img src="https://i.imgur.com/wDgCb1L.png">
  
<br />

## Conclusion
