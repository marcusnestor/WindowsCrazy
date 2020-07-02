---
ID: 2258
post_title: 'How to Create a Backup of Drivers in Windows 10? [Simple Guide]'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/2258-how-to-create-a-backup-of-drivers-in-windows-10-simple-guide/
published: true
post_date: 2020-07-02 04:14:20
---
<ul class="toc">
 	<li><a href="#1">Backup Device Drivers via Command Prompt</a></li>
 	<li><a href="#2">Backup Drivers - Using PowerShell</a></li>
 	<li><a href="#3">Restore Device Drivers</a></li>
 	<li><a href="#4">A Short Synopsis</a></li>
</ul>
<span class="dcap">B</span><strong>ackup Drivers Windows 10</strong>: Device Drivers are software that lets you utilize anything on the computer with the OS. There are drivers for mouse, keyboard, graphics card, and everything else. If any device stops working, you have to remove and reinstall that device's driver.

While it sounds easy, but Windows 10 won't be able to install specific drivers and your device manufacturer will stop providing the driver. In such cases, you don't have to concern about it as there is a command to back up every driver on your PC. This tutorial explains how to <strong>Create a Backup of Drivers in Windows 10</strong>. Further, you will learn the instructions to restore the device drivers.
<h2 id="1">Backup Device Drivers via Command Prompt:</h2>
<ol>
 	<li>First, you have to open the <strong>File Explorer </strong>from the <strong>Taskbar</strong>.</li>
 	<li>Now, go to the location where you want to store the backup of drivers. Then, you have to create a new folder using this shortcut<strong> Ctrl + Shift + N</strong>.</li>
 	<li>After that, click the <strong>Windows key</strong> and type '<strong>cmd</strong>' in the search box.</li>
 	<li>Right-click on the top of the result and choose <strong>Run as administrator</strong> to open the Command Prompt with admin privileges.

[caption id="attachment_2262" align="alignnone" width="1279"]<img class="size-full wp-image-2262" src="https://windowscrazy.com/wp-content/uploads/2020/07/Command-Prompt.png" alt="Command Prompt" width="1279" height="874" /> Command Prompt[/caption]</li>
 	<li>You have to copy and paste the below command and hit <strong>Enter</strong>.<code>DISM /online /export-driver /destination:C:\DriverBackup</code></li>
 	<li>In the above command, you have to change 'C: \DriverBackup' with your folder path where you want to store the backup.

[caption id="attachment_2265" align="alignnone" width="991"]<img class="size-full wp-image-2265" src="https://windowscrazy.com/wp-content/uploads/2020/07/DISM-Command.png" alt="DISM Command" width="991" height="587" /> DISM Command[/caption]</li>
 	<li>Once you are done with the above steps, DISM will make a copy of all the device drivers stored in <code>C:\Windows\System32\DriverStore</code></li>
 	<li>You have to make sure that this method will only take a backup of those .inf drivers. If there are other drivers installed using a .exe or .msi package, it will not be backed up.</li>
</ol>
<h2 id="2">Backup Drivers - Using PowerShell:</h2>
<ol>
 	<li>You have to open the <strong>File Explorer </strong>from the <strong>Taskbar</strong>.</li>
 	<li>Now, go to the location where you want to store the backup of drivers. Then, you have to create a new folder using this shortcut<strong> Ctrl + Shift + N</strong>.</li>
 	<li>After that, click the <strong>Windows key</strong> and type '<strong>powershell</strong>' in the search box.</li>
 	<li>Right-click on the top of the result and choose <strong>Run as administrator</strong> to open the PowerShell with admin privileges.

[caption id="attachment_2266" align="alignnone" width="1320"]<img class="size-full wp-image-2266" src="https://windowscrazy.com/wp-content/uploads/2020/07/PowerShell.png" alt="PowerShell" width="1320" height="881" /> PowerShell[/caption]</li>
 	<li>You have to copy and paste the below command and hit <strong>Enter</strong>.<code>Export-WindowsDriver -Online -Destination “D:\Drivers Backup”</code></li>
 	<li>In the above command, you have to change "D: \DriverBackup" with your folder path where you want to store the backup.

[caption id="attachment_2263" align="alignnone" width="1062"]<img class="size-full wp-image-2263" src="https://windowscrazy.com/wp-content/uploads/2020/07/Command.png" alt="Command" width="1062" height="642" /> Command[/caption]</li>
 	<li>You have to wait for some time until the process gets completed and then go to the folder to check the backup of all the drivers.</li>
</ol>
<h2 id="3">Restore Device Drivers:</h2>
<ul>
 	<li>You can restore the backup drivers on the new installation of Windows 10 with the use of this command <code>DISM /online /Add-Driver /Driver:C:\DriverBackup /Recurse</code>. But, it will show the error when you try to run this command.</li>
 	<li>It is always good to install the driver manually, you need to install a few drivers as the OS will detect most of them automatically.</li>
</ul>
Follow the below steps to restore drivers manually using the Device Manager.
<ol>
 	<li>Use this shortcut <strong>Win key + X</strong> to open the <strong>Device Manager</strong>.

[caption id="attachment_2264" align="alignnone" width="945"]<img class="size-full wp-image-2264" src="https://windowscrazy.com/wp-content/uploads/2020/07/Device-Manager.png" alt="Device Manager" width="945" height="918" /> Device Manager[/caption]</li>
 	<li>Now, you have to double-click on the category that includes the device you want to install the driver.</li>
 	<li>Right-click on that device and choose <strong>Update driver</strong> option.</li>
 	<li>You will be displayed with two options. You have to click the second option '<strong>Browse my computer for driver software</strong>'.</li>
 	<li>In the next screen, you have to click the <strong>Browse</strong> button and locate the folder that contains backup drivers. Click the <strong>Next</strong> button.</li>
 	<li>At last, you have to click the <strong>Finish</strong> button.</li>
</ol>
<h2 id="4">A Short Synopsis:</h2>
In this tutorial, you have learned how to <strong>Create a Backup of Drivers in Windows 10</strong>. In addition, we have illustrated the steps to restore the device drivers easily. If you found this article useful, kindly share your <strong>valuable comments</strong> in the below section. We appreciate your presence in <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.
<h2>Read Ahead:</h2>
<ul>
 	<li><a href="https://windowscrazy.com/892-simple-steps-how-to-enable-loudness-equalization-in-windows-10/">[Simple Steps] How to Enable Loudness Equalization in Windows 10?</a></li>
 	<li><a href="https://windowscrazy.com/869-turn-on-or-off-google-chrome-notifications-in-windows-10-easily/">Turn On or Off Google Chrome Notifications in Windows 10!! {Easily}</a></li>
 	<li><a href="https://windowscrazy.com/1322-reset-the-outlook-app-when-it-is-not-working-on-android/">Reset the Outlook app when it is not working on Android!!</a></li>
 	<li><a href="https://windowscrazy.com/979-how-to-allow-java-through-firewall-windows-10/">How to allow Java through Firewall Windows 10?</a></li>
</ul>