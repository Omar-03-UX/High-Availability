# High-Availability


<h2>Description</h2>
This project focuses on configuring High Availability (HA) between two Palo Alto firewalls to ensure robust network uptime and reliability. 
The implementation includes:
Initial Setup: Configuring identical NAT and Security Policies for seamless traffic flow.
HA Configuration: Establishing HA settings to designate one firewall as Active and the other as Passive.
HA Interfaces: Utilizing HA1 (Layer 3) for control and management traffic, and HA2 (Layer 2) for user traffic, both with backup interfaces for redundancy.
Configuration Synchronization: Ensuring that the passive firewall mirrors the active one through synchronization.
CLI Verification: Checking the status of both firewalls using CLI commands like show high-availability state.
Testing Failover: Conducting tests to validate seamless traffic routing during failover scenarios.

<br />

<h2>Languages and Utilities Used</h2>

- <b> Eve ng </b> 
- <b>VM Workstation </b>
- <b> Palo Alto Firewall </b>

<h2>Environments Used </h2>

- <b> Vm Workstation Pro </b> 

<h2>Program walk-through:</h2>

<p align="center">
Setup devices <br/>
<img src="https://i.imgur.com/OG4cxFD.png" height="80%" width="80%" alt="Palo Alto route"/>
<br />
<br />

<p align="center">
Setup devices <br/>
<img src="https://i.imgur.com/MeoQkmm.png" height="80%" width="80%" alt="Palo ping"/>
<br />
<br />

<p align="center">
Setup devices <br/>
<img src="https://i.imgur.com/9Svm2GJ.png" height="80%" width="80%" alt="Palo ping"/>
<br />
<br />
