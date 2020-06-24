---
ID: 1675
post_title: >
  How to Install Plex Media Server on
  FreeNAS?
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1675-how-to-install-plex-media-server-on-freenas/
published: true
post_date: 2020-06-20 15:12:53
---
<ul class="toc">
 	<li><a href="#1">Install Plex Media Server on FreeNAS</a></li>
 	<li><a href="#2">Closure</a></li>
</ul>
<strong><span class="dcap">H</span>ow to install Plex Media Server on FreeNAS? </strong>It is the <strong>best media server application</strong> designed to organize and stream videos, music, and pictures. Set up a plugin to convert the file server into a <strong>media streaming service</strong> for your home. It designed for any<strong> Windows 10, macOS, and Linux</strong> machines as well as other devices, such as Xbox One, smart TVs, streaming boxes, mobile devices using the Plex client or web application.

In this article, we explain <strong>How to install Plex Media Server on FreeNAS</strong> in simple steps.
<h2 id="1">Install Plex Media Server on FreeNAS:</h2>
Just follow the below process!!
<ol>
 	<li><a href="#3"><strong>Installing Plex plugin</strong></a></li>
 	<li><a href="#4"><strong>Configuring Plex media storage</strong></a></li>
 	<li><a href="#5"><strong>Initial Plex setup</strong></a></li>
</ol>
<h2 id="3">Installing Plex plugin:</h2>
<ul>
 	<li>First, Open <strong>FreeNAS</strong> in your web browser.</li>
 	<li>Then,<strong> Sign in</strong> to your root account.</li>
 	<li>In the left pane, click on <strong>Plugins.</strong></li>
 	<li>Then, select the <strong>Plex Media Server</strong> plugin.</li>
 	<li>Now, click the <strong>settings</strong> next to the <strong>Plex</strong> plugin.</li>
 	<li>Select the <strong>Install</strong> option.

[caption id="attachment_1691" align="aligncenter" width="1271"]<img class="size-full wp-image-1691" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_XEJBY0gF2q.png" alt="Install" width="1271" height="780" /> Install[/caption]</li>
 	<li>Then, select the <strong>DHCP</strong> option if you’re planning to configure your router to use the dynamically assign TCP/IP address as the permanent configuration for the server.</li>
 	<li>Else clear the <strong>DHCP</strong> option to specify a static IP address configuration selecting the network interface, IPv4 address, and netmask.

[caption id="attachment_1678" align="aligncenter" width="1272"]<img class="size-full wp-image-1678" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_1O5C4BZa4U.png" alt="Plex IP configuration " width="1272" height="780" /> Plex IP configuration[/caption]</li>
 	<li>Now, click the <strong>Save</strong> and <strong>Close</strong>.

[caption id="attachment_1687" align="aligncenter" width="1273"]<img class="size-full wp-image-1687" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_ntdJrjn46W.png" alt="Plex plugin installation complete" width="1273" height="786" /> Plex plugin installation complete[/caption]</li>
 	<li>Once you complete the steps, don’t try to open Plex, instead of jump to the following set of instructions to configure the storage for the media files.</li>
</ul>
<h2 id="4">Configuring Plex media storage:</h2>
Use these steps to mount a FreeNAS folder to the Plex server.
<ul>
 	<li>First, Open <strong>FreeNAS</strong> in your web browser.</li>
 	<li>Then, <strong>Sign in</strong> to your root account.</li>
 	<li>In the left pane, click on <strong>Plugins.</strong></li>
 	<li>Click on <strong>Installed</strong>.</li>
 	<li>Now, click the <strong>settings</strong> next to the <strong>Plex</strong> plugin.</li>
 	<li>Select the <b>Stop </b>option.

[caption id="attachment_1685" align="aligncenter" width="1274"]<img class="size-full wp-image-1685" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_kisFX7mL5e.png" alt="Stop" width="1274" height="758" /> Stop[/caption]</li>
 	<li>In the left pane, click on <strong>Jails.</strong></li>
 	<li>Now, click the <strong>settings</strong> next to the <strong>Plex</strong> <strong>jail</strong>.</li>
 	<li>Select the<b> Mount points </b>option.

[caption id="attachment_1679" align="aligncenter" width="1273"]<img class="size-full wp-image-1679" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_3hpFLoukyM.png" alt="Plex mount points " width="1273" height="745" /> Plex mount points[/caption]</li>
 	<li>Click the <strong>Actions</strong>.</li>
 	<li>Then, click the <strong>Add Mount Point</strong> option.

