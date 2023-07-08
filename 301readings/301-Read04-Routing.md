# Routing

## VirtualBox Network Settings

From [VirtualBox Network Settings: Complete Guide](https://www.nakivo.com/blog/virtualbox-network-setting-guide/) Updated July 16, 2019 (accessed June 2, 2023)

* Which network mode in VirtualBox can be used to emulate unplugging the Ethernet cable from the network? 
    
        Settings >> Network >> Adapter Tab >> Advanced (dropdown) >> Uncheck "Cable Connected"

        * or you can choose the "Not Attached" Network Mode.

* Which network mode would be best if you wanted to run a server on a VM that could be fully accessible from your physical local area network?

  * The "Bridged Adapter" Network Setting would be best for this

* What are the three options of promiscuous mode and what does each do?

  * Deny - (Default) Any traffic not intended to the virtual network adapter is hidden from the VM.

  * Allow VMs - All traffic is hidden from the network adapter except the traffic transmitted to and from other VMs.

  * Allow All - There are no restrictions in this mode. A VM network adapter can see all incoming and out going traffic.

* What is Port Forwarding?

  * Port forwarding is a process of intercepting traffic addressed to the appropriate IP address and port in addition to redirecting that traffic to a different IP address and/or port.

## Things I want to know more about 