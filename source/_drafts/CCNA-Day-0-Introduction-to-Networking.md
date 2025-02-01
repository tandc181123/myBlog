---
title: 'CCNA Day 0: Introduction to Networking'
categories: 'CCNA'
tags:
---

### What is a Network?
![aSimpleNetwork.png](https://s2.loli.net/2025/01/05/eEwQAcPa4CNVUOi.png)
>A network can be built with just two PCs and an Ethernet cable. However, in the real world, this is not sufficient; we want to involve more PCs.
<!-- more -->
### Types of Networks
- Local Area Network (**LAN**)
    ![localAreaNetwork.png](https://s2.loli.net/2025/01/05/8DRVj6ixkrsG1Z2.png)

    *We want all PCs in this area (such as a single building or office) to communicate with each other,
    so a **switch** comes into play. This forms a Local Area Network, abbreviated as LAN.*
- Wide Area Network (**WAN**)
    
    >Q: How do they communicate if they are not in the same LAN?
    A: It's time for the **router** to shine!
    
    ![Router.png](https://s2.loli.net/2025/01/06/LdhirjKQkEJzDSt.png)

    ***Router**: For now, think of it as a device that allows different LANs to communicate with each other by forwarding data between them.*
    ![WAN.png](https://s2.loli.net/2025/01/05/C45kRBi8vhlaGt2.png)
    
    *If we have multiple LANs connected through routers, we can refer to it as a **WAN**.*
- Internet    
    ![Internet.jpg](https://s2.loli.net/2025/01/06/UeXBMyWLEsn9D27.jpg)

    *The **Internet** is the connection between all these LANs and WANs around the world.*


### Network Devices Overview
1. Switch
   - **Function**: Connects multiple devices within the same subnet to form a Local Area Network (LAN).
   - **Use Case**: Used for connecting multiple PCs, printers, and other devices within the same network area, such as an office or a home network.
   - **Additional Info**: Managed switches provide advanced features such as **VLAN** configuration, traffic prioritization, and monitoring, which are not available in unmanaged switches.

2. Router
   - **Function**: Connects different networks and directs data packets to their destination using IP addresses. It operates at the network layer (Layer 3) of the OSI model.
   - **Use Case**: A home router connects Wi-Fi devices to the Internet by routing traffic between the local network and the Internet Service Provider (ISP).
   - **Additional Info**: Modern routers often include advanced features such as built-in firewalls for enhanced security, Quality of Service (QoS) to prioritize critical traffic, and VPN (Virtual Private Network) support for secure remote access.

3. Wi-Fi Access Point

   - **Function**: Extends a wired network by enabling wireless devices to connect to it, acting as a bridge between the wired and wireless environments.
   - **Use Case**: Commonly used to provide Wi-Fi access in areas like meeting rooms, coffee shops, and other public spaces.
   - **Additional Info**: Modern Wi-Fi systems, such as mesh networks, use multiple access points working together to provide seamless and extended coverage across large areas, addressing issues like signal dead zones.

### Network Automation and Monitoring

- Why Automation and Monitoring Are Essential in Modern Networking

    In today's fast-paced IT environments, networks are becoming increasingly complex. With the rise of cloud services, hybrid infrastructures, and IoT devices, manual network management is no longer sustainable.
    
    Engineers need tools and processes to streamline operations, minimize human error, and respond quickly to issues. This is where network automation and monitoring play a crucial role.

    Automation ensures repetitive tasks are performed efficiently, while monitoring provides real-time insights into the health of the network. Together, they enable engineers to manage even the most complex infrastructures effectively.

    For example, imagine being alerted instantly when a device goes offline or automating the deployment of configurations across multiple routers. Such capabilities not only save time but also prevent potential outages.
