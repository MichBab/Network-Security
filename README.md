# Network-Security

## Objective
The Network security project aimed to implement network segmentation and access control by configuring host-based and network-based firewalls, and securing an FTP server using the principle of least privilege. The goal is to improve network security by isolating sensitive systems, controlling traffic flow, and reducing potential attack surfaces

### Skills Learned
- Configuring host-based firewalls
- Setting up FTP server access controls using least privilege
- Creating and managing network-based firewall rules (ACLs)
- Applying network segmentation strategies (like VLANs and subnetting)
- Understanding and implementing network isolation and secure access control
- Using authentication and permission management for secure file sharing

### Tools Used in Project
- Host-based firewall configuration tools (Windows Firewall and Linux iptables)
- FTP server software 
- Network-based firewall tools capable of handling Extended Access Control Lists (ACLs)
- VLAN and subnetting configuration tools and network simulators

## Steps


*Ref 1: Configuration*

*Configure the host-based firewall policy to meet project specifications.*
 ![image](https://github.com/user-attachments/assets/49090f02-5285-4cc6-abc8-ca6676c41ed8)

*Configure the FTP server to meet project specifications for access control.*
 ![image](https://github.com/user-attachments/assets/8f051ccb-8fc7-438e-9a8d-6f6b9053ebe8)

*Configure the network-based firewall policy to meet project specifications for the extended access control list.*
 ![image](https://github.com/user-attachments/assets/2f63e396-a3cf-476b-85c2-81cd5815b686)

*Ref 2: Rationale*

A.	Describe how network segmentation is achieved after meeting the configuration requirements for the host-based firewall.
---Once your host-based firewall has been configured to comply with the requirements, you can proceed to network segmentation. This entails separating your network to smaller, easier to manage sections. You may do this using techniques such as VLANs (Virtual Local Area Networks) or subnetting. With VLANs, you can group devices together depending on variables such as department or function, resulting in different networks within the larger network. Subnetting divides the network in smaller sub-networks, each having its own set of IP addresses. Segmenting your network allows you to better regulate access, improve security by restricting the accessibility of potential threats, and maximize performance by handling traffic more efficiently.

B.	Describe how the concept of least privilege is achieved in the configuration of the FTP server.
---When you configure an FTP server with the principle of least privilege, it guarantees that users have the access they need to do their specified responsibilities. This entails creating user accounts having restricted access to only the folders and files they require, without granting unnecessary rights. For example, yootu could create distinct user accounts for uploading and downloading data, and restrict their access to specific directories as needed. In addition, you can utilize authentication measures such as passwords to verify users' identities before giving access to the FTP server. By sticking to the concept of least privilege, you reduce the danger of unwanted access and misuse of resources, so improving the security of your FTP server.

C.	Describe an approach of employing a network-based firewall to achieve network isolation to meet project specifications.
---To achieve network isolation as per project specifications using a network-based firewall, a systematic approach can be used. First, create discrete security zones within our network, separating important systems or departments from less critical ones. Then, set the firewall to enforce stringent traffic flow rules between these zones, allowing necessary communication while preventing illegal access. Access control lists (ACLs) can be used to determine which IP addresses, ports, or protocols are permitted or prohibited between zones. Then utilize virtual private networks (VPNs) to securely link remote users or offices to certain zones while remaining isolated from the rest of the network. Regular monitoring and modifications to firewall rules will ensure continuing compliance with project requirements while also improving network security.

