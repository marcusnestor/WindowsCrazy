---
ID: 1931
post_title: 'How to Allow Ports through the Firewall on Windows 10? {Step-by-Step Guide}'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1931-how-to-allow-ports-through-the-firewall-on-windows-10-step-by-step-guide/
published: true
post_date: 2020-06-27 01:12:26
---
<ul class="toc">
 	<li><a href="#1">Steps to Allow Ports through the Firewall</a></li>
 	<li><a href="#2">Close a Port via Firewall</a></li>
 	<li><a href="#3">A Brief Summary</a></li>
</ul>
<span class="dcap">A</span><strong>llow Ports through the Firewall on Windows 10</strong>: There is a robust in-built firewall feature in Windows 10 that secures your system from viruses or threats. The firewall will obstruct all unwanted ports and deny permission if it can't find any rule in the database. Occasionally, applications may not work properly as they may be blocked by the firewall.

In such cases, you need to allow ports through the firewall so that the trouble gets fixed. So, you can view certain applications and webpages normally. Here, we will illustrate <strong>how to allow ports through the firewall on Windows 10</strong> in an efficient manner.
<h2 id="1">Clear-cut Steps to Allow Ports through the Firewall:</h2>
Follow the below steps if an application wants one or more ports open in order to function properly.
<p id="note"><strong>Note:</strong> Make sure to know the ports and type of protocol that you need to open by verifying your app support documentation. Furthermore, you need to check if the app works with the firewall disabled temporarily, and then you should open the port.</p>

<ol>
 	<li>First, you have to press the <strong>Windows key</strong>.</li>
 	<li>Then, you need to type '<strong>cp</strong>' and hit <strong>Enter</strong> to open the <strong>Control Panel</strong>.

[caption id="attachment_1941" align="alignnone" width="1315"]<img class="size-full wp-image-1941" src="https://windowscrazy.com/wp-content/uploads/2020/06/ap1.png" alt="Control Panel" width="1315" height="883" /> Control Panel[/caption]</li>
 	<li>Tap on the <strong>System and Security</strong> option.

[caption id="attachment_1942" align="alignnone" width="1255"]<img class="size-full wp-image-1942" src="https://windowscrazy.com/wp-content/uploads/2020/06/ap2.png" alt="System and Security" width="1255" height="854" /> System and Security[/caption]</li>
 	<li>Proceed to click on <strong>Windows Defender Firewall</strong>.

[caption id="attachment_1943" align="alignnone" width="1250"]<img class="size-full wp-image-1943" src="https://windowscrazy.com/wp-content/uploads/2020/06/ap3.png" alt="Windows Defender Firewall" width="1250" height="849" /> Windows Defender Firewall[/caption]</li>
 	<li>On the left side, you have to click on the <strong>Advanced settings</strong> link.

[caption id="attachment_1944" align="alignnone" width="1256"]<img class="size-full wp-image-1944" src="https://windowscrazy.com/wp-content/uploads/2020/06/ap4.png" alt="Advanced settings" width="1256" height="851" /> Advanced settings[/caption]</li>
 	<li>It will open the <strong>Windows Defender Firewall with Advanced Security</strong> window.</li>
 	<li>You have to select <strong>Inbound Rules</strong> from the left pane. [If your app requires a specific outbound port to be opened, you have to choose the <strong>Outbound Rules</strong> option.]</li>
 	<li>Then, continue to click on the <strong>New Rule</strong> option that you can find under '<strong>Action</strong>' in the right pane.

[caption id="attachment_1945" align="alignnone" width="1283"]<img class="size-full wp-image-1945" src="https://windowscrazy.com/wp-content/uploads/2020/06/ap5.png" alt="New Rule" width="1283" height="825" /> New Rule[/caption]</li>
 	<li>It will open the <strong>New Inbound Rule Wizard</strong>.</li>
 	<li>Now, you have to choose the <strong>Port</strong> option. After that, you have to click the <strong>Next</strong> button.

