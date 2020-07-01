---
ID: 2223
post_title: >
  Reset Microsoft Store on Windows 10 to
  Fix Problems!!
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/2223-reset-microsoft-store-on-windows-10-to-fix-problems/
published: true
post_date: 2020-07-01 08:50:56
---
<ul class="toc">
 	<li><a href="#1">Fix Microsoft Store using Windows Settings</a></li>
 	<li><a href="#2">Fix Microsoft Store using WSReset command</a></li>
 	<li><a href="#3">Fix Microsoft Store reinstalling app</a></li>
 	<li><a href="#4">Verdict</a></li>
</ul>
<strong><span class="dcap">H</span>ow to fix Microsoft Store problems on Windows 10? </strong>To <strong>download and install</strong> apps, games, and entertainment securely, then the <strong>Microsoft Store</strong> is the best platform.

In this article, we explain <strong>How to fix Microsoft Store problems on Windows 10</strong> in simple steps.
<h2 id="1">Fix Microsoft Store using Windows Settings:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + I</strong> to open <strong>Windows Settings.</strong></li>
 	<li>In the settings window, select the <strong>Apps</strong> option.</li>
 	<li>In the left pane, click on<strong> Apps &amp; features.</strong></li>
 	<li>Now, select the<strong> Microsoft Store</strong> under that click the <strong>Advanced options</strong> in the right pane.

[caption id="attachment_2225" align="aligncenter" width="970"]<img class="size-full wp-image-2225" src="https://windowscrazy.com/wp-content/uploads/2020/07/l6Lqh1uoDe.png" alt="Apps" width="970" height="570" /> Apps[/caption]</li>
 	<li>Then, click the <strong>Reset</strong> button.

[caption id="attachment_2224" align="aligncenter" width="592"]<img class="size-full wp-image-2224" src="https://windowscrazy.com/wp-content/uploads/2020/07/DFkVx7GZK5.png" alt="Reset" width="592" height="653" /> Reset[/caption]</li>
 	<li>Now, it will <strong>delete the data</strong> and <strong>reset</strong> <strong>the</strong> <strong>app</strong> to its default settings.</li>
 	<li>That's all.</li>
</ol>
<h2 id="2">Fix Microsoft Store using WSReset command:</h2>
<ol>
 	<li>Click on the shortcut <strong>Windows + R</strong> to open the <strong>Run command dialog</strong> <strong>box</strong>.</li>
 	<li>Type <strong>WSReset.exe</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_2226" align="aligncenter" width="442"]<img class="size-full wp-image-2226" src="https://windowscrazy.com/wp-content/uploads/2020/07/explorer_SRtRsrVkrK.png" alt="Run command" width="442" height="252" /> Run command[/caption]</li>
 	<li>The <strong>whole</strong> <strong>process</strong> will be executed automatically.</li>
</ol>
<h2 id="3">Fix Microsoft Store reinstalling app:</h2>
<strong>Uninstall Microsoft Store:</strong>
<ol>
 	<li>Go to the<strong> start menu.</strong></li>
 	<li>In the search column, type as <strong>PowerShell.</strong></li>
 	<li>Right-click on the <strong>PowerShell</strong> and select <strong>Run as Administrator</strong> option.

[caption id="attachment_2229" align="aligncenter" width="475"]<img class="size-full wp-image-2229" src="https://windowscrazy.com/wp-content/uploads/2020/07/explorer_qb5Lhd0uac.png" alt="PowerShell" width="475" height="769" /> PowerShell[/caption]</li>
 	<li>Then, to <strong>get the information </strong>from the Microsoft Store app.</li>
 	<li><strong>Type</strong> the following command and press <strong>Enter</strong>.
<pre><code>Get-AppxPackage -name *WindowsStore*</code></pre>
</li>
 	<li><strong>Select</strong> the content which is shown in the<strong> below screenshot</strong> and right-click on it to <strong>copy</strong> the content to the clipboard.

[caption id="attachment_2230" align="aligncenter" width="1766"]<img class="size-full wp-image-2230" src="https://windowscrazy.com/wp-content/uploads/2020/07/powershell_d7VxFSWfUp.png" alt="Commands" width="1766" height="654" /> Commands[/caption]</li>
 	<li>Then, Go to the<strong> start menu.</strong></li>
 	<li>In the search column, type as <strong>Notepad</strong>.</li>
 	<li><strong>Tap</strong> it which appears at the top of the start menu.

[caption id="attachment_2227" align="aligncenter" width="475"]<img class="size-full wp-image-2227" src="https://windowscrazy.com/wp-content/uploads/2020/07/explorer_8h5f8YeWxo.png" alt="Notepad" width="475" height="770" /> Notepad[/caption]</li>
 	<li>Now, <strong>paste</strong> the copied content and <strong>save</strong> the Notepad.</li>
 	<li>To <strong>remove</strong> the Microsoft Store app, then copy and paste the following command.
<pre><code>Get-AppxPackage Microsoft.WindowsStore | Remove-AppxPackage</code></pre>
[caption id="attachment_2228" align="aligncenter" width="1508"]<img class="size-full wp-image-2228" src="https://windowscrazy.com/wp-content/uploads/2020/07/powershell_tY69Jlo7bj.png" alt="Commands" width="1508" height="313" /> Commands[/caption]</li>
 	<li>Press <strong>Enter</strong>.</li>
</ol>
<strong>Install Microsoft Store:</strong>
<ol>
 	<li>Go to the<strong> start menu.</strong></li>
 	<li>In the search column, type as <strong>PowerShell.</strong></li>
 	<li>Right-click on the <strong>PowerShell</strong> and select <strong>Run as Administrator</strong> option.

[caption id="attachment_2229" align="aligncenter" width="475"]<img class="size-full wp-image-2229" src="https://windowscrazy.com/wp-content/uploads/2020/07/explorer_qb5Lhd0uac.png" alt="PowerShell" width="475" height="769" /> PowerShell[/caption]</li>
 	<li>Now, <strong>select</strong> and <strong>paste</strong> the content which you have copied.</li>
 	<li>To replace YourStorePacakgeName with the package name you <strong>copied</strong> to the clipboard.</li>
 	<li>It should look something like this.
<pre><code>Microsoft.WindowsStore_2015.7.1.0_x64__8wekyb3d8bbwe</code></pre>
</li>
 	<li><strong>Copy and paste</strong> the below-mentioned command and press Enter.
<pre><code>Add-AppxPackage -register "C:\Program 
Files\WindowsApps\YourStorePakageName\AppxManifest.xml" -DisableDevelopmentMode</code></pre>
</li>
 	<li>Now, <strong>restart your PC.</strong></li>
 	<li>That's all.</li>
</ol>
<h2 id="4">Verdict:</h2>
Hopefully, this article assisted you to learn information on <strong>How to fix Microsoft Store problems on Windows 10.</strong> Don’t forget to share your <strong>comments</strong> in the below section and leave your <strong>worthwhile</strong> <strong>feedback</strong>.