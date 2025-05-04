# ej5ackson.github.io (SOC Analysis Project)   
# Hi, Hello Evans Martey Jackson Korley
### Dynamic, detail-oriented Cybersecurity Analyst with 10+ years in engineering/cybersecurity. Safeguards infrastructure via advanced configurations, log/network analysis (Wireshark, TCPDump), and incident response (SIEM). Conducts audits aligning with CIA/DAD, improving security and compliance. Engineering background bolsters structured thinking and operational excellence.

   ## 1.Executive Summary 
This report presents a comprehensive analysis of Socra Tech's escalating concerns regarding suspicious network activities, including potential unauthorized access, malware infections, and insider threats. The primary objective was to enhance the organization's cybersecurity posture through a systematic investigation of network security using a three-phase Security Operations Center (SOC) approach, leveraging tools such as Wireshark, pfSense, and Wazuh. 

**The analysis focused on three key objectives**: 

•	**Detection and Response to Network Anomalies**: Utilizing advanced monitoring tools to identify unusual patterns and behaviors in network traffic, which are indicative of potential security threats.

•	**Blocking Malicious Traffic**: Implementing proactive measures to filter out malicious traffic, thereby reducing the risk of compromise from known threats. 

•	**Investigation of Potential Threats**: Conducting in-depth examinations of identified anomalies to understand their nature and impact, which aids in formulating effective response strategies. 
Through these efforts, several critical Indicators of Compromise (IoCs) were identified and mitigated, significantly reducing the risk of security breaches. The final recommendations provided aim to fortify Socra Tech's cybersecurity framework, ensuring a more resilient and secure network environment. The insights gained from this analysis will empower Socra Tech to better safeguard its assets and maintain operational integrity in the face of evolving cyber threats. 

## 2. Project Introduction 
SoCraTech, a growing technology solutions provider, has noticed an increase in suspicious network activity, leading to concerns about potential unauthorized access, malware infections, and insider threats.  
As a cybersecurity analyst in the company's Security Operations Center (SOC), your task is to deploy, monitor, and analyze network security events using Wireshark, pfSense, and Wazuh to strengthen the organization's cybersecurity posture.

## 3. Project Objectives 

•	Deploy and configure Wireshark, pfSense, and Wazuh to monitor and analyze network traffic.

•	Identify and analyze threats such as malware communication, unauthorized access and anomalies. 

•	Implement security policies using pfSense to block malicious traffic. 

•	Perform incident response and document security findings with Wazuh. 
 
## 4. Rationale for the Project 
**Importance of the project to the business and the SOC Analyst**: 

•	To practice with SOC tools and understand incident detection better. 

•	Learn to analyze security threats from packet captures, firewall logs, and SIEM alerts. 

•	Improve network defense strategies using pfSense firewall rules and SIEM automation for the organization. 

## 5. Tech Tools Stack: 
•	Wireshark: A powerful network protocol analyzer used for capturing and analyzing network traffic in real-time. It helps identify anomalies and troubleshooting network issues by providing detailed packet-level information. 

•	pfSense: An open-source firewall and router software based on FreeBSD. It provides extensive network security features, including traffic filtering, VPN support, and intrusion detection/prevention systems (IDS/IPS). 

•	Wazuh: An open-source security monitoring platform designed to detect intrusions and monitor system integrity. Wazuh integrates with various SIEM solutions and provides log analysis, file integrity monitoring, and real-time alerting capabilities. 

•	Ubuntu VM: A virtual machine running the Ubuntu operating system, commonly used for various applications, including hosting servers, developing software, and testing security tools in a controlled environment.

•	Kali Linux: A Debian-based Linux distribution specifically designed for penetration testing and security assessments. It comes preloaded with a wide array of tools for security auditing, vulnerability assessment, and exploitation. 

## 6. Methodology 
The project employs a structured methodology for deploying, monitoring, and analyzing network security events within SoCraTech's infrastructure. The primary goal is to detect, respond to, and mitigate potential threats using a range of SIEM tools, including Wireshark, pfSense, Wazuh, Kali Linux, and Ubuntu VMs. The methodology is organized into specific phases, which facilitate a comprehensive approach to network security management. To investigate and enhance network security, a structured three-phase Security Operations Center (SOC) approach was utilized, incorporating the following tools: 

## Project featured:

•**pfSense as the firewall**: Acting as the primary network defence barrier.

•**Ubuntu servers for centralized logging and SIEM integration**: Serving as the hub for collecting and processing security event data.

