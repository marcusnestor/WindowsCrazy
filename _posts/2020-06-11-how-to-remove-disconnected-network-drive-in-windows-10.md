---
ID: 1242
post_title: >
  How to Remove Disconnected Network Drive
  in Windows 10?
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1242-how-to-remove-disconnected-network-drive-in-windows-10/
published: true
post_date: 2020-06-11 04:32:56
---
<ul class="toc">
 	<li><a href="#1">Disconnect Mapped Network Drive - Using File Explorer</a></li>
 	<li><a href="#2">Delete Mapped Network Drive via Command Prompt</a></li>
 	<li><a href="#3">Delete Mapped Network Drive - Using Registry Editor</a></li>
 	<li><a href="#4">Closure</a></li>
</ul>
<span class="dcap">R</span><strong>emove Disconnected Network Drive in Windows 10</strong>: Mapped drives are ideal especially for organizations or institutions that hold files or documents on the server. Once a drive is mapped, you will be able to read or write files from the shared resource or storage.

But, there comes a time where you want to delete or disconnect the mapped drives that you no longer need it. In this article, you will learn how to <strong>Remove Disconnected Network Drive in Windows 10</strong>.
<h2 id="1">Disconnect Mapped Network Drive - Using File Explorer:</h2>
<ol>
 	<li>Click on the <strong>File Explorer</strong> in the <strong>Taskbar</strong>.

[caption id="attachment_1248" align="alignnone" width="627"]<img class="size-full wp-image-1248" src="https://windowscrazy.com/wp-content/uploads/2020/06/dm2.png" alt="File Explorer" width="627" height="249" /> File Explorer[/caption]</li>
 	<li>Then, in the left pane, you have to click on <strong>This PC</strong>.</li>
 	<li>Look at the 'Network locations' section for mapped drives.</li>
 	<li>You have to right-click on the mapped drive and choose the <strong>Disconnect</strong> option.</li>
</ol>
Once you do the above, the mapped network drives will disappear and stop showing on your system.
<h2 id="2">Delete Mapped Network Drive via Command Prompt:</h2>
<ol>
 	<li>Press the <strong>Windows key </strong>on your keyboard to open the <strong>Start</strong> menu. [You can also click the Windows logo in the bottom left corner of your screen]</li>
 	<li>Now, the start menu will open with a cursor in the search box and type <strong>'cmd'</strong> into the search field.

[caption id="attachment_452" align="alignnone" width="888"]<img class="size-full wp-image-452" src="https://windowscrazy.com/wp-content/uploads/2020/05/up1.png" alt="Search for Command Prompt" width="888" height="680" /> Search for Command Prompt[/caption]</li>
 	<li>Right-click on the top result so it will invoke a drop-down menu and then choose <strong>Run as administrator</strong> option so it will open the command prompt with admin privileges.

[caption id="attachment_453" align="alignnone" width="888"]<img class="size-full wp-image-453" src="https://windowscrazy.com/wp-content/uploads/2020/05/up2.png" alt="Run as administrator" width="888" height="680" /> Run as administrator[/caption]</li>
 	<li>You have to press <strong>'Yes'</strong> in order to confirm this choice when prompted.</li>
 	<li>Type the below command and hit <strong>Enter</strong> to delete the mapped network drive. <code>net use g: /delete</code>

[caption id="attachment_1247" align="alignnone" width="731"]<img class="size-full wp-image-1247" src="https://windowscrazy.com/wp-content/uploads/2020/06/dm1.png" alt="Delete Mapped Drive" width="731" height="413" /> Delete Mapped Drive[/caption]</li>
 	<li>In the above command, you can replace 'g' with the drive letter of your mapped drive.</li>
 	<li>Now, you have to restart your computer.</li>
</ol>
<h2 id="3">Delete Mapped Network Drive - Using Registry Editor:</h2>
<ol>
 	<li>Press <strong>Windows key + R</strong> to open the Run box.</li>
 	<li>Now, you have to type <strong>'regedit' </strong>and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press Yes) <code>regedit</code>

[caption id="attachment_418" align="alignnone" width="428"]<img class="size-full wp-image-418" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi1.png" alt="Regedit" width="428" height="232" /> Regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>. In the left pane, you have to navigate to the following path. <code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\MountPoints2</code></li>
 	<li>Now, you have to right-click on the mapped drive and choose the <strong>Delete</strong> option.</li>
 	<li>Then, you have to click the <strong>Yes</strong> button.</li>
 	<li>After that, navigate to this path.<code>HKEY_CURRENT_USER\Network</code></li>
 	<li>Next, you have to right-click on the network share that refers to the mapped drive and choose the <strong>Delete</strong> option.</li>
 	<li>You have to click the <strong>Yes</strong> button.</li>
 	<li>At last, restart your system.</li>
</ol>
<h2 id="4">Closure:</h2>
We hope that this tutorial guided you with simple ways to <strong>Remove Disconnected Network Drive in Windows 10</strong>. You can follow any one of the ways to disconnect the mapped network drive quickly. If you find this article helpful, kindly share your valuable <strong>comments</strong> in the below section. Thanks for visiting <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.