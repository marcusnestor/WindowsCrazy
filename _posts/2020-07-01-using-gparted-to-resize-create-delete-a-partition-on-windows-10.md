---
ID: 2201
post_title: 'Using GParted to Resize, Create &#038; Delete a Partition on Windows 10!!'
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/2201-using-gparted-to-resize-create-delete-a-partition-on-windows-10/
published: true
post_date: 2020-07-01 08:48:17
---
<ul class="toc">
 	<li><a href="#1">Definition for GParted?</a></li>
 	<li><a href="#2">Create a USB bootable media with GParted</a></li>
 	<li><a href="#3">Resize drive partition using GParted</a></li>
 	<li><a href="#4">Create drive partition using GParted</a></li>
 	<li><a href="#5">Delete drive partition using GParted</a></li>
 	<li><a href="#6">Summary</a></li>
</ul>
<strong><span class="dcap">H</span>ow to resize, create &amp; delete drive partition using GParted on Windows 10? </strong>Mostly the<strong> own partition manager</strong> which is offered by <strong>Windows 10</strong> is mainly used. But when to<strong> resize a drive</strong> to create a dual-boot setup, expand an existing partition, create or delete a partition then <strong>GParted</strong> will help you with some tools and options.

In this article, we explain <strong>How to resize, create &amp; delete drive partition using GParted on Windows 10.</strong>
<h2 id="1">Definition for GParted?</h2>
<ul>
 	<li><strong>GParted </strong>is <strong>Linux</strong> based designed to manage <strong>disk partitions.</strong></li>
 	<li>It is a fully-featured tool with<strong> free open source.</strong></li>
 	<li>By using this <strong>tool</strong> you can resize a drive to create a dual-boot setup, expand an existing partition, create or delete a partition.</li>
 	<li>Here, there is <strong>different file systems,</strong> such as ntfs, btrfs, ext2/3/4, f2fs, FAT16/32, hfs/hfs+, linux-swap, luks, lvm2 pv, nilfs2, reiserfs/4, udf, ufs, and xfs.</li>
</ul>
<h2 id="2">Create a USB bootable media with GParted:</h2>
<ol>
 	<li>First, c<strong>onnect a USB flash drive with at least 2GB of space</strong> to your device, to create a GParted bootable media.</li>
 	<li>Now, Download <a href="https://sourceforge.net/projects/tuxboot/files/0.8/Windows/"><strong>tuxboot</strong> </a>here.</li>
 	<li>Then, double-click the <strong>.exe file.</strong></li>
 	<li>Click <strong>Yes</strong>.</li>
 	<li>Then select the<strong> On-Line Distribution</strong> option and using the drop-down arrow and <strong>select</strong> the <strong>gparted-live-stable</strong> option.</li>
 	<li>In the same window, at the bottom click the drop-down arrow of <strong>Type</strong> and <strong>select</strong> the<strong> USB Drive</strong> option.</li>
 	<li>Then click the drop-down arrow of <strong>Drive</strong> and <strong>select</strong> the<strong> flash drive.</strong></li>
 	<li>Finally, click <strong>OK</strong>.

[caption id="attachment_2202" align="aligncenter" width="655"]<img class="size-full wp-image-2202" src="https://windowscrazy.com/wp-content/uploads/2020/07/sATgXxHgLY.png" alt="Tuxboot tool" width="655" height="441" /> Tuxboot[/caption]</li>
 	<li>Now, <strong>tuxboot</strong> will create a bootable media with the GParted files.</li>
</ol>
<h2 id="3">Resize drive partition using GParted:</h2>
<ol>
 	<li>To resiz<strong>e connect the USB flash drive</strong> with GParted to your device.</li>
 	<li>Now, start your <strong>PC with the GParted USB drive. </strong></li>
 	<li>Click the <strong>GParted Live (Default settings)</strong> option.</li>
 	<li>Then Press <strong>Enter</strong>.

[caption id="attachment_2203" align="aligncenter" width="742"]<img class="size-full wp-image-2203" src="https://windowscrazy.com/wp-content/uploads/2020/07/1IYZfRQETl.png" alt="Start GParted" width="742" height="285" /> GParted[/caption]</li>
 	<li>In the next window, select the <strong>Don’t touch keymap</strong> option and press <strong>Enter</strong>.

[caption id="attachment_2204" align="aligncenter" width="720"]<img class="size-full wp-image-2204" src="https://windowscrazy.com/wp-content/uploads/2020/07/chrome_MoXmN0Bj89.png" alt="GParted keymap settings" width="720" height="465" /> Keymap settings[/caption]</li>
 	<li>Now, in the next window asks you to <strong>select your language.</strong></li>
 	<li>Press <strong>0</strong> to enter the graphical environment and press <strong>Enter</strong>.

