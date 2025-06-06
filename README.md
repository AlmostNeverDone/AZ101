<h1>Azure: Create a Virtual Machine and Deploy a Web Server</h1>
Azure：建立虛擬機器並部署 Web 伺服器
<br />


<h2>Outline 簡介</h2>
In this guided project, we created a Virtual Machine in Microsoft Azure to deploy a web server, specifically a Nextcloud server. Rather than relying solely on presets, we explored the basic architecture of Azure by manually creating a Virtual Machine, assigning it to a subnet within a Virtual Network, and applying inbound and outbound rules through Network Security Groups (NSGs). We also used Azure Bastion to securely access the machine via SSH, avoiding public port exposure. Finally, we installed a basic Nextcloud server and made the VM accessible by configuring a public IP and DNS label.


<b>在這個引導式專題中，我們在 Microsoft Azure 上建立虛擬機器（Virtual Machine）以部署一套 Nextcloud 網頁伺服器。我們沒有直接使用預設設定，而是深入探索 Azure 的基本架構，手動建立虛擬機器、配置至虛擬網路中的子網路，並透過網路安全群組（NSG）設定進出站規則來強化安全性。我們也使用 Azure Bastion 安全地連接機器，避免公開 SSH 埠。最後，我們安裝了基本的 Nextcloud 伺服器，並透過配置公共 IP 與 DNS 標籤讓虛擬機器能對外開放存取。</b>
<br />


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
- <b>Virtual Cloud Workspace (虛擬雲端工作區)</b>
- <b>PC (win10,個人電腦對照差異)</b>

Tasks:
- <b>Install and set up Wireshark on Ubuntu (在 Ubuntu 上安裝並設定 Wireshark)</b>
- <b>Start a packet capture on an ethernet port and save it to file (在乙太網路連接埠上啟動封包擷取並將其儲存到檔案中)</b>
- <b>Use a display filter to detect HTTPS packets (使用顯示過濾器檢測 HTTPS 封包)</b>
- <b>Visit a web page and detect its IP address using a display filter (造訪網頁並使用顯示過濾器偵測其 IP 位址)</b>
- <b>Locate all HTTPS packets from a capture not containing a certain IP address (尋找擷取中不包含特定 IP 位址的所有 HTTPS 封包)</b>

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
