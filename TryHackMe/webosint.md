# WebOSINT
Lab Link - <https://tryhackme.com/room/webosint>

### Task 1: When A Website Does Not Exist
-------------------------------
No Answer Needed!!!

### Task 2: Whois Registration
-------------------------------
**Resources**:
ICANN Lookup: <https://lookup.icann.org/lookup><br>
DomainTools: <https://whois.domaintools.com><br>

Q: What is the name of the company the domain was registered with?<br>
A: NAMECHEAP INC

Q: What phone number is listed for the registration company? (do not include country code or special characters/spaces)<br>
A: 16613102107

Q. What is the first nameserver listed for the site?<br>
A. DNS1.REGISTRAR-SERVERS.COM

Q. What is listed for the name of the registrant?<br>
A. redacted for privacy<br>
Check **Raw Registrar RDAP Response** for the information

Q. What country is listed for the registrant?What country is listed for the registrant?<br>
A. Panama

### Task 3: Ghosts of Websites Past
-------------------------------
**Resources**:
Wayback Machine: <https://archive.org/>

What is the first name of the blog's author?
- Steve

What city and country was the author writing from?
- Gwangju, South Korea<br>
**Hints:** Read the Blog, Search the Name of the Location on Google.

[Research] What is the name (in English) of the temple inside the National Park the author frequently visits?
- Jeungsimsa Temple<br>
**Hints:** Read a Blog named "Caffe Bonito; Mudeungsan" and search the location on Google.

### Task 4: Digging into DNS
-------------------------------
**Resources**:
ViewDNS.Info: <https://viewdns.info/>

What was RepublicOfKoffee.com's IP address as of October 2016? 
- 173.248.188.152<br>
**Hints:** Check "IP History"

Based on the other domains hosted on the same IP address, what kind of hosting service can we safely assume our target uses?
- Shared
**Hints:** Check "Reverse IP Lookup"

How many times has the IP address changed in the history of the domain?
- 4
**Hints:** Check "IP History"

### Task 5: Taking Off The Training Wheels
-------------------------------
**Target**: heat.net

What is the second nameserver listed for the domain
- NS2.HEAT.NET

What IP address was the domain listed on as of December 2011?
- 72.52.192.240

Based on domains that share the same IP, what kind of hosting service is the domain owner using?
- Shared

On what date did was the site first captured by the internet archive? (MM/DD/YY format)
- 06/01/97

What is the first sentence of the first body paragraph from the final capture of 2001?
- After years of great online gaming, it’s time to say good-bye

Using your search engine skills, what was the name of the company that was responsible for the original version of the site?
- SegaSoft

What does the first header on the site on the last capture of 2010 say?
- Heat.net – Heating and Cooling

### Task 6: Taking A Peek Under The Hood Of A Website
-------------------------------
**Target**: heat.net

How many internal links are in the text of the article?
- 5<br>
**Hints:** Check "Source Code"

How many external links are in the text of the article?
- 1<br>
**Hints:** Check "Source Code"

Website in the article's only external link ( that isn't an ad)
- purchase.org

Try to find the Google Analytics code linked to the site
- UA-251372-24<br>
**Hints:** "UA-" for Google Adsence ID

Is the the Google Analytics code in use on another website? Yay or nay
- Nay
**Resources:** <https://www.nerdydata.com>

Does the link to this website have any obvious affiliate codes embedded with it? Yay or Nay
- Nay

### Task 7: Final Exam: Connect the Dots 
-------------------------------
**Target**: heat.net

- Liquid Web, L.L.C
**Hints:** Same IP Owner. Check "IP History" from Viewdns

### Task 8: Debriefing
-------------------------------
No Answer Needed!!!

### Task 9: Wrap-up
-------------------------------
No Answer Needed!!!