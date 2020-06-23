---
ID: 1784
post_title: '{3 Easy Ways} to Stop Sharing a Folder in Windows 10!!'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1784-3-easy-ways-to-stop-sharing-a-folder-in-windows-10/
published: true
post_date: 2020-06-23 07:45:07
---
<ul class="toc">
 	<li><a href="#1">Stop Sharing a Folder - Using Computer Management</a></li>
 	<li><a href="#2">Stop Sharing a Folder via Command Prompt</a></li>
 	<li><a href="#3">Use File Explorer to Stop Sharing a Folder</a></li>
 	<li><a href="#4">A Short Synopsis</a></li>
</ul>
<span class="dcap">S</span><strong>top Sharing Folder in Windows 10</strong>: Sharing a folder over the network in Windows 10 is considered to be a well-known approach to share files or folders with other users. This is quite easy rather than sharing files via USB flash drive or emails.

Although, there comes a time where you want to stop sharing a folder. You can disable the shared access so that the users in your local network can't access those shared files anymore. We come up with three quick and easy ways that let you <strong>Stop Sharing a Folder in Windows 10</strong> efficiently.
<h2 id="1">1) Stop Sharing a Folder - Using Computer Management:</h2>
<ol>
 	<li>Press <strong>Windows key + S</strong> to open the Taskbar search.</li>
 	<li>In the search box, you have to type '<strong>computer management</strong>' and hit <strong>Enter</strong>.

[caption id="attachment_1790" align="alignnone" width="1319"]<img class="size-full wp-image-1790" src="https://windowscrazy.com/wp-content/uploads/2020/06/ss1.png" alt="Computer Management" width="1319" height="884" /> Computer Management[/caption]</li>
 	<li>It will open the <strong>Computer Management</strong> window.</li>
 	<li>On the left pane, you will see many options and you just click the <strong>Shared Folders.</strong></li>
 	<li>Next, you have to move along the right and select <strong>Shares</strong> item.

[caption id="attachment_1791" align="alignnone" width="1340"]<img class="size-full wp-image-1791" src="https://windowscrazy.com/wp-content/uploads/2020/06/ss2.png" alt="Shared Folders and Shares" width="1340" height="809" /> Shared Folders and Shares[/caption]</li>
 	<li>Now, you have to right-click on the folder that you don't want to share and choose <strong>Stop Sharing</strong> option.</li>
 	<li>A message box will pop-up that will ask you to confirm the action, click on the <strong>Yes</strong> button to remove this folder from the sharing folder option.</li>
 	<li>That's it. The folder will no longer be available to access by other users on the network.</li>
</ol>
<h2 id="2">2) Stop Sharing a Folder via Command Prompt:</h2>
Follow the below simple steps to stop sharing a folder.
<ol>
 	<li>Go to the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type '<strong>command prompt</strong>' and then right-click on the top result and choose <strong>Run as administrator</strong>.

[caption id="attachment_1751" align="alignnone" width="1319"]<img class="size-full wp-image-1751" src="https://windowscrazy.com/wp-content/uploads/2020/06/rd1.png" alt="Command Prompt" width="1319" height="881" /> Command Prompt[/caption]</li>
 	<li>After that, you have to run the below command and hit <strong>Enter </strong>to view all the shared folders on your system. <code>net share</code>

[caption id="attachment_1792" align="alignnone" width="1045"]<img class="size-full wp-image-1792" src="https://windowscrazy.com/wp-content/uploads/2020/06/ss3.png" alt="net share" width="1045" height="658" /> net share[/caption]</li>
 	<li>Note down the folder name that you wish to stop sharing.</li>
 	<li>Now, run the below command and hit <strong>Enter</strong> to stop sharing a certain folder. <code>net share SHAREDFOLDERNAME /delete</code></li>
 	<li>Replace SHAREDFOLDERNAME with your folder name that you want to stop sharing.

[caption id="attachment_1793" align="alignnone" width="1100"]<img class="size-full wp-image-1793" src="https://windowscrazy.com/wp-content/uploads/2020/06/ss4.png" alt="Command to stop sharing a folder" width="1100" height="618" /> Command to stop sharing a folder[/caption]</li>
</ol>
<h2 id="3">3) Use File Explorer to Stop Sharing a Folder:</h2>
If you know the name of the shared folder and its location, you can prefer this method.
<ol>
 	<li>Click the <strong>File Explorer</strong> on the Taskbar.</li>
 	<li>After that, you have to browse to the folder that you wish to stop sharing over the network.</li>
 	<li>Right-click on that folder and navigate to <strong>Properties</strong>.

[caption id="attachment_1794" align="alignnone" width="1251"]<img class="size-full wp-image-1794" src="https://windowscrazy.com/wp-content/uploads/2020/06/ss5.png" alt="Properties" width="1251" height="975" /> Properties[/caption]</li>
 	<li>You have to click the <strong>Sharing</strong> tab and then tap on the <strong>Advanced Sharing</strong> button.

[caption id="attachment_1795" align="alignnone" width="599"]<img class="size-full wp-image-1795" src="https://windowscrazy.com/wp-content/uploads/2020/06/ss6.png" alt="Advanced Sharing" width="599" height="779" /> Advanced Sharing[/caption]</li>
 	<li>Next, you have to uncheck the box '<strong>Share this folder</strong>' and then click <strong>Apply</strong> and <strong>OK</strong>.

[caption id="attachment_1796" align="alignnone" width="529"]<img class="size-full wp-image-1796" src="https://windowscrazy.com/wp-content/uploads/2020/06/ss7.png" alt="Uncheck the Share this folder" width="529" height="546" /> Uncheck the Share this folder[/caption]</li>
</ol>
<h2 id="4">A Short Synopsis:</h2>
As you can see, the three ways explained in this tutorial helped you to <strong>Stop Sharing a Folder</strong> <strong>in Windows 10</strong> simply. You can follow any one of the ways and disable file sharing in your system. Kindly share your <strong>comments/feedback</strong> in the below section. We appreciate your presence in <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.