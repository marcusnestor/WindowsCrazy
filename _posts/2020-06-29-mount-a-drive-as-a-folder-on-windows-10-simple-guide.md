---
ID: 2079
post_title: 'Mount a Drive as a Folder on Windows 10!! [Simple Guide]'
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/2079-mount-a-drive-as-a-folder-on-windows-10-simple-guide/
published: true
post_date: 2020-06-29 13:02:34
---
<ul class="toc">
 	<li><a href="#1">By using Computer Management</a></li>
 	<li><a href="#2">By using Command Prompt</a></li>
 	<li><a href="#3">Summary</a></li>
</ul>
<strong><span class="dcap">H</span>ow to mount a drive as a folder on Windows 10? </strong>When you <strong>add more drives to the network, </strong>this adds up can confuse you. To get rid of this problem you can <strong>mount a drive to a folder path</strong>. A <strong>single drive</strong> with mount points to <strong>other drives</strong> can make it easier to<strong> host your content.</strong>

In this article, we discuss <strong>How to mount a drive as a folder on Windows 10</strong> in different ways.
<h2 id="1">By using Computer Management:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + E</strong> to open the <strong>File Explorer.</strong></li>
 	<li>Then <strong>locate</strong> a folder location you want the mount-points to appear.</li>
 	<li><strong>Create</strong> a new folder with as per any descriptive name.</li>
 	<li>Now,<strong> double click</strong> the created folder and create a folder for each hard drive you want to mount.</li>
 	<li>Press <strong>Windows + X</strong> to open <strong>Power Menu</strong> and click <strong><strong>Computer Management.</strong></strong>

[caption id="attachment_2096" align="aligncenter" width="301"]<img class="size-full wp-image-2096" src="https://windowscrazy.com/wp-content/uploads/2020/06/explorer_bU3CYdokQJ.png" alt="Power Menu" width="301" height="531" /> Power Menu[/caption]</li>
 	<li>In the left pane, select the <strong>Disk Management</strong> option.</li>
 	<li>Now, <strong>right-click</strong> on the drive that you want to <strong>mount</strong> to a folder path.</li>
 	<li>Then, select <strong>Change Drive Letter and Paths</strong> option.

[caption id="attachment_2093" align="aligncenter" width="758"]<img class="size-full wp-image-2093" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_C0kbkhdHfs.png" alt="Disk Management" width="758" height="484" /> Disk Management[/caption]</li>
 	<li>In the next window, click the <strong>Add</strong> button.

[caption id="attachment_2092" align="aligncenter" width="482"]<img class="size-full wp-image-2092" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_NrX2uL09oS.png" alt="Add" width="482" height="313" /> Add[/caption]</li>
 	<li>Now, select the <strong>Mount in the following empty NTFS folder</strong> option.</li>
 	<li>Click the <strong>Browse</strong> and locate the folder you have created to work as a mount point.

[caption id="attachment_2091" align="aligncenter" width="478"]<img class="size-full wp-image-2091" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_vUbZfXuD0S.png" alt="Browse" width="478" height="238" /> Browse[/caption]</li>
 	<li>Finally, click <strong>OK.</strong></li>
</ol>
<h2 id="2">By using Command Prompt:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + E</strong> to open the<strong> File Explorer.</strong></li>
 	<li>Then <strong>locate</strong> a folder <strong>location</strong> you want the <strong>mount-points</strong> to appear.</li>
 	<li>Create a <strong>new</strong> <strong>folder</strong> with as per any descriptive name.</li>
 	<li>Go to the <strong>start</strong> menu.</li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li><strong>Right-click</strong> on the Command Prompt and select <strong>Run as Administrator</strong> option.

[caption id="attachment_1094" align="aligncenter" width="485"]<img class="size-full wp-image-1094" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_3-4.png" alt="Start Menu" width="485" height="772" /> Start Menu[/caption]</li>
 	<li>To <strong>run DiskPart, </strong>copy and paste the below command and press <strong>Enter</strong>.
<pre><code>diskpart</code></pre>
</li>
 	<li>To<strong> list all the volume</strong> in your computer, then <strong>type</strong> the following command.</li>
 	<li>Press <strong>Enter</strong>.
<pre><code>list volume</code></pre>
</li>
 	<li>To make sure of <strong>selecting the drive</strong> you want to assign to a folder path.</li>
 	<li><strong>Copy and paste</strong> the below command and press Enter.
<pre><code>select volume 4</code></pre>
</li>
 	<li>In the command, remember to<strong> replace 4 with the number for the drive</strong> you want to mount.</li>
 	<li>To <strong>mount</strong> <strong>a</strong> <strong>drive</strong> as a folder, simply <strong>type</strong> the following command and press <strong>Enter</strong>.
<pre><code>assign mount=C:\mountpoint</code></pre>
</li>
 	<li>Now, you can<strong> visible all the content</strong> of the new drive inside the <strong>mounted</strong> folder.

[caption id="attachment_2094" align="aligncenter" width="836"]<img class="size-full wp-image-2094" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_XOXW9vk74i.png" alt="Command " width="836" height="421" /> Command[/caption]</li>
 	<li>That's all.</li>
</ol>
<strong>Image Source:</strong> <em>pureinfotech.com</em>
<h2 id="3">Summary:</h2>
In the above tutorial, you have learned <strong>How to mount a drive as a folder on Windows 10.</strong> Share your valuable <strong>comments</strong> in the below section and drop your <strong>feedback</strong>.
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://windowscrazy.com/1337-quickly-how-to-use-robocopy-to-transfer-files-on-windows-10/" rel="nofollow">How to Use Robocopy to Transfer Files on Windows 10?</a></li>
 	<li><a href="https://windowscrazy.com/641-how-to-disable-hardware-acceleration-in-google-chrome/" rel="nofollow">Disable Hardware Acceleration in Google Chrome</a></li>
 	<li><a href="https://windowscrazy.com/1567-set-up-a-new-pc-with-a-fresh-copy-of-windows-10/" rel="nofollow">Set Up a New PC with a Fresh Copy of Windows 10</a></li>
</ul>