Design a network in Cisco Packet Tracer to connect ACCOUNTS an DELIVERY departments.

- Each department should contain at least 2 PC
- Appropriate number of switches and routers should be used in the network 
- Using the given network address 192.168.40.0 , all interfaces should be configured with appropriate IP addresses, subnet mask and gateway
- All devices in the network should be connected using appropriate cables
Test the connectivity between ACCOUNTS and DELIVERY departments - PC in DELIVERY department should be able to ping the PC in ACCOUNT department. 


## Departments 
- Accounts 
- Delivery 

## Network requirements 
- 2 PCs (each)
- 1 Printer (each)
- 1 Switch (each)
- Router 

## Subnetting process
- Network Address = 192.168.40.0 
- No of Subnets = 2 (Accounts and Delivery)

## Subnet Formular 
- 2^n = no of subnets ====== 2^n = 2
- n = 1

- Subnet = 255.255.255.255
- Because n= 1
- 11111111.11111111.11111111.10000000
- 255.255.255.128

-1st Subnet 
    Subnet mask: 255.255.255.128
    Network ID: 192.168.40.0
    Range of valid host: 192.168.40.1 - 192.168.40.126
    Broadcast ID: 192.168.40.127


-2st Subnet 
    Subnet mask: 255.255.255.128
    Network ID: 192.168.40.128
    Range of valid host: 192.168.40.129 - 192.168.40.254
    Broadcast ID: 192.168.40.255
