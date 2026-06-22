# Wireshark Filter Cheat Sheet
1. http - Shows all HTTP traffic
2. dns - Shows all DNS queries and responses
3. arp - Shows all ARP packets
4. tcp - Shows all TCP traffic
5. udp - Shows all UDP traffic
6. icmp - Shows all ping traffic
7. ntp - Show all NTP time sync traffic
8. ip.addr == 10.0.2.15 - Traffic to or from specific IP
9. tcp.port == 443 - HTTPS traffic only
10. http.request.method == "GET" - HTTP GET requests only
11. tcp.flags.syn == 1 - TCP connection attempts
12. !arp - All traffic except ARP
