---
ID: 1744
post_title: >
  Enable Remote Desktop from Command Line
  in Windows 10!!
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1744-enable-remote-desktop-from-command-line-in-windows-10/
published: true
post_date: 2020-06-22 07:51:44
---
<ul class="toc">
 	<li><a href="#1">Enable Remote Desktop via Command Prompt</a></li>
 	<li><a href="#2">Enable Remote Desktop - Using PowerShell</a></li>
 	<li><a href="#3">Wind up</a></li>
</ul>
<span class="dcap">E</span><strong>nable Remote Desktop from Command Line</strong>: Remote Desktop Protocol (RDP) is a useful feature that lets you connect two computers and so you can access another computer remotely. You can fix some issues or do any works on another computer as per your needs.

You can<a href="https://windowscrazy.com/102-how-to-enable-remote-desktop-on-windows-10-quick-guide/"><strong> enable remote desktop via Settings or Control Panel</strong></a>. But, if you want to enable this feature without opening the Settings or Control Panel, you can enable it using Command Prompt or PowerShell.  In this guide, we will illustrate how to <strong>Enable Remote Desktop from Command Line </strong>in Windows 10.
<h2 id="1">Enable Remote Desktop via Command Prompt:</h2>
<ol>
 	<li>Press the <strong>Windows key </strong>on your keyboard to open the <strong>Start</strong> menu. [You can also click the Windows logo in the bottom left corner of your screen]</li>
 	<li>Now, the start menu will open with a cursor in the search box and type <strong>‘cmd’</strong> into the search field.</li>
 	<li>Right-click on the top result so it will invoke a drop-down menu and then choose <strong>Run as administrator</strong> option so it will open the command prompt with admin privileges.

[caption id="attachment_1751" align="alignnone" width="1319"]<img class="size-full wp-image-1751" src="https://windowscrazy.com/wp-content/uploads/2020/06/rd1.png" alt="Command Prompt" width="1319" height="881" /> Command Prompt[/caption]</li>
 	<li>You have to press <strong>'Yes'</strong> in order to confirm when prompted.</li>
 	<li>Type the below command and hit <strong>Enter</strong> to enable the remote desktop. <code>reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 0 /f</code>

[caption id="attachment_1752" align="alignnone" width="1182"]<img class="size-full wp-image-1752" src="https://windowscrazy.com/wp-content/uploads/2020/06/rd2.png" alt="Enable Command" width="1182" height="631" /> Enable Command[/caption]</li>
 	<li>[Optional] If you want to enable this feature through the firewall, you have to run the below command and hit <strong>Enter</strong>. <code>netsh advfirewall firewall set rule group="remote desktop" new enable=Yes</code></li>
 	<li>Once you complete the above steps, the remote desktop feature will be enabled.</li>
</ol>
<ul>
 	<li>To disable remote desktop protocol: <code>reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 1 /f</code>

[caption id="attachment_1753" align="alignnone" width="1149"]<img class="size-full wp-image-1753" src="https://windowscrazy.com/wp-content/uploads/2020/06/rd3.png" alt="Disable Command" width="1149" height="690" /> Disable Command[/caption]</li>
 	<li>To disable through the firewall: <code>netsh advfirewall firewall set rule group="remote desktop" new enable=No</code></li>
</ul>
<h2 id="2">Enable Remote Desktop Using PowerShell:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu, type <strong>‘powershell’ </strong>in the search box.</li>
 	<li>Then, right-click on the top result and choose <strong>Run as administrator</strong>.

[caption id="attachment_1757" align="alignnone" width="1313"]<img class="size-full wp-image-1757" src="https://windowscrazy.com/wp-content/uploads/2020/06/rd6.png" alt="PowerShell" width="1313" height="889" /> PowerShell[/caption]</li>
 	<li>After that, you have to copy and paste the below command and hit <strong>Enter</strong>. <code>reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 0 /f</code>

[caption id="attachment_1754" align="alignnone" width="1103"]<img class="size-full wp-image-1754" src="https://windowscrazy.com/wp-content/uploads/2020/06/rd4.png" alt="Enable Command" width="1103" height="605" /> Enable Command[/caption]</li>
 	<li>Now, the remote desktop feature gets enabled.</li>
</ol>
<ul>
 	<li>To disable: <code>reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 1 /f</code>

[caption id="attachment_1755" align="alignnone" width="1098"]<img class="size-full wp-image-1755" src="https://windowscrazy.com/wp-content/uploads/2020/06/rd5.png" alt="Disable Command" width="1098" height="626" /> Disable Command[/caption]</li>
</ul>
<h2 id="3">Wind up:</h2>
This guide assisted you to <strong>Enable Remote Desktop from Command Line </strong>in Windows 10 in clear-cut steps. We hope that the steps let you understand the enabling process easier. Share your <strong>feedback</strong> in the below section. We appreciate your presence in <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.