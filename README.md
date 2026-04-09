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
![P1](https://github.com/user-attachments/assets/c9b18c06-a4e6-4095-9ca4-89e1c4c2f992)

![P2](https://github.com/user-attachments/assets/9cd38ed4-578f-4498-9601-029245cb02a8)

![P3](https://github.com/user-attachments/assets/dab2ae12-8cd9-4227-8c84-d20e96f1d1d9)

*Ref 2: Snort alert log confirming successful detection against PCAP*

![P4](https://github.com/user-attachments/assets/f5dd2f15-6a24-44ba-92bf-f11aa42ecdb1)

*Ref 3: Custom Snort rule detecting FTP-based attack pattern*
![p2_2](https://github.com/user-attachments/assets/99c0b718-e3f2-445e-86cd-02d229eb3e46)

![p3_2](https://github.com/user-attachments/assets/ff60416f-d7dc-45ba-a845-027b66140f7c)

*Ref 4: Snort alert log confirming successful detection against PCAP*
![p4_2](https://github.com/user-attachments/assets/5616becd-f550-404b-9142-9221ca4dcfb5)

*Ref 5: Custom Snort rule detecting PNG-based attack pattern*
![p1_3](https://github.com/user-attachments/assets/6dd68042-4cd7-4fde-90b5-5845a5d4ce86)

![p2_3](https://github.com/user-attachments/assets/b9cc381c-383a-4075-944d-ef47caf03711)

*Ref 6: Custom Snort rule detecting keyword-based attack pattern*

![P1_4](https://github.com/user-attachments/assets/7fe6af03-9788-40f0-b8d4-2ce98b76b254)

![p2_4](https://github.com/user-attachments/assets/75b7d6e4-f9e5-436b-8b5a-b874b7b19ab9)

*Ref 7: Snort alert log confirming successful detection against PCAP*

![p3_4](https://github.com/user-attachments/assets/c6a823dc-e3ac-4cc4-876e-d3bde1d41c2b)

![p4_4](https://github.com/user-attachments/assets/90601c9a-befb-49d1-a424-4cafd619c1cb)







