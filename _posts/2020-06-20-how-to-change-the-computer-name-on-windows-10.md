---
ID: 1672
post_title: >
  How to change the Computer name on
  Windows 10?
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1672-how-to-change-the-computer-name-on-windows-10/
published: true
post_date: 2020-06-20 15:13:08
---
<ul class="toc">
 	<li><a href="#1">Change Computer name using Settings on Windows 10</a></li>
 	<li><a href="#2">Change Computer name using Control Panel on Windows 10</a></li>
 	<li><a href="#3">Change Computer name using Command Prompt on Windows 10</a></li>
 	<li><a href="#4">Change Computer name using PowerShell on Windows 10</a></li>
 	<li><a href="#5">Verdict</a></li>
</ul>
<strong><span class="dcap">H</span>ow to change the Computer name on Windows 10?</strong> Name can help you identify your computer when you have <strong>multiple devices</strong> connected to your home network. It's easier to connect with other devices around the house, or even to configure your router to allow or deny access to the internet when you use the descriptive name. <strong>Renaming your Windows 10 PC</strong> isn’t just about personalization, it’s about making things easier.

In this article, we describe<strong> How to change the Computer Name on Windows 10</strong> in some different methods.
<h2 id="1">Change Computer name using Settings on Windows 10:</h2>
Follow the below steps to change the Computer name using Settings on Windows 10 in simple steps.
<ol>
 	<li>Make use of the shortcut <strong>Windows + I</strong> to open <strong>Windows Settings.</strong></li>
 	<li>In the <strong>settings</strong> window, select the <strong>System</strong> option.

[caption id="attachment_181" align="aligncenter" width="1159"]<img class="size-full wp-image-181" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_1-1.png" alt="Settings" width="1159" height="743" /> Settings[/caption]</li>
 	<li>Select <strong>About</strong> option in the left pane.</li>
 	<li>Then, in the right pane click the <strong>Rename this PC</strong> option.

[caption id="attachment_1697" align="aligncenter" width="1103"]<img class="size-full wp-image-1697" src="https://windowscrazy.com/wp-content/uploads/2020/06/ApplicationFrameHost_CaPfhLjZkg.png" alt="Rename PC" width="1103" height="764" /> Rename PC[/caption]</li>
 	<li>Now, type a<strong> new name</strong> for your computer and click <strong>Next</strong>.

[caption id="attachment_1705" align="aligncenter" width="842"]<img class="size-full wp-image-1705" src="https://windowscrazy.com/wp-content/uploads/2020/06/SystemSettingsAdminFlows_RV11GMT27k.png" alt="Name" width="842" height="366" /> Name[/caption]</li>
 	<li>Finally, click the <strong>Restart</strong> button.</li>
 	<li>After the completion of the above steps, the device will restart and then start with the new name.</li>
 	<li>That's all.</li>
</ol>
<h2 id="2">Change Computer name using Control Panel on Windows 10:</h2>
Follow the below steps to change the Computer name using Control Panel on Windows 10 in simple steps.
<ol>
 	<li>Go to the <strong>start menu.</strong></li>
 	<li>Type <strong>Control Panel</strong> in the search column.</li>
 	<li><strong>Tap</strong> it which appears at the top of the start menu.</li>
 	<li>Then in the control panel window, click on<strong><strong> System and Security.</strong></strong>

[caption id="attachment_1698" align="aligncenter" width="1027"]<img class="size-full wp-image-1698" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_1-25.png" alt="System &amp; Security " width="1027" height="614" /> System &amp; Security[/caption]</li>
 	<li>Now, click the <strong>System</strong>.

[caption id="attachment_1699" align="aligncenter" width="1033"]<img class="size-full wp-image-1699" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_2-24.png" alt="System" width="1033" height="613" /> System[/caption]</li>
 	<li>Click the <strong>Change</strong> <strong>settings</strong> option.

[caption id="attachment_1700" align="aligncenter" width="1027"]<img class="size-full wp-image-1700" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_3-22.png" alt="Change" width="1027" height="609" /> Change[/caption]</li>
 	<li>Select the <strong>Computer</strong> <strong>Name</strong> tab in the <strong>System</strong> <strong>Properties</strong> window.</li>
 	<li>Click the <strong>Change</strong> button.

