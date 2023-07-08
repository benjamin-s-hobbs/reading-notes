# Traffic Mirroring
From Boris R. "How to capture network traffic? SPAN vs TAP" https://accedian.com/blog/capture-network-traffic-span-vs-tap/ Updated June 10, 2016 (accessed by Benjamin Hobbs on 6/8/2023)

## Port Mirroring (SPAN) & Terminal Access Point (TAP)

### Port Mirroring 
* Port mirroring - aka SPAN or roving analysis is a method of monitoring network traffic which forwards a copy of each incoming and/or outgoing packet from one or more ports (or VLANs) of a switch to another port where the analysis device is connected. Port mirroring can be managed locally or remotely.

Administrators can configure port mirroring to include all packets or just transmitted (or just recieved).

* Pros of Port Mirroring

    * Inexpensive
    * Flexible (how much traffic can be captured at once)
    * Remotely configurable
    * The only way to capture intra-switch traffic

* Cons of Port Mirroring

    * Consumes significant CPU resources
    * risk of not recieveing some packets (such as media errors)
    * likely to drop some traffic
    * may be better solutions to capture traffic (such as a passive TAP or Ethernet repeater)

### Terminal Access Points (TAPs)

* TAPs - are hardware devices that can passively capture traffic on a network.  If the network connection consists of a physical cable...a TAP is likely the best way to capture traffic.

* Pros of TAPs

    * No dropped packets
    * Monitoring of all packets (including media errors)
    * Provides full visibility, including congestion situations

* Cons of TAPs

    * Expensive
    * No visibility on intra-switch traffic
    * May require two listening interfaces

## Questions for Understanding from the reading

1. What are the differences between SPAN and TAP?
2. What types of network devices can support network traffic mirroring? 
 * Switches
3. How can network traffic mirroring be used for network security?
4. Are there any legal or ethical considerations when using network traffic mirroring?

## What do I want to know more about?
