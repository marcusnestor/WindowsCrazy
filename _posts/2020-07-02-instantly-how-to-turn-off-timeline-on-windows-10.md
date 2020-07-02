---
ID: 2302
post_title: '[Instantly] How to Turn Off Timeline on Windows 10?'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/2302-instantly-how-to-turn-off-timeline-on-windows-10/
published: true
post_date: 2020-07-02 08:45:24
---
<ul class="toc">
 	<li><a href="#1">Turn Off Timeline - Using Settings</a></li>
 	<li><a href="#2">Disable Timeline via Group Policy Editor</a></li>
 	<li><a href="#3">Turn Off Timeline through Registry Editor</a></li>
 	<li><a href="#4">Verdict</a></li>
</ul>
<span class="dcap">T</span><strong>urn Off Timeline on Windows 10</strong>: Windows 10 gathers a history of activities that include web pages you have viewed, files you have opened, and even more by means of the Timeline feature. It helps you to track your system's activities but some users may think to disable this feature as they concern about their security or privacy.

If you don't want this feature to collect your PC's activities, you can disable this feature easily. In this tutorial, you will learn three diverse ways to <strong>Turn Off Timeline on Windows 10 </strong>quickly.
<h2 id="1">1) Turn Off Timeline - Using Settings:</h2>
<ol>
 	<li>In order to open the <strong>Settings</strong>, you have to use this keyboard shortcut <strong>Windows key + I</strong>.</li>
 	<li>Next, you have to click on the <strong>Privacy</strong> option.

[caption id="attachment_2318" align="alignnone" width="1332"]<img class="size-full wp-image-2318" src="https://windowscrazy.com/wp-content/uploads/2020/07/Privacy.png" alt="Privacy" width="1332" height="812" /> Privacy[/caption]</li>
 	<li>In the left pane, you have to tap on the Activity history option.</li>
 	<li>You have to uncheck these two options <strong>Store my activity history on this device </strong>and <strong>Send my activity history to Microsoft</strong>.

[caption id="attachment_2323" align="alignnone" width="1333"]<img class="size-full wp-image-2323" src="https://windowscrazy.com/wp-content/uploads/2020/07/Uncheck-options.png" alt="Uncheck the two options" width="1333" height="817" /> Uncheck the two options[/caption]</li>
 	<li>Further, you have to <strong>turn off the toggle switch</strong> under '<strong>Show activities from these accounts</strong>'.

[caption id="attachment_2322" align="alignnone" width="1339"]<img class="size-full wp-image-2322" src="https://windowscrazy.com/wp-content/uploads/2020/07/Turn-off-1.png" alt="Turn off" width="1339" height="825" /> Turn off[/caption]</li>
 	<li>To refresh this page, you just jump to another settings page and then come back to this Activity history page.</li>
 	<li>Now, click the <strong>Clear</strong> button under '<strong>Clear activity history</strong>'.

[caption id="attachment_2313" align="alignnone" width="1321"]<img class="size-full wp-image-2313" src="https://windowscrazy.com/wp-content/uploads/2020/07/Clear.png" alt="Clear" width="1321" height="814" /> Clear[/caption]</li>
 	<li>Click the <strong>OK</strong> button to clear all your activity history from all your devices. Make sure that you cannot resume any cleared activities.

[caption id="attachment_2314" align="alignnone" width="1335"]<img class="size-full wp-image-2314" src="https://windowscrazy.com/wp-content/uploads/2020/07/Click-OK.png" alt="Click OK" width="1335" height="818" /> Click OK[/caption]</li>
</ol>
<h2 id="2">2) Disable Timeline via Group Policy Editor:</h2>
<ol>
 	<li>Using this shortcut <strong>Windows + R,</strong> you can open the <strong>Run command</strong> dialog box.</li>
 	<li>After that, you have to type as <strong>gpedit.msc</strong> in the given space of <strong>Open</strong> and click <strong><strong>OK.</strong></strong>

