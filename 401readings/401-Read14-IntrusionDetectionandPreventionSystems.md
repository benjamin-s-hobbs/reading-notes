# Intrusion Detection and Prevention Systems (IDS/IPS)
From: [The Pros and Cons of Network Intrusion Detection Systems](https://www.rapid7.com/blog/post/2017/01/11/the-pros-cons-of-intrusion-detection-systems/)

* NIDS are a part of a cohesive network strategy of security.
  * Have strengths AND weaknesses.
  * Be sure to layer

## What is an Intrusion Detection System (IDS) 

* IDSs are like fire alarms. They detect when something may be wrong and they alert you. They don't address the problem themselves. The response is on you.

  - There are always trade-offs when employing a IDS (host-based or network-based)
    * 

## What is an Intrusion Prevention System (IPS)
* IPS are simliar to IDSs, except they are a bit more proactive. They are capable of stopping some threats. In order to do this, it must have very good instructions or it runs the risk of false positives (or false negatives)



## Questions for understanding

1. List 2 differences between firewalls and an IDS?
* Firewalls allow or deny traffic, and they won't have any alerts. An IDS/IPS will alert a user to the malicious traffic (blocked or not)
* Firewalls wouldn't necessarily detect key loggers or spyware...or data loss.

2. Under what circumstances would you choose a network-based IDS over a host-based IDS?
* If you have more than one computer that you're concerned about, you'd want a NIDS instead of a HIDS. Otherwise other devices may be attacked and you would not be alerted.
* also, NIDS detect attacks that HIDS will miss because it views packets in real-time, HIDS monitors event and audit logs...
* Likewise, if "the call is coming from inside the house" then the NIDS won't detect it. If someone accesses the endpoint and makes changes directly there, the NIDS won't catch that. 

3. Name 3 major drawbacks of a NIDS?
* An IDS (any IDS) drawback is that it won't take any action to stop the traffic that it detects. 
* Again if "the call is coming from inside the house" then the NIDS won't detect it. If someone accesses the endpoint and makes changes directly there, the NIDS won't catch that, you've cut it out of the loop.
* Even though you need an engineer to set it up...they still need a lot of tuning and false positives are frequent.


## Additional Resources
* Videos
  * [Network Intrusion Detection and Prevention - CompTIA Security+ SY0-501 - 2.1](https://www.youtube.com/watch?v=hEgWPWIuq_s)