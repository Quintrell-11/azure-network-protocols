<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


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

- See traffic from other virtual Machine
- Filter Inforation
- Mske secure connection to other VM

<h2>Actions and Observations</h2>

<p>
  
![6FE5E24C-8BCD-48C0-914D-02A04BAD61E8](https://github.com/user-attachments/assets/2e00c0f0-3ff7-44a3-b7e0-cfe1916b6c04)

</p>
<p>
After downloading (Wire Shark) observed traffic between the virtual machines by useing (Powershell) to (ping)ing the private ip address. Now that i can see the traffic I isolated the data from the other (VM) by typing (icmp) into wire shark. Now I can see the CPU's communicating between eachother.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/44e37d3a-6685-41d9-a1ad-25f006013610)

</p>
<p>
To create a secure connection to my other (VM) or connection to another computer and observe the traffic; filtering for (SSH). Inside of Powershell I typed ssh the other day(VM's) username@the private ip address. (ssh labuser@10.5.0.5) and when prompted entered my credentials and have secured a secure connection to the other computer. Access to all information is now disoverable by search from within Powershell.
</p>
<br />
