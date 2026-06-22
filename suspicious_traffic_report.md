# Suspicious Traffic Report
## 1. ARP Storm (arp-storm.pcap)
- Observed: Hundreds of ARP requests with no replies
- Why suspicious: Indicates ARP flood attack or misconfigured device
- Risk: Can cause network slowdown or be used for reconnaissance
## 2. Unencrypted HTTP Traffic (v6-http.cap)
- Observed: HTTP GET request with full headers visible in plaintext
- User-Agent: Lynx/2.8.6rel.2
- Why suspicious: All data visible to anyone intercepting traffic
- Risk: Credentials and data exposed
## 3. NTP Traffic (capture.pcap)
- Observed: Repeated NTP client/server exchanges
- Source: 170.187.147.56
- Why suspicious: Could indicate NTP amplification attack
- Risk: Used in DDoS attacks
