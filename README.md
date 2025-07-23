<h1>Azure: Create a Virtual Machine and Deploy a Web Server</h1>
Azure：建立虛擬機器並部署 Web 伺服器
<br />


<h2>Outline 簡介</h2>

This project involved deploying an Ubuntu Server virtual machine on Microsoft Azure, configuring a virtual network, and securing it using a Network Security Group (NSG). The project also included connecting to the VM using Azure Bastion and installing the open-source cloud storage solution Nextcloud.

本專案在 Microsoft Azure 上建立虛擬網路與 Ubuntu Server 虛擬機，並透過 Bastion SSH 連線方式安裝並部署 Nextcloud 雲端儲存平台。同時設定 網路安全群組（NSG），以控制虛擬網路中子網的進出流量，強化整體安全性。


<h2>Project Objectives 專題目的</h2>

- <b>Create a Resource Group (建立資源群組)</b>
- <b>Create a Virtual Network and a subnet (建立虛擬網路和子網路)</b> 
- <b>Protect a subnet using a Network Security Group (使用網路安全群組保護子網路)</b> 
- <b>Deploy Bastion to connect to a Virtual Machine (部署 Bastion 以連接到虛擬機)</b> 
- <b>Create an Ubuntu Server Virtual Machine (建立 Ubuntu Server 虛擬機)</b> 
- <b>Install Nextcloud by connecting via SSH using Bastion (使用 Bastion 透過 SSH 連線安裝 Nextcloud)</b>
- <b>Publish an IP (發布 IP)</b>
- <b>Create a DNS label (建立 DNS 標籤)</b>


<h2>Materials and Methods 材料與方法</h2>

- <b>[Coursera platform (Coursera 線上學習平台)](https://www.coursera.org/)</b> 
- <b>[Azure Cloud account (Azure 雲端帳戶)](https://azure.microsoft.com/en-us/get-started/azure-portal)</b>


Tasks:
- <b>Created a resource group to logically group related resources. (建立 Resource Group)</b>
- <b>Created a Virtual Network (VNet) and associated subnet. (建立虛擬網路與子網)</b>
- <b>Configured NSG to manage inbound and outbound traffic for the subnet. (使用 Network Security Group 保護子網</b>
- <b>Deployed Azure Bastion to securely connect to the VM via web-based SSH. (部署 Azure Bastion 以供安全 SSH 連線)</b>
- <b>Created an Ubuntu ver.22.04 Server virtual machine in the subnet. (建立 Ubuntu ver.22.04 Server 虛擬機)</b>
- <b>Used Bastion to SSH into the VM and install Nextcloud via terminal.(透過 Bastion SSH 安裝 Nextcloud)</b>
- <b>Published a public IP and configured a DNS label to access the server.(發佈 Public IP 並建立 DNS 標籤)</b>


<h2>Practice 實踐</h2>

<p align="center">
Task 1: Install and set up Wireshark on Ubuntu (在 Ubuntu 上安裝並設定 Wireshark) <br/>
<img src="https://i.imgur.com/NXBzFip.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Task 2: Start a packet capture on an ethernet port and save it to file (在乙太網路連接埠上啟動封包擷取並將其儲存到檔案中)  <br/>
<img src="https://i.imgur.com/wQ1eb8n.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Task 3: Use a display filter to detect HTTPS packets (使用顯示過濾器檢測 HTTPS 封包) <br/>
<img src="https://i.imgur.com/ftcogGB.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Task 4: Visit a web page and detect its IP address using a display filter (造訪網頁並使用顯示過濾器偵測其 IP 位址) <br/>
<img src="https://i.imgur.com/1NwFWYB.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Task 5: Locate all HTTPS packets from a capture not containing a certain IP address (尋找擷取中不包含特定 IP 位址的所有 HTTPS 封包) <br/>
<img src="https://i.imgur.com/budqLQX.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2>Results 成果展示</h2>

- <b>Nextcloud successfully installed and accessible via browser(成功部署 Nextcloud 並能透過瀏覽器存取)</b>
- <b>Successfully configured Azure VNet, subnet, NSG, and public DNS access(Azure 內網與網路安全組織配置完整)</b>
- <b>Gained hands-on experience using Azure Bastion for secure VM access(體驗透過 Bastion 進行安全 SSH 操作)</b>


<h2>Reference 參考</h2>

[Azure: Create a Virtual Machine and Deploy a Web Server](https://www.coursera.org/projects/azure-create-a-virtual-machine-and-deploy-a-web-server)

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>


- <b>()</b>
