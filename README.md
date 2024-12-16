<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
This tutorial covers the observation of various network traffic to and from Azure Virtual Machines using Wireshark, and experiments with Network Security Groups.<br />


<h2>Environments and Technologies Used</h2>

- **Microsoft Azure**: Provision and manage Virtual Machines
- **Remote Desktop Protocol (RDP)**: Access and manage VMs remotely
- **Command-Line Tools**: Execute various commands for configuration and testing
- **Network Protocols**: SSH, RDP, DNS, HTTP/S, ICMP for traffic analysis
- **Wireshark**: Analyze network traffic

<h2>Operating Systems Used</h2>

- **Windows 10 (21H2)**
- **Ubuntu Server 20.04**

<h2>High-Level Steps</h2>

1. **Provision Azure Virtual Machines**: Create and set up VMs in Azure.
2. **Configure Network Security Groups (NSG) Rules**: Define rules to control network traffic to and from VMs.
3. **Capture Network Traffic with Wireshark**: Use Wireshark to monitor and capture network packets.
4. **Analyze Captured Traffic**: Evaluate the captured traffic to understand network behavior and security implications.

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Actions and Observations"/>
</p>
<p>
Step 1: Setup VMs: We started by setting up two virtual machines in Azure, one running Windows 10 and the other running Ubuntu Server 20.04. We configured the Network Security Groups to control traffic flow between these VMs.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Network Setup"/>
</p>
<p>
Step 2: Configure NSGs: We created and applied NSG rules to manage and filter the traffic. This included allowing and denying specific types of traffic based on the protocol and port numbers.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Traffic Analysis"/>
</p>
<p>
Step 3: Capture Traffic Using Wireshark: We captured various types of network traffic using Wireshark, such as SSH, RDP, DNS queries, HTTP/S, and ICMP packets. This helped us understand the traffic flow and identify any anomalies or security issues.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Traffic Analysis Results"/>
</p>
<p>
Step 4: Analyze Captured Traffic: We analyzed the captured traffic to gain insights into the network behavior. This analysis helped us understand the impact of NSG rules on traffic flow and identify potential security risks.
</p>
<br />

<h2>Conclusion</h2>

By following these, you will have a understanding of how to inspect and manage network traffic between Azure Virtual Machines using Network Security Groups and Wireshark. )
