---
ID: 189
post_title: >
  How to delete win log files in windows
  10?
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/189-how-to-delete-win-log-files-in-windows-10/
published: true
post_date: 2020-05-23 07:00:59
---
<ul class="toc">
 	<li><a href="#1">Delete Log Files on Windows 10</a></li>
 	<li><a href="#2">Verdict</a></li>
</ul>
<strong><strong><strong><span class="dcap">R</span><strong>emove log files on Windows 10</strong>: </strong></strong></strong>Windows filling up the spaces by saving unwanted files, apps, etc., To remove the log files in windows 10.

This article will illustrate some simple different <strong>ways to delete the log files in Windows 10.</strong>
<h2 id="1"><strong>Delete Log Files on Windows 10:</strong></h2>
There are <strong>three different ways</strong> to delete the log files, just follow the steps.
<h3>Way 1: <span id="Method_3_Use_The_Event_Viewer_GUI"><strong>Use The Event Viewer</strong></span></h3>
<ol>
 	<li>Open a <strong>Run</strong> <strong>command dialog box</strong> using the shortcut key <strong>Windows + R.</strong></li>
 	<li>Type <strong>eventvwr.msc</strong> in the given space box of Open and click<strong><strong> OK.</strong></strong>

[caption id="attachment_230" align="aligncenter" width="513"]<img class="wp-image-230 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_1-2.png" alt="Run command dialog box" width="513" height="336" /> A run command dialog box[/caption]</li>
 	<li>The <strong>Event Viewer window</strong> gets appears on the desktop.</li>
 	<li>From the left pane, select the <strong><strong>Windows Logs.</strong></strong>

[caption id="attachment_231" align="aligncenter" width="1137"]<img class="wp-image-231 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_2-2.png" alt="Event Viewer" width="1137" height="716" /> Event Viewer[/caption]</li>
 	<li>Click the dropdown arrow of <strong>Windows Logs</strong> and Choose <strong>Applications</strong> option.

[caption id="attachment_232" align="aligncenter" width="1110"]<img class="wp-image-232 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_3-2.png" alt="Dropdown arrow" width="1110" height="749" /> Dropdown arrow[/caption]</li>
 	<li><strong>Select</strong> the <strong>events</strong> that you want to <strong>delete</strong> and then click the <strong>clear log option.</strong></li>
 	<li>Refer to the screenshot to find out a<strong><strong> clear log option.</strong></strong>

[caption id="attachment_233" align="aligncenter" width="1101"]<img class="wp-image-233 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_4-2.png" alt="Clear log" width="1101" height="763" /> Clear log[/caption]</li>
 	<li>Finally, select the option in which way you want to clear the selected events.

[caption id="attachment_234" align="aligncenter" width="725"]<img class="wp-image-234 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_5-2.png" alt="Final" width="725" height="155" /> Final[/caption]</li>
 	<li>Repeat this for all the <strong>entries</strong> that you wish to <strong>delete</strong>.</li>
</ol>
<h3>Way 2: <span id="Method_3_Use_The_Event_Viewer_GUI"><strong>Use Command Prompt</strong></span></h3>
<ul>
 	<li>Go to <strong>Start menu</strong> and type <strong>Command Prompt</strong> in the<strong> Search column.</strong></li>
 	<li>Select the<strong> Command Prompt</strong> which appears on the top of the<strong><strong> start menu.</strong></strong></li>
</ul>
[caption id="attachment_235" align="aligncenter" width="492"]<img class="wp-image-235 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_6-1.png" alt="Command prompt" width="492" height="778" /> Command prompt[/caption]
<ul>
 	<li>There are different manners of <strong>deleting log files,</strong> simply<strong> copy and paste the below command one by one</strong> in the command prompt.</li>
 	<li><strong>To clear all the win log files,</strong> copy and paste the below command and press Enter.</li>
</ul>
<code>del *.log /a /s /q /f</code>

[caption id="attachment_236" align="aligncenter" width="1192"]<img class="wp-image-236 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_7-1.png" alt="To clear all the win log files" width="1192" height="687" /> To clear all the win log files[/caption]
<ul>
 	<li><strong>To list the log files,</strong> copy and paste the below command and press Enter.</li>
</ul>
<code>wevtutil el</code>

[caption id="attachment_237" align="aligncenter" width="1050"]<img class="wp-image-237 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_8-1.png" alt="To list the log files" width="1050" height="689" /> To list the log files[/caption]
<ul>
 	<li>From the list that appears, if you find a certain <strong>log file that you wish to delete,</strong> then use the below command in the same way of using the above commands.</li>
</ul>
<code>wevtutil cl &lt;name of the log&gt;</code>

[caption id="attachment_239" align="aligncenter" width="1178"]<img class="wp-image-239 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_9-1.png" alt="Clear individual log files" width="1178" height="688" /> Clear individual log files[/caption]
<h3>Way 3: <span id="Method_3_Use_The_Event_Viewer_GUI"><strong>Use Powershell</strong></span></h3>
<ul>
 	<li>In the <strong>Start menu,</strong> type as <strong>PowerShell</strong> in the search column.</li>
 	<li>Click on the <strong>PowerShell</strong> which appears at the top of the Start Menu.</li>
</ul>
[caption id="attachment_241" align="aligncenter" width="489"]<img class="wp-image-241 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_11.png" alt="PowerShell" width="489" height="768" /> PowerShell[/caption]
<ul>
 	<li>Simply,<strong> copy and paste</strong> the below-mentioned command in the<strong> PowerShell.</strong></li>
</ul>
<code>wevtutil el | Foreach-Object {wevtutil cl “$_”}</code>

[caption id="attachment_240" align="aligncenter" width="1189"]<img class="wp-image-240 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_10.png" alt=" Clear all the event logs" width="1189" height="420" /> Clear all the event logs[/caption]
<ul>
 	<li>This will <strong>clear</strong> all the<strong> event logs in Windows 10.</strong></li>
</ul>
<h2 id="2">Verdict:</h2>
Hoping that the above article will help you to<strong> delete win log files</strong> <strong>in Windows 10</strong><strong>.</strong> If you have any <strong>doubts,</strong> please kindly share in the below <strong>comment section</strong> and leave your <strong>valuable feedback.</strong>