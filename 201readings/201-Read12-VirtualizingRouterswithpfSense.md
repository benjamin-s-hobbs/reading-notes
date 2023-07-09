# Virtualizing a Router with pfSense
From S. Kear "Introduction to pfSense: An Open-Source Firewall and Router Platform" https://turbofuture.com/computers/Introduction-to-pfSense-An-Open-Source-Firewall-and-Router-Platform Updated Feb 11, 2023 (accessed May 8, 2023) 

* Relevance: Understanding how to configure and manage network security assets such as firewalls, routers, switches, intrusion detection/prevention systems (IDS/IPS) greatly enhances the ability to defeat bad actors from accessing your system. Allowing you to leverage specific controls like allowlists/denylists, port forwarding, and segmentation. Knowledge of these tools may also help you to recognize them when they are being deployed.

## What is pfSense?

* pf is a free, customized distribution of FreeBSD that can turn an old computer into a full-featured router and firewall. pfSense was created by BSD Perimeter (check out this book>>> ["pfSense: The Definitive Guide" by Chris Buechler](https://www.thriftbooks.com/w/pfsense-the-definitive-guide_michael-w-lucas_christopher-m-buechler/791277/item/5863876/?utm_source=google&utm_medium=cpc&utm_campaign=pmax_low_vol_f%2fm%2fs_under_%2410&utm_adgroup=&utm_term=&utm_content=&gclid=Cj0KCQjwu-KiBhCsARIsAPztUF0PqpG8cE9vGD9Mc5DhFAurw9zUEQJnkKxoWWjojINlmLlz83xrP9MaAi3zEALw_wcB#idiq=5863876&edition=7203065) 

* Some popular uses of pfSense are:

  * LAN/WAN router

  * Internet cafes

  * Wireless hotspot (captive portal)

  * VPN router

  * Firewall

  * DHCP/DNS server

  * Wireless Access Point

  * Transparent squid proxy server

  * Multi wan router or load balancer

  * DNS denylist

  * Port forwarding/NAT (network address translation)

## Embedded Installation

pfSense can be installed on embedded platforms - like PC-engines, Soekris, Alix and others (I don't know what these are)

  * Embedded installs are a good option in you are looking to create a small, quiet , low-power appliance to run your network. If you're a consultant-you may want to consider this. If you go this route... be sure to download the embedded version of pfSense. This release is designed to be installed on hardware that uses compact flash for storage and has special tweaks that will greatly extend the life of the storage media.


## What do I want to know more about?
Embedded Installation?
pfSense has its own operating system?! FreeBSD? 

pfSense has its own operating system?! FreeBSD? 
