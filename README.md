# EVE-ng-Networking-Topology
Internetwork Security Project

A network security simulation project built in EVE-NG that demonstrates secure communication between multiple subnets using Cisco IOS routers, ACL-based firewall rules, NAT, and routing configurations.

Features
Multi-subnet network topology design
Cisco IOS router and firewall configuration
Access Control Lists (ACLs) for traffic filtering
Controlled ICMP and HTTP communication between hosts
NAT and Internet access configuration
Web server access restrictions based on subnet policies
Network connectivity and security testing
Security Policies Implemented
PC1 allowed to access Server1 and Server2 only
PC2 allowed to access Server3 only
Controlled ICMP communication between internal networks
Internet access rules with filtered inbound replies
HTTP traffic filtering using TCP ACL rules
Technologies Used
Cisco IOS
EVE-NG
Networking fundamentals (Routing, NAT, ACLs, ICMP, TCP/IP)
Virtualized network environments
Notes

Due to macOS virtualization limitations and unavailable KVM acceleration in the testing environment, lightweight Cisco IOS images were used instead of heavier FortiOS and Windows images. Despite EVE-NG cloud-bridging limitations affecting external Internet connectivity, all internal routing, NAT, and ACL configurations were successfully verified within the simulated environment.
