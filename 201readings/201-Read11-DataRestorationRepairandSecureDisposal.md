# Data Restoration, Startup Repair, and Secure Disposal
## SSD Data Recovery Best Practices

From N-able "SSD Data Recovery Best Practices" https://www.n-able.com/blog/ssd-data-recovery-best-practices Updated August 6, 2019 (accessed May 7, 2023)

## How Do I know if my SSD is failing?

Solid-State Drives (or SSDs) are similar to Hard-Disk Drives (HDDs) in that they are both long-term storage media for computers and electronic devices. SSDs succeed their HDD cousins in the ever-advancing march of technology. Whereas HDDs contained a spinning disk and some other moving parts, SSDs were, as their name implies - more solid (no moving parts). This makes them more durable and a great deal faster than HDDs are. However, all drives eventually fail, and SSDs are no different. Because they had moving parts inside, when HDDs were close to failure or were malfunctioning they would usually make audible sounds; noises that would indicate there was a problem. SSDs can operate in silence until one day, they just don't operate.

There ARE some warning signals that SSDs exhibit to the trained eye that educated users can learn to identify. Here are common indicator to look out for to anticipate your SSD reaching the end of its read/write cycle limit or is experiencing other issues:

- Bad Blocks (storage segments that, through memory corruption or physical damage, impede data storage and retrieval functions)

    * Saving/Reading/Moving files may result in failure

    * Active Applications may operate slowly or frequently crash

    * The user may receive prompts to repair the file system 

    * General performance may steadily decrease, especially when handling large files.

- File System Repair (Computer or file system requires repair but physical defect software shows no damage)

- Crashing (Computer crashes while booting up, but works normally after several reboots)

- Read-only mode (SSD only performs read-only functions - not common; but possible)

## What Do I do Now? How do you fix a failed SSD?

- Perform Root Cause Analysis

    * If cause is a physical problem (hardware damage, degraded flash cells, etc)

       -  SSD may need to be replaced

    * If cause is a logical (technical) problem (bad blocks, software glitches, malware, outdated firmware, etc.)

       -  Some techniques may save the SSD

- Some Recovery Options are:

    * Formatting the drive and redownloading the operating system.

    * Power cycling the SSD
      
      - Unplug the SATA data cable but leave the power cable in

      - Leave the power on for half an hour (30 min), then turn it off for 30 seconds. 

      - Turn the power back on again for another half hour (30 min), then turn it off for 30 seconds.

      - Turn the power back on and reconnect the data cable. If it worked, the SSD will be back up at this point.

    * Idling in the boot menu (similar to power cycling, except when the power is on for the half hour intervals, idle the computer in the boot menu. Keep it in the BIOS screen)

      - Unplug the SATA data cable but leave the power cable in

      - Leave the power on for half an hour while staying in the BIOS boot screen on the computer (30 min), then turn it off for 30 seconds. 

      - Turn the power back on again for another half hour while staying in the BIOS boot screen on the computer (30 min), then turn it off for 30 seconds.

      - Turn the power back on and reconnect the data cable. If it worked, the SSD will be back up at this point.

    * Updating the firmware
      
    * Updating the drivers

## Is it possible to recover data from a failed SSD?

While difficult, yes. Many SSDs use TRIM, an Advanced Technology Attachment (ATA) command that help it to know which blocks it can clear. Because of the way TRIM works, SSDs that enable TRIM may lose their data forever if they fail...even if they could be revived. 

## SSD Best Practices
  
* Download a program from a selection of existing free software options designed to monitor SSD health by tracking operation temp and performance metrics. 

* When investing in SSDs, buy strategically


* Have a backup strategy. Backup data regularly and routinely, even if your SSD is new. Because you never know.

# How to Erase a Hard Drive Using DBAN

From T. Fisher "How to Erase a Hard Drive Using DBAN" https://www.lifewire.com/how-to-erase-a-hard-drive-using-dban-2619148 Updated May 25, 2022 (accessed May 7, 2023)

Darik's Boot And Nuke is an entirely free data destruction program used to completely erase all the files on a hard drive.
**_EVERYTHING_** - every installed application, all personal files, and even the operating system. For that reason, DBAN has to run when the OS is not in use so it needs to be burned to a CD/DVD/USB and run from there.

DBAN just uses your keyboard (no mice).

1. Download the DBAN program. Get the .ISO file downloaded and burned to a bootable device (CD/DVD/USB).


2. Save the DBAN ISO file to your computer. Remember where you downloaded it to. Size should be less than 20MB


3. Burn DBAN to a disc or USB device. The ISO file cannot just be copied over and expected to work correctly. Source info to do that here: 

    * [How to Burn an ISO Image File to a DVD](https://www.lifewire.com/how-to-burn-an-iso-image-file-to-a-dvd-2626156)

    * [How to Burn an ISO Image File to a USB Drive](https://www.lifewire.com/how-to-burn-an-iso-file-to-a-usb-drive-2619270)


4. Restart and boot into the DBAN disc or USB device

    * Do you see the below screen?

    * ![Screenshot 2023-05-07 181847](https://user-images.githubusercontent.com/128242183/236714002-122dbd61-460e-49f3-a70d-5fc6700ed87c.png)

    * If not, and your operating system begins to start up, troubleshoot your steps. 


5. Choose an option from the DBAN main menu



6. Immediately start using DBAN with a Quick Command

* DBAN can use one of several ways to erase files. The pattern used to erase files, as well as the number of times to repeat the pattern, are the differences in the methods.

    - DBAN Commands and Data Sanitization Methods

       * **dod** - DoD 5220.22-M

       * **dodshort** - same as **dod** except only 3 passes are run instead of 7

       * **ops2** - RCMP TSSIT OPS-II

       * **gutmann **- Gutmann

       * **prng** - Random Data

       * **quick** - Write Zero

       * **autonuke** - same as **dodshort**

7. Choose which drives to wipe with Interactive Mode.

8. Wait for DBAN to erase the hard drive(s)

9. Verify DBAN has successfully erased the hard drive(s)
 
      * ![Screenshot 2023-05-07 183827](https://user-images.githubusercontent.com/128242183/236715566-6ab509e7-7a1b-455a-9fee-51c91867d58c.png)
     

## What do I want to know more about 