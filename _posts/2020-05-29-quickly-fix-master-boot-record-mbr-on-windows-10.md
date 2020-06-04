---
ID: 748
post_title: '{Quickly} Fix Master Boot Record (MBR) on Windows 10!!'
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/748-quickly-fix-master-boot-record-mbr-on-windows-10/
published: true
post_date: 2020-05-29 08:54:22
---
<ul class="toc">
 	<li><a href="#1">How to fix MBR on Windows 10?</a></li>
 	<li><a href="#2">Verdict</a></li>
</ul>
<strong><strong><strong><span class="dcap">F</span><strong>ix Master Boot Record (MBR) on Windows 10</strong>:</strong></strong></strong> It enables your PC to find and identify the location of the operating system to allow Windows 10 to boot. MBR is also referred to as the <strong>master partition table or partition sector.</strong>

In this tutorial, we will describe the piece of information to<strong> fix Master Boot Record (MBR) on Windows 10</strong> using simple steps.
<h2 id="1">How to fix MBR on Windows 10?</h2>
Here, the below steps are used to<strong> fix MBR on Windows 10</strong>. Simply, follow the steps.
<ul>
 	<li>Firstly, you have to <a href="https://windowscrazy.com/317-can-windows-xp-be-upgraded-to-windows-10/"><strong>create a USB bootable media to install Windows 10.</strong></a></li>
 	<li>Then change your device<strong> BIOS settings</strong> to start from the bootable media.</li>
</ul>
<strong>Note:</strong> In this process, it usually requires to press one of the function keys F1, F2, F3, F10, or F12, ESC, or Delete key.
<ul>
 	<li>After that, start your PC with the bootable media and click the <strong>Next</strong> button in the Windows 10 Setup.</li>
 	<li>On the bottom left side, you have to press the <strong>Repair your computer </strong>tab.</li>
</ul>
[caption id="attachment_780" align="aligncenter" width="759"]<img class="wp-image-780 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_5-7.png" alt="Repair your computer" width="759" height="555" /> Repair your computer[/caption]
<ul>
 	<li>Then click <strong>Troubleshoot </strong>and in that select the <strong>Advanced options.</strong></li>
 	<li>In the Advanced options select the <strong>Command Prompt.</strong></li>
</ul>
[caption id="attachment_782" align="aligncenter" width="1099"]<img class="wp-image-782 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_6-6.png" alt="Advanced settings" width="1099" height="518" /> Advanced settings[/caption]
<ul>
 	<li>Type <strong>Bootrec.exe</strong> in the command prompt to launch this tool to repair the Master Boot Record on your Windows 10 PC.</li>
 	<li>Bootrec.exe tool supports a number of options depending on your situation.</li>
 	<li>To repair Master Boot Record corruption problems or need to clean the code from the MBR, you have to use the <strong>FixMbr</strong> option because this command will not overwrite the existing partition table in the hard drive.</li>
 	<li>Simply<strong>, copy and paste</strong> the below command in the command prompt.</li>
</ul>
<pre><code>Bootrec /fixMbr</code></pre>
<ul>
 	<li>When you installed an early version of the operating system alongside another more recent version or when the boot sector was replaced with another non-standard code, the boot sector is damaged you have to use the  <strong>FixBoot</strong> option.</li>
 	<li><strong>Type</strong> the following command.</li>
</ul>
<pre><code>Bootrec /fixBoot</code></pre>
<ul>
 	<li>When the Boot Manager menu doesn’t list all the operating systems installed on your device, then you have to use the option of  <strong>ScanOS. </strong>Copy and paste the below command.</li>
</ul>
<pre><code>Bootrec /ScanOS</code></pre>
<ul>
 	<li>The <strong>RebuildBcd</strong> option is used when you don’t have another option and you must rebuild the BCD (Boot Configuration Data) store.</li>
 	<li><strong>Copy and paste</strong> the below-mentioned command in your command prompt window.</li>
</ul>
<pre><code>Bootrec /RebuildBcd</code></pre>
[caption id="attachment_749" align="aligncenter" width="1242"]<img class="wp-image-749 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_1-8.png" alt="Commands" width="1242" height="642" /> Commands[/caption]
<ul>
 	<li>If you are trying to troubleshoot a <strong>Bootmgr Is Missing</strong> error and rebuilding the BCD store doesn’t fix the problem.</li>
 	<li>Then, you can use the following commands to export and erase the BCD store and using the <strong>RebuildBcd</strong> command again to try getting Windows 10 to boot.</li>
 	<li><strong>Copy and paste</strong> the following commands in the command prompt and press <strong>Enter.</strong></li>
</ul>
<pre><code>BCDedit /export C:\BCD_Backup
C:
CD boot
Attrib BCD -s -h -r
Ren C:\boot\bcd bcd.old
Bootrec /RebuildBcd</code></pre>
<ul>
 	<li>To confirm adding Windows 10 to the list of the bootable operating systems on your computer <strong>press Y.</strong></li>
</ul>
[caption id="attachment_750" align="aligncenter" width="1235"]<img class="wp-image-750 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_2-8.png" alt="Commands" width="1235" height="645" /> Commands[/caption]
<ul>
 	<li>Finally, close the<strong> command prompt</strong> window.</li>
 	<li>After completion of the above steps, you have to <strong>reboot your computer.</strong></li>
 	<li>Then, you should now be able to load <strong>Windows 10</strong> again.</li>
</ul>
<h2 id="2">Verdict:</h2>
In the above article, we have illustrated the easy steps <strong>to fix MBR on Windows 10. </strong>If you found this article helpful? Don’t forget to share your comments in the below section.