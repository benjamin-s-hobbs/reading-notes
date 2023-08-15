# Persistence
From: [PowerShell Empire No Longer Maintained](https://www.bleepingcomputer.com/news/security/powershell-empire-framework-is-no-longer-maintained/)
(accessed by Benjamin Hobbs on 8/14/2023)



While no longer maintained by its original creator as of writing, PowerShell Empire has been forked many times and was 
used by nation state actors from 2015-2019. The PowerShell Empire project is now actively maintained by BC Security. 
As you read this article, take note of its original purpose as well as the tactical advantages offered to its users.

## Questions for Understanding
1. What is one of the major advantages of PowerShell Empire?
   *  It used encrypted commands to communicate with the C2 server, making it difficult to detect.
2. What are some of the APT groups that have been known to use PS Empire and into which step of the Cyber Kill Chain
   does the use of PS Empire fall?
   * Groups Known to use PS Empire:
     * APT  Hades
     * FIN7
     * FIN10
     * APT 19 (Codoso)
     * APT 33 (HOLMIUM)
     * APT 41 (Wicked Panda)
   * Cyber Kill Chain step correlation:
     * according to MITRE ATT&CK the answer is multiple stages. Discovery, Collection, Persistence, Privilege Escalation, etc.
     * For the Cyber Kill Chain, I'd have to say that C2 (Command and Control) is likely the primary. However, it was likely versatile
       enough to also be Actions on Objective, and Installation as well.
3. What are the four main components needed to pull off an attack using PS Empire?
   * Listener
   * Stager
   * Agent
   * Module

## Bookmark and Review (Additional Resources)
Hacking with Empire – PowerShell Post-Exploitation Agent
