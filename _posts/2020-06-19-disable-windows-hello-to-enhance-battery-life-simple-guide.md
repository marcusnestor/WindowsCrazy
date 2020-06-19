---
ID: 1590
post_title: 'Disable Windows Hello to Enhance Battery Life!! {Simple Guide}'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1590-disable-windows-hello-to-enhance-battery-life-simple-guide/
published: true
post_date: 2020-06-19 04:58:33
---
<ul class="toc">
 	<li><a href="#1">Disable Windows Hello - Using Settings</a></li>
 	<li><a href="#2">How to Disable Windows Hello using Group Policy Editor?</a></li>
 	<li><a href="#3">Disable Windows Hello via Registry Editor</a></li>
 	<li><a href="#4">Put your computer into Hibernate mode</a></li>
 	<li><a href="#5">Disable Wi-Fi to Save Battery Power</a></li>
 	<li><a href="#6">A Short Synopsis</a></li>
</ul>
<span class="dcap">D</span><strong>isable Windows Hello</strong>: Most of the users face battery drain and heat issues during a sleep mode in Surface Book or Surface Pro. This kind of problem may occur due to the Windows Hello feature. In such cases, you just need to disable this feature temporarily and check whether you are facing the battery drain issue.

This tutorial explains how to <strong>Disable Windows Hello </strong>in three different ways. In addition, we will illustrate how to put your computer into Hibernate mode and disable Wi-Fi to save your battery power of Surface Book or Surface Pro 4.
<h2 id="1">Disable Windows Hello - Using Settings:</h2>
<ol>
 	<li>To open the <strong>Settings</strong>, you have to press <strong>Windows key + I</strong>.</li>
 	<li>After that, you have to click on the <strong>Accounts</strong> option.

[caption id="attachment_1598" align="alignnone" width="840"]<img class="size-full wp-image-1598" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh1.png" alt="Accounts" width="840" height="519" /> Accounts[/caption]</li>
 	<li>In the left pane, you have to tap on <strong>Sign-in options</strong>.

[caption id="attachment_1599" align="alignnone" width="841"]<img class="size-full wp-image-1599" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh2.png" alt="Sign-in options" width="841" height="521" /> Sign-in options[/caption]</li>
 	<li>Now, you have to click the <strong>Remove</strong> button under <strong>Windows Hello</strong>.</li>
</ol>
<h2 id="2">How to Disable Windows Hello using Group Policy Editor?</h2>
<ol>
 	<li>You have to open the <strong>Run command</strong> by using this shortcut <strong>Windows key + R</strong>.</li>
 	<li>Next, you have to type '<strong>gpedit.msc</strong>' and click <strong>OK</strong>.

[caption id="attachment_1600" align="alignnone" width="398"]<img class="size-full wp-image-1600" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh3.png" alt="gpedit.msc" width="398" height="205" /> gpedit.msc[/caption]</li>
 	<li>Now, go to <strong>Computer Configuration -&gt; Administrative Templates -&gt; System -&gt; Logon</strong>.</li>
 	<li>On the right side, you have to double click on <strong><strong>Turn on convenience PIN sign-in.</strong></strong>

[caption id="attachment_1601" align="alignnone" width="878"]<img class="size-full wp-image-1601" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh4.png" alt="Turn on convenience PIN sign-in" width="878" height="577" /> Turn on convenience PIN sign-in[/caption]</li>
 	<li>After that, you have to choose <strong>Disabled</strong>. Similarly, you can disable the Windows Hello options if any.</li>
 	<li>Then, you can close the Group Policy Editor and reboot your system.</li>
</ol>
<h2 id="3">Disable Windows Hello via Registry Editor:</h2>
<ol>
 	<li>Open the <strong>Run box </strong>with the use of this shortcut <strong>Windows key + R</strong>.</li>
 	<li>After that, you have to type '<strong>regedit.exe</strong>' and click the <strong>OK </strong>button.

[caption id="attachment_418" align="alignnone" width="428"]<img class="size-full wp-image-418" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi1.png" alt="Regedit" width="428" height="232" /> Regedit[/caption]</li>
 	<li>In the Registry Editor window, you have to navigate to the below path.<code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PolicyManager\default\Settings\AllowSignInOptions</code></li>
 	<li>In the right pane, you have to double-click on <strong>value.</strong>

