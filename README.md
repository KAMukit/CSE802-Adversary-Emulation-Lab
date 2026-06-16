# CSE802 - Adversary Emulation & Detection Lab

## Student Information
Name: K.A. Mukit 
Roll: 60006

## Environment
- Kali Linux VM
- Windows Server 2019 VM
- Splunk Enterprise
- Sysmon
- Splunk Universal Forwarder

## Completed Tasks
- Installed Splunk Enterprise on Kali Linux
- Enabled Receiving Port 9997
- Installed Sysmon on Windows Server
- Installed Splunk Universal Forwarder
- Configured log forwarding
- Verified network connectivity

## Repository Contents
- Report
- Screenshots
- Configuration Files# CSE802-Adversary-Emulation-Lab

- Lab Setup

1. Windows Server 2019 Virtual Machine

![Windows Server](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/WINDOWS%20SERVER.PNG?raw=true)


Windows Server 2019 virtual machine was deployed as the target endpoint for log collection and security monitoring.

2. Kali Linux Virtual Machine

![Kali Machine](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/KALI%20MACHINE.PNG?raw=true)


Kali Linux was used as the monitoring server where Splunk Enterprise was installed and configured.

3.Kali Linux IP Configuration

![KALI IP](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/8.KALI%20IP.PNG?raw=true)

The IP address of the Kali Linux VM was verified to ensure proper communication with the Windows Server and Splunk Forwarder.

4.Network Connectivity Verification

![NETWORK CONNECTIVITY TEST])https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/8.%20NETWORK%20CONNECTIVITY%20TEST.PNG?raw=true)

A ping test was performed from Windows Server to Kali Linux (192.168.56.101) to confirm successful network connectivity.
