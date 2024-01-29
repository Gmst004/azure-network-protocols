<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create 2 Virtual Machines (VM) within Azure.
- Confirm that both VMs are on the same v-net  
- Open powershell, this is whereI will observe the traffice in between computers  
- Remote desk into a VM-1 and ping VM-2 private ip address to observe traffic in powershell

<h2>Actions and Observations</h2>

<p>

![wiresharkpinggoogle](https://github.com/Gmst004/azure-network-protocols/assets/155221840/a890fbc2-8912-40bd-bbb9-e155352444b7)


I am currently logged into VM-1 through remote desktop on the screen, and I've just initiated a ping to VM-2. At this moment, my focus is directed towards actively observing the data traffic flowing between VM-1 and VM-2, gaining insights into the communication patterns and ensuring a smooth interaction between the two virtual machines.
</p>
<br />

<p>

![wiresharkpinggoogle](https://github.com/Gmst004/azure-network-protocols/assets/155221840/759e70cc-e4cf-4bf6-bf91-f1fc5774576f)


In the displayed interface, I've initiated a ping towards the Google website from VM-1, purposefully engaging in this action to meticulously examine the data traffic that transpires between VM-1 and the Google servers.
</p>
<br />

<p>

![observingssh](https://github.com/Gmst004/azure-network-protocols/assets/155221840/5daae073-0b19-4273-847c-3fef9727f5cf)


Using PowerShell, I executed an SSH secure shell connection to VM-2. While the activity within the connection may seem minimal, the primary intent is to monitor the traffic flowing between VM-1 and VM-2 closely.
</p>
<br />
