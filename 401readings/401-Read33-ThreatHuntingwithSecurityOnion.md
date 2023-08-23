# Threat Hunting with Security Onion
From: [What Is Threat Hunting and Why Is It so Important? – Video Blog](https://www.activecountermeasures.com/what-is-threat-hunting-and-why-is-it-so-important-video-blog/)

## Threat Hunting Process Order
### 1. Identify connection persistency
  * Monitor traffic to and from the internet
    * PCAP or Zeek data
  * Analyze in large time blocks
    * More data = better fidelity
    * Minimum 12 hours; 24 is better.
  * Analyze communication pairs
    * Every outbound session passing the firewall 
    * Ignore internal to internal (high false positives)
### 2. Check for a business need for connection
  * Reputation Check of IP
### 3. Abnormal Protocol Behavior
### 4. Investigation of internal IP
### 5. Disposition
  * No threat - add to safelist
  * Threat = Compromise = Trigger Incident Response

## Safelisting
* Not all persistence is "evil"
* When a business need can be identified - "safelist" the connection 
  * exclude it from future hunts
  * Don't make safelists any broader than necessary

## Questions for further understanding
1. How are Threat Hunting and Pentesting different?
  * Pentesting is protection-based
  * Threat-hunting seeks to bridge the gap between protection-based measures and response-based measures.
2. What is the primary objective of Threat Hunting?
  * To proactively look for threats in the networks that may be there that HAVEN'T set off any alerts. 
  * To drastically reduce the dwell time that attackers are in your system
 (It's currently about six months)  
3. Your organization has a fully functioning SOC but not active Threat Hunting. How would you advocate for your security organization to start Threat Hunting activities?
  * We have a fully functioning SOC, yay! We probably spend a lot of money on this, right? Great. So which of you here can report with a solid degree of confidence on the likelihood that our network is pristine (no threats present), a few systems maaaaaay be compromised (and which ones), or we are overrun by tip-top pros that are just not setting off alerts? Any takers? Right. FYI, a threat hunter would be able to do that.
  * Look at it like this, We HAVE protection in place...and we HAVE response measures in place. When do we know when our protections have failed and it's time to respond? When the adversary trips up? ORRRRRRRRR? We can go find IoC inside our wire and know ourselves. Better, right?
    * Side effect of not finding anything is that you can be confident there is nothing there right now.

## What do I what to know more about?!

HOW DOES ONE GET INTO THIS?!!!!
  

## Additional Resources
[Active Countermeasures](https://www.activecountermeasures.com/)
The creator of the RITA tool, AC is an excellent resource for threat hunting tools and topics.

[SQRLL Archive](https://www.threathunting.net/sqrrl-archive)
“From about 2015 until they were purchased by Amazon Web Services (AWS) in early 2018, Sqrrl was a threat hunting platform vendor with an unusually strong focus on teaching the cybersecurity community about threat hunting best practices. They published some of what are still foundational documents about threat hunting.”