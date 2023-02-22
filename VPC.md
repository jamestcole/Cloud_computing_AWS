# Virtual Private Cloud

## Virtual private cloud
virtual private clouds are a pool of shared rescources allocated within a public cloud environment. You can add subnets to this virtual private cloud which is a range of IP addresses in your VPC.

- You can assign IPv4 addresses and IPv6 addresses to your VPCs and subnets. 

- route tables can be used to determine where network traffic from your subnet or gateway is directed.

- A gateway connects your VPC to another network. For example, use an internet gateway to connect your VPC to the internet. 

- The VPC endpoint to connect to AWS services privately, without the use of an internet gateway or NAT device.

- Use a VPC peering connection to route traffic between the resources in two VPCs.

- Copy network traffic from network interfaces and send it to security and monitoring appliances for deep packet inspection.

- Use a transit gateway, which acts as a central hub, to route traffic between your VPCs, VPN connections, and AWS Direct Connect connections.

- A flow log captures information about the IP traffic going to and from network interfaces in your VPC.

- Connect your VPCs to your on-premises networks using AWS Virtual Private Network (AWS VPN).