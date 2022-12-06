| **Domain** | **Status** | **DOD** | **RFN** | **DOM** | **Affiliated domains/subdomains** |
| --- | --- | --- | --- | --- | --- |
| portswigger.net | <span style="color: red;">spoofable</span> | 12/2/22 | Refusal | N/A | <span style="color: red;">(All existing and non-existent subdomains)</span> <details><summary>Known existing subdomains</summary> forum.portswigger.net<br>enterprise-demo.portswigger.net</details> |
| timcast.com | <span style="color: red;">spoofable</span> | 11/5/22 | Unresponsive | N/A | <span style="color: red;">(All existing and non-existent subdomains)</span> |
| projectveritas.com | <span style="color: red;">spoofable</span> | 10/17/22 | Inaction | N/A | <span style="color: red;">(All existing and non-existent subdomains)</span> <details><summary>Known affiliated domains</summary>projectveritasshop.com</details> |
| inversecos.com | <span style="color: red;">spoofable</span> | 11/19/22 | Unresponsive | N/A | <span style="color: red;">(All existing and non-existent subdomains)</span> |
| dailywire.com | <span style="color: red;">spoofable</span> | 10/17/22 | Unresponsive | N/A | <span style="color: red;">(All existing and non-existent subdomains)</span> <details><summary>Known existing subdomains</summary>store.dailywire.com<br>get.dailywire.com<br>advertise.dailywire.com<br>privacy.dailywire.com<br> </details> |
| hashcat.net | <span style="color: red;">spoofable</span> | 10/17/22 | Refusal | N/A | <span style="color: red;">(All existing and non-existent subdomains)</span> |
| highbitsecurity.com | <span style="color: red;">spoofable</span> | 10/17/22 | Unresponsive | N/A | <span style="color: red;">(All existing and non-existent subdomains)</span> <details><summary>Known affiliated domains</summary> hibitsec.com<br>linkmountain.com</details> |
| safex.io | <span style="color: red;">spoofable</span> | 2/15/22 | Unresponsive | N/A | <span style="color: red;">(All existing and non-existent subdomains)</span> <details><summary>Known affiliated domains</summary> safex.org<br>dandabek.com</details> |
| utulsa.edu | <span style="color: red;">spoofable</span> | 2/15/22 | Unresponsive | N/A | <span style="color: red;">(All existing and non-existent subdomains)</span> <details><summary>Known affiliated domains</summary>tulsahurricane.com<br>tualumni.com<br> </details> <details><summary>Known existing subdomains</summary>applytulsa.utulsa.edu<br>libraries.utulsa.edu<br>bulletin.utulsa.edu<br>hub.utulsa.edu<br>artsandsciences.utulsa.edu<br>business.utulsa.edu<br>engineering.utulsa.edu<br>healthsciences.utulsa.edu<br>graduate.utulsa.edu<br>law.utulsa.edu<br>calendar.utulsa.edu<br> </details> |
| sega.com | <span style="color: red;">spoofable</span> | 2/15/22 | Unresponsive | N/A | <span style="color: red;">(All existing and non-existent subdomains)</span> <details><summary>Known affiliated domains</summary> sega.es<br>sega.co.jp<br>amplitude-studios.com<br>segashop.co.uk<br>segashop.eu<br>mpandc.co.jp<br>sega-games.co.jp<br>sega-interactive.co.jp<br>sonicteam.co.jp<br>sonicteam.com<br>sega-net.com<br>sega-net.jp<br>sega-group.co.jp<br>segaplaza.jp<br>segaluckykujionline.net<br>pso2.jp<br>segatoys.co.jp<br>worryeaters.jp<br>mylittlepony.jp<br>segasammy.co.jp<br>bayonetta.com<br>companyofheroes.com<br>dawnofwar.com<br>games2gether.com<br>endlessdungeon.game<br>endless-space.com<br>footballmanager.com<br>humankind.game<br>sonicthehedgehog.com<br>vanquishgame.com<br> </details> <details><summary>Known existing subdomains</summary> shop.sega.com<br>miku.sega.com<br>smb.sega.com<br>yakuza.sega.com<br> privacy.sega.com<br> careers.sega.com<br> games.sega.com<br> newsletter.sega.com<br> smtp3.sega.com<br> sega.sega.jp<br>puyo.sega.jp<br>gw.sega.jp <br>sns.sega.jp<br>lp.pso2.jp<br>puyopuyoquest.sega-net.com<br>segaid.segatoys.co.jp<br>mail01.segaonline.jp<br>mail.segaplaza.jp<br>careers.sega.co.uk<br> support.sega.co.uk<br>creators.humankind.game<br> fmfc.footballmanager.com<br>cdn.sega.co.uk<br>frontiers.sonicthehedgehog.com<br>colors.sonicthehedgehog.com<br>origins.sonicthehedgehog.com </details> |

