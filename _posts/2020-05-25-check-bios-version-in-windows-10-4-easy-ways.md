---
ID: 415
post_title: 'Check (*BIOS Version*) in Windows 10!! {4 Easy Ways}'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/415-check-bios-version-in-windows-10-4-easy-ways/
published: true
post_date: 2020-05-25 12:48:53
---
<ul class="toc">
 	<li><a href="#1">Check BIOS Version by opening System Information</a></li>
 	<li><a href="#2">Check BIOS Version via Command Prompt</a></li>
 	<li><a href="#3">Check BIOS Version - Using Registry Editor</a></li>
 	<li><a href="#4">Check BIOS Version - Use DXdiag</a></li>
 	<li><a href="#5">A Short Synopsis</a></li>
</ul>
<span class="dcap">C</span><strong>heck BIOS Version in Windows 10</strong>: <strong>BIOS</strong> stands for <strong>Basic Input Output System </strong>is a vital component that makes it feasible for <strong>software and hardware communication</strong>. As part of some hardware troubleshooting processes (that includes a new CPU or RAM not working properly), updating BIOS to the latest version is a good thing to try.

Your motherboard software - BIOS occasionally gets updated to fix bugs or add new features. In such a case, you have to know the <strong>BIOS Version</strong>. There are several ways to see your BIOS version from within Windows Desktop. We come up with four quick and easy ways that let you <strong>Check BIOS Version in Windows 10</strong> in a few seconds.
<h2 id="1">Way 1 - Check BIOS Version by opening System Information:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type <strong>'system information' </strong>and press Enter.

[caption id="attachment_427" align="alignnone" width="883"]<img class="size-full wp-image-427" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi7.png" alt="System Information" width="883" height="680" /> System Information[/caption]</li>
 	<li>The <strong>System Information</strong> window will be opened. Now, you can locate the <strong>BIOS Version</strong>.

[caption id="attachment_428" align="alignnone" width="924"]<img class="size-full wp-image-428" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi8.png" alt="BIOS Version" width="924" height="574" /> BIOS Version[/caption]</li>
</ol>
<h2 id="2">Way 2 - Check BIOS Version via Command Prompt:</h2>
<ul>
 	<li>Click on the <strong>Start</strong> button. Search for <strong>'cmd'</strong> and click on the result to open the <strong>Command Prompt</strong>.

[caption id="attachment_425" align="alignnone" width="885"]<img class="size-full wp-image-425" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi5.png" alt="Command Prompt" width="885" height="679" /> Command Prompt[/caption]</li>
 	<li>Now, you have to copy and paste the below command and hit <strong>Enter</strong>.</li>
</ul>
<code>wmic bios get smbiosbiosversion</code>
<ul>
 	<li>You will be displayed with the <strong>BIOS version</strong>.

[caption id="attachment_426" align="alignnone" width="747"]<img class="size-full wp-image-426" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi6.png" alt="BIOS Version" width="747" height="447" /> BIOS Version[/caption]</li>
</ul>
<h2 id="3">Way 3 - Check BIOS Version - Using Registry Editor:</h2>
<ul>
 	<li>To open the <strong>Run box</strong>, you have to press <strong>Windows key + R</strong>.</li>
 	<li>Next, you have to type <strong>'regedit' </strong>and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press Yes)</li>
</ul>
<code>regedit</code>

[caption id="attachment_418" align="alignnone" width="428"]<img class="size-full wp-image-418" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi1.png" alt="Regedit" width="428" height="232" /> Regedit[/caption]
<ul>
 	<li>It will open the <strong>Registry Editor</strong>. In the left pane, you have to navigate to <strong>HKEY_LOCAL_MACHINE\HARDWARE\DESCRIPTION\System\BIOS.</strong></li>
 	<li>In the right pane, you can locate the <strong>BIOSVersion</strong>.

[caption id="attachment_419" align="alignnone" width="962"]<img class="size-full wp-image-419" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi2.png" alt="BIOS Version" width="962" height="551" /> BIOS Version[/caption]</li>
</ul>
<h2 id="4">Way 4 - Check BIOS Version - Use DXdiag:</h2>
<ul>
 	<li>You just have to open the <strong>Run command</strong> by using this shortcut <strong>Windows key + R</strong>.</li>
 	<li>Then, you have to type <strong>'dxdiag' </strong>in the <strong>'open'</strong> field and tap the <strong>OK</strong> button.</li>
</ul>
<code>dxdiag</code>

[caption id="attachment_422" align="alignnone" width="432"]<img class="size-full wp-image-422" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi3.png" alt="Dxdiag" width="432" height="234" /> Dxdiag[/caption]
<ul>
 	<li>Now, the <strong>DirectX Diagnostic Tool</strong> will get opened. You can see the<strong> BIOS version</strong> in the <strong>System</strong> tab.

[caption id="attachment_423" align="alignnone" width="777"]<img class="size-full wp-image-423" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi4.png" alt="BIOS Version" width="777" height="577" /> BIOS Version[/caption]</li>
</ul>
<h2 id="5">A Short Synopsis:</h2>
As you can see, the four ways explained in this tutorial to <strong>Check BIOS Version in Windows 10</strong> are quite simple. You can follow any one of the ways and get to know about your BIOS version if you want to update it. Kindly share your <strong>comments/feedback</strong> in the below section. Thanks for visiting <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.