# Configuring an Intrusion Detection System

<h2>Description</h2>
In this lab, I will use an IDS sensor to monitor packets on a LAN router's interface with the outside internetwork. I will use the Security Onion Linux distribution (securityonion.net) and its bundled Snort IDS as the sensor. Security Onion is installed to the SIEM1 VM.
<br />


<h2>Utilities Used</h2>

- <b>Sguil</b> 

<h2>Environments Used </h2>

- <b>Ubuntu 16.04 LTS</b>
- <b>Kali Linux 2023.3</b>
- <b>Windows Server 2016 Server</b>

<h2>Program walk-through:</h2>

<p align="center">
1. Logging into Sguil: <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/b3e7a994-6935-4ca5-9c01-3dd30c571537

<br />
<br />
2. Pinging SIEM1 from Kali Machine:  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/e2e92207-94d1-4cdd-9374-76cf20b58d0f

<br />
<br />
3. Analyzing an alert and finding the SID: <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/347ef8a7-e9c9-4ffd-a198-757b2cee0cfe

<br />
<br />
4. Recording the SID:  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/ef35235b-940a-4618-8fca-5c084ba1aa2c

<br />
<br />
5. Disabling rule that identifies ping alerts based on specified SID:  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/d0d72245-8005-4efd-bda5-30dd335a6a61

<br />
<br />
6. Updating rule change in IDS:  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/d5f15031-335d-4516-9e8b-131ed446bcef

<br />
<br />
7. Testing updated IDS rule:  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/0e770890-9bed-4f6a-9c2b-731263244fb1

<br />
<br />
Which of the following best describes the purpose of editing the /etc/nsm/pulledpork/disablesidconf configuration file? <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/8e6b67e6-55fd-4dbd-ad74-cbd4f6524d00

<br />
<br />
8. Sending an attack to SIEM1:  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/e492544e-6b09-40d4-9264-19b123131344

<br />
<br />
What kind of attack is hping3 perpetrating in this activity?  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/6ee9e901-8449-4b3e-ae6e-9b6ce42a874c

<br />
<br />
9. Sending DDoS attack to MS1 server, observing how it affects performance, and viewing alerts in SIEM1:  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/0941005f-5c04-494b-9ddc-93321617f9eb

<br />
<br />
Which of the following best describes the event messages displayed by SGUIL?  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/b418c15b-39b3-4f5c-89b1-3e3b34c25bce

<br />
<br />
Why are the sourceIP addresses all different in the SGUI if the attack originates from PT1-Kali at 192.168.2.192?  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/60b0f29a-227b-41a5-ae85-793e3ef34a55

<br />
<br />
Why was the Nmap scan identified as a threat by SGUIL?  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/fa252879-700c-4394-b7ed-0e7c49271003

<br />
<br />
Why might it be useful to set a rule that ignores ICMP (ping) network traffic?  <br/>

https://github.com/ObiBryant/Configuring-an-Intrusion-Detection-System/assets/143296412/0a101044-40a0-4d91-8761-76c98b94e07a

<br />
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
--!>
