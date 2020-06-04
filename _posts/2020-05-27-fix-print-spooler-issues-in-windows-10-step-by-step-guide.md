---
ID: 501
post_title: 'Fix Print Spooler Issues in Windows 10! {Step-by-Step Guide}'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/501-fix-print-spooler-issues-in-windows-10-step-by-step-guide/
published: true
post_date: 2020-05-27 04:23:24
---
<ul class="toc">
 	<li><a href="#1">Fix Print Spooler - Using Services</a></li>
 	<li><a href="#2">Fix Print Spooler via Command Prompt</a></li>
 	<li><a href="#2">Wrap-up</a></li>
</ul>
<span class="dcap">F</span><strong>ix Print Spooler in Windows 10</strong>: If you are trying to use your printer and run into issues, here are two ways to fix the problems to get things to work again. Print Spooler is known to stop working in Windows 10 quite often.

We are here to illustrate two ways that help you to <strong>Fix Print Spooler Issues in Windows 10 </strong>via services and command prompt.
<h2 id="1">Fix Print Spooler - Using Services:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu. In the search box, you have to type <strong>'services.msc'</strong> and hit <strong>Enter</strong> to open the <strong>Services</strong> console.

[caption id="attachment_515" align="alignnone" width="884"]<img class="size-full wp-image-515" src="https://windowscrazy.com/wp-content/uploads/2020/05/ps1.png" alt="Open Services" width="884" height="681" /> Open Services[/caption]</li>
 	<li>In the right pane, you have to scroll down and locate <strong>Print Spooler</strong>.

[caption id="attachment_516" align="alignnone" width="945"]<img class="size-full wp-image-516" src="https://windowscrazy.com/wp-content/uploads/2020/05/ps2.png" alt="Locate Print Spooler" width="945" height="570" /> Locate Print Spooler[/caption]</li>
 	<li>Right-click on the Print Spooler and navigate to <strong>Properties</strong> option.

[caption id="attachment_518" align="alignnone" width="935"]<img class="size-full wp-image-518" src="https://windowscrazy.com/wp-content/uploads/2020/05/ps4.png" alt="Choose Properties" width="935" height="568" /> Choose Properties[/caption]</li>
 	<li>In the <strong>General</strong> tab, you have to click on the <strong>Stop</strong> button.

[caption id="attachment_519" align="alignnone" width="939"]<img class="size-full wp-image-519" src="https://windowscrazy.com/wp-content/uploads/2020/05/ps5.png" alt="Click Stop" width="939" height="562" /> Click Stop[/caption]</li>
 	<li>Now, you have to open the <strong>Run command</strong> by using this shortcut <strong>Windows key + R</strong>.</li>
 	<li>Copy and paste the below command and click <strong>OK</strong>.</li>
 	<li><code>C:\Windows\System32\spool\printers</code>

[caption id="attachment_520" align="alignnone" width="430"]<img class="size-full wp-image-520" src="https://windowscrazy.com/wp-content/uploads/2020/05/ps6.png" alt="Open printers folder" width="430" height="234" /> Open printers folder[/caption]</li>
 	<li>You have to click the <strong>Continue</strong> button if prompted.</li>
 	<li>Press <strong>Ctrl + A</strong> to select everything in the <strong>printers</strong> folder and click the <strong>Delete</strong> button.</li>
 	<li>Now, you have to move on to the Print Spooler Properties window. In the General tab, you have to click on the <strong>Start</strong> button.

[caption id="attachment_521" align="alignnone" width="941"]<img class="size-full wp-image-521" src="https://windowscrazy.com/wp-content/uploads/2020/05/ps7.png" alt="Click Start" width="941" height="568" /> Click Start[/caption]</li>
 	<li>Finally, click the <strong>OK</strong> button. Now, you can try to print a document so it works well.

[caption id="attachment_522" align="alignnone" width="941"]<img class="size-full wp-image-522" src="https://windowscrazy.com/wp-content/uploads/2020/05/ps8.png" alt="Click OK" width="941" height="568" /> Click OK[/caption]</li>
</ol>
<h2 id="2">Fix Print Spooler via Command Prompt:</h2>
<ol>
 	<li>Press the <strong>Windows key </strong>on your keyboard to open the <strong>Start</strong> menu. [You can also click the Windows logo in the bottom left corner of your screen]</li>
 	<li>Now, the start menu will open with a cursor in the search box and type <strong>'cmd'</strong> into the search field.

[caption id="attachment_452" align="alignnone" width="888"]<img class="size-full wp-image-452" src="https://windowscrazy.com/wp-content/uploads/2020/05/up1.png" alt="Search for Command Prompt" width="888" height="680" /> Search for Command Prompt[/caption]</li>
 	<li>Right-click on the top result so it will invoke a drop-down menu and then choose <strong>Run as administrator</strong> option so it will open the command prompt with admin privileges.

[caption id="attachment_453" align="alignnone" width="888"]<img class="size-full wp-image-453" src="https://windowscrazy.com/wp-content/uploads/2020/05/up2.png" alt="Run as administrator" width="888" height="680" /> Run as administrator[/caption]</li>
 	<li>You have to press <strong>'Yes'</strong> in order to confirm this choice when prompted.</li>
 	<li>Now, you have to type the following commands one by one in the command prompt and hit <strong>Enter</strong>.</li>
 	<li>To stop print spooler service: <code>net stop spooler</code>

[caption id="attachment_523" align="alignnone" width="751"]<img class="size-full wp-image-523" src="https://windowscrazy.com/wp-content/uploads/2020/05/ps9.png" alt="Stop Print Spooler" width="751" height="403" /> Stop Print Spooler[/caption]</li>
 	<li>To delete the content in the printers folder: <code>del /Q /F /S "%systemroot%\System32\Spool\Printers\*.*"</code>

[caption id="attachment_524" align="alignnone" width="751"]<img class="size-full wp-image-524" src="https://windowscrazy.com/wp-content/uploads/2020/05/ps10.png" alt="Delete printers folder content" width="751" height="403" /> Delete printers folder content[/caption]</li>
 	<li>To start the print spooler: <code>net start spooler</code>

[caption id="attachment_525" align="alignnone" width="751"]<img class="size-full wp-image-525" src="https://windowscrazy.com/wp-content/uploads/2020/05/ps11.png" alt="Start Print Spooler" width="751" height="403" /> Start Print Spooler[/caption]</li>
 	<li>Once you complete the above steps, your printer should work well now.</li>
</ol>
<h2 id="3">Wrap-up:</h2>
As you can see, the above two ways are really simple to <strong>Fix Print Spooler Issues in Windows 10</strong>. You can follow any one of the ways to fix the problem and start to print again. Your <strong>comments</strong> are highly welcomed so don't forget to share it. Thanks for visiting <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.