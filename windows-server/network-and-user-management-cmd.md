# Windows Server Command Line: Network and User Management

## Objective
Use Command Prompt to verify network configuration and domain user account information in a Windows Server environment.


## Tools Used

- Windows Server 2016
- Command Prompt
- Active Directory Domain Environment
- VirtualBox Lab Environment


## Command 1: ipconfig

### Purpose
Displays basic IP configuration information for the server/user.

### Result

Displays network information including:

- IPv4 Address: 10.0.2.15  
- Subnet Mask: 255.255.255.0  
- Default Gateway: 10.0.2.2  

This confirms the server is properly connected to the network.

Screenshot:  
![ipconfig](/windows-server/screenshots/ipconfig.png)


## Command 2: ipconfig /all

### Purpose
Displays detailed network configuration information.

### Result

Displays detailed network settings including:

- Host Name: Server2016  
- DNS Suffix: ampere.com  
- Network Adapter: Intel PRO/1000 MT Desktop Adapter  
- Physical Address (MAC Address)  
- DHCP Status  

This helps verify DNS configuration and network adapter details.

Screenshot:  
![ipconfig all](/windows-server/screenshots/ipconfig_all.png)



## Command 3: net user

### Purpose
Displays active network connections and mapped network drives.


This confirms there are currently no mapped network drives or active network connections.

Screenshot:  
![net use](/windows-server/screenshots/net_use.png)


## Command 4: net user helpdesk /domain

### Purpose
Displays detailed information about a domain user account in Active Directory.


### Result

Displays domain user account details including:

- Username: helpdesk  
- Account Status: Active  
- Password Settings  
- Group Membership:
  - Domain Users
  - Domain Admins
  - Enterprise Admins
  - Schema Admins

This confirms the user exists and is properly configured in Active Directory.

Screenshot:  
![net user helpdesk](/windows-server/screenshots/net_user.png)



## Result

Successfully verified:

- Server network configuration
- IP address and DNS settings
- Network connection status
- Domain user account information

All commands executed successfully in Windows Server command line environment.


## Skills Learned

- Using Command Prompt for system administration
- Verifying network configuration
- Troubleshooting network connectivity
- Managing and verifying Active Directory user accounts
- Using essential Windows Server administrative commands













