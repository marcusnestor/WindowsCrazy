---
ID: 1210
post_title: 'Reset Mail App on Windows 10!! [Quickly]'
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1210-reset-mail-app-on-windows-10-quickly/
published: true
post_date: 2020-06-10 13:08:54
---
<ul class="toc">
 	<li><a href="#1">Reset Mail App using PowerShell</a></li>
 	<li><a href="#2">Reset Mail App using Settings</a></li>
 	<li><a href="#3">Install missing Mail app packages on Windows 10</a></li>
 	<li><a href="#4">Conclusion</a></li>
</ul>
<strong><strong><strong><span class="dcap">H</span><strong>ow to reset the Mail App on Windows 10? </strong></strong></strong></strong>Microsoft's products these days, the Mail app is offered as a service, which means that it’s always considered a work in progress, which also means that throughout the life of the app you’re likely to come across more issues. A lot of users often complain about emails not syncing, the Mail app not opening, problems adding new email accounts, and certain settings not working, among other issues.

In this article, we will give some steps <strong>to reset the Mail app on Windows 10</strong> in simple steps.
<h2 id="1">Reset the Mail app on using PowerShell:</h2>
Follow the steps to reset the Mail app on using PowerShell in simple steps.

<strong>Note:</strong> To reset the Mail app using this method, we need to use PowerShell to remove the app and then use the Microsoft Store to reinstall it.

<strong>Uninstall Mail using PowerShell:</strong>
<ol>
 	<li>Go to the <strong>Start Menu.</strong></li>
 	<li>In the search column, type as <strong>PowerShell.</strong></li>
 	<li>Then, right-click on the PowerShell and select the <strong>Run as administrator </strong>option.

[caption id="attachment_1211" align="aligncenter" width="480"]<img class="wp-image-1211 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_1-11.png" alt="Start Menu" width="480" height="767" /> Start the Menu[/caption]</li>
 	<li><strong>Copy and paste</strong> the below-mentioned command and press <strong>Enter.</strong>
<pre><code>Get-AppxPackage Microsoft.windowscommunicationsapps | Remove-AppxPackage</code></pre>
[caption id="attachment_1212" align="aligncenter" width="890"]<img class="wp-image-1212 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_2-11.png" alt="Commands" width="890" height="250" /> Commands[/caption]</li>
 	<li>Now, <strong>restart</strong> your computer.</li>
</ol>
<strong>Reinstalling Mail app using Microsoft Store:</strong>
<ol>
 	<li>Go to the <strong>Microsoft Store</strong>.</li>
 	<li>Then, search for <strong>Mail and Calendar.</strong></li>
 	<li>Now, click the <strong>Install</strong> button.

[caption id="attachment_1213" align="aligncenter" width="1472"]<img class="wp-image-1213 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_3-8.png" alt="Microsoft Store" width="1472" height="549" /> Microsoft Store[/caption]</li>
 	<li>Launch the <strong>Mail</strong> app.</li>
 	<li>Finally, continue with the on-screen directions to complete the setup.</li>
</ol>
<h2 id="2">Reset the Mail app on using Settings:</h2>
Follow the steps to reset the Mail app on using Settings in simple steps.
<ol>
 	<li>Make use of the shortcut <strong>Windows +I</strong> to open the Windows Settings.</li>
 	<li>Then, click the Apps option.</li>
 	<li>Select <strong>Apps &amp; features</strong>.</li>
 	<li>Then, select the <strong>Mail and Calendar</strong> app from the list.</li>
 	<li>Now, click the <strong>Advanced options</strong> link.

[caption id="attachment_1215" align="aligncenter" width="1179"]<img class="wp-image-1215 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_5-4.png" alt="Mail app Advanced options link" width="1179" height="862" /> Mail app Advanced options link[/caption]

<strong>Image Source:</strong><em> </em><em>pureinfotech.com</em></li>
 	<li>Finally, click the <strong>Reset</strong> button and click the <strong>Reset</strong> button again to confirm.

[caption id="attachment_1214" align="aligncenter" width="759"]<img class="wp-image-1214 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_4-5.png" alt="Reset" width="759" height="881" /> Reset[/caption]

<strong>Image Source:</strong><em> </em><em>pureinfotech.com</em></li>
 	<li>That's all.</li>
</ol>
<h2 id="3">Install missing Mail app packages on Windows 10:</h2>
<ol>
 	<li>Go to the <strong>Start Menu.</strong></li>
 	<li>In the search column, type as<strong> Command Prompt.</strong></li>
 	<li>Then, right-click on the Command Prompt and select the <strong>Run as administrator </strong>option.</li>
 	<li>Copy and paste the below-mentioned command and press <strong>Enter</strong>.
<pre><code>dism /online /Add-Capability /CapabilityName:OneCoreUAP.OneSync~~~~0.0.1.0</code></pre>
</li>
 	<li>Now, <strong>restart</strong> your computer.</li>
 	<li>Then, open <strong>Mail</strong>.</li>
 	<li>Click the <strong>Settings</strong> and Click on <strong>Manage Accounts.</strong></li>
 	<li>That's all.</li>
</ol>
<h2 id="4">Conclusion:</h2>
In this tutorial, we have explained <strong>how to reset the Mail app on Windows 10 in simple steps.</strong> Besides, the screenshots let you understand even simpler. Kindly share your <strong>queries/feedback</strong> in the below comment section.