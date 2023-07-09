# Windows Command Tools
## UpGuard- Attack Surface Management

From A. Tyas Tunggal "_What is an SMB Port + Ports 445 and 139 Explained_" https://www.upguard.com/blog/smb-port Updated Aug 22, 2022 (accessed Apr 28, 2023)

SMB stands for Server Message Block Protocol. This is a protocol that is primarily used for sharing access to files, printers, serial ports, data on a network. Computers interact with each other through this protocol.

**How it Works**

SMB works via response-request protocol. 

**History**

SMB was designed in 1983 by Barry Feigenbaum who worked at IBM. His intention was to convert the DOS INT 21h local into a networked file system. He created SMB to run on top of NetBIOS over TCP/IP (NBT) using port 139 and on UDP using ports 137 and 138. In 1990, Microsoft merged the SMB protocol with their LAN Manager product and continued to add features to it in Windows for Workgroups.

SMB faced an initiative to rebrand to "Common Internet File System" (CIFS) by Microsoft in 1996, and more features were added (support for hard links, symbolic links, larger file sizes, and the initial attempt to support direct connections over TCP port 445 without needing NetBIOS as a transport (which was very experimental at the time that needed more work. By the time Microsoft Windows 2000 debuted, the company had changed SMB to operate over port 445, where it is to this day.

Microsoft's SMB/CIFS imperfect protocol could negatively affect network performance by latency and acknowledgements by up to 10%.  SMB 2.0 improved on this by shedding hundreds of commands and subcommands down to just 19. SMB continues to improve, as SMB 3.0 was introduced in Windows 8 and Windows Server 2012, introducing security enhancements as well (like end-to-end encryption and an AES-based signing algorithm).

**What are the SMB Protocol Dialects?**

SMB was created in 1983 and has inspired a few dialects, or versions, that have been designed to meet changing network requirements. Here are a few important dialects below:
* **SMB 1.0 (1984)** 
* **Samba (1992)**
* **Common Internet File System (CIFS) (1996)**
* **NQ (1998)**
* **Netsmb (2004)**
* **SMB (2006)**
* **Tuxera SMB (2009)**
* **Likewise (2009)**
* **SMB 2.1 (2010)**
* **SMB 3.0 (2012)**
* **MoSMB (2012)**
* **SMB 3.02 (2014)**
* **SMB 3.11 (2015)**

## What Are Ports 139 and 445?

SMB requires an open port to communicate with other systems. These ports are generally 139 and 445. Port 139 is used by SMB dialects that communicate over NetBIOS (printers and serial ports). Port 445 is used by SMB dialects that communicate on top of a TCP stack (newer dialects-after Windows 2000).

## Are Open Ports Dangerous?
The short answer is no--not in, and of, themselves. However, like doors in a house, if left open there could be a risk. That risk varies depending on whether your back door is open (and yard fenced in), or your front door is open. The article tells us that the most dangerous ports are wormable ports-like the one that the SMB protocol uses (which can be open by default on some operating systems OSs). Malware like WannaCry (Ransomware) takes advantage of this to deliver its payloads. Here are some ways to secure ports 139 and 445:

* Avoid exposing SMB Ports

* Patch Everything

* No Single Point Of Failure

* Use a Firewall or Endpoint Protection

* Use a Virtual Private Network (VPN)

* Implement Virtual Local Area Networks (VLANs)

* Use MAC Address Filtering

***
# A+ Certification Cheat Sheet

* chkdsk.exe - Check Disk: Check your hard drive for problems with the file system and for bad sectors.

* msinfo.exe - System Information: View hardware and configuration information for your computer.

* taskkill.exe - Task Kill: Terminate a running application or service on a computer.

* eventvwr.msc - Event Viewer: Logging component of the operating system; the central location for all logging activity.

### ipconfig 

- Display basic TCP/IP configuration, such as IP address subnet mask, and default gateway.

     * ipconfig /all: Display TCP/IP settings

     * ipconfig /release: Release your IP address.

     * ipconfig /renew: Renew your IP address.

     * ping<IP address> or ping<host name>: Send four test message to the IP address of host name you specify; verify whether the other system is up and running.

### netstat 
 
- Display TCP/IP protocol statistics and connection information. Used to see who is connected to your system; 
what ports are open; and if you use an -o switch, what the process ID is of the program that opened the port.

### nbtstat 
 
- Troubleshoot NetBIOS over TCP/IP. View a remote NetBIOS name table using nbstat.

### nslookup 

- Troubleshoot DNS problems. Get a listing of all the records in DNS using nslookup.

### arp 
    
- Troubleshoot ARP. Use arp -a to view Address Resolution Protocol (ARP) cache.

### Tasklist 

- View a list of running processes

### Taskkill /PID <pid> /F 

- Terminates a process when you supply the process ID.


# Professor Messer: Microsoft Command Tools - CompTIA A+ 220-1002 - 1.4

## Things I want to know more about  

If SMB was designed by IBM how did it get owned by Microsoft?

Is there any difference between dialect and version?

Is the last Linux-based SMB MoSMB (2012) 