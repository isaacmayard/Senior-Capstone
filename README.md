Feb 5 : Initial file creation and population of network ideas

Feb 13 : After 2nd team meeting, tested out accessibility for team members with file removal and reupload

Feb 20 : Added IP schemes to diagram

Mar 8 : Layer 2 setup on all 4 networks. Engineering and R&D have RoaS connectivity. Server is set up for DHCP but will require additional troubleshooting and research on operability with RoaS. May need to pivot to either Inter-Vlan routing or router based DHCP. Goal 1: Implement spanning tree protocol at layer 2 COMPLETED, Goal 2: connect multiple computers to each switch in the network, which then utilizes a tiered structure to connect to network routers. COMPLETED

Mar 23: Fixed DHCP issue by converting RoaS to layer 3 switches, then adding /30 networks between the switches and the routers, then finally ip-helper addresses to the SVIs. Goal 3: Host DHCP server that will serve IP addresses to endpoints COMPLETED.

Goal 4: Each network now has EIGRP implemented as it's layer 3 routing protocol up until the boundary router. All hosts within each internal network can ping each other, their server and their gateway (this went surprisingly seamlessly, which was refreshing! Big thank you to the Cisco online documentation). COMPLETED. 

Goal 5: Connect multiple different L3 autonomous systems together via routing protocols PENDING 20 April
