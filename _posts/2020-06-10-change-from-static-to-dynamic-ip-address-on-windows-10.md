---
ID: 1194
post_title: >
  Change from static to dynamic IP address
  on Windows 10!!
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1194-change-from-static-to-dynamic-ip-address-on-windows-10/
published: true
post_date: 2020-06-10 13:08:41
---
<ul class="toc">
 	<li><a href="#1">Configure a dynamic IP address (DHCP) using Control Panel</a></li>
 	<li><a href="#2">Configure a dynamic IP address (DHCP) using Command Prompt</a></li>
 	<li><a href="#3">Configure a dynamic IP address (DHCP) using PowerShell</a></li>
 	<li><a href="#4">Configure a dynamic IP address (DHCP) using Settings</a></li>
 	<li><a href="#5">Summary</a></li>
</ul>
<strong><strong><strong><span class="dcap">H</span><strong>ow to change from static to dynamic IP address on Windows 10? </strong></strong></strong></strong>Configure a network adapter to use a static IP address manually or you can use an automatically assigned configuration using the local Dynamic Host Configuration Protocol (DHCP) server.

In this article, we explain <strong>how to change from static to a dynamic IP address on Windows 10 in different ways.</strong>
<h2 id="1">Configure a dynamic IP address (DHCP) using Control Panel:</h2>
Follow the below steps to Configure dynamic IP address (DHCP) using Control Panel in simple steps.
<ol>
 	<li>Go to the <strong>Start Menu.</strong></li>
 	<li>In the search column, type as <strong>Control Panel.</strong></li>
 	<li><strong>Tap</strong> it which appears at the top of the start menu.

[caption id="attachment_1195" align="aligncenter" width="476"]<img class="wp-image-1195 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_1-10.png" alt="Control Panel" width="476" height="768" /> Control Panel[/caption]</li>
 	<li>In the control panel window, select the <strong>Network and Internet</strong>.

[caption id="attachment_1200" align="aligncenter" width="838"]<img class="wp-image-1200 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_6-2.png" alt="Network and Sharing Center" width="838" height="607" /> Network and Sharing Center.[/caption]</li>
 	<li>After that, click on <strong>Network and Sharing Center</strong>.</li>
 	<li>Then, click the <strong>Change adapter settings</strong> link on the left pane of the Network and Sharing Center window.

[caption id="attachment_1196" align="aligncenter" width="838"]<img class="wp-image-1196 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_2-10.png" alt="Change adapter link" width="838" height="610" /> Change adapter link[/caption]</li>
 	<li>Now right-click the network adapter and select the <strong>Properties </strong>option.

[caption id="attachment_1197" align="aligncenter" width="840"]<img class="wp-image-1197 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_3-7.png" alt="Properties" width="840" height="612" /> Properties[/caption]</li>
 	<li>In that select the <strong>Internet Protocol Version 4 (TCP/IPv4)</strong> option and click the <strong>Properties</strong> button.

[caption id="attachment_1198" align="aligncenter" width="455"]<img class="wp-image-1198 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_4-4.png" alt="Internet Protocol Version 4 (TCP/IPv4)" width="455" height="588" /> Internet Protocol Version 4 (TCP/IPv4)[/caption]</li>
 	<li>Select the <strong>Obtain an IP address automatically</strong> option.</li>
 	<li>Then, select the <strong>Obtain the following DNS server address automatically</strong> option.

[caption id="attachment_1199" align="aligncenter" width="491"]<img class="wp-image-1199 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_5-3.png" alt="Options" width="491" height="560" /> Options[/caption]</li>
 	<li>Finally, click<strong> OK. </strong></li>
</ol>
<h2 id="2">Configure a dynamic IP address (DHCP) using Command Prompt:</h2>
Follow the below steps to Configure dynamic IP address (DHCP) using Command Prompt in simple steps.
<ol>
 	<li>Go to the <strong>Start Menu.</strong></li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li>Right-click on the command prompt and select the <strong>Run as administrator</strong> option.</li>
 	<li>To note the name of the network adapter <strong>copy and paste</strong> the below command and press <strong><strong>Enter.</strong></strong>
