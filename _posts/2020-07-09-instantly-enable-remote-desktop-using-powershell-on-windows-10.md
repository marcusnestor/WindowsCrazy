---
ID: 2384
post_title: '{Instantly} Enable Remote Desktop using PowerShell on Windows 10!!'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/2384-instantly-enable-remote-desktop-using-powershell-on-windows-10/
published: true
post_date: 2020-07-09 07:50:16
---
<ul class="toc">
 	<li><a href="#1">Enable Remote Desktop via PowerShell</a></li>
 	<li><a href="#1">Disable Remote Desktop via PowerShell</a></li>
 	<li><a href="#4">Sum-up</a></li>
</ul>
<span class="dcap">E</span><strong>nable Remote Desktop Using PowerShell: </strong>If you want to enable Remote Desktop on the computer or server, we will show you how to do it by PowerShell. While you can enable this remote desktop feature via settings, you can also enable or disable it via PowerShell.

You just need to run a simple command to enable or disable this feature. It will not take more time and effort. Once you enable it, you can access your system remotely. This is a quick tutorial on how to <b>Enable Remote Desktop using PowerShell</b> on Windows 10. In addition, you will learn the steps to disable remote desktop via PowerShell.
<h2 id="1">Enable Remote Desktop via PowerShell:</h2>
<ol>
 	<li>First of all, you have to click the <strong>Windows key</strong>.</li>
 	<li>In the search box, you have to type '<strong>powershell</strong>'.</li>
 	<li>After that, you have to right-click on the top result and choose <strong>Run as administrator</strong>.</li>
 	<li>You need to copy and paste the below command and hit <strong>Enter</strong>. <code>Set-ItemProperty -Path 'HKLM:\System\CurrentControlSet\Control\Terminal Server' -name "fDenyTSConnections" -value 0</code>

[caption id="attachment_2391" align="alignnone" width="1028"]<img class="size-full wp-image-2391" src="https://windowscrazy.com/wp-content/uploads/2020/07/Enable-Remote-Desktop.png" alt="Enable Remote Desktop" width="1028" height="563" /> Enable Remote Desktop[/caption]</li>
 	<li>Once you complete the above steps, you can able to use Remote Desktop to access your system remotely.</li>
</ol>
<strong>Optional:</strong>
<ul>
 	<li>If you want to enable remote desktop through Windows Firewall, you can run the below command and hit <strong>Enter</strong>.</li>
 	<li><code>Enable-NetFirewallRule -DisplayGroup "Remote Desktop"</code></li>
</ul>
<h2 id="1">Disable Remote Desktop via PowerShell:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu and type '<strong>powershell</strong>' in the search box.</li>
 	<li>You have to right-click on the top result and choose <strong>Run as administrator</strong>.</li>
 	<li>Then, you need to run the below command and hit <strong>Enter</strong>. <code>Set-ItemProperty -Path 'HKLM:\System\CurrentControlSet\Control\Terminal Server' -name "fDenyTSConnections" -value 1</code>

[caption id="attachment_2390" align="alignnone" width="1033"]<img class="size-full wp-image-2390" src="https://windowscrazy.com/wp-content/uploads/2020/07/Disable-Remote-Desktop.png" alt="Disable Remote Desktop" width="1033" height="521" /> Disable Remote Desktop[/caption]</li>
 	<li>Once you complete the above steps, the Remote Desktop feature will be disabled.</li>
</ol>
<strong>Optional:</strong>
<ul>
 	<li>If you want to disable remote desktop through Windows Firewall, you can run the below command and hit <strong>Enter</strong>.</li>
 	<li><code>Disable-NetFirewallRule -DisplayGroup "Remote Desktop"</code></li>
</ul>
<h2 id="4">Sum-up:</h2>
In the above tutorial, you have learned the quick steps to <b>Enable Remote Desktop using PowerShell </b>on Windows 10. Access your computer remotely or manage users or services without being present at the location by enabling the remote desktop feature. Feel free to share your <strong>valuable comments</strong> in the below section. We appreciate your presence in <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.