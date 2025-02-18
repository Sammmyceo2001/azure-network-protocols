<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com/watch?v=Mu_2UnOdVHM)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Creating Virtual Machines
- Downloading WireShark
- Opening up PowerShell
- Observing ICMP, etc traffic

<h2>Actions and Observations</h2>

<p>
<img src="https://github.com/user-attachments/assets/805b00a4-ecb1-4d5a-9632-6bce4b7381e1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This pictyure shows the creation of the Virtual Machines such as Ubuntu and Windows 10 and making sure both VMs run in the same subnet mask so data could be transmitted from one VM to Another
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/5ae30599-e3bc-4480-ba42-896bc36d4149" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This picture shows Wireshark and how it looks when it's downloaded, the blue shark fin at the top right is where the packet captures happens and that's where you could filter for Network Protocols
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/fdc697dd-2bfe-4265-a589-d7466e07a1fc" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly this picture shows the packet capture without filtering it and letting the packets of data do their job
</p>
<br />
