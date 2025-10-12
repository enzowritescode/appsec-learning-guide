# AppSec Learning Guide

Key AppSec resources that I have used (or am aware of)

## OWASP Top 10s

Offensive security is a key aspect off AppSec. The various vulnerabilities spanning the misc OWASP Top 10 lists that pertain to your role should be a fundamental pillar of your knowledge. Also if you are expanding into a new area, this is a good place to start.

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [OWASP Top 10 API](https://owasp.org/www-project-api-security/)
- [OWASP Top 10 Mobile](https://owasp.org/www-project-mobile-top-10/)
- [OWASP Top 10 CI/CD](https://owasp.org/www-project-top-10-ci-cd-security-risks/)
- [OWASP Top 10 LLM](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- etc. There are [other Top 10 lists](https://owasp.org/search/?searchString=top+10), and surely more will be produced.

## Offensive Security

- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
	- PortSwigger, the creator behind the popular penetration testing tool Burp Suite, has over 250 free labs on their Web Security Academy. They often share bleeding edge research and their researchers often speak at conferences such as DEF CON.
- Open-source intentionally vulnerable projects
	- [Damn Vulnerable Web Application (DVWA)](https://github.com/digininja/DVWA)
	- [OWASP Juice Shop](https://github.com/juice-shop/juice-shop)
	- [Vulnerable Adversely Programmed Interface (vAPI)](https://github.com/roottusk/vapi)
	- [Damn Vulnerable API (DVAPI)](https://github.com/payatu/DVAPI)
	- etc. There are other intentionally vulnerable applications, some of which are no longer maintained but may still be relevant.
- HackTheBox, TryHackMe, etc

## Secure SDLC / DevSecOps

These resources are key for implenting tools and processes into your software development lifecycle (SDLC).

- [OWASP DevSecOps Guideline](https://owasp.org/www-project-devsecops-guideline/)
	- A great place to start when learning about DevSecOps. Start at the left, learn about a particular step, what its goals are, some common tools to accomplish it, and try them out yourself.
		- Ex. for Secret scanning, learn what it is, how software developers should manage secrets, and then pick a tool such as TruffleHog and scan some repositories.
- [OWASP SAMM](https://owaspsamm.org/model/)
- [OWASP DSOMM](https://dsomm.owasp.org/)
- [Video: Strategic use of OWASP SAMM and OWASP DSOMM](https://www.youtube.com/watch?v=MIzENOyylZI)

##  Developer Training

- [OWASP Developer Guide](https://devguide.owasp.org/)
- [OWASP Top 10 Proactive Controls](https://top10proactive.owasp.org/)
- [OWASP Cheat Sheet series](https://cheatsheetseries.owasp.org/)

## Conferences and Meetups

- Local [OWASP Chapter](https://owasp.org/chapters/) meetups
- BSides conferences
- [OWASP conferences](https://owasp.org/events/) (LASCON, OWASP Global AppSec, etc)
- [DEF CON](https://defcon.org/)
- Find other conferences and meetups:
	- [InfoSecMap](https://infosecmap.com/)
	- [Developers Conference Agenda](https://developers.events/#/2025/calendar)
	- [Meetup](https://www.meetup.com/)

## Resource Collections

- "awesome" repositories are list of resources pertaining to a specific topic. When learning about a new topic sometimes it is useful to find an "awesome" repository on the subject. Example: using your favorite search engine search "awesome cloud security github", "awesome mobile security", etc
	- [Awesome AppSec](https://github.com/paragonie/awesome-appsec)
- [Ultime DevSecOps library](https://github.com/sottlmarek/DevSecOps)

## Books

Some cybersecurity related books that are not necessarily AppSec related, but have stood out to me.

- The Code Book by Simon Singh
- The Cuckoo's Egg by Clifford Stoll
- Becoming an Ethical Hacker by Gary Rivlin
