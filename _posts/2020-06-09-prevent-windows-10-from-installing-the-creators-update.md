---
ID: 1146
post_title: >
  Prevent Windows 10 from installing the
  Creators Update!!
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1146-prevent-windows-10-from-installing-the-creators-update/
published: true
post_date: 2020-06-09 14:48:12
---
<ul class="toc">
 	<li><a href="#1">Stop Windows 10 Creators Update using Group Policy</a></li>
 	<li><a href="#2">Stop Creators Update on Windows 10 Home</a></li>
 	<li><a href="#3">Stop Windows 10 Creators Update using Settings</a></li>
 	<li><a href="#4">Summary</a></li>
</ul>
<strong><strong><strong><span class="dcap">H</span><strong>ow to Prevent Windows 10 from installing the Creators Update?</strong></strong></strong></strong> Updates keep your PC secure and up to date with improvements, security patches, and new features, but when installing big feature updates as soon as they release could mean more problems.

Here, this article will help you to <strong>Prevent Windows 10 from installing the Creators Update</strong><strong> </strong>in simple steps.
<h2 id="1">Stop Windows 10 Creators Update using Group Policy:</h2>
Use the below steps to Stop Windows 10 Creators Update using Group Policy in simple steps.
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the Run command dialog box.</li>
 	<li>Type as <strong>gpedit.msc</strong> in the given space of <strong>Open</strong> and click <strong>OK.</strong></li>
 	<li>Now, it will open the <strong>Local Group Policy Editor</strong>.</li>
 	<li>Follow the below path,
<pre><code>Computer Configuration &gt; Administrative Templates &gt; Windows Components &gt; 
Windows Update &gt; Defer Windows Updates</code></pre>
</li>
 	<li>After that, double-click the <strong>Select when Feature Updates are received</strong> policy.

[caption id="attachment_1155" align="aligncenter" width="1176"]<img class="wp-image-1155 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_6-1.png" alt="Group policy" width="1176" height="657" /> Group policy[/caption]</li>
 	<li>In the Select when Feature Updates are received window, select the <strong>Enabled</strong> option.</li>
 	<li>Then, in Options select the <strong>Current Branch for Business</strong> option from the drop-down menu and choose for how long you want to defer upgrades. You can defer receiving feature updates <strong>up to 180 days.</strong></li>
 	<li>Then, <strong>check-in</strong> the <strong>Pause feature updates</strong> option.</li>
 	<li>Click <strong>Apply</strong> and <strong>OK</strong>.

[caption id="attachment_1156" align="aligncenter" width="857"]<img class="wp-image-1156 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_7-1.png" alt="Group policy" width="857" height="794" /> Group policy[/caption]</li>
 	<li>That's all.</li>
</ol>
<h2 id="2">Stop Creators Update on Windows 10 Home:</h2>
Use the below steps to Stop Creators Update on Windows 10 Home in simple steps.
<ol>
 	<li>Make use of the shortcut <strong>Windows + I</strong> to open Windows Settings.</li>
 	<li>Then select the <strong>Network &amp; Internet.</strong>

[caption id="attachment_1152" align="aligncenter" width="1101"]<img class="wp-image-1152 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_3-6.png" alt="Settings" width="1101" height="601" /> Settings[/caption]</li>
 	<li>In the left pane click on the <strong>Wi-Fi.</strong></li>
 	<li>Now, click the <strong>Advanced options.</strong>

[caption id="attachment_1153" align="aligncenter" width="1103"]<img class="wp-image-1153 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_4-3.png" alt="Wi-FI" width="1103" height="770" /> Wi-FI[/caption]</li>
 	<li>After opening, under Metered connection, make sure to turn on the <strong>Set as a metered connection</strong> toggle switch.<img class="aligncenter wp-image-1154 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_5-2.png" alt="" width="1102" height="766" /></li>
 	<li>The caveat with this feature is that it only works with when connected using a Wi-Fi network.</li>
</ol>
<h2 id="3">Stop Windows 10 Creators Update using Settings:</h2>
Use the below steps to Stop Windows 10 Creators Update using Settings in simple steps.
<ol>
 	<li>Make use of the shortcut <strong>Windows + I</strong> to open Windows Settings.</li>
 	<li>Then select the <strong>Update &amp; security</strong> and in the left pane click on the<strong> Windows Update.</strong>

[caption id="attachment_1148" align="aligncenter" width="1098"]<img class="wp-image-1148 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_1-8.png" alt="Windows Update" width="1098" height="760" /> Windows Update[/caption]</li>
 	<li>Now, click the <strong>Advanced options</strong>.</li>
 	<li>Check in the <strong>Defer upgrades</strong> option.

[caption id="attachment_1157" align="aligncenter" width="1110"]<img class="wp-image-1157 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_2-9.png" alt="Defer upgrades" width="1110" height="774" /> Defer upgrades[/caption]</li>
 	<li>That's all.</li>
</ol>
<h2 id="4">Summary:</h2>
In the above article, we have illustrated the easy steps <strong>to prevent Windows 10 from installing the Creators Update.</strong> If you found this article helpful? Don’t forget to share your comments in the below section.