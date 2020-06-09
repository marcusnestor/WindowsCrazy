---
ID: 1104
post_title: >
  How to Fix Ethernet Unidentified Network
  Error on Windows 10?
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1104-how-to-fix-ethernet-unidentified-network-error-on-windows-10/
published: true
post_date: 2020-06-09 06:07:52
---
<ul class="toc">
 	<li><a href="#1">Resetting Winsock Stack</a></li>
 	<li><a href="#2">Turn Off Airplane Mode</a></li>
 	<li><a href="#3">Disable Windows Defender Firewall</a></li>
 	<li><a href="#4">A Brief Summary</a></li>
</ul>
<span class="dcap">F</span><strong>ix Ethernet Unidentified Network Error on Windows 10</strong>: Network connectivity problems are possibly the most often encountered errors in the Windows 10 system. If you are connected to the Ethernet or Wi-Fi network on a Windows PC, you may come across an 'unidentified network' error. In such circumstances, you don't have to be panic.

There are many fixes available to get rid of this error. Here, we will illustrate the methods to <strong>Fix Ethernet Unidentified Network Error on Windows 10</strong> in an efficient manner.
<h2 id="1">Method 1 - Resetting Winsock Stack:</h2>
<ul>
 	<li>Press the <strong>Windows key </strong>on your keyboard to open the <strong>Start</strong> menu. [You can also click the Windows logo in the bottom left corner of your screen]</li>
 	<li>Now, the start menu will open with a cursor in the search box and type <strong>'cmd'</strong> into the search field.

[caption id="attachment_452" align="alignnone" width="888"]<img class="size-full wp-image-452" src="https://windowscrazy.com/wp-content/uploads/2020/05/up1.png" alt="Search for Command Prompt" width="888" height="680" /> Search for Command Prompt[/caption]</li>
 	<li>Right-click on the top result so it will invoke a drop-down menu and then choose <strong>Run as administrator</strong> option so it will open the command prompt with admin privileges.

[caption id="attachment_453" align="alignnone" width="888"]<img class="size-full wp-image-453" src="https://windowscrazy.com/wp-content/uploads/2020/05/up2.png" alt="Run as administrator" width="888" height="680" /> Run as administrator[/caption]</li>
 	<li>You have to press <strong>'Yes'</strong> in order to confirm this choice when prompted.</li>
 	<li>Run the below commands one by one and hit <strong>Enter </strong>for each command to reset the Winsock networking stack</li>
</ul>
<code>netsh winsock reset
netsh int ip reset</code>

[caption id="attachment_1109" align="alignnone" width="822"]<img class="size-full wp-image-1109" src="https://windowscrazy.com/wp-content/uploads/2020/06/eu1.png" alt="Reset Winsock" width="822" height="535" /> Reset Winsock[/caption]
<ul>
 	<li>To reset the DNS information, you have to type the following command and hit <strong>Enter</strong>.</li>
</ul>
<code>Ipconfig /flushdns</code>

[caption id="attachment_1110" align="alignnone" width="789"]<img class="size-full wp-image-1110" src="https://windowscrazy.com/wp-content/uploads/2020/06/eu2.png" alt="Reset DNS" width="789" height="461" /> Reset DNS[/caption]
<ul>
 	<li>At last, you have to restart your Windows system. After that, try to connect the network so you can connect successfully.</li>
</ul>
<h2 id="2">Method 2 - Turn Off Airplane Mode:</h2>
If you are experiencing the 'Unidentified Network' issue, turning off Airplane mode could fix the problem.
<ol>
 	<li>To launch the <strong>Action Center</strong>, you have to click on the note-like icon on the system tray (at the lower bottom of your screen).

[caption id="attachment_1111" align="alignnone" width="590"]<img class="size-full wp-image-1111" src="https://windowscrazy.com/wp-content/uploads/2020/06/eu3.png" alt="Launch Action Center" width="590" height="388" /> Launch Action Center[/caption]</li>
 	<li>If you find the Airplane mode is on, tap on it to turn off.</li>
 	<li>If the Airplane mode is off, you just turn it on and then turn it off again.

[caption id="attachment_1112" align="alignnone" width="665"]<img class="size-full wp-image-1112" src="https://windowscrazy.com/wp-content/uploads/2020/06/eu4.png" alt="Airplane mode" width="665" height="400" /> Airplane mode[/caption]</li>
 	<li>After that, reconnect to your ethernet network so you will not see any error.</li>
</ol>
<h2 id="3">Method 3 - Disable Windows Defender Firewall:</h2>
<ol>
 	<li>In order to open the Settings, you can use this shortcut <strong>Windows key + I</strong>.</li>
 	<li>After that, you have to click on <strong>Update &amp; Security</strong>.

[caption id="attachment_1114" align="alignnone" width="878"]<img class="size-full wp-image-1114" src="https://windowscrazy.com/wp-content/uploads/2020/06/eu5.png" alt="Update &amp; Security" width="878" height="569" /> Update &amp; Security[/caption]</li>
 	<li>In the left pane, you have to tap on <strong>Windows Security</strong>.

[caption id="attachment_1115" align="alignnone" width="890"]<img class="size-full wp-image-1115" src="https://windowscrazy.com/wp-content/uploads/2020/06/eu6.png" alt="Windows Security" width="890" height="584" /> Windows Security[/caption]</li>
 	<li>Under Protection areas, you have to click on <strong>Firewall &amp; network protection</strong>.

[caption id="attachment_1116" align="alignnone" width="888"]<img class="size-full wp-image-1116" src="https://windowscrazy.com/wp-content/uploads/2020/06/eu7.png" alt="Firewall &amp; network protection" width="888" height="581" /> Firewall &amp; network protection[/caption]</li>
 	<li>Next, you have to select the <strong>Public network</strong> in the Windows Security window.

[caption id="attachment_1117" align="alignnone" width="890"]<img class="size-full wp-image-1117" src="https://windowscrazy.com/wp-content/uploads/2020/06/eu8.png" alt="Public Network" width="890" height="588" /> Public Network[/caption]</li>
 	<li>Turn off the toggle switch under the <strong>Windows Defender Firewall</strong>.

[caption id="attachment_1118" align="alignnone" width="883"]<img class="size-full wp-image-1118" src="https://windowscrazy.com/wp-content/uploads/2020/06/eu9.png" alt="Turn off Windows Defender Firewall" width="883" height="575" /> Turn off Windows Defender Firewall[/caption]</li>
 	<li>You have to do the same for the Private network.</li>
 	<li>Now, you can try to reconnect to your network.</li>
</ol>
<h2 id="4">A Brief Summary:</h2>
Probably, the above methods helped you a lot to <strong>Fix Ethernet Unidentified Network Error on Windows 10</strong> easily and effectively. We hope that the fixes are not really complex. Your comments are highly welcomed as it cheers our write-up. Thanks for visiting <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.