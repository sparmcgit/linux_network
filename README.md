# linux_network
Linux network

ip-route - routing table management

Get a single route to a destination and prints its contents exactly as the
kernel sees it.

ip route get to 8.8.8.8

Route tables
ip route show table main|local|all|ID

ip-rule - routing policy database management

ip rule show

0.0.0.0

From wikipedia:
In routing tables, 0.0.0.0 can also appear in the gateway column. This 
indicates that the gateway to reach the corresponding destination subnet is 
unspecified. This generally means that no intermediate routing hops are 
necessary because the system is directly connected to the destination.

0.0.0.0/0 which defines an IP block containing all possible IP addresses. It is 
commonly used in routing to depict the default route