[caption id="attachment_1946" align="alignnone" width="1070"]<img class="size-full wp-image-1946" src="https://windowscrazy.com/wp-content/uploads/2020/06/ap6.png" alt="Port &amp; Next" width="1070" height="871" /> Port &amp; Next[/caption]</li>
 	<li>As per the application, you have to choose a suitable protocol either <strong>TCP or UDP</strong>. Mostly the option will be TCP.</li>
 	<li>You have to type the port number in the <strong>Specific local ports</strong> field.</li>
 	<li>You can specify a port range with a hyphen (-) as like this 5000-5200. Sometimes, one single application may need several ports to open so you can type more number of ports by separating each one with a comma like this 2000, 3400, 4900.</li>
 	<li>Click on the <strong>Next</strong> button.

[caption id="attachment_1947" align="alignnone" width="1070"]<img class="size-full wp-image-1947" src="https://windowscrazy.com/wp-content/uploads/2020/06/ap7.png" alt="Next" width="1070" height="871" /> Next[/caption]</li>
 	<li>Now, you have to select the <strong>Allow the connection</strong> option and then tap on the <strong>Next</strong> button.

[caption id="attachment_1948" align="alignnone" width="1070"]<img class="size-full wp-image-1948" src="https://windowscrazy.com/wp-content/uploads/2020/06/ap8.png" alt="Allow the connection" width="1070" height="871" /> Allow the connection[/caption]</li>
 	<li>Under '<strong>When does this rule apply?</strong>', you have to choose the network type and click the <strong>Next</strong> button.

[caption id="attachment_1949" align="alignnone" width="1070"]<img class="size-full wp-image-1949" src="https://windowscrazy.com/wp-content/uploads/2020/06/ap9.png" alt="Next" width="1070" height="871" /> Next[/caption]</li>
 	<li>You just give a <strong>Name</strong> for this rule then write <strong>Description</strong> if you want and then select the <strong>Finish </strong>button.

[caption id="attachment_1950" align="alignnone" width="1070"]<img class="size-full wp-image-1950" src="https://windowscrazy.com/wp-content/uploads/2020/06/ap10.png" alt="Finish" width="1070" height="871" /> Finish[/caption]</li>
</ol>
<h2 id="2">Close a Port via Firewall:</h2>
<ol>
 	<li>You just follow the above steps from <strong>1 to 6</strong>.</li>
 	<li>After that, you have to choose either <strong>Inbound Rules</strong> or <strong>Outbound Rules</strong> as per the rule with open the port location.</li>
 	<li>Then, you have to select the rule you want.</li>
 	<li>In the right pane, under '<strong>Actions</strong>', you can choose either <strong>Disable Rule</strong> or <strong>Delete</strong> as per your needs.

[caption id="attachment_1951" align="alignnone" width="1295"]<img class="size-full wp-image-1951" src="https://windowscrazy.com/wp-content/uploads/2020/06/ap11.png" alt="Disable Rule or Delete" width="1295" height="842" /> Disable Rule or Delete[/caption]</li>
</ol>
<h2 id="3">A Brief Summary:</h2>
Probably, the above steps helped you a lot to understand on <strong>how to allow ports through the firewall on Windows 10</strong> effectively. Once you allow the ports through the firewall, the respective service or application that is not worked will run smoothly. Your <strong>comments</strong> are highly welcomed as it cheers our write-up. We appreciate your presence in <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.
<h2>Read Ahead:</h2>
<ul>
 	<li><a href="https://windowscrazy.com/618-uninstall-microsoft-office-365-from-windows-10-quickly/">Uninstall Microsoft Office 365 from Windows 10! (*Quickly*)</a></li>
 	<li><a href="https://windowscrazy.com/1252-fix-bluetooth-connection-issues-in-windows-10-4-easy-fixes/">Fix Bluetooth Connection Issues in Windows 10!! (*4 Easy Fixes*)</a></li>
 	<li><a href="https://windowscrazy.com/748-quickly-fix-master-boot-record-mbr-on-windows-10/">{Quickly} Fix Master Boot Record (MBR) on Windows 10!!</a></li>
 	<li><a href="https://windowscrazy.com/1275-set-a-custom-image-as-your-xbox-one-background/">Set a custom image as your Xbox One background!!</a></li>
 	<li><a href="https://windowscrazy.com/852-how-to-download-windows-10-version-1803-iso-file/">How to Download Windows 10 version 1803 ISO File?</a></li>
</ul>