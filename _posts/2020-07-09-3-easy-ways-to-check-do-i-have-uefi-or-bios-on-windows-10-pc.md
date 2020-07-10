---
ID: 2403
post_title: >
  3 Easy Ways to Check Do I Have UEFI or
  BIOS on Windows 10 PC!!
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/2403-3-easy-ways-to-check-do-i-have-uefi-or-bios-on-windows-10-pc/
published: true
post_date: 2020-07-09 22:30:28
---
<ul class="toc">
 	<li><a href="#1">Check if your PC using UEFI or BIOS through System Information</a></li>
 	<li><a href="#2">Check if your PC using UEFI or BIOS via setupact.log file</a></li>
 	<li><a href="#3">Disk Management to check if your PC using UEFI or BIOS</a></li>
 	<li><a href="#4">A Short Synopsis</a></li>
</ul>
<span class="dcap">C</span><strong>heck if your Device is UEFI or BIOS:</strong> Most of the Windows users might be aware of the term UEFI (Unified Extensible Firmware Interface) that is a type of BIOS replacement to load and start an OS and set up the hardware. UEFI was introduced by Intel and referred to as Intel Boot Initiative and later it was changed to EFI. Then, EFI was taken over by the Unified EFI forum so it named as UEFI. It offers better networking support and faster start-ups.

Further, it comes with a boot manager so there is no need for an individual boot loader. While most of the systems come with UEFI support, still there are many older computers using BIOS. Those who are wondering to know if your Windows 10 system is using UEFI or BIOS then you are at the right place. This tutorial explains how to check<strong> Do I Have UEFI or BIOS </strong>on Windows 10 PC in three diverse ways.
<h2 id="1">1) Check if your PC using UEFI or BIOS - Using System Information:</h2>
It is an easy method to make sure your system is using UEFI or BIOS as you just need to <a href="https://windowscrazy.com/2343-3-quick-ways-how-to-view-system-information-on-windows-7/"><strong>view the system information</strong></a>.
<ol>
 	<li>To open the Run dialog box, you have to press <strong>Windows key</strong> +<strong>R. </strong></li>
 	<li>Then, you have to type '<strong>msinfo32</strong>' in the Run window and press the <strong>OK</strong> button.

[caption id="attachment_2347" align="alignnone" width="480"]<img class="size-full wp-image-2347" src="https://windowscrazy.com/wp-content/uploads/2020/07/msinfo32.png" alt="msinfo32" width="480" height="299" /> msinfo32[/caption]</li>
 	<li>It will open the <strong>System Information</strong> window.</li>
 	<li>On the right-hand side, locate the BIOS Mode. If it shows <strong>UEFI</strong>, then it indicates your system is using <strong>UEFI</strong>. If it says <strong>BIOS or Legacy</strong>, then your device is using <strong>BIOS</strong>.

[caption id="attachment_2414" align="alignnone" width="1285"]<img class="size-full wp-image-2414" src="https://windowscrazy.com/wp-content/uploads/2020/07/System-Information-1.png" alt="System Information" width="1285" height="770" /> System Information[/caption]</li>
</ol>
<h2 id="2">2) Check if your PC using UEFI or BIOS via setupact.log file:</h2>
<ol>
 	<li>You have to open the <strong>File Explorer</strong>.</li>
 	<li>In the address bar, you have to type the below path and hit <strong>Enter</strong>. <code>%SystemRoot%\Panther</code></li>
 	<li>Locate the setupact.log file and open it using <strong>Notepad</strong>.

[caption id="attachment_2413" align="alignnone" width="1416"]<img class="size-full wp-image-2413" src="https://windowscrazy.com/wp-content/uploads/2020/07/setupact.png" alt="setupact" width="1416" height="835" /> setupact[/caption]</li>
 	<li>Press <strong>Ctrl + F</strong> to open <strong>Find</strong> and look for a <strong>Detected boot environment</strong>.

[caption id="attachment_2410" align="alignnone" width="1401"]<img class="size-full wp-image-2410" src="https://windowscrazy.com/wp-content/uploads/2020/07/Detected-boot-environment.png" alt="Detected boot environment" width="1401" height="652" /> Detected boot environment[/caption]</li>
 	<li>If it says <code>Callback_BootEnvironmentDetect: Detected boot environment: UEFI</code>, then your device is using UEFI.</li>
 	<li>If it says <code>Callback_BootEnvironmentDetect: Detected boot environment: BIOS</code>, then your device is using BIOS.</li>
</ol>
<h2 id="3">3) Disk Management to check if your PC using UEFI or BIOS:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu and type '<strong>disk management</strong>' in the search box and press <strong>Enter</strong>.

[caption id="attachment_2411" align="alignnone" width="1110"]<img class="size-full wp-image-2411" src="https://windowscrazy.com/wp-content/uploads/2020/07/Disk-Management.png" alt="Disk Management" width="1110" height="857" /> Disk Management[/caption]</li>
 	<li>If it shows the <strong>EFI partition</strong>, then it is using <strong>UEFI</strong>.

[caption id="attachment_2412" align="alignnone" width="1037"]<img class="size-full wp-image-2412" src="https://windowscrazy.com/wp-content/uploads/2020/07/Disk-Partition.png" alt="Disk Partition" width="1037" height="660" /> Disk Partition[/caption]</li>
 	<li>If it says the<strong> System Reserved partition</strong>, then it indicates that your system is using <strong>BIOS</strong>.</li>
</ol>
<h2 id="4">A Short Synopsis:</h2>
In this tutorial, you have learned how to check<strong> Do I Have UEFI or BIOS </strong>on Windows 10 PC. You just follow any one of the ways to make sure if your system using UEFI or BIOS so that you can know the type of your PC. If you found this article useful, kindly share your <strong>valuable comments</strong> in the below section. We appreciate your presence in <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.