# task1
scanning local network for open ports
The NMAP scan identified several open ports, primarily related to Microsoft Windows networking protocols. These ports—including 135, 137, 139, and 445—are associated with services that have a history of significant vulnerabilities. The presence of these open ports represents a critical security risk, as they can be exploited for information disclosure, unauthorized access, and the propagation of malware, such as ransomware. Immediate action is required to mitigate these risks.
Ports 135, 137, 139 (RPC & NetBIOS): These ports are tied to legacy Windows protocols. Their presence on the network can be a sign of outdated security practices. These services can be exploited by attackers to gather network information, enumerate users, and launch denial-of-service attacks. They have been a primary attack vector for well-known malware.
Based on this analysis, the following actions are recommended to enhance the security posture of the network:
​Patch Management: Ensure the operating system and all services are regularly updated with the latest security patches to fix known vulnerabilities.
​Firewall Configuration: Implement strict firewall rules to block incoming connections to these ports from outside the local network. Consider restricting access even within the network to only essential, trusted devices.
​Disable Unused Services: Disable any services associated with the identified open ports that are not critical for the system's function. This is particularly relevant for legacy protocols like NetBIOS.
​Network Segmentation: Isolate critical systems and sensitive data from the rest of the network to limit an attacker's ability to move laterally.
