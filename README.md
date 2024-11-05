# Wireshark-Labs
Overview
This Wireshark lab provides a hands-on approach to network packet analysis. Using Wireshark, you’ll capture, analyze, and interpret different types of network traffic to understand protocols, data flows, and network behavior. This lab will enhance your understanding of how data moves within a network, how various protocols work, and how to troubleshoot common network issues.

Objectives
Learn to capture network traffic using Wireshark.
Analyze packet data for common protocols (e.g., TCP, UDP, HTTP, DNS, ICMP).
Identify key packet details such as IP addresses, port numbers, protocol types, and data payloads.
Understand network behaviors such as handshake processes, data exchange, and error messages.
Troubleshoot network issues by analyzing packet contents.
Prerequisites
Basic understanding of networking concepts (e.g., IP addresses, MAC addresses, protocols).
Familiarity with the OSI and TCP/IP models.
Wireshark installed on your computer.
Lab Setup
Install Wireshark: Download Wireshark from https://www.wireshark.org/download.html.
Network Access: Ensure your computer has network access for live packet capture.
Administrative Privileges: Wireshark may require admin access to capture packets.
Tasks and Instructions
Task 1: Capture Network Traffic
Open Wireshark and select the network interface to capture packets.
Start the capture by clicking the Start button.
Visit various websites, ping a server, or initiate another network activity.
Stop the capture after a few seconds by clicking the Stop button.
Task 2: Filter and Analyze Packets
Filter Packets: Use the display filter to isolate specific protocols:
HTTP: http
DNS: dns
ICMP: icmp
TCP: tcp
Analyze Packet Details:
Right-click on a packet and select Follow TCP/UDP Stream to observe a conversation.
Expand packet details in the lower pane to see fields like Source and Destination IP, Port numbers, Flags, and Payload.
Task 3: Observe Protocol Behaviors
Identify three-way handshake in TCP communications.
Locate DNS requests and responses.
Inspect HTTP GET and POST requests to understand data exchanges.
Task 4: Network Troubleshooting
Simulate a connection error (e.g., incorrect URL or IP).
Capture packets and identify error messages (e.g., ICMP unreachable).
Use filters to pinpoint issues and document your findings.
Task 5: Document Findings
Take screenshots of important packet details and conversations.
Describe the data flow and protocol behavior.
Identify any observed issues and propose potential solutions.
Report Template
Create a report with the following sections:

Introduction: Briefly describe the purpose of the lab.
Methodology: Explain the steps followed to capture and analyze packets.
Results:
Key findings from protocol analysis.
Screenshots of packet details and summaries of observed network behavior.
Conclusion: Summarize insights gained from the lab.
Troubleshooting Notes: Describe any issues identified and steps to resolve them.
Additional Resources
Wireshark User Guide: https://www.wireshark.org/docs/wsug_html_chunked/
Wireshark Filters: https://wiki.wireshark.org/DisplayFilters
