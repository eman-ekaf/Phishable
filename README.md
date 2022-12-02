| **Domain**         | **Status**    | **DOD** | **RFN**    |**DOM**|
|:------------------:|:-------------:|:-------:|:----------:|:-----:|
| portswigger.net    | spoofable     | 12/2/22 |Refusal     | N/A   |
| timcast.com        | spoofable     | 11/5/22 |Unresponsive| N/A   |
| projectveritas.com | spoofable     | 10/17/22|Inaction    | N/A   |
| inversecos.com     | spoofable     | 11/19/22|Unresponsive| N/A   |
| dailywire.com      | spoofable     | 10/17/22|Unresponsive| N/A   |
| hashcat.net        | spoofable     | 10/17/22|Refusal     | N/A   |





# Key

DOD = Date of Disregard 

RFN = Reason for Negligence

DOM = Date of Mitigation


# Why?
I'm always looking at the DNS of any domain I come across for fun and I come across a lots of misconfigurations in regards to email security from the largest organizations to the smallest. Being that phishing is the #1 way to gain initial access, and that it takes virtually 0 time and resources to get DNS right, I made this "wall of shame and negligence". 
	
The ultimate goal of this project spread awareness about which domains are contributing to the global phishing problem and maybe if this list gets popular enough it will put pressure on those who refuse to change.

# Methodology and details
I basically take a look at the DNS of any domain I come across on the internet. If I see they have an email vulnerability I attempt to notify the organization and offer help with a screenshot of a POC. After about a week or two, if the problem isn't fixed or being addressed in some way they get added to the list.

There is no order to the list. I will not add domains to this list that I have evaluated previous to 2022, the only domains that will be on this list are the ones notified during and after the year 2022. Those on this list are all contributing to the global phishing problem via a critical and easy to fix vulnerability (This type of vulnerability is a "Critical 9.5" according to HackerOne's CVE criticality calculator). I will periodically update the list during my free time, it will slowly but surely grow. 

# FAQ

Q: How do I get removed from the list?  
A: You cannot, this is a permanent record.

Q: Isn't 2 weeks a little unfair? Large organizations may have trouble implementing a fix if their infrastructure is too complex.  
A: No, the fix for this particular email authentication vulnerability takes approximately 0 money and about 5 minutes on even the most complex infrastructures.

Q: Why should I believe this list?  
A: Well, you can see if they are spoofable or not yourself by doing a DNS lookup or using the free tool I helped build: https://github.com/MattKeeley/Spoofy  
If someone on the list attempts to cover up their mistakes and claim they were never vulnerable, you can see their past DNS posture for yourself with this free tool: https://dnshistory.org

Q: Why don't you have a "Responsible Domains" list?  
A: It wouldn't make any sense mostly, as this is the basics of owning a domain. Being vulnerable means you didn't do the security basics which means you're negligent or ignorant. Being that the domains on the list have been notified or have no effective way of being notified, there is nothing left to be but negligent. If you aren't vulnerable that means you are just doing what you are supposed to, nothing to be praised.

# Contact
Have any questions, concerns, suggestions, or potential additions to the list? Reach out to calamity#6391 on Discord or reach out via email <a href="mailto:emailsecuritytest@protonmail.com?subject=Phishable">here.</a>

If you are on the list and have fixed the issue yourself please reach out via email <a href="mailto:emailsecuritytest@protonmail.com?subject=I fixed my domain!">here.</a>

If you are on the list and need help fixing the issue please reach out via email <a href="mailto:emailsecuritytest@protonmail.com?subject=I need help fixing my domain!">here.</a>

# Ideas
- [ ] Create social media for the Phishable project so people can be updated when the list is updated.
- [ ] Add more ideas to the ideas list