[caption id="attachment_1689" align="aligncenter" width="1273"]<img class="size-full wp-image-1689" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_oCGrshpwQf.png" alt="Add new mount point to Plex" width="1273" height="743" /> Add new mount point to Plex[/caption]</li>
 	<li>Now, in <strong>Source</strong>, click the folder icon, navigate, and select the folder or dataset where your media library will be stored.</li>
 	<li>Then, in <strong>Destination</strong>, click the folder icon, navigate, and select the <strong>media</strong> folder.

[caption id="attachment_1682" align="aligncenter" width="1277"]<img class="size-full wp-image-1682" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_FdiRmFrIcP.png" alt="Plex configure source and destination mount point" width="1277" height="610" /> Plex configure source and destination mount point[/caption]</li>
 	<li>Finally, click the <strong>Save</strong>.</li>
 	<li>Then in the left pane, click on <strong>Plugins.</strong></li>
 	<li>Again, click on <strong>Installed</strong>.</li>
 	<li>Now, click the <strong>settings</strong> next to the <strong>Plex</strong> <strong>plugin</strong>.</li>
 	<li>Select the <strong>Start</strong> option.

[caption id="attachment_1692" align="aligncenter" width="1276"]<img class="size-full wp-image-1692" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_YVitnWvbHk.png" alt="Start" width="1276" height="606" /> Start[/caption]</li>
 	<li>After you complete the steps, the Plex server will be ready for the initial setup.</li>
</ul>
<h2 id="5">Initial Plex setup:</h2>
Just use these steps to add a folder to the Plex library to access media files stored on FreeNAS.
<ul>
 	<li>First, Open <strong>FreeNAS</strong> in your web browser.</li>
 	<li>Then, <strong>Sign in</strong> to your root account.</li>
 	<li>In the left pane, click on <strong>Plugins.</strong></li>
 	<li>Click on <strong>Installed.</strong></li>
 	<li>Now, click the <strong>settings</strong> next to the <strong>Plex</strong> <strong>plugin</strong>.</li>
 	<li>Select the <strong>Management</strong> option.

[caption id="attachment_1686" align="aligncenter" width="1274"]<img class="size-full wp-image-1686" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_mmvSIjpi6f.png" alt="Management" width="1274" height="609" /> Management[/caption]</li>
 	<li>Then, Sign in with your <strong>Plex</strong> account.</li>
 	<li>Click the <strong>Got it</strong>.

[caption id="attachment_1683" align="aligncenter" width="1265"]<img class="size-full wp-image-1683" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_HedFNdMGOC.png" alt="Initial Plex server setup" width="1265" height="866" /> Initial Plex server setup[/caption]</li>
 	<li>Then, <strong>type</strong> a name for the Plex server.</li>
 	<li>Now, clear the <strong>Allow me to access my media outside my home</strong> option if you won’t use this feature.</li>
 	<li>Click the <strong>Next</strong>.</li>
 	<li>Then, click the <strong>Add Library</strong>.

[caption id="attachment_1688" align="aligncenter" width="1266"]<img class="size-full wp-image-1688" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_o7gBKG9txg.png" alt="Plex add library option" width="1266" height="860" /> Plex adds library option[/caption]</li>
 	<li>Now, select the media type you’re about to include and click the <strong>Next</strong>.

[caption id="attachment_1690" align="aligncenter" width="1270"]<img class="size-full wp-image-1690" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_qgZM9wyxLf.png" alt="Select Plex library type" width="1270" height="869" /> Select Plex library type[/caption]</li>
 	<li>Click the <strong>Browse for a media folder option</strong>.

[caption id="attachment_1680" align="aligncenter" width="1264"]<img class="size-full wp-image-1680" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_6qIXJTEC5M.png" alt="Plex add folders to library option" width="1264" height="866" /> Plex adds folders to library option[/caption]</li>
 	<li>Then, select the folder icon, navigate, and select the media folder.

[caption id="attachment_1684" align="aligncenter" width="1265"]<img class="size-full wp-image-1684" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_IHSuTm1Ct1.png" alt="Plex select media folder from FreeNAS" width="1265" height="844" /> Plex select media folder from FreeNAS[/caption]</li>
 	<li>Click the <strong>Add </strong>and click the <strong>Add Library</strong>.

[caption id="attachment_1681" align="aligncenter" width="1271"]<img class="size-full wp-image-1681" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_358RWqViyC.png" alt="Complete Plex adding folder to library setup" width="1271" height="871" /> Complete Plex adding the folder to library setup[/caption]</li>
 	<li>Finally, click the <strong>Next and </strong><strong>Done</strong>.</li>
 	<li>Once you complete the steps, you can start streaming the media you added using Plex.</li>
 	<li>That's all.</li>
</ul>
<h2 id="2">Closure:</h2>
We hope that this tutorial guided you <strong>How to install Plex Media Server on FreeNAS.</strong> If you find this article helpful, kindly share your valuable <strong>comments</strong> in the below section and drop your worthwhile feedback.