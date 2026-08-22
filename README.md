# AppSec Learning Guide

A list of key ways/resources for learning about Application Security (AppSec).

## How To Use This Guide

This guide highlights all the different ways that one can learn about AppSec. Each section should not be treated as a comprehensive list, but rather a jumping off point for you to explore. Resources that are particularly useful are indicated with `***` and/or annotated with additional information.

There is no single way to get into AppSec, and you will find that AppSec practitioners come from varying backgrounds (software development, offensive security, etc). For that reason it's up to you to use this guide in a way that suits your unique needs.

An example learning path:
- Learn more about an AppSec Engineer on SecurityTitles.com
- Complete the apprentice level labs on PortSwigger Web Security Academy
- Understand the common defensive security controls that software developers should implement via OWASP Top 10 Proactive Controls
- Learn about how to incorporate security gates into a CI/CD pipeline with the OWASP DevSecOps Guideline
- Learn more about how security is incorporated into the SDLC with OWASP SAMM

## What is an AppSec Engineer?

An AppSec Engineer's focus is the security of software applications. The role can span many areas such as web, API, mobile, cloud, CI/CD, and more. For a better idea of what the required skills and responsibilities are, check out [SecurityTitles.com](https://securitytitles.com/specialized#appsec-engineer).

##  Secure Coding and Developer Training

Learn more about defensive programming as well as useful resources to share with your developers.

