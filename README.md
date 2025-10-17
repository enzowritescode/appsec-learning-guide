# AppSec Learning Guide

A list of key resources for learning about Application Security (AppSec). Each section should not be treated as a comprehensive list, but rather a jumping off point for you to explore.

## OWASP Top 10s

The various vulnerabilities spanning the misc OWASP Top 10 lists that pertain to your role should be a fundamental pillar of your knowledge. Also if you are expanding into a new area, this is a good place to start.

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [OWASP Top 10 API](https://owasp.org/www-project-api-security/)
- [OWASP Top 10 Mobile](https://owasp.org/www-project-mobile-top-10/)
- [OWASP Top 10 CI/CD](https://owasp.org/www-project-top-10-ci-cd-security-risks/)
- [OWASP Top 10 LLM](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- etc. There are [other Top 10 lists](https://owasp.org/search/?searchString=top+10), and surely more will be produced.

## Offensive Security Labs

Learn offensive security in a safe/legal environment.

- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
	- PortSwigger, the creator behind the popular penetration testing tool Burp Suite, has over 250 free labs on their Web Security Academy. They often share bleeding edge research and their researchers often speak at conferences such as DEF CON.
- Open-source intentionally vulnerable projects
	- [Damn Vulnerable Web Application (DVWA)](https://github.com/digininja/DVWA)
	- [OWASP Juice Shop](https://github.com/juice-shop/juice-shop)
	- [Vulnerable Adversely Programmed Interface (vAPI)](https://github.com/roottusk/vapi)
	- [Damn Vulnerable API (DVAPI)](https://github.com/payatu/DVAPI)
	- etc. There are other intentionally vulnerable applications, some of which are no longer maintained but may still be relevant.
- [CloudFoxable](https://cloudfoxable.bishopfox.com/)
- HackTheBox, TryHackMe, etc

## Secure SDLC / DevSecOps

These resources are key for implementing automation and processes into your software development lifecycle (SDLC).

- [OWASP DevSecOps Guideline](https://owasp.org/www-project-devsecops-guideline/)
	- A great place to start when learning about DevSecOps. Start at the left, learn about a particular step, what its goals are, some common tools to accomplish it, and try them out yourself.
		- Ex. for Secret scanning, learn what it is, how software developers should manage secrets, and then pick a tool such as TruffleHog and scan some repositories.
- [OWASP SAMM](https://owaspsamm.org/model/)
- [OWASP DSOMM](https://dsomm.owasp.org/)
- [Video: Strategic use of OWASP SAMM and OWASP DSOMM](https://www.youtube.com/watch?v=MIzENOyylZI)

##  Secure Coding and Developer Training

- [OWASP Developer Guide](https://devguide.owasp.org/)
- [OWASP Top 10 Proactive Controls](https://top10proactive.owasp.org/)
- [OWASP Cheat Sheet series](https://cheatsheetseries.owasp.org/)

## Conferences and Meetups

Reputable conferences and meetups. It's worth noting that conference talks are often recorded and can frequently be found on YouTube.

- Local [OWASP Chapter](https://owasp.org/chapters/) meetups
- BSides conferences
- [OWASP conferences](https://owasp.org/events/) (LASCON, OWASP Global AppSec, etc)
- [DEF CON](https://defcon.org/)
- [fwd:cloudsec](https://fwdcloudsec.org/)
- Find other conferences and meetups:
	- [HackerTracker](https://hackertracker.app/)
	- [InfoSecMap](https://infosecmap.com/)
	- [Developers Conference Agenda](https://developers.events/#/2025/calendar)
	- [Meetup](https://www.meetup.com/)

## Certifications

- [Practical DevSecOps](https://www.practical-devsecops.com/)
	- DevSecOps and AppSec related certifications
- [CloudBreach](https://cloudbreach.io/)
	* Offensive security certifications for cloud
- [Burp Suite Certified Practitioner](https://portswigger.net/web-security/certification)
- [APISec University](https://www.apisecuniversity.com/certifications)
- [TCM Security](https://certifications.tcm-sec.com/)
	- A variety of offensive security certifications including some related to mobile and web
- Cloud vendor-specific (ex. AWS Certified Security Speciality)
- Other offensive security (GIAC, OffSec, etc)

## Podcasts

- The Boring AppSec Podcast
- Absolute AppSec
- 404 Security Not Found
- Application Paranoia
- Where Warlocks Stay Up Late
- Cloud Security Podcast
- Darknet Diaries

## Content Creators / Influencers

COMING SOON

## Resource Collections

- [awesome](https://github.com/topics/awesome) repositories are curated lists of resources pertaining to a specific topic. When learning about a new topic sometimes it is useful to find an awesome repository on the subject. Example: search "awesome cloud security" or "awesome mobile security" on GitHub
	- [Awesome AppSec](https://github.com/paragonie/awesome-appsec)
- [Ultime DevSecOps library](https://github.com/sottlmarek/DevSecOps)

## Books

- Alice and Bob Learn Application Security
- Misc cybersecurity books that I have enjoyed:
	- The Code Book by Simon Singh
	- The Cuckoo's Egg by Clifford Stoll
	- Becoming an Ethical Hacker by Gary Rivlin
