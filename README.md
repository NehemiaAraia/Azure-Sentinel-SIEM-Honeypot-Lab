# Azure-Sentinel-SIEM-Honeypot-Lab
Deployed a honeypot within Microsoft Azure to simulate vulnerabilities and capture attack logs, which I then analyzed using Azure Sentinel as my SIEM solution. Implemented the SIEM by configuring Azure resources, which includes virtual machines and Log Analytics Workspaces and used Kusto Query Language (KQL) for log querying. Lastly, I created an interactive world map dashboard to visualize attack patterns and geolocation data.

Tools & Resources
- **Microsoft Azure**: Requried for accessing cloud-based reources and services
- **Azure Sentinel**: Key to SIEM setup for detecting and responding to security threats in real-time.
- **Kusto Query Language (KQL)**: Used for building complex queries to visualize attack patterns
- **Network Security Groups**: Manage firewall configurations at layer 3/4 in Azure
- **Remote Desktop Protocol (RDP)**: Essential for remote management of virtual machines.
- **Custom PowerShell Script**: Enhances the logs with geolocation data, providing a clear view of the attackers' locations.
- **3rd Party API**: Utilized ipgeolocatio.io which provided geographical data for enhancing log inforamtion.
