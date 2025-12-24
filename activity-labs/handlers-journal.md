# Activity: Incident handler's journal

## Instructions

As you continue through this course, you may use this template to record your findings after completing an activity or to take notes on what you've learned about a specific tool or concept. You can also use this journal as a way to log the key takeaways about the different cybersecurity tools or concepts you encounter in this course.

# Date: July 23, 2024: Entry 1

## Description: Documenting a cybersecurity incident 

## The incident occurred in the following two phases: 

1.	Detection and Analysis: The organization first detected the ransomware incident and contacted several organizations for assistance.

2.	Containment, Eradication, and Recovery: The scenario details the steps taken to contain the incident, such as shutting down their computer systems but these couldn’t eradicate and recover from the incident alone. Then, they contacted other organizations for support.

## Tool(s) used: The 5 W's 

## Additional notes

- Who: Organized hackers
- What: Ransomware security incident
- Where: Health care company
- When: Tuesday 9:00 a.m.
- Why: Unethical hackers were able to access using a phishing attack. After gaining access, the attackers launched their ransomware on the company's systems, encrypting critical files. The attackers' interest seems to be financial because the ransom note they left demanded a large sum of money in exchange for the decryption key.

## Questions:

1.	How could the health care company prevent an incident like this from occurring again?
2.	Should the company pay the ransom to retrieve the decryption key?

# Date: July 25 2024: Entry 2

## Description:  Analyzing a packet capture file 

## Tool(s) used

For this activity, I used Wireshark to analyze a packet capture file. Wireshark is a network protocol analyzer that uses a graphical user interface. The value of Wireshark in cybersecurity is that it allows security analysts to capture and analyze network traffic. This can help in detecting and investigating malicious activity.

## The 5 W's

- Who: N/A
- What: N/A
- Where: N/A
- When: N/A
- Why: N/A

## Additional notes

It’s my first time using Wireshark. At first, the interface was very overwhelming. I can see why is so important for understanding network traffic.

# Date: July 25 2024: Entry 3

## Description: Capturing my first packet

## Tool(s) used	

I used tcpdump to capture and analyze network traffic. Tcpdump is a network protocol analyzer that's accessed using the command-line interface. Similar to Wireshark, it allows security analysts to capture, filter, and analyze network traffic. 

## The 5 W's	

- Who: N/A
- What: N/A
- Where: N/A
- When: N/A
- Why: N/A

## Additional notes	

I'm still new to using the command-line interface, but after carefully following the instructions and practice the steps, I finally understood how to capture network traffic.

# Date: July 27 2024: Entry 4

## Description: Investigate a suspicious file hash

Tool(s) used	

I used VirusTotal, which analyzes files and URLs for malicious content (viruses, worms, trojans, etc.) and here I used it to analyze a file hash, which was reported as malicious. And it has the required potential when there is compromise like a website or file has been reported as malicious in the Detection and Analysis phase. 

As a security analyst at a SOC, we conducted the steps and the suspicious file was detected by the security systems in place. We performed a deeper analysis to determine if the alert signified a real threat. 

## The 5 W's	

- Who: Unknown malicious actor 
- What: An email sent to an employee contained a malicious file attachment with the SHA-256 file hash of 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b
- Where: The employee's computer at a financial services company
- When: At 1:20 p.m., an alert was sent to the organization's SOC after the intrusion detection system detected the file
- Why: An employee downloaded and executed a malicious file attachment via e-mail.


## Additional notes	

How can we prevent these events in the future? Security awareness training should be improved so that employees are aware of what they click on.

## Reflections/Notes:

1.	Were there any specific activities that were challenging for you? Why or why not?

The activity using tcpdump was challenging. I am new to using the command line, I redid the activity and figured out where I went wrong. 

2.	Has your understanding of incident detection and response changed after taking this course?

At the beginning, I had some basic understanding of what detection and response meant, but I had no idea it was this complex. I learned about the lifecycle of an incident, the importance of plans, processes, and people in addition to the tools used. Overall, I feel that my understanding has changed regarding the incident detection and response.

3.	Was there a specific tool or concept that you enjoyed the most? Why?

I really enjoyed studying about network traffic analysis and applying it through network protocol analyzer tools. I am  interested in becoming more proficient in using network protocol analyzer tools and put my skills into practice in the near future.


