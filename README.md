# network_analysis
# Task 5 - Network Traffic Capture and Analysis

## Tools Used
- *Wireshark* on Kali Linux (inside Oracle VirtualBox)

## Task Description
Captured and analyzed network traffic using Wireshark. Identified four key network protocols from the captured packets and saved the capture as a .pcap file.

## Protocols Identified

1. *ICMP* (Internet Control Message Protocol)
   - Used for diagnostic tools like ping
   - Example: Packet exchange with IP 142.250.77.110 (Google)

2. *DNS* (Domain Name System)
   - Resolves domain names to IP addresses
   - Example: Query for openai.com

3. *TCP* (Transmission Control Protocol)
   - Ensures reliable delivery of data between devices
   - Seen in connections to port 443 (HTTPS)

4. *TLS* (Transport Layer Security)
   - Provides encryption over TCP (used in HTTPS)
   - Detected in secure communication to websites

## Files
- task5_capture.pcap: The packet capture file containing the analyzed traffic.
- i added some screenshot that i done in the task5 to understand
- i added a readme file 
