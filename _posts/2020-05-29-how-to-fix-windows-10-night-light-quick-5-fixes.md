---
ID: 663
post_title: 'How to Fix Windows 10 Night Light? {Quick 5 Fixes}'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/663-how-to-fix-windows-10-night-light-quick-5-fixes/
published: true
post_date: 2020-05-29 06:45:46
---
<ul class="toc">
 	<li><a href="#1">Update Graphics Driver</a></li>
 	<li><a href="#2">Reset Night Light Settings Manually</a></li>
 	<li><a href="#3">Disable Fast Startup via Control Panel</a></li>
 	<li><a href="#4">Install a Third-Party App</a></li>
 	<li><a href="#5">Reinstall Windows 10</a></li>
 	<li><a href="#6">A Brief Summary</a></li>
</ul>
<span class="dcap">F</span><strong>ix Night Light on Windows 10</strong>: Night Light is a useful feature in Windows 10 as it reduces the blue light on the screen at night. It enhances your sleep quality and also reduces eye strain. So, if you are supposed to work on laptops or desktops for more hours during the night, then this is the feature for you.

In some cases, you may find that the night light grayed out or it starts to malfunction all of a sudden or some other issues. But can you do anything about it? Here, we will illustrate the five ways to <strong>Fix Windows 10 Night Light</strong> in an efficient manner.
<h2 id="1">Fix 1 - Update Graphics Driver:</h2>
<ul>
 	<li>In order to solve the night light not working issue, you have to manually download and install the appropriate display drivers by visiting your PC manufacturer’s support website.</li>
 	<li>Simply visit the NVIDIA, AMD, or Intel download portals, and then specify your graphics chipset to download the latest drivers.</li>
 	<li>After installing the driver, restart your Windows PC and you likely won’t see night light issue.</li>
</ul>
<h2 id="2">Fix 2 - Reset Night Light Settings Manually:</h2>
Resetting night light settings manually in the registry editor is also helpful for fixing the night light not working problem.
<ol>
 	<li>Press <strong>Windows key + R</strong> to open the Run box.</li>
 	<li>Now, you have to type <strong>'regedit' </strong>and click <strong>OK</strong>. (If you get any pop-up from User Account Control, you have to press Yes) <code>regedit</code>

[caption id="attachment_418" align="alignnone" width="428"]<img class="size-full wp-image-418" src="https://windowscrazy.com/wp-content/uploads/2020/05/bi1.png" alt="Regedit" width="428" height="232" /> Regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>. In the left pane, you have to navigate to the following path. <code>HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudStore\Store\DefaultAccount\Cloud</code></li>
 	<li>Next, you have to right-click and select the <strong>Delete</strong> option to delete the below keys. <code>$$windows.data.bluelightreduction.bluelightreductionstate
$$windows.data.bluelightreduction.settings</code>

[caption id="attachment_673" align="alignnone" width="725"]<img class="size-full wp-image-673" src="https://windowscrazy.com/wp-content/uploads/2020/05/nl1.png" alt="Click Delete" width="725" height="419" /> Click Delete[/caption]</li>
 	<li>Reboot your computer so the night light feature will start to work again.</li>
</ol>
<h2 id="3">Fix 3 - Disable Fast Startup via Control Panel:</h2>
The fast startup is a combination of the hibernate and cold startup. Disabling fast startup and rebooting the device can assist you to bring back the night light.
<ol>
 	<li>Go to the Start button. In the search box, type <strong>'control panel'</strong> and hit Enter to open it.

[caption id="attachment_132" align="alignnone" width="885"]<img class="size-full wp-image-132" src="https://windowscrazy.com/wp-content/uploads/2020/05/rd5.png" alt="Open Control Panel" width="885" height="677" /> Open Control Panel[/caption]</li>
 	<li>Click on the <strong>Hardware and Sound</strong> option.

[caption id="attachment_564" align="alignnone" width="812"]<img class="size-full wp-image-564" src="https://windowscrazy.com/wp-content/uploads/2020/05/upd4.png" alt="Hardware and Sound" width="812" height="507" /> Hardware and Sound[/caption]</li>
 	<li>Now, you have to click on the <strong>Power Options</strong>.

[caption id="attachment_677" align="alignnone" width="822"]<img class="size-full wp-image-677" src="https://windowscrazy.com/wp-content/uploads/2020/05/nl2.png" alt="Click Power Options" width="822" height="510" /> Click Power Options[/caption]</li>
 	<li>You have to click the link <strong>Choose what the power button does</strong>.

[caption id="attachment_678" align="alignnone" width="822"]<img class="size-full wp-image-678" src="https://windowscrazy.com/wp-content/uploads/2020/05/nl3.png" alt="Choose what the power button does" width="822" height="510" /> Choose what the power button does[/caption]</li>
 	<li>Then, you have to click on <strong><strong>Change settings that are currently unavailable.</strong></strong>

[caption id="attachment_679" align="alignnone" width="822"]<img class="size-full wp-image-679" src="https://windowscrazy.com/wp-content/uploads/2020/05/nl4.png" alt="Change settings that are currently unavailable" width="822" height="510" /> Change settings that are currently unavailable[/caption]</li>
 	<li>Next, you have to uncheck the <strong>'Turn on fast startup (recommended)' </strong>check-box.</li>
 	<li>At last, click on the <strong>Save changes</strong> button.

[caption id="attachment_680" align="alignnone" width="822"]<img class="size-full wp-image-680" src="https://windowscrazy.com/wp-content/uploads/2020/05/nl5.png" alt="Uncheck and click Save changes" width="822" height="510" /> Uncheck and click Save changes[/caption]</li>
</ol>
<h2 id="4">Fix 4 - Install a Third-Party App:</h2>
<ul>
 	<li>The <strong>f.lux</strong> is a very famous app that lets you go to a blue light filter before Night Light showed up. This application offers several sliders for personalized experience throughout the day.</li>
 	<li>It has the ability to filter out diverse levels of blue light at daytime, sunset, and at nighttime.</li>
 	<li>If you already installed this app, it may conflict with the Night Light feature in your device. Make sure you use either Night Light in Windows 10 or this third-party application.</li>
 	<li>If you want to use this app, you have to turn off night light completely. To do so, go to Settings &gt; System &gt; Display &gt; Turn off Night light toggle switch.</li>
 	<li>You can <a href="https://justgetflux.com/" target="_blank" rel="noopener noreferrer"><strong>download f.lux</strong></a> and try this app in your system.

[caption id="attachment_712" align="alignnone" width="764"]<img class="size-full wp-image-712" src="https://windowscrazy.com/wp-content/uploads/2020/05/nl6.png" alt="f.lux" width="764" height="426" /> f.lux[/caption]</li>
</ul>
<h2 id="5">Fix 5 - Reinstall Windows 10:</h2>
<ul>
 	<li>If all the above fixes do not work and you are in need to use this night light feature, you can try to reinstall your Windows 10.</li>
</ul>
<h2 id="6">A Brief Summary:</h2>
Probably, the above fixes helped you a lot to <strong>Fix Windows 10 Night Light</strong> easily and effectively. We hope that the fixes are not really complex. Fix the issue and start to use this feature to reduce your eye strain. Your comments are highly welcomed as it cheers our write-up. Thanks for visiting <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.