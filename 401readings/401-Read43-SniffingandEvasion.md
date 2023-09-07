# Sniffing and Evasion
From: [What is a Sniffing Attack in System Hacking?](https://www.geeksforgeeks.org/what-is-sniffing-attack-in-system-hacking/)

* Sniffing Attack in system hacking is a type of DoS (Denial Of Service Attack)  which is carried out by sniffing or capturing packets on the network and then either sending them repeatedly to a victim machine or replaying them back to the sender with modifications. Sniffers are often used in system hacking as a tool for analyzing traffic patterns when more intrusive or damaging attacks are not desirable. sniffers are also used in MITM (Man-in-the-Middle) Attacks

* Sniffing attacks can also be used in attempts to recover a passphrase, like when an SSH private key has been compromised. The sniffer captures the SSH packets with the encrypted versions of the password which can then be cracked offline using brute force methods.

   * What's "Sniffing" - defined in RFC 2301 as "Any act of capturing network traffic and replaying it, usually for the purpose of espionage or sabotage."

   ### Other 'sniffing' attacks

   * ARP Spoofing 

   * Smurf Attack

   * 



## Questions for Understanding
1. Explain a Sniffing attack using non-technical terms.
   * Sniifing attack like 80's landline phone conversations. Remember back in the day when you'd be on the phone in your house and then someone else on your side would pick up and maybe listen in...They were conducting a sniffing attack on you - listening in on your conversation.
2. What are the two types of sniffing attacks and what are some pros and cons of each approach?
   * Sniffing- basically eavesdropping on a legit session. It is less intrusive, which may take longer to detect.
   * ARP Spoofing - copies a MAC address so that traffic is sent to the attacking computer that is intended for the targeted computer.
3. How does encryption protect traffic against sniffing attacks?
   * Really by delaying it. The traffic can be captured- but its still confidential (perhaps just not available) until the encryption can be defeated.  