<pre><code>ipconfig</code></pre>
[caption id="attachment_1205" align="aligncenter" width="799"]<img class="wp-image-1205 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_10-1.png" alt="Commands" width="799" height="637" /> Commands[/caption]</li>
 	<li>Configuring the network adapter to obtain its TCP/IP configuration using DHCP.</li>
 	<li>In the command prompt window, <strong>copy and paste</strong> the below command and press<strong><strong> Enter.</strong></strong>
<pre><code>netsh interface ip set address "Ethernet0" dhcp</code></pre>
[caption id="attachment_1206" align="aligncenter" width="698"]<img class="wp-image-1206 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_11.png" alt="Commands" width="698" height="318" /> Commands[/caption]</li>
 	<li>That's all.</li>
</ol>
<h2 id="3">Configure a dynamic IP address (DHCP) using PowerShell:</h2>
Follow the below steps to Configure dynamic IP address (DHCP) using PowerShell in simple steps.
<ol>
 	<li>Go to the <strong>Start Menu.</strong></li>
 	<li>In the search column, type as <strong>PowerShell.</strong></li>
 	<li>Right-click on the PowerShell and select the <strong>Run as administrator</strong> option.</li>
 	<li><strong>Copy and paste</strong> the below command to note the InterfaceIndex number for the network adapter and press <strong><strong>Enter.</strong></strong>
<pre><code>Get-NetIPConfiguration</code></pre>
[caption id="attachment_1207" align="aligncenter" width="703"]<img class="wp-image-1207 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_12.png" alt="Commands" width="703" height="502" /> Commands[/caption]</li>
 	<li>To enable the network adapter to obtain its TCP/IP configuration using DHCP.</li>
 	<li><strong>Type</strong> the <strong>following</strong> command and press <strong><strong>Enter.</strong></strong>
<pre><code>Get-NetAdapter -Name Ethernet0 | Set-NetIPInterface -Dhcp Enabled</code></pre>
</li>
 	<li>To enable the network adapter to obtain its DNS configuration using DHCP.</li>
 	<li><strong>Copy and paste</strong> the below command and press Enter.
<pre><code>Set-DnsClientServerAddress -InterfaceIndex 4 -ResetServerAddresses</code></pre>
[caption id="attachment_1208" align="aligncenter" width="858"]<img class="wp-image-1208 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_13.png" alt="Commands" width="858" height="307" /> Commands[/caption]</li>
 	<li>That's all.</li>
</ol>
<h2 id="4">Configure a dynamic IP address (DHCP) using Settings:</h2>
Follow the below steps to Configure dynamic IP address (DHCP) using Settings in simple steps.
<ol>
 	<li>Make use of shortcut <strong>Windows + I</strong> to open Windows Settings.</li>
 	<li>Click the <strong>Network &amp; Internet</strong>.</li>
 	<li>In the left pane, select <strong>Ethernet</strong> or <strong>Wi-Fi</strong>.</li>
 	<li>Then, click the network connection.

[caption id="attachment_1201" align="aligncenter" width="1417"]<img class="wp-image-1201 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_7-2.png" alt="Ethernet network " width="1417" height="549" /> Ethernet network[/caption]</li>
 	<li>In the IP settings section, click the <strong>Edit</strong> button.

[caption id="attachment_1202" align="aligncenter" width="585"]<img class="wp-image-1202 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_8-1.png" alt="Edit IP settings " width="585" height="704" /> Edit IP settings[/caption]</li>
 	<li>The dialog box opens, in that click the drop-down menu of <strong>Edit IP settings</strong> and <strong>select the Automatic (DHCP)</strong>option.

[caption id="attachment_1203" align="aligncenter" width="1289"]<img class="wp-image-1203 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_9.png" alt="Enable automatic (DHCP) IP address " width="1289" height="697" /> Enable automatic (DHCP) IP address[/caption]</li>
 	<li>Finally, click the <strong>Save</strong> button.</li>
</ol>
<strong>Image Source:</strong><em> </em><em>pureinfotech.com</em>
<h2 id="5">Summary:</h2>
In the above article, you can get a piece of brief information on <strong>how to change from static to a dynamic IP address on Windows 10</strong> by using different methods with clear cut<strong> screenshots.</strong> Kindly share the <strong>suggestions/queries</strong> in the below comment box and drop your worthwhile <strong>feedback.</strong>