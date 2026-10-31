# wireshark-tcp-analysis
TCP packet analysis assignment using Wireshark
# Wireshark TCP Packet Analysis

## 📌 Project Overview
This repository documents a comprehensive network traffic analysis focusing on the **Transmission Control Protocol (TCP)** using Wireshark. The goal of this project is to capture real-world network packets, isolate TCP traffic, and examine core connection mechanics such as the Three-Way Handshake and packet sequencing[span_2](start_span)[span_2](end_span).

---
## Tools & Environment
* **Protocol Analyzer:** Wireshark[span_3](start_span)[span_3](end_span)
* **Operating System:** Cross-platform network capture interface[span_4](start_span)[span_4](end_span)
* **Captured Protocol:** TCP [span_5](start_span)[span_5](end_span)[span_6](start_span)[span_6](end_span)
---

## 🚀 Methodology & Steps Performed

1. **Traffic Capture:** 
   * Opened Wireshark and selected the active network interface (Ethernet/Wi-Fi) to begin recording live data packets[span_7](start_span)[span_7](end_span).
   * Generated web browsing and background system traffic to ensure active TCP streams were present.

2. **Packet Filtering:** 
   * Applied the display filter `tcp` in the Wireshark filter bar to eliminate noise from background protocols (like ARP, DNS, and UDP) and isolate purely TCP-related traffic[span_8](start_span)[span_8](end_span)[span_9](start_span)[span_9](end_span).

3. **TCP Three-Way Handshake Analysis:** 
   * Located a standard connection establishment sequence between a client and server IP address[span_10](start_span)[span_10](end_span).
   * **SYN (Synchronize):** The client initiates connection synchronization by sending a packet with the SYN flag set.
   * **SYN-ACK (Synchronize-Acknowledgment):** The server responds acknowledging the request and sets its own SYN flag.
   * **ACK (Acknowledgment):** The client sends a final acknowledgment packet back, establishing a reliable bidirectional connection.

---

## 📷 Captured Evidence / Screenshot
<img width="1917" height="645" alt="Screenshot 2026-10-31 115146" src="https://github.com/user-attachments/assets/33f3706d-7ad3-4f7b-b471-6a83f9a76da6" />
*(The screenshot above displays Wireshark filtering active TCP streams, showing flags, sequence numbers, and length parameters.)*

---

## 📈 Conclusion
This exercise successfully demonstrated how to capture live network packets, filter specific transport layer protocols, and trace connection handshakes using Wireshark[span_11](start_span)[span_11](end_span).
