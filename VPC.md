# Virtual Private Cloud

![Alt text](pics/vpc.jpg "a title")

## How does the VPC help Devops

- keeps instances private, good for instances that should not be connected to the internet.

## Virtual private cloud
virtual private clouds are a pool of shared rescources allocated within a public cloud environment. You can add subnets to this virtual private cloud which is a range of IP addresses in your VPC.

- You can create any number of subnets, though you cannot overlap them within the same VPC

- You can assign IPv4 addresses and IPv6 addresses to your VPCs and subnets. 

- route tables can be used to determine where network traffic from your subnet or gateway is directed.

- A gateway connects your VPC to another network. For example, use an internet gateway to connect your VPC to the internet. 

- The VPC endpoint to connect to AWS services privately, without the use of an internet gateway or NAT device.

- Use a VPC peering connection to route traffic between the resources in two VPCs.

- Copy network traffic from network interfaces and send it to security and monitoring appliances for deep packet inspection.

- Use a transit gateway, which acts as a central hub, to route traffic between your VPCs, VPN connections, and AWS Direct Connect connections.

- A flow log captures information about the IP traffic going to and from network interfaces in your VPC.

- Connect your VPCs to your on-premises networks using AWS Virtual Private Network (AWS VPN).

## CIDR
- Classless inter-domain routing (CIDR) is a method for allocating IP addresses and IP routing. 
- A collection of Internet Protocol (IP) standards is used to create unique identifiers for networks and individual devices. 
- The IP addresses allow the transmission of unique packets of information to specific computers.

- CIDR is mainly used to use IP addresses and solve the routing table explosion efficiently. 
- It is defined in RFC (Request for comments) 1518 and RFC 4632. It is an address block allocation. 
- There are five different classes in the IPV4 addressing system. The IP address classes are used for Internet IP addresses assignment.

## What is an Internet gateway

- A gateway connects networks, while a router typically delivers data within a network. 
- Historically, gateways and routers have been separate devices. However, it's becoming more common for their functions to be combined and simply called a router. 
- For example, the Wi-Fi routers commonly provided for home and small business internet service are both a router (delivering data) and a gateway (translating it so destination devices can use it).