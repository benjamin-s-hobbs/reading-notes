# Network Segmentation and CIDR Notation

definition by Ben:

* Network Segmentation refers to the logical (read: digital) blocking off of sections of a network from each other to further divide it. The reasons for this can include for organization, independence/autonomy, security, privacy, etc. In information security, network segmentation offers another layer of protection from attackers. 

From David L. [""What Is Network Segmentation and Why It Matters?"](https://www.comptia.org/blog/security-awareness-training-network-segmentation) Updated Oct 23, 2020 (accessed June 1, 2023)


Network segmentation isn’t important as long as the network is using a well configured firewall. Do you agree? 

* I don't agree with this statement for a couple of reasons:

  * Defense-In-Depth: Even with a well-configured firewall, any action to enchance and support the defense should be welcomed especially if they work in tandem. To use sports analogies, it is very rare that offensive lines are solely relied on to stop running backs, that goalkeepers are solely relied on to stop forwards, that pitchers are solely relied on to stop runs from being scored, that centers are solely relied on to defend the basket, etc.

  * Network segmentation can also minimize mishaps, errors, and/or insider threats by limiting the impact to operations throughout an organization. Since this occurs inside an org, the robustness of the firewall would not really assist much without hindering day-to-day processes, but segmentation could.


What is a screened subnet? [From Wikipedia](https://en.wikipedia.org/wiki/Screened_subnet#:~:text=A%20true%20DMZ%20is%20a,located%20behind%20a%20screening%20router.)

* A protected area of a network usually maintained separately from the external network (The Internet) via a router, and even another (internal) router - creating a perimeter network, or demilitarized zone (DMZ). 

* All DMZs are screened subnets, not all screened subnets are considered DMZs.


## What is CIDR notation?

From Michael N. ["CIDR Block Notation Explained in 2 Minutes"](https://medium.com/@ethicalentrepreneur/cidr-block-notation-explained-in-2-minutes-1010ec0dbc15) Updated Aug 15, 2018 (accessed June 1, 2023)

Classless Inter-Domain Routing (CIDR) is a method for allocating IP addresses and organizing IP routing. According to Wikipedia, it was created to slow the growth of routing tables and the rapid exhaustion of IPv4 addresses.

* What is a CIDR block?

  * A CIDR block refers to how many hosts are available on the network and is identified by a "/". The number after this slash has ((2^(32-n))-2) hosts available [the minus 2 is because the first IP address in the block is considered the network ID, and the last address is the broadcast ID.]

         192.168.142.0/24 has 32-24=8... 2^8 = 256
         256 - 2 = 254
         192.168.142.0/24 has 254 available hosts (192.168.142.0 is the Network ID and 192.168.142.255 is the Broadcast ID for this network.)

Setting binary aside and using the decimal system, what is the range of numbers found in an octet? 

* The range of numbers found in an octect is from 0-255 (there are 256 numbers [aka 2^8..."eight" or octect] and because we begin counting from "0" instead of "1", we only get to 255.)

  * How many octets are found in an IPv4 address? 

    * If you have seen a subnet mask express 255.255.255.0, then you'll get that 3 of the 4 octects are full - with only the last available to be changed. There are 4 octects in an IPv4 address. 

  * An IPv6 address?

    * 16