[caption id="attachment_1602" align="alignnone" width="749"]<img class="size-full wp-image-1602" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh5.png" alt="value" width="749" height="440" /> value[/caption]</li>
 	<li>Set the <strong>Value data </strong>to<strong> 0 </strong>and click<strong><strong><strong> OK.</strong></strong></strong>

[caption id="attachment_1603" align="alignnone" width="744"]<img class="size-full wp-image-1603" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh6.png" alt="Set Value data 0" width="744" height="431" /> Set Value data 0[/caption]</li>
 	<li>This will disable the Windows Hello for all user accounts. If you want to re-enable it, you have to set the value as 1.</li>
</ol>
<h2 id="4">Put your computer into Hibernate mode:</h2>
You can also put your computer into Hibernate mode in order to enhance your battery life. If you don't find the Hibernate option in the <strong>Power</strong> button, you have to follow the below steps.
<ol>
 	<li>Go to the <strong>Control Panel</strong>.</li>
 	<li>Choose <strong>Large icons</strong> in the <strong>View by</strong> drop-down menu.

[caption id="attachment_1604" align="alignnone" width="806"]<img class="size-full wp-image-1604" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh7.png" alt="Large icons" width="806" height="337" /> Large icons[/caption]</li>
 	<li>After that, you have to click on <strong>Power Options</strong>.

[caption id="attachment_1605" align="alignnone" width="1365"]<img class="size-full wp-image-1605" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh8.png" alt="Power Options" width="1365" height="601" /> Power Options[/caption]</li>
 	<li>Click the link <strong>Choose what the power button does</strong>.

[caption id="attachment_1606" align="alignnone" width="844"]<img class="size-full wp-image-1606" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh9.png" alt="Choose what the power button does" width="844" height="343" /> Choose what the power button does[/caption]</li>
 	<li>Next, you have to tap on '<strong>Change settings that are currently unavailable</strong>'.

[caption id="attachment_1607" align="alignnone" width="646"]<img class="size-full wp-image-1607" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh10.png" alt="Change settings that are currently unavailable" width="646" height="425" /> Change settings that are currently unavailable[/caption]</li>
 	<li>Select the checkbox of the <strong>Hibernate</strong> option under <strong>Shutdown settings</strong>.</li>
 	<li>Now, you have to click on the <strong>Save changes</strong> button.

[caption id="attachment_1608" align="alignnone" width="1365"]<img class="size-full wp-image-1608" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh11.png" alt="Hibernate" width="1365" height="727" /> Hibernate[/caption]</li>
</ol>
<h2 id="5">Disable Wi-Fi to Save Battery Power:</h2>
When you put your system to sleep, you can disable the Wi-Fi to improve your battery performance.
<ol>
 	<li>Use this shortcut <strong>Windows key + I</strong> to open the <strong>Settings</strong>.</li>
 	<li>Now, you have to click on the <strong>System</strong> option.

[caption id="attachment_1363" align="alignnone" width="825"]<img class="size-full wp-image-1363" src="https://windowscrazy.com/wp-content/uploads/2020/06/dm2-1.png" alt="System" width="825" height="526" /> System[/caption]</li>
 	<li>In the left pane, you have to tap on <strong>Power &amp; sleep</strong> option.

[caption id="attachment_1609" align="alignnone" width="847"]<img class="size-full wp-image-1609" src="https://windowscrazy.com/wp-content/uploads/2020/06/wh12.png" alt="Power &amp; sleep" width="847" height="523" /> Power &amp; sleep[/caption]</li>
 	<li>Then, you have to uncheck the option '<strong>On battery power, stay connected to Wi-Fi while asleep</strong>'.</li>
</ol>
<h2 id="6">A Short Synopsis:</h2>
In this tutorial, you have learned how to <strong>Disable Windows Hello</strong> in diverse ways. You can also disable Wi-Fi or put your computer into Hibernate mode as per our suggestion in order to enhance your battery life. If you found this article useful, kindly share your <strong>valuable comments</strong> in the below section. We appreciate your presence in <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.