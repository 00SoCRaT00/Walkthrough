# THREAT INTELLIGENCE

Lab Link - <https://tryhackme.com/room/threatintelligence>

### Task 1: Understanding a Threat Intelligence blog post on a recent attack
-------------------------------
No Answer needed!!!<br>

### Task 2: Review the FireEye Threat Intel on the SUNBURST Malware
-------------------------------
No Answer needed!!!<br>

### Task 3: Analyze Threat Intelligence
-------------------------------
**Q**: After reading the report what did FireEye name the APT?<br>
**A**: UNC2452<br>

**Q**: FireEye released some information to help security orgranizations Blue Team to detect the tools which have been leaked. What 'multiple languages' can you find the rules?<br>
**A**: Snort|Yara|IOC|ClamAV<br>

**Q**: Which dll file was used to create the backdoor?
<br>
**A**: SolarWinds.Orion.Core.BusinessLayer.dll<br>

**Q**: What is the MD5 sum of this file?<br>
**A**: b91ce2fa41029f6955bff20079468448<br>

**Q**: Authorized system administrators commonly perform tasks which ultimately led to how was the malware was delivered and installed into the network. What is the file extension of the software which contains the delivery of the dll file mentioned earlier?<br>
**A**: MSP<br>
**Hint**: SolarWinds-Core-v2019.4.5220-Hotfix5.msp<br>

**Q**: A C2 Framework will Beacon out to the botmaster after some amount of time. This particular malware sample was purposely crafted to evade common sandboxing techniques by using a longer than normal time with a large jitter interval as well. How long does the malware stay hidden on infected machines before beginning the beacon? Min Time | Max Time | Unit of Measure for time<br>
**A**: 12|14|Days<br>

**Q**: Can you find the IoCs for host-based and network-based detection of the C2? The flag is the name of the classification which the first 3 network IP address blocks belong to?<br>
**A**: RFC 1918<br>

**Q**: In the snort rules you can find a number of messages reffering to Backdoor.SUNBURST and Backdoor.BEACON. Only one of these domains resolves to a fake organization posing as an online college. What is the quoted domain name in the content field for this organization?<br>
**A**: digitalcollege.org<br>

**Q**: Steganography was used to obfuscate the commands and data over the network connection to the C2. If I wanted to change registry values on a remote machine which number command would the attacker use?<br>
**A**: 14<br>
**Hint**: SetRegistryValue - Arbitrary registry write from one of the supported hives.<br>

**Q**: How was that payload encoded?<br>
**A**: Base64<br>

**Q**: What is the name of the program which dispatches the jobs?<br>
**A**: JobExecutionEngine<br>

**Q**: How many Mitre Attack techniques were used?<br>
**A**: 17<br>

**Q**: According to Solarwinds response only a certain number of machines fall vulnerable to this attack. What is the number of potentially affected machines?<br>
**A**: 18,000<br>

**Q**: FireEye recommends a number of items to do immediately if you are an administrator of an affected machine. What is the name of the new recommended patch release?<br>
**A**: 2020.2.1 HF 1,<br>

### Task 4: Additional Resources
-------------------------------
No Answer needed!!!<br>