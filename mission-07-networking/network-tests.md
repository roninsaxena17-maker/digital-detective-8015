# Task 7.2 — Network Testing

## 1. Connectivity Test

Command used:
`ping -c 4 example.com`

Results:
- 4 packets transmitted
- 4 packets received
- 0% packet loss
- Average round-trip time: 11.290 ms

Conclusion:
The ping test confirmed that my Mac could reach example.com successfully with no packet loss during the test.

## 2. DNS Lookup

Command used:
`nslookup example.com`

Results:
- DNS server used: 8.8.8.8
- DNS port: 53
- Domain queried: example.com
- IP addresses returned: 172.66.147.243 and 104.20.23.154

Conclusion:
The DNS lookup successfully resolved example.com into IP addresses, showing that DNS name resolution was working.