- [OWASP Developer Guide](https://devguide.owasp.org/) ***
	* This is a great place to start learning and includes several of the other resources in this guide
- [OWASP Top 10 Proactive Controls](https://top10proactive.owasp.org/) ***
- [OWASP Cheat Sheet series](https://cheatsheetseries.owasp.org/)

## Secure SDLC / DevSecOps

Key resources for implementing automation and processes into your software development life-cycle (SDLC).

- [OWASP DevSecOps Guideline](https://owasp.org/www-project-devsecops-guideline/) ***
	- A great place to start when learning about DevSecOps. Start at the left, learn about a particular step, what its goals are, some common tools to accomplish it, and try them out yourself.
		- Ex. for Secret scanning, learn what it is, how software developers should manage secrets, and then pick a tool such as TruffleHog and scan some repositories.
- [OWASP SAMM](https://owaspsamm.org/model/) ***
- [OWASP DSOMM](https://dsomm.owasp.org/)
- [Video: Strategic use of OWASP SAMM and OWASP DSOMM](https://www.youtube.com/watch?v=MIzENOyylZI)

## OWASP Top 10s

The various vulnerabilities spanning the misc OWASP Top 10 lists that pertain to your role should be a fundamental pillar of your knowledge. Also if you are expanding into a new area, this is a good place to start.

- [OWASP Top 10](https://owasp.org/www-project-top-ten/) ***
- [OWASP Top 10 API](https://owasp.org/www-project-api-security/)
- [OWASP Top 10 Mobile](https://owasp.org/www-project-mobile-top-10/)
- [OWASP Top 10 CI/CD](https://owasp.org/www-project-top-10-ci-cd-security-risks/)
- [OWASP Top 10 LLM](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [OWASP Top 10 Agentic Applications](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/)
- [OWASP Top 10 Agentic Skills](https://owasp.org/www-project-agentic-skills-top-10/)
- etc. There are [other Top 10 lists](https://owasp.org/search/?searchString=top+10), and surely more will be produced.

## Offensive Security Labs

Learn offensive security in a safe/legal environment.

- [PortSwigger Web Security Academy](https://portswigger.net/web-security) ***
	- PortSwigger, the creator behind the popular penetration testing tool Burp Suite, has over 250 free labs on their Web Security Academy. They often share bleeding edge research and their researchers often speak at conferences such as DEF CON.
	- This is probably the best place to start for learning about web and API vulnerabilities.
- Open-source intentionally vulnerable projects
	- [Damn Vulnerable Web Application (DVWA)](https://github.com/digininja/DVWA)
	- [OWASP Juice Shop](https://github.com/juice-shop/juice-shop)
	- [Vulnerable Adversely Programmed Interface (vAPI)](https://github.com/roottusk/vapi)
	- [Damn Vulnerable API (DVAPI)](https://github.com/payatu/DVAPI)
	- etc. There are other intentionally vulnerable applications, some of which are no longer maintained but may still be relevant.
- [CloudFoxable](https://cloudfoxable.bishopfox.com/)
- [HackTheBox](https://www.hackthebox.com/)
- [TryHackMe](https://tryhackme.com/)

## Certifications

- [Practical DevSecOps](https://www.practical-devsecops.com/)
	- DevSecOps and AppSec related certifications
- [CloudBreach](https://cloudbreach.io/)
	* Offensive security certifications for cloud
- [Burp Suite Certified Practitioner](https://portswigger.net/web-security/certification)
- [APISec University](https://www.apisecuniversity.com/certifications)
- [TCM Security](https://certifications.tcm-sec.com/)
	- A variety of offensive security certifications including some related to mobile and web
- Cloud vendor-specific (ex. [AWS Certified Security Specialty](https://aws.amazon.com/certification/certified-security-specialty/))
- Other offensive security (GIAC, OffSec, etc)

## Conferences and Meetups

Reputable conferences and meetups. It's worth noting that conference talks are often recorded and can frequently be found on YouTube.

- Local [OWASP Chapter](https://owasp.org/chapters/) meetups
- [BSides conferences](https://bsides.org/events/)
- [OWASP conferences](https://owasp.org/events/) (LASCON, OWASP Global AppSec, etc)
- [DEF CON](https://defcon.org/)
- [fwd:cloudsec](https://fwdcloudsec.org/)
- Find other conferences and meetups:
	- [HackerTracker](https://hackertracker.app/)
	- [InfoSecMap](https://infosecmap.com/)
	- [Developers Conference Agenda](https://developers.events/#/2025/calendar)
	- [Meetup](https://www.meetup.com/)

## Online Communities

There are many regional and global online communities (Slack, Discord, etc) for various frameworks, programming languages, cybersecurity focuses, etc. These can be good places to network, talk shop, learn new ideas, find job postings, and so on.

* [OWASP](https://owasp.org/slack/invite)
* [Cloud Security Forum](https://fwdcloudsec.org/forum/)
* OWASP chapters
* BSides communities
* etc

## Blogs

- [GitHub Security Lab](https://github.blog/tag/github-security-lab/)
- [Uber Security](https://www.uber.com/us/en/blog/engineering/security/)
- [OverSecured](https://oversecured.com/blog)
- [Opensource Malware](https://opensourcemalware.com/blog)
- [Calif](https://blog.calif.io/)

## Podcasts

- [The Boring AppSec Podcast](https://www.boringappsec.com/s/podcast)
- [Absolute AppSec](https://absoluteappsec.com/)
- [404 Security Not Found](https://podcast.app/404-security-not-found-p6017551)
- [Application Paranoia](https://appscan.buzzsprout.com/)
- [Where Warlocks Stay Up Late](https://wherewarlocksstayuplate.com/episodes/)
- [Cloud Security Podcast](https://www.cloudsecuritypodcast.tv/)
- [Darknet Diaries](https://darknetdiaries.com/episode/)

## Content Creators

There are a variety of great content creators on platforms such as YouTube, X (Twitter), and LinkedIn. Depending on the topic you may have to search around. Just try not to get caught up in the clickbait.

- [John Hammond](https://www.youtube.com/@_JohnHammond)
- [Sandra Liu](https://www.youtube.com/@WithSandra)
- [Grant Collins](https://www.youtube.com/@collinsinfosec)

## Resource Collections

- [awesome](https://github.com/topics/awesome) repositories are curated lists of resources pertaining to a specific topic. When learning about a new topic sometimes it is useful to find an awesome repository on the subject. Example: search "awesome cloud security" or "awesome mobile security" on GitHub
	- [Awesome AppSec](https://github.com/paragonie/awesome-appsec)
- [Ultimate DevSecOps library](https://github.com/sottlmarek/DevSecOps)

## Books

- Alice and Bob Learn Application Security
- Misc cybersecurity books that I have enjoyed:
	- The Code Book by Simon Singh
	- The Cuckoo's Egg by Clifford Stoll
	- Becoming an Ethical Hacker by Gary Rivlin

## Sample Interview Questions

Sample interview questions can be found here (more to follow):

- [Entry level](interview_questions/entry_level.md)
