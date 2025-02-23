# VLAN-ROUTING-WITH-ACL-USING-PACKET-TRACER
This project demonstrates Inter-VLAN Routing using Router-on-a-Stick and Access Control Lists (ACLs) in Cisco Packet Tracer. It includes VLAN segmentation for Sales (VLAN 10) and HR (VLAN 20) while implementing ACLs to restrict unauthorized access between departments.

Network Topology:
VLAN 10 (Sales): 192.168.10.0/24
VLAN 20 (HR): 192.168.20.0/24
Router-on-a-Stick: 2 subinterfaces (G0/0.10, G0/0.20)
DHCP Server for Automatic IP Allocation
ACLs to Control Traffic Between VLANs

![image](https://github.com/user-attachments/assets/064add68-5cae-4c7a-8497-7c39c241d8f7)


Configuration:
![image](https://github.com/user-attachments/assets/8f725b17-f2f9-4324-87ef-7291dd7246cd)

![image](https://github.com/user-attachments/assets/07f3fd0c-4f38-462e-92a3-903851c040a3)

![image](https://github.com/user-attachments/assets/dbce1e4d-3e81-46cd-b89e-641a47d607dc)

![image](https://github.com/user-attachments/assets/e3255d5f-7aea-4d98-bb83-b1c2d5df47a0)

Testing & Troubleshooting:
 1. Ping from VLAN 10 (Sales) to VLAN 20 (HR): Should be blocked. 
 2. Ping from VLAN 20 (HR) to VLAN 10 (Sales): Should be allowed. 
