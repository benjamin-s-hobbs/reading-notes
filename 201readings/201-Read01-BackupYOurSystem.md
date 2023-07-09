# Backup Your System - Using System Restore
Notes on:  **T. Fisher "_How to Use System Restore in Windows: System Restore will 'undo' major changes in Windows._" https://www.lifewire.com/how-to-use-# system-restore-in-windows-2626131 Updated June 11, 2022 (accessed Apr 23, 2023)**


System Restore - What is it? 
 1. System Restore is a tool that allows reversion to a previous "restore point"
      A. software, registry, and driver configuration is affected
          i. These encompass the majority of Windows issues
      B. Usually takes about 10 to 30 min to undo changes in most cases
          i. HOW you access this tool differs between Windows versions
               a. one way for Windows 8, 8.1, 10, and 11
               b. one way for Windows 7 or Windows Vista 
               c. one way for Windows XP
 2. Way #1: System Restore for Windows 8, 8.1, 10, and 11
     A. Open Control Panel
     B. Select "System and Security"
     C. Select "System"
     D. On the left hand vertical menu, choose "System protection"
     E. The System Properties window will appear. Make sure that the "System Protection" tab is selected and you should see a "System Restore" section with a "System Restore" button. Press the "System Restore" button.
     F. On the System Restore window, Select "Next >"
     G. Select the desired restore point listed
          i. Click Show More Restore Points to see older points.
         ii. There is no way to "restore" older restore points. The oldest one available is the furthest back you may possibly restore Windows to without restoring from an existing backup.
     H. After choosing a restore point, select "Next >" to proceed.
     I. Select "Finish" to confirm.
     J. Choose "Yes" to Pop-up dialog box "Once started, System Restore cannot be interrupted. Do you want to continue?"
          i. ***Be Advised: If running this procedure from Windows in Safe Mode, the changes will not be reversible.***
         ii. *Be Advised: Your computer will restart as part of this process.*
     K. System Restore will begin. 
          i. This may take around 15 min, and messages will continue to display information
         ii. Do not turn off or restart the machine.
        iii. Wait for the computer to restart.
     L. Sign into Windows as normal. Go to the Desktop if you aren't automatically redirected there.
     M. A System Restore should appear to indicate that the Restore has been completed successfully. Select "Close"
     N. Continue Troubleshooting
          i. If System Restore did not correct the problem - consider choosing an older restore point.
         ii. If System Restore caused an additional problem - repeat steps A-E and select "Undo System Restore".
 3. Way #2 System Restore for Windows 7 and Vista
     A. Open "Start > All Programs > Accessories > System Tools."
     B. Select "System Restore."
     C. Select "Next >" when the "Restore system files and settings" window appears
     D. Select the desired restore point listed
          i. Click Show More Restore Points to see older points.
     E. Select "Next >."
     F. On the System Restore window, Select "Next >"
     G. Select "Finish" to confirm.
     H. Choose "Yes" to Pop-up dialog box "Once started, System Restore cannot be interrupted. Do you want to continue?"
          i. *Be Advised: Your computer will restart as part of this process.*
     I. A message should appear to indicate that the Restore has been completed successfully. Select "Close"
     J. Continue Troubleshooting
          i. If System Restore did not correct the problem - consider choosing an older restore point.
         ii. If System Restore caused an additional problem - repeat steps A-D and select a different restore point.
 4. Way #3 System Restore for Windows XP
     A. Open "Start > All Programs > Accessories > System Tools."
     B. Select "System Restore."
     C. Select "Restore my computer to an earlier time."
     D. Select "Next >."
     E. Choose an available date on the calendar on the left.
     F. Select an available restore point from the list on the right.
     G. Select "Next >"
          i. *Be Advised: Your computer will restart as part of this process.*
     H. System Restore will begin. 
          i. Do not turn off or restart the machine.
         ii. Wait for the computer to restart.
     I. A "Restoration Complete" window should appear to indicate that the Restore has been completed successfully. Select "Close"
     J. Continue Troubleshooting
          i. If System Restore did not correct the problem - consider choosing an older restore point.
         ii. If System Restore caused an additional problem - repeat steps A-E and select a different restore point.
 5. More System Restore Info
     A. System Restore can be executed in any version of Windows from the Command Prompt by typing "rstjrui.exe"
     B. Restore Points do not need to be created manually.
 
## Things I Want To Know More About 
     