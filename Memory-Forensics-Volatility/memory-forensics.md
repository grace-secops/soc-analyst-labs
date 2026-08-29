 Memory Forensics Investigation

 Overview

I worked on this lab to understand how memory forensics can be used to investigate a compromised system. Using Volatility and Redline, I analysed a memory dump and looked for processes, command execution and network activity that could indicate suspicious behaviour.

This exercise helped me understand that memory analysis can provide useful evidence about what was happening on a system at the time the memory was captured.

 Objective

The objective was to analyse a compromised system memory dump and identify suspicious processes, command execution and network communication.

 Tools Used

* Volatility
* Redline

 Investigation

 1. Analysed the Memory Dump

I used memory forensic tools to examine the captured memory and look for processes and other activity that could provide evidence of suspicious behaviour.

 2. Investigated Suspicious Processes

During the investigation, I identified a suspicious process:

oneetx.exe

I treated the process as suspicious based on the findings from the memory analysis and continued investigating the activity associated with it.

 3. Investigated Command Execution

I also identified activity involving:

`rundll32.exe`

This was important to investigate because `rundll32.exe` can be used to execute DLL-related activity and may require further analysis when it appears in a suspicious context.

4. Investigated Network Communication

The investigation also identified communication with the following IP address:

`77.91.124.20`

This provided another piece of evidence to consider when investigating the activity found in the memory dump.

 Investigation Findings

The main findings from the investigation were:

* Suspicious process: `oneetx.exe`
* Suspicious command execution: `rundll32.exe`
* Network communication with: `77.91.124.20`

Looking at these findings together helped me understand how different pieces of evidence can be connected during a digital forensics investigation.

 What I Learned

This lab gave me practical experience with:

* Analysing system memory
* Investigating running processes
* Identifying suspicious activity
* Investigating command execution
* Examining network indicators
* Using memory forensic tools during an investigation

 Challenge

The challenging part was knowing which findings required further investigation. A memory dump can contain a large amount of information, so I had to focus on processes, commands and network activity that appeared unusual and then connect the different findings together.

Conclusion

This investigation helped me understand how memory forensics can be used to reconstruct activity on a compromised system. It also showed me the importance of looking at multiple pieces of evidence instead of relying on one suspicious process or indicator alone. The experience increased my interest in digital forensics and incident investigation.
