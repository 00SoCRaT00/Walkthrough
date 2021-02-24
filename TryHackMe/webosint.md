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

**Q:** What is the name of the company the domain was registered with?<br>
**A:** NAMECHEAP INC

**Q:** What phone number is listed for the registration company? (do not include country code or special characters/spaces)<br>
**A:** 16613102107

**Q:** What is the first nameserver listed for the site?<br>
**A:** DNS1.REGISTRAR-SERVERS.COM

**Q:** What is listed for the name of the registrant?<br>
**A:** redacted for privacy<br>
Check **Raw Registrar RDAP Response** for the information

**Q:** What country is listed for the registrant?What country is listed for the registrant?<br>
**A:** Panama

### Task 3: Ghosts of Websites Past
-------------------------------
**Resources**:
Wayback Machine: <https://archive.org/>

**Q:** What is the first name of the blog's author?<br>
**A:** Steve

**Q:** What city and country was the author writing from?<br>
**A:** Gwangju, South Korea<br>
**Hints:** Read the Blog, Search the Name of the Location on Google.

**Q:** [Research] What is the name (in English) of the temple inside the National Park the author frequently visits?<br>
**A:** Jeungsimsa Temple<br>
**Hints:** Read a Blog named "Caffe Bonito; Mudeungsan" and search the location on Google.

### Task 4: Digging into DNS
-------------------------------
**Resources**: ViewDNS.Info: <https://viewdns.info/>

**Q:** What was RepublicOfKoffee.com's IP address as of October 2016?<br> 
**A:** 173.248.188.152<br>
**Hints:** Check "IP History"

**Q:** Based on the other domains hosted on the same IP address, what kind of hosting service can we safely assume our target uses?<br>
**A:** Shared
**Hints:** Check "Reverse IP Lookup"

**Q:** How many times has the IP address changed in the history of the domain?<br>
**A:** 4
**Hints:** Check "IP History"

### Task 5: Taking Off The Training Wheels
-------------------------------
**Target**: heat.net

**Q:** What is the second nameserver listed for the domain<br>
**A:** NS2.HEAT.NET

**Q:** What IP address was the domain listed on as of December 2011?<br>
**A:** 72.52.192.240

**Q:** Based on domains that share the same IP, what kind of hosting service is the domain owner using?<br>
**A:** Shared

**Q:** On what date did was the site first captured by the internet archive? (MM/DD/YY format)<br>
**A:** 06/01/97

**Q:** What is the first sentence of the first body paragraph from the final capture of 2001?<br>
**A:** After years of great online gaming, it’s time to say good-bye

**Q:** Using your search engine skills, what was the name of the company that was responsible for the original version of the site?<br>
**A:** SegaSoft

What does the first header on the site on the last capture of 2010 say?<br>
- Heat.net – Heating and Cooling

### Task 6: Taking A Peek Under The Hood Of A Website
-------------------------------
**Target**: heat.net

**Q:** How many internal links are in the text of the article?<br>
**A:** 5<br>
**Hints:** Check "Source Code"

**Q:** How many external links are in the text of the article?<br>
**A:** 1<br>
**Hints:** Check "Source Code"

**Q:** Website in the article's only external link ( that isn't an ad)<br>
**A:** purchase.org

**Q:** Try to find the Google Analytics code linked to the site<br>
**A:** UA-251372-24<br>
**Hints:** "UA-" for Google Adsence ID

**Q:** Is the the Google Analytics code in use on another website? Yay or nay<br>
**A:** Nay
**Resources:** <https://www.nerdydata.com>

**Q:** Does the link to this website have any obvious affiliate codes embedded with it? Yay or Nay<br>
**A:** Nay

### Task 7: Final Exam: Connect the Dots 
-------------------------------
**Target**: heat.net

**Q:** Use the tools in Task 4 to confirm the link between the two sites. Try hard to figure it out without the hint.<br>
**A:** Liquid Web, L.L.C<br>
**Hints:** Same IP Owner. Check "IP History" from Viewdns

### Task 8: Debriefing
-------------------------------
No Answer Needed!!!

### Task 9: Wrap-up
-------------------------------
No Answer Needed!!!
