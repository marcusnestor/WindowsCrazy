---
ID: 1987
post_title: >
  Step By Step Guide To Fix Windows 8.1
  Wireless Limited Connectivity!!
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1987-step-by-step-guide-to-fix-windows-8-1-wireless-limited-connectivity/
published: true
post_date: 2020-06-27 09:43:18
---
<ul class="toc">
 	<li><a href="#1">To Reset the Windows TCP/IP stack</a></li>
 	<li><a href="#2">To Reset the Wi-Fi network on Windows 8</a></li>
 	<li><a href="#3">To Reset the Wi-Fi network on Windows 8.1</a></li>
 	<li><a href="#4">To Reset WinSock on Windows</a></li>
 	<li><a href="#5">To Disable Power Saving Mode</a></li>
 	<li><a href="#6">Changing the Network Settings</a></li>
 	<li><a href="#7">The Conclusion</a></li>
</ul>
<strong><span class="dcap">H</span>ow to Fix Windows 8.1 Wireless Limited Connectivity? </strong>Sometimes the <strong>wireless network</strong> won’t connect to the internet and the wireless network settings will popup a message as<strong> Limited Connectivity.</strong> This issue will occur because of technical glitches. Follow this article to <strong>resolve</strong> it.

Read this tutorial, to get rid of<strong> the Limited Connectivity issue on Windows 8.1</strong> in simple ways.
<h2 id="1">To Reset the Windows TCP/IP stack:</h2>
Follow the below steps to reset the Windows TCP/IP stack in simple steps.
<ol>
 	<li>Make use of the shortcut <strong>Windows + X</strong> and choose <strong><strong>Command Prompt (Admin).</strong></strong>

[caption id="attachment_2003" align="aligncenter" width="305"]<img class="size-full wp-image-2003" src="https://windowscrazy.com/wp-content/uploads/2020/06/KPFXlJNPoC.png" alt="Menu" width="305" height="528" /> Menu[/caption]</li>
 	<li>Then simply <strong>type</strong> the following command in your Command Prompt window.
<pre><code>netsh int ip reset C:\ipresetlog.txt</code></pre>
</li>
 	<li>Now, <strong>restart</strong> your <strong>Windows</strong> <strong>8</strong> computer.</li>
 	<li>Then check the <strong>wireless</strong> <strong>network</strong> has been successfully connected or not.</li>
 	<li>When you <strong>didn't</strong> <strong>resolve</strong> the problem by using the above steps then <strong>delete</strong> <strong>the</strong> <strong>wireless</strong> <strong>profile</strong> in question and connect again.</li>
 	<li>Because of the wireless security key (WEP or WPA 2) in the router or in your computer may be gone wrong.</li>
 	<li>At last, you need to <strong>refresh</strong> it.</li>
</ol>
<h2 id="2">To Reset the Wi-Fi network on Windows 8:</h2>
Use the below steps to reset the Wi-Fi network on Windows 8.
<ol>
 	<li>Use the shortcut<strong> Windows + I</strong> to open the <strong>Windows Settings.</strong></li>
 	<li>In the settings window, click the <strong>Network &amp; Internet</strong> option.</li>
 	<li>In the left pane, click the<strong> Wi-Fi</strong> option.</li>
 	<li>To <strong>delete</strong> the wireless profile that is causing the problem, select <strong>Forget this network </strong>option.

[caption id="attachment_1998" align="aligncenter" width="417"]<img class="size-full wp-image-1998" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_5HhFJDUQcK.png" alt="Forget this Network" width="417" height="522" /> Forget this Network[/caption]

<strong>Image Source:</strong> <em>pureinfotech.com</em></li>
 	<li>Now,<strong> turn off and on</strong> the wireless adapter from the <strong>Network</strong> <strong>settings</strong>.</li>
 	<li>Finally, connect to the same <strong>network</strong> again.</li>
</ol>
<h2 id="3">To Reset the Wi-Fi network on Windows 8.1:</h2>
In the new version of the operating system, there is no menu to delete the wireless profiles. So here we can use the Command Prompt to delete.
<ol>
 	<li>Make use of the shortcut <strong>Windows + X</strong> and choose <strong><strong>Command Prompt (Admin).</strong></strong>

