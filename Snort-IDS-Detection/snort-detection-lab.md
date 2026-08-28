Snort Intrusion Detection Lab

 Overview

I worked on this lab to understand how an Intrusion Detection System (IDS) can be used to monitor network traffic and identify suspicious activity. I used Snort on Kali Linux to create a simple detection rule, generate network traffic and observe the alerts produced by Snort.

This was a hands-on exercise that helped me understand the relationship between network traffic, detection rules and security alerts.

 Objective

The main objective was to configure Snort, monitor network traffic and test whether it could detect traffic that matched a defined rule.

 Tools Used

* Snort IDS
* Kali Linux

 What I Did

1. Configured and validated Snort

I started by configuring Snort and checking that the configuration was valid before beginning the detection test.

![Snort Configuration Validation](snort-config-validation.jpeg)

2. Created a detection rule

I created a Snort rule to identify the network activity I wanted to monitor. This helped me understand how detection rules can be used to tell an IDS what type of traffic to look for.

![Snort Detection Rule](snort-rule.jpeg)

3. Generated network traffic

I generated network traffic while Snort was running so that I could test whether the rule would identify the activity.

![Traffic Generation](traffic-generation.jpeg)

 4. Monitored the alerts

Snort successfully generated an alert when the monitored traffic matched the detection rule. I reviewed the alert to understand how Snort reports detected activity.

![Snort Alert](snort-alert-detected.jpeg)

 What I Observed

The lab showed me how an IDS can continuously monitor network traffic and generate an alert when activity matches a defined detection rule. Seeing the alert appear after generating the traffic made the process much clearer to me than simply reading about IDS concepts.

 What I Learned

Through this lab, I gained practical experience with:

* Configuring and validating Snort
* Creating basic IDS detection rules
* Monitoring network traffic
* Interpreting Snort alerts
* Understanding the basic workflow of network threat detection

 Challenge

One of the things I found challenging was understanding how the configuration, detection rule and generated traffic all needed to work together for the alert to appear. Working through the lab helped me understand that a detection rule is only useful when it is correctly configured and tested against the type of traffic it is designed to detect.

Conclusion

This lab gave me a better understanding of how SOC analysts can use intrusion detection tools to monitor network activity and investigate potential threats. It also increased my interest in learning more about network security and security monitoring.


