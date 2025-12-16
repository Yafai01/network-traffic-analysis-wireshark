# 📡 Network Traffic Capture and Analysis Using Wireshark

## Objective
The objective of this task is to capture live network traffic using Wireshark and analyze basic network protocols to understand how data flows across a network.

---

## Tool Used
- **Wireshark** (Version 4.x)

---

## System Details
- Network Interface: **Wi-Fi**
- Operating System: **Windows**
- Capture Duration: ~1 minute

---

## Methodology
1. Installed and launched Wireshark.
2. Selected the active **Wi-Fi** network interface.
3. Started live packet capture.
4. Generated network traffic by browsing websites and pinging a server.
5. Stopped the capture after sufficient packets were collected.
6. Applied display filters to analyze specific protocols.
7. Saved the captured traffic as a `.pcap` file.

---

## Protocols Identified
During packet analysis, the following protocols were observed:

1. **DNS (Domain Name System)**  
   - Used to resolve domain names into IP addresses.
   - Observed DNS query and response packets when accessing websites.

2. **TCP (Transmission Control Protocol)**  
   - Provides reliable, connection-oriented communication.
   - TCP packets with ACK flags confirmed successful data transmission.

3. **HTTPS / TLS**  
   - Encrypted web traffic observed on port 443.
   - Ensures secure communication between client and server.

---

## Packet Analysis Observation
- TCP packets showed acknowledgment (ACK) flags, indicating reliable delivery.
- HTTPS traffic was encrypted, preventing readable payload inspection.
- DNS traffic occurred before establishing web connections.

---

## Files Generated
- `network_capture.pcap` – Packet capture file containing live network traffic.
- `REPORT.md` – Summary of analysis and observations.

---

## Conclusion
This task provided hands-on experience with packet capture and protocol analysis using Wireshark. It helped in understanding real-time network communication, identifying common protocols, and analyzing secure and reliable data transmission. The exercise improved practical knowledge of networking and troubleshooting concepts.

---

## Key Concepts Learned
- Packet capture  
- Protocol filtering  
- TCP/IP communication  
- Encrypted traffic analysis  
- Network troubleshooting basics
