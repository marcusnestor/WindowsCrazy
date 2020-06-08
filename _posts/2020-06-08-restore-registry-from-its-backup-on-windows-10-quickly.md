---
ID: 1078
post_title: 'Restore Registry from its backup on Windows 10!! [Quickly]'
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1078-restore-registry-from-its-backup-on-windows-10-quickly/
published: true
post_date: 2020-06-08 13:10:45
---
<ul class="toc">
 	<li><a href="#1">Restore Registry from its backup on Windows 10</a></li>
 	<li><a href="#2">Summary</a></li>
</ul>
<strong><strong><strong><span class="dcap">H</span><strong>ow to Restore Registry from its backup on Windows 10? </strong></strong></strong></strong>To modify the <strong>Registry</strong> to change specific system settings, and if you forget to create the <strong>backup</strong>, or during an installation of a faulty update the <strong>Registry</strong> gets <strong>corrupted</strong>, you can still recover Windows 10 using the secret Registry backup.<strong> To edit the Registry</strong>, because the database contains<strong> low-level settings</strong> necessary for the <strong>OS</strong> and certain apps to work correctly. Probably, <strong>OS</strong> keeps a backup of a working <strong>Registry</strong> for recovery purposes, which you can use to manually <strong>restore your computer</strong> to a working condition when you don’t have a backup.

Here, this article will help you to <strong>Restore Registry from its backup on Windows 10 </strong>in simple steps.
<h2 id="1"><strong>Restore Registry from its backup on Windows 10:</strong></h2>
Follow the steps to <strong>Restore Registry from its backup on Windows 10 </strong>in simple and easy steps.
<ol>
 	<li>First, open the Windows Settings using shortcut <strong>Windows + I.</strong></li>
 	<li>Then, select <strong>Update &amp; security.</strong>

[caption id="attachment_1086" align="aligncenter" width="1094"]<img class="wp-image-1086 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_7.png" alt="Windows Settings" width="1094" height="657" /> Windows Settings[/caption]</li>
 	<li>In the left pane, select the <strong>Recovery</strong> option.</li>
 	<li>Under the <strong>Advanced</strong> <strong>startup</strong>, click the <strong>Restart</strong> <strong>now</strong> button.

[caption id="attachment_1080" align="aligncenter" width="1167"]<img class="wp-image-1080 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_1-5.png" alt="Recovery" width="1167" height="815" /> Recovery[/caption]</li>
 	<li>Then click the <strong>Troubleshoot</strong> option.</li>
 	<li>After that, click the <strong>Advanced</strong> <strong>options</strong> and select the <strong>Command</strong> <strong>Prompt</strong>.</li>
 	<li>Now, the <strong>Command Prompt</strong> window gets open, in that it starts with<strong> X:\Windows\System32</strong>. The operating system is installed on <strong>C:\</strong> when you boot your computer on <strong>recovery</strong> mode, this drive letter changes to something else. However, in most cases, the drive letter is <strong>D:\</strong>.</li>
 	<li><strong>Copy and Paste the following command</strong> to enter into the correct drive where Windows is installed.</li>
 	<li>Press <strong><strong>Enter.</strong></strong>
<pre><code>d:\</code></pre>
</li>
 	<li>Now, type the following command to <strong>verify</strong> that you are in the correct drive and press <strong><strong>Enter.</strong></strong>
<pre><code>dir</code></pre>
[caption id="attachment_1081" align="aligncenter" width="1234"]<img class="wp-image-1081 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_2-5.png" alt="Commands" width="1234" height="642" /> Commands[/caption]</li>
 	<li><strong>To enter into the System32 folder,</strong> simply Copy and Paste the below-mentioned command and press <strong><strong>Enter.</strong></strong>
<pre><code>cd d:\windows\system32</code></pre>
</li>
 	<li>Don't forget to <strong>change D</strong> in the command with the correct drive letter.

[caption id="attachment_1082" align="aligncenter" width="1233"]<img class="wp-image-1082 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_3-3.png" alt="Commands" width="1233" height="638" /> Commands[/caption]</li>
 	<li>To create a folder to <strong>temporarily</strong> backup files <strong>on the config folder</strong>, which also happens to store a copy of the Registry.</li>
 	<li>Type the <strong>following</strong> command and press Enter.
<pre><code>mkdir configBak</code></pre>
</li>
 	<li> Again to create a <strong>temporary</strong> backup of the files<strong> in the config folder.</strong></li>
 	<li><strong>Copy and paste</strong> the below command and press Enter.
<pre><code>copy config configBak</code></pre>
[caption id="attachment_1083" align="aligncenter" width="1231"]<img class="wp-image-1083 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_4-1.png" alt="Commands" width="1231" height="641" /> Commands[/caption]</li>
 	<li>To move inside the <strong>RegBack</strong>, which contains a<strong> backup of the Registry,</strong> just type the <strong>following</strong> <strong>command</strong> and press <strong>Enter</strong>.
<pre><code>cd config\RegBack</code></pre>
</li>
 	<li> Now, to <strong>verify</strong> the content of the <strong>RegBack</strong> folder,<strong> Copy and paste</strong> the command and press <strong><strong>Enter.</strong></strong>
<pre><code>dir</code></pre>
[caption id="attachment_1084" align="aligncenter" width="1231"]<img class="wp-image-1084 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_5.png" alt="Commands" width="1231" height="640" /> Commands[/caption]</li>
 	<li><strong>Copy and paste</strong> the below command to<strong> copy the files</strong> from the <strong>RegBack</strong> <strong>folder</strong> to the <strong>config folder.</strong></li>
 	<li>Press <strong>Enter</strong> to proceed and <strong>Press Y</strong> on each line.
<pre><code>copy * ..\*</code></pre>
[caption id="attachment_1085" align="aligncenter" width="1233"]<img class="wp-image-1085 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_6.png" alt="Commands" width="1233" height="642" /> Commands[/caption]</li>
 	<li>Finally, click the <strong>Close</strong> button from the top-right.</li>
</ol>
<h2 id="2">Summary:</h2>
In this article, we will help you to know <strong>how to restore Registry from its backup on Windows 10</strong> using simple steps. Kindly share if any <strong>queries/suggestions</strong> in the below comment section and Don't forget to drop your worthwhile <strong>feedback.</strong>