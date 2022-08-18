# Azure_Honeypot

Most of the time when our website or host is live in server is vulnerable to various kind of attack. Through this project we built an vulnerable machine and track the attackers from where they are form and take necessary actions on it.

In this project we are setting up a honeypot using Virtual machine and connect it to Azure Sentinel which acts as Security Information and  Even Management service through which we can track the attack and build a custom log analytics workspace which gives 'Failed RDP log in attempts' metadata.

Through this metadata we can gather IP address which we can use to get geo-location of the attacks from a third party API and get the longitude and latitude of the locations. Later map the points on the world using log analytics workspace in Azure 
