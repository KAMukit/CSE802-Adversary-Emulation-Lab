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

![NETWORK CONNECTIVITY TEST](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/8.%20NETWORK%20CONNECTIVITY%20TEST.PNG?raw=true)

A ping test was performed from Windows Server to Kali Linux (192.168.56.101) to confirm successful network connectivity.

5.Starting Splunk Enterprise

![sPLUNK OPEN](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/sPLUNK%20OPEN.PNG?raw=true)
Splunk Enterprise service was started successfully on the Kali Linux machine.

6.Splunk Enterprise Login Page
![sPLUNK OPEN 2](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/sPLUNK%20OPEN%202.PNG?raw=true)

The Splunk Enterprise web interface was accessed through the browser.

7.Splunk Enterprise Dashboard
![SPLUNK OPEN 3](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/SPLUNK%20OPEN%203.PNG?raw=true)
The Splunk dashboard was successfully loaded, confirming that the Splunk server was operational.

8.Splunk Receiving Port Configuration
![SPLUNK RECIVING PORT 9997](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/SPLUNK%20RECIVING%20PORT%209997.PNG?raw=true)
Port 9997 was configured and enabled to receive logs from Splunk Universal Forwarder.

9.Splunk Universal Forwarder Installation
![SPLUNK UNIVERSAL FORWARDER](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/SPLUNK%20UNIVERSAL%20FORWARDER.PNG?raw=true)
Splunk Universal Forwarder was installed on Windows Server 2019 for forwarding security logs to Splunk Enterprise.

10.Sysmon Operational Log Verification
![sYSMOS INSTALL](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/sYSMOS%20INSTALL.PNG?raw=true)
Sysmon was successfully installed and generating process creation and system monitoring events.

11.Universal Forwarder Output Configuration
![Capture](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/Capture.PNG?raw=true)
The Universal Forwarder was configured to send logs to the Splunk server at 192.168.56.101:9997.

12.Windows Security Logs in Splunk
![1](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/1.PNG?raw=true)
Windows Security Event Logs were successfully collected and indexed in Splunk.

13.Event ID 4624 (Successful Logon)
![2](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/2.PNG?raw=true)
![2.1](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/2.1.PNG?raw=true)

Windows Security Event ID 4624 indicates a successful user login and was successfully detected in Splunk.

14.Windows System Logs in Splunk
![3](https://github.com/KAMukit/CSE802-Adversary-Emulation-Lab/blob/main/3.PNG?raw=true)
Windows System Event Logs were collected and analyzed through Splunk.

15.Windows System Event Log Collection in Splunk

