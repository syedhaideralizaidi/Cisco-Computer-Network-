# Cisco-Computer-Network-
You are given the network design with minimal technical documentation; your task is to make this up and run in 4 hrs. Use all your mind capabilities to solve this. 1. Following are the steps you need to perform in the topology according to the given layout. Configure this scenario and find your given IP address in the file " IP address " attached with this. Find out the Network Addresses and start working with them. And use them as required. 2. Please find the number of required hosts per subnet in the given file. Each student is given a different number of required hosts per subnet. Networks are labeled alphabetically in the given file of IP ADDRESSES. The networks with Router23 are not labeled so you can choose any number of hosts for those subnets. 3. Use EIGRP in First Block for Routing , OSPF with area 1 in Second Block , Rip in Block Third and OSPF with area 0 in the last block as mentioned on the top of each block. 4. Use Redistribution on Router6 and Router13 for connecting EIGRP with OSPF and OSPF with RIP. Use Redistribution on Router11 for connecting OSPF area 1 with OSPF area 0. 5. All hosts in EIGRP, OSPF area 1 and RIP will get IP addresses from "DHCP Server" present in the first block. 6. All hosts in OSPF area 0 will get hosts from “DHCP Server” present in its own block. (named as web server in the picture) 7. You have to use VLSM in each network of the topology. 8. You have to IMPLEMENT NAT in Router7 with the NetworkG. Use the Private IP Address given to you in the attached file for Natting. 9. One of the PCs of Network L will not be allowed to access the TFTP server. One of the PCs of Network E will not be allowed to access the Data server in the 1st block. All hosts connected in network A will not be allowed to access "Web Server". 10. The TFTP and Data servers do not need to have running services. They will simply be treated as hosts. You just need to block the access of those servers from respective networks. (Access List) 





Topology has been attached above and below are the IPs and subnets used in the project.
211.112.122.15/1(Public IP) 
192.168.1.6(Private IP) 
A 67882 
B 5601 
C 1950 
D 3887 
E 92878 
F 51183 
G 5540 
H 395 
I 48 
J 688 
L 11845 
M 1256 
N 428
