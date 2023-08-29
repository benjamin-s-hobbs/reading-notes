# Automated AppSec with ZAP
From: [Getting Started with Zed Attack Proxy](https://www.zaproxy.org/getting-started/) (accessed by Benjamin Hobbs on 8/25/2023)

Security testing is often sorted like this:
* Vulnerability Assessment - An existing system is scanned and analyzed for security issues. 
* Penetration Testing - The system undergoes strucutred analysis and attack from simulated threat actors 
* Runtime Testing - The system undergoes analysis and security testing from a knowledgeable end-user 
* Code Review - The system code undergoes a detailed review and analysis that specifically searches for security vulnerabilities.

## Penetration Testing
* Structured engagement in which the testers simulate being threat actors and test a network for vulnerabilities by attacking it (under an agreed to set of rules and conduct, and without malicious intent)

* Penetration Testing (or pentesting for short) has fewer false positives, yet can be time-consuming and capital-intensive to conduct.

### The Pentesting Process

Usually, both manual and automated pentesting follow a basic pattern of stages to conduct tests; testing anything from servers, to networks, to devices, to endpoints...The process generally looks like:

1. Recon - Tester learn about the system to be tested. 
2. Attack - Tester attempts to exploit any vulnerabilities that they have discovered to prove their existence. 
3. Report - Tester compiles a report of the test, outlining all vulnerabilities discovered, attacked, whether successful or not, rating the impact of exploitation

## ZAP (Zed Attack Proxy)
* is an open-source pentesting tool 
* considered a man-in-the-middle (MITM) proxy

* ZAP Spiders - 
  * Traditional ZAP spider: discovers links by examining the HTML in responses from the web app.

  * ZAP's AJAX spider: explores the web app by invoking browers and then follows the generated links.  





## Questions for further understanding
1. What are the three common stages of the Penetration Testing process and what tasks are performed at each one?
  1. Stage I - Recon. Find out what operating systems and versions are used. find out software running. search for vulns.
  2. Stage II - Attack. Use what you've learned to get in and stay in. Exploit the vulns you've found.
  3. Stage III - Report. Attack complete. Write up a report of the test. What vulns were found. how were they exploited (how COULD they be exploited). What is the impact from them being leveraged (score the exploits). Recommend remediation. 
2. Explain a “man-in-the-middle proxy” in non-technical terms.
* A go-between. An intermediary of sorts. 
3. What are the 2 spiders available for use in ZAP?
* Traditional ZAP spider
* ZAP AJAX spider 
4. What situations are they best suited for?
* Trad spider- for HTML 
* AJAX spder - on AJAX applications (JavaScript)

## Additional Resources
Bookmark and Review
[Python Tools for Cyber](https://hackersonlineclub.com/python-tools/)