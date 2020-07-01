---
ID: 2246
post_title: >
  2 Easy Ways to Set Ethernet as Metered
  Connection in Windows 10!!
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/2246-2-easy-ways-to-set-ethernet-as-metered-connection-in-windows-10/
published: true
post_date: 2020-07-01 12:51:33
---
<ul class="toc">
 	<li><a href="#1">Set Ethernet as Metered Connection through Settings</a></li>
 	<li><a href="#2">Set Ethernet as Metered Connection via Registry Editor</a></li>
 	<li><a href="#3">Closure</a></li>
</ul>
<span class="dcap">E</span><strong>thernet Metered Connection in Windows 10</strong>: In Windows 10, the regular updates, driver updates, security updates, etc will download automatically and once the download completes, you will be notified about the installation of updates. If you have an unlimited data plan and a faster internet connection, you may not concern about these automatic updates.

But, if you are using a limited internet connection with a specific data limit, you will definitely worry about it. Metered connections assist by altering the way some services and apps use your data. If you are using an ethernet connection, then it is possible to set it as metered connections. In this tutorial, we will illustrate the simple steps of two methods to set <strong>Ethernet as Metered Connection in Windows 10. </strong>
<h2 id="1">1) Set Ethernet as Metered Connection through Settings:</h2>
<ol>
 	<li>To open the <strong>Settings</strong>, you have to press the <strong>Windows key + I</strong> keyboard shortcut.</li>
 	<li>In the Windows Settings screen, you have to click on <strong>Network &amp; Internet</strong>.

[caption id="attachment_2252" align="alignnone" width="1322"]<img class="size-full wp-image-2252" src="https://windowscrazy.com/wp-content/uploads/2020/07/Network-Internet.png" alt="Network &amp; Internet" width="1322" height="812" /> Network &amp; Internet[/caption]</li>
 	<li>You have to go with the <strong>Ethernet</strong> option in the left pane.

[caption id="attachment_2251" align="alignnone" width="1321"]<img class="size-full wp-image-2251" src="https://windowscrazy.com/wp-content/uploads/2020/07/Ethernet.png" alt="Ethernet" width="1321" height="816" /> Ethernet[/caption]</li>
 	<li>Now, you have to click on your current ethernet connection.</li>
 	<li>After that, you have to <strong>turn on</strong> the toggle switch of '<strong>Set as metered connection</strong>' so that it limits the background data usage.

[caption id="attachment_2254" align="alignnone" width="1319"]<img class="size-full wp-image-2254" src="https://windowscrazy.com/wp-content/uploads/2020/07/Set-as-metered-connection.png" alt="Set as metered connection" width="1319" height="818" /> Set as metered connection[/caption]</li>
</ol>
<h2 id="2">2) Set Ethernet as Metered Connection via Registry Editor:</h2>
You have to follow the below steps to set ethernet as a metered connection if you are using Windows 10 v1607 (Anniversary Update) or earlier and Windows 8 as well.
<ol>
 	<li>Open the <strong>Run box </strong>with the use of this shortcut <strong>Windows key + R</strong>.</li>
 	<li>After that, you have to type '<strong>regedit</strong>' and click the <strong>OK </strong>button.

[caption id="attachment_2253" align="alignnone" width="606"]<img class="size-full wp-image-2253" src="https://windowscrazy.com/wp-content/uploads/2020/07/regedit.png" alt="regedit" width="606" height="366" /> regedit[/caption]</li>
 	<li>In the Registry Editor window, you have to navigate to the below path.<code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\NetworkList\DefaultMediaCost </code></li>
 	<li>In the right pane, you will see five DWORD values.</li>
 	<li>You have to double-click on <strong>Ethernet</strong> and set it value as <strong>2 </strong>and click<strong> OK</strong>.

[caption id="attachment_2250" align="alignnone" width="1193"]<img class="size-full wp-image-2250" src="https://windowscrazy.com/wp-content/uploads/2020/07/Ethernet-Value-as-2.png" alt="Ethernet Value as 2" width="1193" height="730" /> Ethernet Value as 2[/caption]</li>
 	<li>That's it. You have to restart your PC to apply the changes.</li>
</ol>
<h2 id="3">Closure:</h2>
We hope that this tutorial assisted you to set <strong>Ethernet as Metered Connection in Windows 10</strong>. The above methods are really easy and so you can use the ethernet as a metered connection to save data. Kindly share your <strong>queries/comments</strong> in the below box. We appreciate your presence in <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.
<h2>Read Ahead:</h2>
<ul>
 	<li><a href="https://windowscrazy.com/1275-set-a-custom-image-as-your-xbox-one-background/">Set a custom image as your Xbox One background!!</a></li>
 	<li><a href="https://windowscrazy.com/1022-change-notification-default-sounds-on-windows-10/">Change notification default sounds on Windows 10!!</a></li>
 	<li><a href="https://windowscrazy.com/967-download-windows-10-iso-direct-file-different-methods/">Download Windows 10 ISO Direct File!! {Different Methods}</a></li>
</ul>