# Key

DOD = Date of Disregard

RFN = Reason for Negligence

DOM = Date of Mitigation

All affiliated domains and subdomains are under the umbrella of the parent organization and all have the same misconfiguration.

# Why?

I'm always looking at the DNS of any domain I come across for fun and I come across a lots of misconfigurations in regards to email security from the largest organizations to the smallest. Being that phishing is the #1 way to gain initial access, and that it takes virtually 0 time and resources to get DNS right, I made this "wall of shame and negligence".

The ultimate goal of this project is to spread awareness about which domains are contributing to the global phishing problem and maybe if this list gets popular enough it will put pressure on those who refuse to change.

# Methodology and details

I basically take a look at the DNS of any domain I come across on the internet. If I see they have an email vulnerability I attempt to notify the organization and offer help with a screenshot of a POC. After around 2 weeks, if the problem isn't fixed or being addressed in some way they get added to the list.

There is no order to the list. I will not add domains to this list that I have evaluated previous to 2022, the only domains that will be on this list are the ones notified during and after the year 2022. Those on this list are all contributing to the global phishing problem via a critical and easy to fix vulnerability (This type of vulnerability is a "Critical 9.5" according to HackerOne's CVE criticality calculator). I will periodically update the list during my free time, it will slowly but surely grow.

# FAQ

<details><summary>How do I get removed from the list?</summary> You cannot, this is a permanent record.</details> 

<details><summary>Isn't 2 weeks a little unfair for larger orgs with complex infrastructures?</summary>  No, the fix for this particular email authentication vulnerability takes approximately 0 money and about 5 minutes on even the most complex infrastructures.</details>

<details><summary>Why should I believe this list?</summary> Well, you can see if they are spoofable or not yourself by doing a DNS lookup or using the free tool I helped build: <a href="https://github.com/MattKeeley/Spoofy">Spoofy</a>  
If someone on the list attempts to cover up their mistakes and claim they were never vulnerable, you can see their past DNS posture for yourself with this free tool: <a href="https://dnshistory.org">DNS history</a></details>

<details><summary>Why don't you have a "Responsible Domains" list?</summary> It wouldn't make any sense mostly, as this is the basics of owning a domain. Being vulnerable means you didn't do the security basics which means you're negligent or ignorant. Being that the domains on the list have been notified or have no effective way of being notified, there is nothing left to be but negligent. If you aren't vulnerable that means you are just doing what you are supposed to, nothing to be praised.</details>


<details><summary>How do you attempt to contact domain owners/ organizations?</summary> It's different depending on the size of the organization and how much information is available to me. I'm not getting paid to make sure these organization's domains are setup correctly. I'm not going to go out of my way and take a month to attempt to contact someone all sorts of different ways.

I may attempt to reach out more than once to particularly large or popular organizations due to the potential severity and scope their misconfigurations have on customers or fans who don't know any better, otherwise I'm reaching out once.
(Also it should be known that organizations with DNS misconfigurations could be experiencing deliverability issues with email, which means my communications might never make it to the inbox do to finicky workarounds instead of doing the basics)

If it's a personal domain of some security researcher that's active on social media, then I may just message them directly if available. If not, I'll look for an email or some other way to contact on the domain. If the contact information is unavailable or takes it me more than a reasonable amount of research to find the contact information, the domain is added to the list.

If the organization is big or popular I look for contact information on the website. If there is none I will attempt to reach applicable staff on social media. If there is nobody to contact or whoever is contacted doesn't respond, the domain is added to the list.

If an organization has HackerOne or similar, and links to it on their website I will go through the submission process on their platform. If the company has HackerOne or similar and doesn't link to it or if communications with the organization don't link me to it, I'm not going out of my way to look for it.</details>


# Contact

Have any questions, concerns, suggestions, or potential additions to the list? Reach out to calamity#6391 on Discord or reach out via email [here.](mailto:emailsecuritytest@protonmail.com?subject=Phishable)

If you are on the list and have fixed the issue yourself please reach out via email [here.](mailto:emailsecuritytest@protonmail.com?subject=I%20fixed%20my%20domain!)

If you are on the list and need help fixing the issue please reach out via email [here.](mailto:emailsecuritytest@protonmail.com?subject=I%20need%20help%20fixing%20my%20domain!)

# Ideas

- [ ] Create social media for the Phishable project so people can be updated when the list is updated.
- [ ] Add more ideas to the ideas list
