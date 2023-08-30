# Attacking Juice Shop with Burp Suite
From: [What is Burp Suite?](https://www.technipages.com/what-is-burp-suite/)

## What IS BurpSuite and why does it matter?

* BurpSuite is a suite of tools from PortSwigger designed for pentesting web apps over HTTP and HTTPS. 
The primary tool is a proxy that allows analysis and editing of web traffic in sort of a MITM (man-in-the-middle) format
across a variety of Operating Systems (Windows, MacOS, Linux)

* Many of BurpSuite's tools are designed to integrate with the main proxy and can have requests imported to them.

   * Intruder - is a tool that allows you to import a request then configure payloads.
   * Repeater - is a tool that import a request and then modify it and see the effect.
   * Sequencer - is a tool that analyzes the randomness of data.
   * Decoder - is a tool that offers a range of encoding standards to decode and recode data.
   * Comparer - is a tool that compares two strings for minor differences.



## Questions for further understanding
1. Explain how Burp Suite allows us to analyze web application traffic.
 * BurpSuite's toolset allows a professional to analyze, adjust, verify, effects and modifications made to web traffic. This would greatly reduce the time needed to deploy a successful attack on a system. 
 

2. What does the Repeater tool allow us to do with requests?
 * Repeater allows you to import a web request and then tweak it to make modifications and see if those mods are having the desired effect.

3. Why might this be a useful tool for an attacker?
 * This tool would allow an attacker to confidently know that their exploit is behaving as they designed it PRIOR to firing it off, trial-and-error-style.