[caption id="attachment_2205" align="aligncenter" width="983"]<img class="size-full wp-image-2205" src="https://windowscrazy.com/wp-content/uploads/2020/07/chrome_wW006GlRs0.png" alt="Language" width="983" height="686" /> Language[/caption]</li>
 	<li>Then, in the top right corner click the drop-down arrow and <strong>select the drive</strong> that you want to resize.

[caption id="attachment_2211" align="aligncenter" width="1082"]<img class="size-full wp-image-2211" src="https://windowscrazy.com/wp-content/uploads/2020/07/ShareX_rcY2B5Rv1c.png" alt="Select Drive" width="1082" height="420" /> Select Drive[/caption]</li>
 	<li>Click the<strong> Resize/Move</strong> to select the partition that you want to shrink or extend.</li>
 	<li>You can also use the slider at the top to set the new parameters.</li>
 	<li>Now, select the <strong>new</strong> <strong>size</strong> for the existing partition and click the <strong><strong><strong><strong>Resize/Move.</strong></strong></strong></strong>

[caption id="attachment_2218" align="aligncenter" width="1079"]<img class="size-full wp-image-2218" src="https://windowscrazy.com/wp-content/uploads/2020/07/ShareX_LmjauCoEX3.png" alt="Resize/Move" width="1079" height="623" /> Resize/Move[/caption]</li>
 	<li>In the top click the <strong>Apply</strong> option.

[caption id="attachment_2209" align="aligncenter" width="1080"]<img class="size-full wp-image-2209" src="https://windowscrazy.com/wp-content/uploads/2020/07/ShareX_m9BGDmO6fH.png" alt="Apply" width="1080" height="387" /> Apply[/caption]</li>
 	<li>Finally, click <strong>Yes</strong> to confirm the changes and click <strong>Close</strong>.</li>
 	<li>That's all.</li>
</ol>
<h2 id="4">Create a drive partition using GParted:</h2>
<ol>
 	<li><strong>Repeat</strong> the same steps from <strong>2-7</strong> which are explained in the<strong> resize drive partition.</strong></li>
 	<li>Now, select the<strong> Unallocated space</strong> on the empty drive, and in the top left corner click the <strong>New</strong> option.

[caption id="attachment_2219" align="aligncenter" width="1085"]<img class="size-full wp-image-2219" src="https://windowscrazy.com/wp-content/uploads/2020/07/ShareX_WOv36CrhOI.png" alt="Unallocated" width="1085" height="391" /> Unallocated[/caption]</li>
 	<li>Create a new partition window, using the drop-down arrow change the <strong>File System to ntfs.</strong></li>
 	<li>In the same window, type a name for the drive on the <strong>Label</strong> tab.</li>
 	<li>Then use the <strong>default</strong> selection for the rest of the settings.</li>
 	<li>Now, click the <strong>Add</strong> button.

[caption id="attachment_2220" align="aligncenter" width="1081"]<img class="size-full wp-image-2220" src="https://windowscrazy.com/wp-content/uploads/2020/07/ShareX_T0E7B32E78.png" alt="NTFS" width="1081" height="599" /> NTFS[/caption]</li>
 	<li>In the top click the <strong>Apply</strong> option.</li>
 	<li>Finally, click <strong>Yes</strong> to confirm the changes and click <strong>Close</strong>.</li>
 	<li>That's all.</li>
</ol>
<h2 id="5">Delete drive partition using GParted:</h2>
<ol>
 	<li><strong>Repeat</strong> the same steps from<strong> 2-8</strong> which are explained in the<strong> resize drive partition.</strong></li>
 	<li>Then,<strong> select the partition</strong> that you want to delete, and click the <strong>Delete</strong> button.

[caption id="attachment_2221" align="aligncenter" width="1083"]<img class="size-full wp-image-2221" src="https://windowscrazy.com/wp-content/uploads/2020/07/ShareX_K3Nnf6Sj4h.png" alt="Delete" width="1083" height="394" /> Delete[/caption]</li>
 	<li>In the top click the <strong>Apply</strong> option.</li>
 	<li>Again click <strong>Apply</strong> to confirm the changes and click <strong>Close</strong>.</li>
 	<li>That's all.</li>
</ol>
<h2 id="6">Summary:</h2>
Probably, the above information helped you a lot to understand <strong>How to resize, create &amp; delete drive partition using GParted on Windows 10.</strong> Don’t forget to share your <strong>comments</strong> in the below section and leave your <strong>worthwhile</strong> <strong>feedback</strong>.