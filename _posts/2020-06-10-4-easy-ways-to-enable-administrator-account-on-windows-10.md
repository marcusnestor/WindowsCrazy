---
ID: 1176
post_title: '(*4 Easy Ways *) to Enable Administrator Account on Windows 10!'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1176-4-easy-ways-to-enable-administrator-account-on-windows-10/
published: true
post_date: 2020-06-10 06:21:01
---
<ul class="toc">
 	<li><a href="#1">Enable Administrator Account via Command Prompt</a></li>
 	<li><a href="#2">How to Enable Administrator Account using Group Policy Editor?</a></li>
 	<li><a href="#3">Enable Administrator Account via Local Users and Groups</a></li>
 	<li><a href="#4">Use Powershell to Enable Administrator Account</a></li>
 	<li><a href="#5">Verdict</a></li>
</ul>
<span class="dcap">E</span><strong>nable Administrator Account in Windows 10</strong>: In Windows 10, when you are on the welcome or login screen, you will not see the Administrator account as an option by default. There are several ways to enable this feature within a few efforts. In this article, you will learn four different ways on how to <strong>Enable Administrator Account in Windows 10 </strong>quickly.
<h2 id="1">1) Enable Administrator Account via Command Prompt:</h2>
<ol>
 	<li>Press the <strong>Windows key </strong>on your keyboard to open the <strong>Start</strong> menu. [You can also click the Windows logo in the bottom left corner of your screen]</li>
 	<li>Now, the start menu will open with a cursor in the search box and type <strong>'cmd'</strong> into the search field.

[caption id="attachment_452" align="alignnone" width="888"]<img class="size-full wp-image-452" src="https://windowscrazy.com/wp-content/uploads/2020/05/up1.png" alt="Search for Command Prompt" width="888" height="680" /> Search for Command Prompt[/caption]</li>
 	<li>Right-click on the top result so it will invoke a drop-down menu and then choose <strong>Run as administrator</strong> option so it will open the command prompt with admin privileges.

[caption id="attachment_453" align="alignnone" width="888"]<img class="size-full wp-image-453" src="https://windowscrazy.com/wp-content/uploads/2020/05/up2.png" alt="Run as administrator" width="888" height="680" /> Run as administrator[/caption]</li>
 	<li>You have to press <strong>'Yes'</strong> in order to confirm this choice when prompted.</li>
 	<li>Type the below command and hit <strong>Enter</strong> to enable a built-in administrator account.<code>net user "Administrator" /active:yes</code>

[caption id="attachment_1185" align="alignnone" width="683"]<img class="size-full wp-image-1185" src="https://windowscrazy.com/wp-content/uploads/2020/06/ea4.png" alt="Command Prompt" width="683" height="428" /> Command Prompt[/caption]</li>
 	<li>Now, you can sign out of the account and sign in with the administrator account on your Windows system.</li>
</ol>
<blockquote>Tip: If you want to disable the administrator account, you have to run this command <code>net user "Administrator" /active:no</code></blockquote>
<h2 id="2">2) How to Enable Administrator Account using Group Policy Editor?</h2>
<ol>
 	<li>Using this shortcut <strong>Windows + R,</strong> you can open the Run command dialog box.</li>
 	<li>After that, you have to type as <strong>gpedit.msc</strong> in the given space of <strong>Open</strong> and click <strong><strong>OK.</strong></strong>

[caption id="attachment_1182" align="alignnone" width="426"]<img class="size-full wp-image-1182" src="https://windowscrazy.com/wp-content/uploads/2020/06/ea1.png" alt="gpedit.msc" width="426" height="230" /> gpedit.msc[/caption]</li>
 	<li>Now, it will open the <strong>Local Group Policy Editor</strong>.</li>
 	<li>Follow the below path,
<code>Computer Configuration &gt; Windows Settings &gt; Security Settings &gt;
Local Policies &gt; Security Options</code></li>
 	<li>Now, you have to double-click on <strong>Accounts: Administrator Account Status</strong>.

[caption id="attachment_1183" align="alignnone" width="924"]<img class="size-full wp-image-1183" src="https://windowscrazy.com/wp-content/uploads/2020/06/ea2.png" alt="Administrator" width="924" height="618" /> Administrator[/caption]</li>
 	<li>Then, you have to select the <strong>Enabled</strong> option and click <strong>Apply</strong> and then <strong>OK</strong>.

[caption id="attachment_1184" align="alignnone" width="926"]<img class="size-full wp-image-1184" src="https://windowscrazy.com/wp-content/uploads/2020/06/ea3.png" alt="Enable" width="926" height="618" /> Enable[/caption]</li>
</ol>
<h2 id="3">3) Enable Administrator Account via Local Users and Groups:</h2>
<ol>
 	<li>On your keyboard, you have to hit the <strong>Windows Key + R</strong> button combination to open the Run Command box.</li>
 	<li>Then, you have to type <strong>lusrmgr.msc </strong>and click <strong>OK</strong>.

[caption id="attachment_1186" align="alignnone" width="426"]<img class="size-full wp-image-1186" src="https://windowscrazy.com/wp-content/uploads/2020/06/ea5.png" alt="lusrmgr.msc" width="426" height="228" /> lusrmgr.msc[/caption]</li>
 	<li>Now, click on the <strong>Users</strong> option.</li>
 	<li>After that, you have to double-click on the <strong>Administrator</strong>.

[caption id="attachment_1187" align="alignnone" width="728"]<img class="size-full wp-image-1187" src="https://windowscrazy.com/wp-content/uploads/2020/06/ea6.png" alt="Administrator" width="728" height="508" /> Administrator[/caption]</li>
 	<li>Uncheck the <strong>'Account is disabled'</strong> option.</li>
 	<li>Then, you have to click on the <strong>Apply</strong> and <strong>OK</strong> button.

[caption id="attachment_1188" align="alignnone" width="728"]<img class="size-full wp-image-1188" src="https://windowscrazy.com/wp-content/uploads/2020/06/ea7.png" alt="Administrator Properties" width="728" height="502" /> Administrator Properties[/caption]</li>
</ol>
<h2 id="4">4) Use Powershell to Enable Administrator Account:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu, search for <strong>‘powershell’ </strong>in the search box.</li>
 	<li>Right-click on the top result and choose <strong>Run as administrator</strong>.

[caption id="attachment_1189" align="alignnone" width="878"]<img class="size-full wp-image-1189" src="https://windowscrazy.com/wp-content/uploads/2020/06/ea8.png" alt="Powershell" width="878" height="666" /> Powershell[/caption]</li>
 	<li>After that, you have to copy and paste the below command and hit <strong>Enter</strong>.
<code>Get-LocalUser -Name "Administrator" | Enable-LocalUser</code>

[caption id="attachment_1190" align="alignnone" width="830"]<img class="size-full wp-image-1190" src="https://windowscrazy.com/wp-content/uploads/2020/06/ea9.png" alt="PowerShell - Run command" width="830" height="417" /> PowerShell - Run command[/caption]</li>
 	<li>That's it. Now the administrator account will be enabled.</li>
</ol>
<h2 id="5">Verdict:</h2>
We hope that this tutorial guided you with four simple ways to <strong>Enable Administrator Account in Windows 10</strong>. Follow any one of the above methods and enable the administrator account in your Windows system. If you find this article helpful, kindly share your valuable <strong>comments</strong> in the below section. Thanks for visiting <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.