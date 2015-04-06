# DevBox.ServiceBus
Goal of this project is to create a One-click install for developers to easily Install and Configure the latest version of Service Bus Server and be able to run their test applications against it. 
This will not be a production configuration and is purely intended for a developer scenario. 

Pre-requisites: 
1) Windows 8.1 or higher 
2) Internet connection. 

Installer will pull the following components: 
1) SqlExpress latest version or a version with which the Server will work  
2) Service Bus Server 1.1 (along with Windows Fabric 1.1).

Install Instructions:
------- -------------
1) Open Windows Powershell as Admin
2) Run the Powershell Script - Install is done here. 
3) To create a Sample Q or Topic - Download https://github.com/paolosalvatori/ServiceBusExplorer 