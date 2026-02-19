# Task 5 – Wireshark Packet Analysis

Wireshark

1. Started capture on Wi-Fi interface.
2. Generated traffic by browsing google.com and pinging google.com.
3. Stopped capture after 1 minute.
4. Applied filters: dns, tcp, http.
5. Exported capture as task5_capture.pcap.


### DNS
Used to resolve domain names to IP addresses. Observed DNS query for google.com.

### TCP
Reliable transport protocol. Observed TCP 3-way handshake (SYN, SYN-ACK, ACK).

### HTTP
Used for web communication. Observed HTTP GET request for a webpage.

## Conclusion
Captured and analyzed live packets and identified DNS, TCP and HTTP protocols successfully.
