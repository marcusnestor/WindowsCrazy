---
ID: 1337
post_title: '[Quickly] How to Use Robocopy to Transfer Files on Windows 10?'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1337-quickly-how-to-use-robocopy-to-transfer-files-on-windows-10/
published: true
post_date: 2020-06-15 03:00:48
---
<ul class="toc">
 	<li><a href="#1">Robocopy - Help Syntax</a></li>
 	<li><a href="#2">Configuring File Sharing</a></li>
 	<li><a href="#3">Using Robocopy to Copy Files</a></li>
 	<li><a href="#4">Verdict</a></li>
</ul>
<span class="dcap">R</span><strong>obocopy on Windows 10</strong>: <strong>Robocopy (Robust File Copy)</strong> is one of the most used command-line tools to copy large volumes of data in Windows 10. It allows you to copy or transfer files and folders from one place to another effectively in one go.

In addition, you can also sync the folder's destinations. If you want to copy more files or folders faster, then you have to make use of this Windows utility. In this tutorial, you will learn the steps to <strong>Use Robocopy to Transfer Files on Windows 10</strong> PC so you can copy files quickly.
<h2 id="1">Robocopy - Help Syntax:</h2>
There are a lot of options to copy or move files using robocopy. Each individual section comes up with several options. If you want to view all sorts of options, then you want to run the help command of robocopy.
<ul>
 	<li>Copy and paste the below help command to view more useful information.</li>
 	<li><code>robocopy /?</code>

[caption id="attachment_1344" align="alignnone" width="870"]<img class="size-full wp-image-1344" src="https://windowscrazy.com/wp-content/uploads/2020/06/ro1.png" alt="Robocopy - Help" width="870" height="485" /> Robocopy - Help[/caption]</li>
</ul>
<h2 id="2">Configure File Sharing:</h2>
First and foremost, we have to enable <strong><a href="https://windowscrazy.com/207-get-started-with-file-sharing-in-windows-10-simple-guide/">file sharing</a></strong> in order to copy files between the two systems.
<ol>
 	<li>You have to open the <strong>File Explorer</strong> and choose any folder that you want to share.</li>
 	<li>Then, right-click on the selected folder and navigate to <strong>Properties</strong> option.

[caption id="attachment_1345" align="alignnone" width="964"]<img class="size-full wp-image-1345" src="https://windowscrazy.com/wp-content/uploads/2020/06/ro2.png" alt="Properties" width="964" height="726" /> Properties[/caption]</li>
 	<li>Now, you have to click on the <strong>Sharing</strong> tab. Choose the <strong>Share</strong> button and it will open the <strong>Network access</strong> window.

[caption id="attachment_1346" align="alignnone" width="959"]<img class="size-full wp-image-1346" src="https://windowscrazy.com/wp-content/uploads/2020/06/ro3.png" alt="Share" width="959" height="624" /> Share[/caption]</li>
 	<li>Make use of the drop-down menu to <strong>choose the user or group</strong> to share a file or folder. You can also create a new user. Here, we have selected <strong>Everyone</strong>.</li>
 	<li>After that, click on the <strong>Add</strong> button.

[caption id="attachment_1347" align="alignnone" width="968"]<img class="size-full wp-image-1347" src="https://windowscrazy.com/wp-content/uploads/2020/06/ro4.png" alt="Add" width="968" height="622" /> Add[/caption]</li>
 	<li>Then, you have to select the type of sharing permissions under the <strong>Permission Level</strong>. By default, it will be in <strong>'</strong><strong>Read' </strong>mode so if you wish you can leave as it is or else you can choose <strong>'Read/Write'</strong>.</li>
 	<li>Tap on the <strong>Share</strong> button.

[caption id="attachment_1348" align="alignnone" width="973"]<img class="size-full wp-image-1348" src="https://windowscrazy.com/wp-content/uploads/2020/06/ro5.png" alt="Share" width="973" height="621" /> Share[/caption]</li>
 	<li>You have to note the network path as other users will get access to your shared file over the network in that path.</li>
 	<li>Once you make sure about it, you can click the <strong>Done</strong> button. You can also copy and paste links of this shared file into another app and even you can email it.

[caption id="attachment_1349" align="alignnone" width="980"]<img class="size-full wp-image-1349" src="https://windowscrazy.com/wp-content/uploads/2020/06/ro6.png" alt="Network Path" width="980" height="622" /> Network Path[/caption]</li>
 	<li>At last, you have to click the <strong>Close</strong> button.</li>
</ol>
<h2 id="3">Using Robocopy to Copy Files:</h2>
Just follow the below steps once the file-sharing is configured.
<ul>
 	<li>Press the <strong>Windows key </strong>on your keyboard to open the <strong>Start</strong> menu. [You can also click the Windows logo in the bottom left corner of your screen]</li>
 	<li>Now, the start menu will open with a cursor in the search box and type <strong>'cmd'</strong> into the search field.

[caption id="attachment_452" align="alignnone" width="888"]<img class="size-full wp-image-452" src="https://windowscrazy.com/wp-content/uploads/2020/05/up1.png" alt="Search for Command Prompt" width="888" height="680" /> Search for Command Prompt[/caption]</li>
 	<li>Right-click on the top result so it will invoke a drop-down menu and then choose <strong>Run as administrator</strong> option so it will open the command prompt with admin privileges.

[caption id="attachment_453" align="alignnone" width="888"]<img class="size-full wp-image-453" src="https://windowscrazy.com/wp-content/uploads/2020/05/up2.png" alt="Run as administrator" width="888" height="680" /> Run as administrator[/caption]</li>
 	<li>You have to press <strong>'Yes'</strong> in order to confirm the action when prompted.</li>
 	<li>Refer to the below syntax to copy the files over the network.</li>
</ul>
<code>robocopy source-path destination-path /E /Z /ZB /R:5 /W:5 /TBD /NP /V /MT:16</code>
<ul>
 	<li>Example: <code>robocopy C:\Users\Robocopy C:\Users\Public /E /Z /ZB /R:5 /W:5 /TBD /NP /V /MT:16</code>

[caption id="attachment_1350" align="alignnone" width="1023"]<img class="size-full wp-image-1350" src="https://windowscrazy.com/wp-content/uploads/2020/06/ro7.png" alt="Copying Files" width="1023" height="553" /> Copying Files[/caption]</li>
 	<li>In the above command, you just change the source and destination paths and run it.</li>
</ul>
<h2 id="4">Verdict:</h2>
In this guide, we outlined the essential steps to <strong>Use Robocopy to Transfer Files on Windows 10. </strong>First, enable the file sharing and then copy or transfer files from one location to another quickly using the robocopy utility. Don't forget to share your <strong>valuable comments</strong> in the below section. Thanks for visiting <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.