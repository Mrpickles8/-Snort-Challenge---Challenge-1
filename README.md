# -Snort-Challenge---Challenge-1

## Objective
Learn and apply Snort IDS/IPS rule syntax to analyze network traffic and write custom detection rules for known attack patterns. The focus was on understanding rule structure, testing against PCAP files, and validating detection accuracy.

### Skills Learned
- Snort rule syntax (header + options)
- PCAP analysis and traffic pattern recognition
- IDS vs IPS mode configuration
- Custom rule writing and validation
- Network protocol understanding (TCP, UDP, ICMP, HTTP)

### Tools Used
- Snort IDS/IPS (version 2/3)
- Wireshark for PCAP pre-analysis
- Linux CLI for Snort execution and log review
- tcpdump

## Steps
Each task required writing a custom Snort rule targeting a specific traffic pattern identified in the provided PCAP. Rules were tested in IDS mode first to verify alert generation without dropping traffic. Traffic was pre-analyzed in Wireshark to identify key fields (source/destination IP, port, payload signatures) before writing rules. Rules were iteratively refined based on false positive and false negative rates. Final rules were documented with explanations of each option used.

*Ref 1: Custom Snort rule detecting HTTP-based attack pattern*
*Ref 2: Snort alert log confirming successful detection against PCAP*
