# Reconstructing a Cloud Attack with Splunk
From: [What is a reverse proxy?](https://www.cloudflare.com/learning/cdn/glossary/reverse-proxy/) (accessed by Benjamin Hobbs on 7/21/2023)






## Questions for understanding

1. What are the benefits of a forward proxy?

* A forward proxy has a few use cases

  * Forward proxies can effectively block access to certain content.
  * Forward proxies can be employed to obscure a user's identity online. 
  

2. Explain the differences between a forward and a reverse proxy?

* The differences between a forward and a reverse proxy are more easily explain from the relative viewpoint of a client accessing information.

  * clients (e.g. personal computers, etc) send a request for information up to a forward proxy, which then forwards that request out to the internet and on to the web server to request the information. The forward proxy is connected to the Internet, not the personal computer.
  * clients (e.g. personal computers, etc.) connect directly to the internet to send their request for information which then goes to the reverse proxy. The reverse proxy passes the request to the web servers.

With a forward proxy, clients requesting the information are protected. When using a reverse proxy, the focus is on protecting the web servers that are fielding the requests. Traveling in the direction of (initiated) data flow...a forward proxy is encountered closest to the sender/requester, and BEFORE the Internet and web servers. Using the same model, a reverse proxy is encountered furtherest from the sender/requester, and AFTER the Internet prior to reaching the web servers.  

3. Explain to your manager why your organization might benefit from implementing a reverse proxy?

* I would outline two major reasons to implement a reverse proxy for our organization. 
  * Increased performance - depending on how much traffic my organization deals with, load balancing would be a viable mechanism to improve perfomance with the efficient handling of that traffic. A reverse proxy would assist in this effort.

  * Increased Security - Effectively reducing the attack surface presented to attackers, making the reverse proxy easier to support and defend.
  



## Bookmark and Review
* [A Conversation About REST API](https://gist.github.com/brookr/5977550)

* [Operationalize Ransomware Detections Quickly and Easily with Splunk](https://www.splunk.com/en_us/blog/industries/operationalize-ransomware-detections-quickly-and-easily-with-splunk.html)