[caption id="attachment_2003" align="aligncenter" width="305"]<img class="size-full wp-image-2003" src="https://windowscrazy.com/wp-content/uploads/2020/06/KPFXlJNPoC.png" alt="Menu" width="305" height="528" /> Menu[/caption]</li>
 	<li>Then simply <strong>type</strong> the following command in your Command Prompt window.</li>
 	<li>Press Enter.
<pre><code>netsh wlan delete profile name=type-wireless-profile-name</code></pre>
</li>
 	<li>Now, you can try to <strong>reconnect</strong> your network.</li>
</ol>
<h2 id="4">To Reset WinSock on Windows:</h2>
Use the Windows network software to resolve. Follow the below steps.
<ol>
 	<li>To reset the <strong>WinSock</strong>, open the Command Prompt.</li>
 	<li>Try the <strong>following</strong> command.</li>
 	<li>Press <strong>Enter</strong>.
<pre><code>netsh winsock reset catalog</code></pre>
</li>
 	<li>The above command needs to <strong>restart</strong> your PC.</li>
</ol>
<h2 id="5">To Disable Power Saving Mode:</h2>
There is a chance if the Wi-Fi adapter has gone into Power Saving Mode.
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the Run command dialog box.</li>
 	<li>Type <strong>ncpa.cpl</strong> in the given space box of <strong>Open</strong>.</li>
 	<li>Click <strong><strong>OK.</strong></strong>

[caption id="attachment_2002" align="aligncenter" width="448"]<img class="size-full wp-image-2002" src="https://windowscrazy.com/wp-content/uploads/2020/06/explorer_FSM67qOFO0.png" alt="Run command" width="448" height="261" /> Run command[/caption]</li>
 	<li>Now, right-click on the <strong>wireless network adapter</strong> and select <strong>Properties</strong>.

[caption id="attachment_2001" align="aligncenter" width="1026"]<img class="size-full wp-image-2001" src="https://windowscrazy.com/wp-content/uploads/2020/06/explorer_1bU23OpBdh.png" alt="Properties" width="1026" height="607" /> Properties[/caption]</li>
 	<li>Click on the <strong>Configure</strong>.

[caption id="attachment_2000" align="aligncenter" width="444"]<img class="size-full wp-image-2000" src="https://windowscrazy.com/wp-content/uploads/2020/06/dllhost_M8yXGfnbiC.png" alt="Configure" width="444" height="576" /> Configure[/caption]</li>
 	<li>Select the <strong>Power Management</strong> tab and <strong>uncheck</strong> the option<strong> Allow the computer to turn off this device to save power.</strong></li>
 	<li>Click <strong><strong>OK.</strong></strong>

[caption id="attachment_1999" align="aligncenter" width="518"]<img class="size-full wp-image-1999" src="https://windowscrazy.com/wp-content/uploads/2020/06/rundll32_lYQ2qQt12F.png" alt="Uncheck" width="518" height="545" /> Uncheck[/caption]</li>
 	<li>Now, try to <strong>reconnect</strong> your Network.</li>
</ol>
<h2 id="6">Changing the Network Settings:</h2>
If any of the above fixes don't work then try to change the Network Settings.
<ol>
 	<li>Make use of the shortcut <strong>Windows + X</strong> and choose<strong><strong> Command Prompt (Admin).</strong></strong>

[caption id="attachment_2003" align="aligncenter" width="305"]<img class="size-full wp-image-2003" src="https://windowscrazy.com/wp-content/uploads/2020/06/KPFXlJNPoC.png" alt="Menu" width="305" height="528" /> Menu[/caption]</li>
 	<li>Then simply <strong>type</strong> the following commands (one by one) in your Command Prompt window.</li>
 	<li>Press <strong>Enter</strong>.
<pre><code>netsh int tcp set heuristics disabled
netsh int tcp set global autotuninglevel=disabled
netsh int tcp set global rss=enabled</code></pre>
</li>
 	<li>To verify all the <strong>previous</strong> <strong>settings</strong> are disabled, <strong>Copy &amp; Paste</strong> the below command.
<pre><code>netsh int tcp show global</code></pre>
</li>
 	<li>Now, <strong>restart</strong> your PC.</li>
 	<li>Then, try to <strong>reconnect</strong> to your network.</li>
</ol>
<h2 id="7">The Conclusion:</h2>
<div>Hopefully, this article guided you <strong>How to Fix Windows 8.1 Wireless Limited Connectivity. </strong>Clear-cut instructions let you understand the process easily. Don’t forget to share your valuable queries in the below section.</div>