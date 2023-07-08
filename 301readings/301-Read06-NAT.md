# Network Address Translation (NAT)
From GeeksForGeeks.org's  [Network Address Translation (NAT)](https://www.geeksforgeeks.org/network-address-translation-nat/) by saurabhsharma56. Last updated Dec 13, 2021 (accessed 6/5/2023 by Benjamin Hobbs)

* Network Address Translation or NAT is a process in which one or local IP addresses (which are private and can not access the Internet) is translated into one or more Global IP address (which is not private and CAN access the Internet) and vice versa in order to provide access to the local hosts.

* It also translates port numbers (masks the port number of the host with another port number). NAT then enters all of this info into the NAT table. NAT generally operates on a router or firewall.  

### Masking Port Numbers

### NAT inside and outside addresses

* Inside local addresses

* Inside global addresses

* Outside local addresses

* Outside global addresses

### Types of NAT (3 Types)

* Static NAT

* Dynamic NAT

* Port Address Translation (PAT)

## Advantages of NAT

- NAT conserves legally registered IP addresses

- NAT provides privacy as the devices's IP address, when sending and receiving traffic, will be hidden.

- Eliminates address renumbering when a network evolves.

## Disadvantages of NAT

* Translation results in switching path delays. 
 
* Some applications won't function while NAT is enabled. 
 
* NAT Complicates tunneling protocols such as IPsec. 
 
* Routers are Layer 3 (Network Layer) devices, they should not obscure port numbers on Layer 4(Transport Layer) but do so because of NAT.

