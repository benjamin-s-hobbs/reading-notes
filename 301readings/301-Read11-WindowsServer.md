# Windows Server
From Josh H. "What's the Difference Between Windows and Windows Server?" https://www.howtogeek.com/404763/whats-the-difference-between-windows-and-windows-server/ Updated Feb 21, 2019 (accessed Jun 12, 2023 by Benjamin Hobbs)

Windows Server is a product of Microsoft that is designed to manage many computers, files, and services. 

## Windows 10 and Windows Server Share Similar Code

Both systems use the same kernel. Due to the Graphical User Interface (GUI), They also look a bit similar. Microsoft actually recommends that Windows Server be installed and run from the command line (because it reduces the overhead to run the server). For the Nano install, there is not a GUI and it takes up a lot less space.

## Windows Server Includes Server Software

Services like DHCP, Active Directory, Group Project Object Management, etc. These Server features aren't natively available on Windows 10, but can be obtained via third-party software (like Apache web server). Windows Server also supports higher end hardware, and has a stronger security posture.

## Questions for Understanding

-What is a server, and how is it different from a regular computer? How would you describe this difference to a friend who doesn’t know much about computers?

  * A server differs from desktop or "regular" computers in that they are not designed to be "personalized". Configured, yes. However, you are not able to sign in with a Microsoft account and import your settings from another PC. You also won't find many user friendly services like Cortana, Microsoft Edge (Server still uses Internet Explorer), or Timeline on Server. Additionally, security is increased- so normal web browing is hindered a bit.


-How does the way Windows Server receives updates differ from Windows Home and Pro?

  * Windows Server receives updates easier than Windows 10. Windows 10 can download from the Internet easier (it's security is less robust)

-Does Windows Server have different hardware requirements than Windows Home or Pro?

  * The hardware requirements for Server are far higher as one of its main purposes is to manage other computers/workstations. max RAM for Server is 24TB compared to 2TB for Windows 10 and processor core limits are vastly different. Windows 10 can support 256 cores maximum and Windows Server doesn't have a limit for the amount of cores it can support.

## What do I want to know more about?