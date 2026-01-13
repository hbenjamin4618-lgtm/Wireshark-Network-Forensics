# Wireshark-Network-Forensics
Project: Network Traffic Analysis & Forensic Investigation
Objective: To identify security vulnerabilities in network protocols and simulate an incident response scenario.
Key Findings:
Protocol Vulnerability - Identified unencrypted Telnet traffic containing administrative credentials.
Traffic Filtering - Utilized display filters (ip.addr == x.x.x.x and tcp.port == 23) to isolate the suspicious session.
Impact - Demonstrated how an attacker could perform a Man-In-The-Middle (MiTM) attack to gain unauthorized access.