[caption id="attachment_2294" align="alignnone" width="602"]<img class="size-full wp-image-2294" src="https://windowscrazy.com/wp-content/uploads/2020/07/gpedit.msc_.png" alt="gpedit.msc" width="602" height="368" /> gpedit.msc[/caption]</li>
 	<li>Now, it will open the <strong>Local Group Policy Editor</strong>.</li>
 	<li>Follow the below path,
<code>Computer Configuration &gt; Administrative Templates &gt; System &gt; OS Policies</code></li>
 	<li>You have to double-click on <strong>Enables Activity Feed </strong>policy that is present on the right side.

[caption id="attachment_2317" align="alignnone" width="1180"]<img class="size-full wp-image-2317" src="https://windowscrazy.com/wp-content/uploads/2020/07/Enables-Activity-Feed.png" alt="Enables Activity Feed" width="1180" height="833" /> Enables Activity Feed[/caption]</li>
 	<li>Mark the <strong>Disabled</strong> option, click <strong>Apply</strong>, and then <strong>OK</strong>.

[caption id="attachment_2316" align="alignnone" width="1028"]<img class="size-full wp-image-2316" src="https://windowscrazy.com/wp-content/uploads/2020/07/Enables-Activity-Disabled.png" alt="Enables Activity - Disabled" width="1028" height="954" /> Enables Activity - Disabled[/caption]</li>
 	<li>Then, you have to double-click on the <strong>Allow publishing of User Activities</strong> policy.

[caption id="attachment_2310" align="alignnone" width="1174"]<img class="size-full wp-image-2310" src="https://windowscrazy.com/wp-content/uploads/2020/07/Allow-publishing-of-User-Activities.png" alt="Allow publishing of User Activities" width="1174" height="837" /> Allow publishing of User Activities[/caption]</li>
 	<li>Mark the <strong>Disabled</strong> option, click <strong>Apply</strong>, and then <strong>OK</strong>.

[caption id="attachment_2309" align="alignnone" width="1028"]<img class="size-full wp-image-2309" src="https://windowscrazy.com/wp-content/uploads/2020/07/Allow-publish-Disabled.png" alt="Allow publish - Disabled" width="1028" height="954" /> Allow publish - Disabled[/caption]</li>
 	<li>Double-click on the <strong>Allow upload of User Activities</strong> policy.

[caption id="attachment_2312" align="alignnone" width="1188"]<img class="size-full wp-image-2312" src="https://windowscrazy.com/wp-content/uploads/2020/07/Allow-upload-of-User-Activities.png" alt="Allow upload of User Activities" width="1188" height="840" /> Allow upload of User Activities[/caption]</li>
 	<li>Mark the <strong>Disabled</strong> option, click <strong>Apply</strong>, and then <strong>OK</strong>.

[caption id="attachment_2311" align="alignnone" width="1028"]<img class="size-full wp-image-2311" src="https://windowscrazy.com/wp-content/uploads/2020/07/Allow-upload-Disabled.png" alt="Allow upload - Disabled" width="1028" height="954" /> Allow upload - Disabled[/caption]</li>
 	<li>Finally, you have to restart your computer so that the Timeline feature will not collect your activities anymore.</li>
</ol>
<h2 id="3">3) Turn Off Timeline through Registry Editor:</h2>
<ol>
 	<li>Press <strong>Windows key + R</strong> to open the Run box.</li>
 	<li>Now, you have to type <strong>'regedit' </strong>and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press Yes) <code>regedit</code>

[caption id="attachment_2253" align="alignnone" width="606"]<img class="size-full wp-image-2253" src="https://windowscrazy.com/wp-content/uploads/2020/07/regedit.png" alt="regedit" width="606" height="366" /> regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>In the left pane, you have to navigate to the following path.<code>HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows</code></li>
 	<li>Now, you have to right-click on the <strong>Windows </strong>folder and choose <strong><strong>New -&gt; Key.</strong></strong>

