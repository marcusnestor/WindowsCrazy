---
ID: 449
post_title: >
  Change Password using Net User Command
  in Windows 10!!
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/449-change-password-using-net-user-command-in-windows-10/
published: true
post_date: 2020-05-26 08:35:45
---
<ul class="toc">
 	<li><a href="#1">Change Password using Net User Command</a></li>
 	<li><a href="#2">Verdict</a></li>
</ul>
<span class="dcap">C</span><strong>hange User Password in Windows 10</strong>: Changing the user password is quite easy and effortless in Windows 10 with the use of<strong> net user</strong> command. You just have to make use of Command Prompt to change the password of user accounts in your Windows PC. It is really the quickest way.

In this article, you will learn how to <strong>Change the Password using Net User Command in Windows 10</strong>.
<h2 id="1">Change Password using Net User Command:</h2>
<ul>
 	<li>Press the <strong>Windows key </strong>on your keyboard to open the <strong>Start</strong> menu. [You can also click the Windows logo in the bottom left corner of your screen]</li>
 	<li>Now, the start menu will open with a cursor in the search box and type <strong>'cmd'</strong> into the search field.

[caption id="attachment_452" align="alignnone" width="888"]<img class="size-full wp-image-452" src="https://windowscrazy.com/wp-content/uploads/2020/05/up1.png" alt="Search for Command Prompt" width="888" height="680" /> Search for Command Prompt[/caption]</li>
 	<li>Right-click on the top result so it will invoke a drop-down menu and then choose <strong>Run as administrator</strong> option so it will open the command prompt with admin privileges.

[caption id="attachment_453" align="alignnone" width="888"]<img class="size-full wp-image-453" src="https://windowscrazy.com/wp-content/uploads/2020/05/up2.png" alt="Run as administrator" width="888" height="680" /> Run as administrator[/caption]</li>
 	<li>You have to press <strong>'Yes'</strong> in order to confirm this choice when prompted.</li>
 	<li>Type the below command and hit <strong>Enter</strong> to list all user accounts on your Windows PC.</li>
</ul>
<code>net user</code>

[caption id="attachment_454" align="alignnone" width="811"]<img class="size-full wp-image-454" src="https://windowscrazy.com/wp-content/uploads/2020/05/up3.png" alt="List of User Accounts" width="811" height="480" /> List of User Accounts[/caption]
<ul>
 	<li>Then, you have to type the following command and press <strong>Enter</strong> to change the account password. You have to replace 'USERNAME' with the name of the account for which you wish to change the password.</li>
</ul>
<code>net user USERNAME *</code>
<ul>
 	<li>Then, you have to <strong>'Type a new password for the user'</strong> and press <strong>Enter</strong>.</li>
 	<li>After that, you have to <strong>'Retype the new password to confirm'</strong> and press <strong>Enter</strong>.</li>
 	<li>Once the two entries of the password match each other, you will see <strong>'The command completed successfully'</strong>. The next time when you log onto the account which you changed the password,  you will need to enter your updated password to continue.

[caption id="attachment_455" align="alignnone" width="811"]<img class="size-full wp-image-455" src="https://windowscrazy.com/wp-content/uploads/2020/05/up4.png" alt="Change Password" width="811" height="480" /> Change Password[/caption]</li>
</ul>
<p id="note">Note: The above steps will not be applicable if your user account is linked to your Microsoft Account.</p>

<h2 id="2">Verdict:</h2>
We hope that this tutorial guided you with simple steps to <strong>Change the Password using Net User Command in Windows 10</strong>. Changing a password for your user account is really easy via the Command Prompt. If you find this article helpful, kindly share your valuable <strong>comments</strong> in the below section. Thanks for visiting <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.