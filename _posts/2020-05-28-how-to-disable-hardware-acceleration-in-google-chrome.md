---
ID: 641
post_title: >
  How to Disable Hardware Acceleration in
  Google Chrome?
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/641-how-to-disable-hardware-acceleration-in-google-chrome/
published: true
post_date: 2020-05-28 11:56:03
---
<ul class="toc">
 	<li><a href="#1">Disable Hardware Acceleration in Chrome</a></li>
 	<li><a href="#2">Disable Hardware Acceleration via Registry Editor</a></li>
 	<li><a href="#3">A Short Synopsis</a></li>
</ul>
<span class="dcap">D</span><strong>isable Hardware Acceleration in Google Chrome</strong>: In Google Chrome, hardware acceleration uses your system's graphics processing unit (GPU) to handle intensive tasks related to graphics that includes games, videos, etc.

While it sounds great in many cases, but sometimes hardware acceleration can cause Chrome to freeze, crash or lag and even it drain your laptop's battery. In addition, if you are seeing dialog boxes or menus are not displaying as expected, then it's time to fix this problem.

Disabling hardware acceleration is easy and simple, and we will show you exactly how to <strong>Disable Hardware Acceleration in Google Chrome</strong> in two ways.
<h2 id="1">Method 1 - Disable Hardware Acceleration in Chrome:</h2>
By default, hardware acceleration is enabled on Chrome, so let's look at how to disable it.
<ol>
 	<li>You have to open <strong>Google Chrome</strong>.</li>
 	<li>Next, you have to click on the <strong>menu icon</strong> at the top-right corner of the browser.</li>
 	<li>Click on the <strong>Settings</strong>.

[caption id="attachment_705" align="alignnone" width="826"]<img class="size-full wp-image-705" src="https://windowscrazy.com/wp-content/uploads/2020/05/ha4.png" alt="Choose Settings" width="826" height="493" /> Choose Settings[/caption]</li>
 	<li>In the left pane, you have to tap on <strong>Advanced</strong>.

[caption id="attachment_706" align="alignnone" width="825"]<img class="size-full wp-image-706" src="https://windowscrazy.com/wp-content/uploads/2020/05/ha5.png" alt="Click Advanced" width="825" height="458" /> Click Advanced[/caption]</li>
 	<li>Then, you have to click on <strong>System</strong>.

[caption id="attachment_707" align="alignnone" width="822"]<img class="size-full wp-image-707" src="https://windowscrazy.com/wp-content/uploads/2020/05/ha6.png" alt="Click System" width="822" height="458" /> Click System[/caption]</li>
 	<li>Now, you have to turn off the toggle button of <strong>'Use hardware acceleration when available' </strong>under the <strong>System</strong> section.</li>
 	<li>You have to click on the <strong>Relaunch</strong> button so the hardware acceleration will be disabled.

[caption id="attachment_708" align="alignnone" width="822"]<img class="size-full wp-image-708" src="https://windowscrazy.com/wp-content/uploads/2020/05/ha7.png" alt="Turn off &amp; Relaunch" width="822" height="458" /> Turn off &amp; Relaunch[/caption]</li>
</ol>
<h2 id="2">Method 2 - Disable Hardware Acceleration via Registry Editor:</h2>
<ol>
 	<li>To open the <strong>Run box</strong>, you have to press <strong>Windows key + R</strong>.</li>
 	<li>Next, you have to type <strong>'regedit' </strong>and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press Yes) <code>regedit</code>

[caption id="attachment_418" align="alignnone" width="428"]<img class="size-full wp-image-418" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi1.png" alt="Regedit" width="428" height="232" /> Regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>. In the left pane, you have to navigate to <strong><strong>HKEY_LOCAL_MACHINE\SOFTWARE\Google\Chrome.</strong></strong>

[caption id="attachment_653" align="alignnone" width="856"]<img class="size-full wp-image-653" src="https://windowscrazy.com/wp-content/uploads/2020/05/ha1.png" alt="Click Chrome" width="856" height="498" /> Click Chrome[/caption]</li>
 	<li>Right-click on <strong>Chrome</strong> and select <strong>New</strong> and choose <strong><strong><strong>DWORD 32-bit value.</strong></strong></strong>

[caption id="attachment_654" align="alignnone" width="719"]<img class="size-full wp-image-654" src="https://windowscrazy.com/wp-content/uploads/2020/05/ha2.png" alt="Right-click on Chrome" width="719" height="420" /> Right-click on Chrome[/caption]</li>
 	<li>Now, give the value a name as <strong>'HardwareAccelerationMode'. </strong>Double-click on the name and give the <strong>Value data</strong> as <strong>'0' </strong>and click <strong>OK </strong>to disable hardware acceleration. To enable, you have to set it as '1'.

[caption id="attachment_655" align="alignnone" width="858"]<img class="size-full wp-image-655" src="https://windowscrazy.com/wp-content/uploads/2020/05/ha3.png" alt="Set Value data" width="858" height="496" /> Set Value data[/caption]</li>
</ol>
<h2 id="3">A Short Synopsis:</h2>
Hopefully, this article guided you with two easy ways to <strong>Disable Hardware Acceleration in Google Chrome</strong>. You just follow any one of the ways to disable the hardware acceleration. <strong>Leave a reply</strong> below so it enhances our write-up. Thanks for visiting <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.