[caption id="attachment_1701" align="aligncenter" width="541"]<img class="size-full wp-image-1701" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_4-17.png" alt="Change" width="541" height="567" /> Change[/caption]</li>
 	<li>Now, type a <strong>new name</strong> for your computer and click<strong><strong> OK.</strong></strong>

[caption id="attachment_1702" align="aligncenter" width="424"]<img class="size-full wp-image-1702" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_5-14.png" alt="Name" width="424" height="471" /> Name[/caption]</li>
 	<li>Click <strong>Close</strong> and<strong> Restart your PC.</strong></li>
 	<li>After completion of the above steps, the computer will reboot, and upon restart and then start with the new name.</li>
 	<li>That's all.</li>
</ol>
<h2 id="3">Change Computer name using Command Prompt on Windows 10:</h2>
Follow the below steps to change the Computer name using Command Prompt on Windows 10 in simple steps.
<ol>
 	<li>Go to the <strong>start menu.</strong></li>
 	<li>Type <strong>Command Prompt</strong> in the search column.</li>
 	<li>Right-click on the Command Prompt and select<strong><strong> Run as Administrator.</strong></strong>

[caption id="attachment_1094" align="aligncenter" width="485"]<img class="size-full wp-image-1094" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_3-4.png" alt="Start Menu" width="485" height="772" /> Start Menu[/caption]</li>
 	<li>In the Command Prompt window, type the following command and press <strong>Enter</strong>.</li>
 	<li>The below command is to <strong><strong>reveal the current device name.</strong></strong>
<pre><code>hostname</code></pre>
</li>
 	<li>To <strong>rename the Windows 10 PC</strong> name copy and paste the below command and press <strong>Enter</strong>.
<pre><code>WMIC computersystem where caption='CURRENT-PC-NAME' rename NEWPCNAME</code></pre>
[caption id="attachment_1703" align="aligncenter" width="1223"]<img class="size-full wp-image-1703" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_6-11.png" alt="Command" width="1223" height="639" /> Command[/caption]</li>
 	<li>Then<strong> to restart the device,</strong> type the following command, and press <strong>Enter</strong>.
<pre><code>shutdown -r -t 00</code></pre>
</li>
 	<li>Once you complete the steps, the changes will apply after restarting the computer.</li>
 	<li>That's all.</li>
</ol>
<h2 id="4">Change Computer name using PowerShell on Windows 10:</h2>
Follow the below steps to change the Computer name using PowerShell on Windows 10 in simple steps.
<ol>
 	<li>Go to the <strong>start menu.</strong></li>
 	<li>Type <strong>PowerShell</strong> in the search column.</li>
 	<li>Right-click on the PowerShell and select <strong><strong>Run as Administrator.</strong></strong>

[caption id="attachment_1211" align="aligncenter" width="480"]<img class="size-full wp-image-1211" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_1-11.png" alt="Start Menu" width="480" height="767" /> Start Menu[/caption]</li>
 	<li>To<strong> reveal the current PC name</strong>, type the following command.</li>
 	<li>Press <strong>Enter</strong>.
<pre><code>Rename-Computer -NewName "NEW-PC-NAME"</code></pre>
[caption id="attachment_1704" align="aligncenter" width="1070"]<img class="size-full wp-image-1704" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_7-12.png" alt="Command" width="1070" height="369" /> Command[/caption]</li>
 	<li>To <strong>restart the device</strong>, copy and paste the below command.</li>
 	<li>Press <strong>Enter</strong>.
<pre><code>Restart-Computer</code></pre>
</li>
 	<li>The computer will restart to apply the changes, after the completion of the above steps.</li>
 	<li>That's all.</li>
</ol>
<h2 id="5">Verdict:</h2>
We hope that this tutorial assisted you in <strong>How to Change the Computer Name on Windows 10</strong> in some different methods. The above four methods are really easy to change the Computer Name on Windows 10 with clear cut screenshots. Kindly share your queries/comments in the below box.