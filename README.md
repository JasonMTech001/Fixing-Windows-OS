<h1>Fixing Windows OS</h1>

<h2>Description</h2>
This project demonstrates the complete process of recovering a Windows system using the System Restore utility, from identifying unresolvable startup issues to restoring the system to a previously saved restore point. It highlights practical troubleshooting skills such as navigating recovery environments, selecting appropriate restore points, and validating successful recovery without data loss. The task reinforces essential IT technician competencies in system recovery, diagnostic workflow, and Windows troubleshooting procedures.
<br />


<h2>Lab walk-through:</h2>

<p align="center">
<b>1. Identified Boot Failure Issue:</b>
Detected that Windows failed to start properly and displayed the “Automatic Repair couldn’t repair your PC” screen, prompting further troubleshooting.
 <br/>
<img src="https://i.imgur.com/v7zeaGY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>2. Accessed Recovery Environment:</b>
Navigated to the Windows Recovery Environment and selected the “Troubleshoot” option to begin system repair steps.
<br/>
<img src="https://i.imgur.com/FICsshY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>3. Opened Advanced Options:</b>
Chose “Advanced options” to access deeper system recovery tools such as Startup Repair, Command Prompt, and System Restore. <br/>
<img src="https://i.imgur.com/xQMUYjg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>4. Executed System File Checker (SFC):</b>
Launched Command Prompt and ran sfc /scannow to scan and attempt to repair corrupted system files.
  <br/>
<img src="https://i.imgur.com/F5ewpRv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>5. Launched System Restore Tool:</b>
Selected “System Restore” to roll back the system to a previous stable state without affecting personal files.  <br/>
<img src="https://i.imgur.com/DUboYDy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>6. Selected Restore Point:</b>
Chose the manual restore point labeled “Manual RP – HelpDesk” to revert the system to a known working configuration.
  <br/>
<img src="https://i.imgur.com/wcfVXYM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>7. Confirmed Restore Operation:</b>
Approved the final confirmation to start the system restore process, understanding that the operation cannot be interrupted.
  <br/>
<img src="https://i.imgur.com/Q8ofsSt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>8. Restoring Files in Progress:</b>
System Restore began processing the rollback and restoring system files to the chosen restore point.
 <br/>
<img src="https://i.imgur.com/IiRgwzC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>9. Restore Completed Successfully:</b>
System displayed a success message confirming the system was restored and that no user documents were affected.
<br/>
<img src="https://i.imgur.com/9SaHegt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>10. System Restart and Logon:</b>
Rebooted the machine and reached the Windows logon screen, ready for user authentication.
 <br/>
<img src="https://i.imgur.com/1vt4e9o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>11. Lab Completion Validation:</b>
Final steps included confirming the task was completed successfully and submitting it for scoring within the lab environment.
 <br/>
<img src="https://i.imgur.com/qlwtviJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