[caption id="attachment_2321" align="alignnone" width="1200"]<img class="size-full wp-image-2321" src="https://windowscrazy.com/wp-content/uploads/2020/07/Right-click-on-Windows.png" alt="Right-click on Windows" width="1200" height="733" /> Right-click on Windows[/caption]</li>
 	<li>You have to name the key as <strong>System</strong> and hit <strong>Enter</strong>.</li>
 	<li>Right-click on the <strong>System</strong> folder and choose <strong>New</strong> -&gt; <strong><strong>DWORD (32-bit) Value.</strong></strong>

[caption id="attachment_2320" align="alignnone" width="1197"]<img class="size-full wp-image-2320" src="https://windowscrazy.com/wp-content/uploads/2020/07/Right-click-on-System.png" alt="Right-click on System" width="1197" height="760" /> Right-click on System[/caption]</li>
 	<li>You have to name the key as <strong>EnableActivityFeed</strong> and hit <strong>Enter</strong>.</li>
 	<li>Double-click on the <strong>EnableActivityFeed </strong>folder and make sure its value is set to<strong> 0</strong>.

[caption id="attachment_2315" align="alignnone" width="1205"]<img class="size-full wp-image-2315" src="https://windowscrazy.com/wp-content/uploads/2020/07/EnableActivityFeed.png" alt="EnableActivityFeed" width="1205" height="737" /> EnableActivityFeed[/caption]</li>
 	<li>Now, again you have to right-click on the <strong>System</strong> folder and choose <strong>New</strong> -&gt; <strong>DWORD (32-bit) Value. </strong></li>
 	<li>You have to name the key as <strong>PublishUserActivities</strong> and hit <strong>Enter</strong>.</li>
 	<li>Double-click on the <strong>PublishUserActivities</strong><strong> </strong>folder and make sure its value is set to<strong> 0</strong>.

[caption id="attachment_2319" align="alignnone" width="1191"]<img class="size-full wp-image-2319" src="https://windowscrazy.com/wp-content/uploads/2020/07/PublishUserActivities.png" alt="PublishUserActivities" width="1191" height="728" /> PublishUserActivities[/caption]</li>
 	<li>After that, you have to right-click on the <strong>System</strong> folder and choose <strong>New</strong> -&gt; <strong>DWORD (32-bit) Value. </strong></li>
 	<li>You have to name the key as <strong>UploadUserActivities</strong> and hit <strong>Enter</strong>.</li>
 	<li>Double-click on the <strong>UploadUserActivities</strong><strong> </strong>folder and make sure its value is set to<strong> 0</strong>.

[caption id="attachment_2324" align="alignnone" width="1197"]<img class="size-full wp-image-2324" src="https://windowscrazy.com/wp-content/uploads/2020/07/UploadUserActivities.png" alt="UploadUserActivities" width="1197" height="721" /> UploadUserActivities[/caption]</li>
 	<li>That's it. Now, you have to restart your PC and make sure that the Timeline feature is disabled.</li>
</ol>
<h2 id="4">Verdict:</h2>
In this guide, we outlined the three ways to <strong>Turn Off Timeline on Windows 10. </strong>We hope that the above ways assisted you to disable the timeline quickly. Don't forget to share your <strong>valuable comments</strong> in the below section. We appreciate your presence in <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.
<h2>Read Ahead:</h2>
<ul>
 	<li><a href="https://windowscrazy.com/892-simple-steps-how-to-enable-loudness-equalization-in-windows-10/">[Simple Steps] How to Enable Loudness Equalization in Windows 10?</a></li>
 	<li><a href="https://windowscrazy.com/1996-how-to-create-a-partition-in-windows-10-during-installation/">How to Create a Partition in Windows 10 during Installation?</a></li>
 	<li><a href="https://windowscrazy.com/1242-how-to-remove-disconnected-network-drive-in-windows-10/">How to Remove Disconnected Network Drive in Windows 10?</a></li>
</ul>