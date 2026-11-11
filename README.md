\# Day 5 – Network Traffic Analysis Using Wireshark



\## Objective

Capture and analyze live network traffic using Wireshark and identify different network protocols.



\## Tools Used

\- Wireshark

\- Windows 11

\- Command Prompt



\## Practical Tasks Completed



\### 1. ICMP Analysis

\- Applied the `icmp` display filter.

\- Identified ICMP Destination Unreachable messages.

\- Analyzed ICMP Type 3 and Code 3.



\### 2. DNS Analysis

\- Applied the `dns` display filter.

\- Used `nslookup example.com`.

\- Identified A and AAAA DNS queries and responses.

\- Observed UDP port 53.



\### 3. TCP Analysis

\- Used `curl http://example.com`.

\- Captured TCP SYN, SYN-ACK and ACK packets.

\- Identified HTTP GET requests and server responses.

\- Observed FIN and ACK flags.



\## Display Filters Used



```text

icmp

dns

dns.qry.name == "example.com"

tcp

tcp.port == 80

tcp.flags.syn == 1

udp

```



\## Project Structure



\- `screenshots/` – Practical screenshots

\- `reports/` – Final internship report

\- `captures/` – Packet capture files



\## Conclusion



This practical improved my understanding of network traffic analysis, packet capture, DNS resolution, ICMP error messages, TCP connection establishment and HTTP communication.



\## Disclaimer

This project was conducted on my own network for educational purposes.

