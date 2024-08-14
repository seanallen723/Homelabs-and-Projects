# Project: Dynamic DNS (DDNS) for a Home Server Using Windows Server 2022 on Oracle VirtualBox
## Objective:

The goal of this project is to set up a Dynamic DNS (DDNS) service to map a dynamic public IP address to a custom domain name. This will allow me access 
to my home server remotely from anywhere on the Internet, even if the ISP frequently changes my public IP address. This will help me learn more about the fundamentals of DNS functions. This will also provide me with practical experience with DNS management and Windows Server administration.

## Install and Configure DNS Server Role and DNS Zone

![image](https://github.com/user-attachments/assets/c6286015-2329-4334-87cf-ae121cfd5544)
![image](https://github.com/user-attachments/assets/7a029e41-dbc3-47c2-8c38-aacff6edebac)

 * Before starting the project, I had to verify that the DNS server role was successfully installed onto the DC (Domain Controller).
 * I also configured the DNS Zone by adding a Forward Lookup Zone, making a primary zone, and configuring it to allow both secure 
 and non-secure dynamic updates, which will enable DDNS.

## Setting up DDNS with a Third-Party Provider

The service that I will use in my virtual environment will be DuckDNS. DuckDNS is a third-party provider that will grant me the ability to configure a custom name for my DNS server. Unlike a typical DNS, the name will be perpetually referred to my server, so even if the server's IP address were to change, the domain name would still be directed to the server.

![image](https://github.com/user-attachments/assets/6481cf24-2996-43cc-b374-a0d26b5a8360) 
![image](https://github.com/user-attachments/assets/4b98689c-b372-4b34-bd4f-fe7a9fea4991)

* Still Editing

## Verifying the DDNS's Functionality

  *
  *
  *
  
##

##

##

##

##

##

##

##

