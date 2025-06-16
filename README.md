<h1>Site-to-Site IPsec VPN</h1>

 ### [Kaltura Capture Recording](https://mediaspace.minnstate.edu/media/Kaltura+Capture+recording+-+April+26th+2025%2C+11%3A11%3A10+pm/1_sp0j5ef9)

<h2>Description</h2>
In this project, I configured a Site-to-Site IPsec VPN between two branch offices—Site A and Site B—to securely connect two separate internal networks over the public internet using Cisco ISR 4331 routers.

Site A uses the network 192.168.1.0/24, while Site B uses 192.168.2.0/24. Each site is connected to an ISP router via a point-to-point WAN link (100.100.100.0/30 for Site A and 200.200.200.0/30 for Site B). The IPsec VPN tunnel was established between the Gigabit Ethernet 0/0 interfaces of the routers to allow secure communication across sites.
This project enhanced my understanding of VPN technologies, Cisco IOS configuration, and secure WAN communication for enterprise networks.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Cisco IOS CLI commands</b> 

<h2>Environments Used </h2>

- <b>Cisco Packet Tracer</b> (8.2)

<h2>Program walk-through:</h2>

<p align="center">
Network Design: <br/>
<img src="https://i.imgur.com/4uZnmdZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Phase 1 (ISAKMP) and Phase 2 (IPsec) setup (Router R1):  <br/>
<img src="https://i.imgur.com/MQ82SLC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Interface Config & NAT exemption (Router R1): <br/>
<img src="https://i.imgur.com/KPePkun.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuration of Static routes and NAT overload (Router R1):  <br/>
<img src="https://i.imgur.com/hgTCMnw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring VPN-ACL and NAT-ACL (Router R1):  <br/>
<img src="https://i.imgur.com/PHnPeA5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Static Routing and Interface Configuration (ISP Router):  <br/>
<img src="https://i.imgur.com/PHEvzV4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Phase 1 (ISAKMP) and Phase 2 (IPsec) setup (Router R2):  <br/>
<img src="https://i.imgur.com/zpepP2Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Interface Config & NAT exemption (Router R2): <br/>
<img src="https://i.imgur.com/kY4PIJT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuration of Static routes and NAT overload (Router R2):  <br/>
<img src="https://i.imgur.com/QmrJdN1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring VPN-ACL and NAT-ACL (Router R2):  <br/>
<img src="https://i.imgur.com/vIjn4kF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify that the tunnel is established (Router R1):  <br/>
<img src="https://i.imgur.com/De4fZD8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify that data is bi-directionally encrypted (Router R1):  <br/>
<img src="https://i.imgur.com/5SJQNlp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```

Autofill

;
--!>
