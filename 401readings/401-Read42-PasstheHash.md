# Pass the Hash with Mimikatz
From: [What is Mimikatz?](https://www.varonis.com/blog/what-is-mimikatz)

## What is Mimikatz?
* Created by Benjamin Delpy originally to show Microsoft that its authentication protocols were vulnerable to an attack...Mimikatz has become one of the most widely used and downloaded threat actor tools in the past two decades. Mimikatz is still available for download on Benjamin's GitHub

Mimkatz is an open-source application that allows users to view and save authentication credentials such as Kerberos tickets. It is often used to steal credentials and escalate privileges.

### Attacks Mimikatz can help execute
* Pass-the-hash
* Pass-the-ticket
* Overpass-the-hash
* Kerberoast golden tickets
* Kerberoast silver tickets
* Pass-the-cache

### Mimikatz Modules

* Crypto Module
* Kerberos Module
* Service Module
* Coffee (yay!)

## How does one defend against Mimikatz?
1. Change admin privileges - Use PoLP. Limit admin only to users who NEED it.
2. Change caching policy - Disable password-caching (Windows Settings> Local Policy> Security Options> Interactive Logon)
3. Turn off debugging privileges
4. Increase local security authority

## Questions for Understanding

1. Name the six credential-gathering techniques which Mimikatz is able to perform and explain how two of them work?
  * Pass-the-hash
  * Pass-the-ticket
  * Overpass-the-hash
  * Kerberoast golden tickets
  * Kerberoast silver tickets
  * Pass-the-cache
2. What are four ways we can defend against Mimikatz attacks. Explain how two of the mitigations can stop Mimikatz?
    * Change admin Privileges
    * Change caching policy (Mimikatz can gain access to the cached passwords...setting it to zero give it nothing to grab)
    * Turn off debugging privileges (Mimikatz takes advantage of Windows' default setting to allow local admins access to debug the system)
    * Increase Local Security Authority (LSA) protection - reduces surface attack area.