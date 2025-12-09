## Incident report analysis: Applying the NIST CSF

# Summary

The organization experienced an even in which all network services stopped working. The team researched the event and found the disruption was caused by a distributed denial by a distributed denial of services (DDoS) attack through a large influx of ICMP packets. The team blocked the attack, all non-critical network services were stopped in order to restore the critical services.

# Identify

The team in charge of the incident has audited all access policies that were involved in the attack. Later, it was found that a malicious attacker has sent a flood of ICMP pings into the organization’s network through an unconfigured firewall overwhelming the company’s network through a distributed denial of service (DDoS) attack.

# Protect

In order to address this security event and enforce a stronger system, devices and access policies the team implemented the following: a new firewall rule to limit the rate of incoming ICMP packets, source IP address verification of the firewall to check for spoofed IP addresses on incoming ICMP packets, network monitoring software to detect abnormal traffic patterns and an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.

# Detect

The source IP address verification was configured and implemented on the firewall in order to check for spoofed IP addresses on incoming ICMP packets. Additionally, the team implemented network monitoring software to detect unusual influx patterns.

# Respond

In order to prevent future malicious attacks, the team will isolate the systems that were affected in the event in order to prevent further disruption. The team will implement the restoration of the critical systems that were disrupted by the malicious attack. A report will be expedited to upper management documenting the activities and results for future reference.

# Recover

The access to all network services must be restored in order to recover from a DDoS malicious attack. In future instances, the firewall will block ICMP block attacks coming from external actors. The services under the category of non-critical should be stopped, in order to restore the critical network firstly. Lastly, when the flood of ICMP packets is over, we can bring the non-critical services back to normal.
 
# Notes:

This incident showed how a small security gap, such as an unconfigured firewall, can lead to a major disruption. The DDoS attack overwhelmed the network ad forced the team to make quick decisions to protect critical services.
Clearly, the event highlighted the need of stronger preventive controls and better monitoring, adding firewall rate limiting, IP verification, and network monitoring tools, the organization improved its ability to detect these attacks in the future.

This experience reinforced the importance of reviewing configurations to prevent malicious incidents.