•	**Wazuh for endpoint monitoring and anomaly detection**: Providing visibility and security analysis on individual devices.

•	**Wireshark for in-depth packet inspection and traffic analysis**: Enabling detailed examination of network communications.

•	**Simulation of diverse attacks using Kali Linux**: Testing the network's defences against realistic threats.

•	Specifically, I utilized pfSense to serve as the network's firewall, controlling and filtering incoming and outgoing traffic. Ubuntu servers were deployed to act as the central repository for logging data, 
facilitating the crucial function of SIEM (Security Information and Event Management) integration.

•	Snort is a security engine utilized to runs on pfSense (as a package) to provide advanced intrusion detection and prevention capabilities by analyzing network traffic against a set of rules.

•	For endpoint monitoring and anomaly detection, I implemented Wazuh, a powerful open-source security platform. This allowed me to gain visibility into the activity on individual devices within the network and identify unusual or suspicious behaviour.

•	To enable in-depth examination of network communications, I utilized Wireshark for packet inspection and traffic analysis. This tool provided granular insights into the data flowing across the network, aiding in understanding normal behaviour and identifying potential threats.

•	To rigorously evaluate the resilience of the constructed defence system, I conducted simulations of diverse attacks using Kali Linux. These simulated attacks included common tactics such as brute force attempts, port scanning, and malware injection, allowing me to test the system's ability to detect and potentially block these threats.
I emphasize that this practical project not only deepened my understanding of security architecture principles but also reinforced the critical importance of proactive surveillance and implementing multi-layered defences to effectively protect a network. I now eager to apply these acquired competencies in a professional cybersecurity role to help organizations anticipate and mitigate emerging risks.

- [LinkedIn Profile](https://linkedin.com/in/yourprofile)
  
  ![image alt](https://github.com/ej5ackson/ej5ackson.github.io/blob/main/A%20screenshot%20illustrates%20Wazuh%20dashboard%20overview%20after%20the%20attack.jpg)
- A screenshot illustrates Wazuh dashboard overview after the attack  
 ![image alt](https://github.com/ej5ackson/ej5ackson.github.io/blob/main/A%20screenshot%20illustrates%20configuring%20Snort%20LAN%20settings%20on%20pfSense.jpg)
- A screenshot illustrates configuring Snort LAN settings on pfSense 
 ![image alt](https://github.com/ej5ackson/ej5ackson.github.io/blob/main/A%20screenshot%20illustrates%20the%20firewall%20rules%20that%20have%20been%20configured%20to%20block%20access%20to%20SSH%20(port%2022)%20from%20specific%20untrusted%20sites..jpg)
- A screenshot illustrates the firewall rules that have been configured to block access to SSH (port 22) from specific untrusted sites. 
 ![image alt](https://github.com/ej5ackson/ej5ackson.github.io/blob/main/Displays%20a%20screenshot%20of%20the%20Installed%20Rules%20and%20updating%20Snort%20settings%20on%20pfSense.jpg)
- Displays a screenshot of the Installed Rules and updating Snort settings on pfSense 
 ![image alt](https://github.com/ej5ackson/ej5ackson.github.io/blob/main/Displays%20a%20screenshot%20of%20the%20capturing%20network%20traffic%2C%20focusing%20on%20HTTP%20in%20Wireshark.jpg)
- Displays a screenshot of the capturing packets Identify Suspicious Traffic Patterns. in Wireshark 
 ![image alt](https://github.com/ej5ackson/ej5ackson.github.io/blob/main/Wazuh%20dashboard%20illustrates%20a%20range%20of%20detected%20threats%20related%20to%20threat%20hunting.jpg)
- A screenshot of Wazuh dashboard illustrates a range of detected threats related to threat hunting activities. It provides a visual representation of various attack types, highlighting the security incidents identified within the monitored environment, facilitating effective analysis and response to potential security threats.
   
## Skills: Protecting digital assets through technical knowledge and practical application.
- **Technical Expertise**: Web &amp; Application Security, Penetration Testing,
Risk Assessments, Network Security, Endpoint security,
- **Tools**:Nmap, Metasploit, Wireshark, Google Cloud, Wazuh, PFSense, Qradar
### GitHub Stats
![GitHub Stats](https://github-readme-
stats.vercel.app/api?username=yourusername&amp;show_icons=true&amp;theme=radical)
### ✨ Fun Fact
I&#39;m on a (fill in the gap).
