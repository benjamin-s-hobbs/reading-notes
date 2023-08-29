# XSS with w3af, DVWA
From: [Cross-site scripting](https://portswigger.net/web-security/cross-site-scripting) (accessed by Benjamin Hobbs on 8/25/2023)

## What is Cross-site Scripting (XSS)?

Cross-ste scripting is a web security vulnerability that allows an attacker to compromise the interactions that users have with a vulnerable application. It allows an attacker to go around the same origin policy, which is designed to keep different websites apart from each other. XSS vulns normally allow an attacker to masquerade as the victim user, carry out any actions that the user can perform and then gain full control of the application's functionality and data.


## How does XSS work?

## Types of XSS attacks:
* Reflected XSS - malicious script comes from the current http request
   * 

* Stored XSSW (aka "persistent XSS" or "second-order XSS")- where the malicious script comes from the website's database.

* DOM-based XSS (DOM XSS)- where the vuln exists in client-side code rather than server-side code.
 
## What can XSS be used for?
Someone who uses a XSS attack is generally trying to:

* Impersonate/masquerade as the victim user
* Carry out an action on the victim's behalf
* Read any data that the victim could normally access.
* Capture the user's login creds
* Perform virtual vandalism (defacement of web site)
* Inject trojan functionality into the web site.

1. Explain how a cross-site scripting attack works in non-technical terms.
   * So if you leave your wallet, phone, and work badge out and I find them...then I might be able to (if I was skilled) pretend I was you and go around and do things that could be attributed to you

2. What are the three types of XSS attacks?
   * Reflected, Stored, and DOM-based

3. If an attacker successfully exploits a XSS vulnerability, what malicious actions would they be able to perform?
   * any action that the victim user would be able to perform.

4. What are some security controls that can be implemented to prevent XSS attacks? 
   * encryption, Use appropriate response headers, Adjust Content Security Policy 

## Addiotnal Resources
Bookmark and Review
[Security Report for In-Production Web Applications](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.rapid7.com/globalassets/_pdfs/whitepaperguide/rapid7-tcell-application-security-report.pdf)