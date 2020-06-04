---
ID: 245
post_title: >
  2 Methods to Reset the Windows Update on
  Windows 10!!
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/245-2-methods-to-reset-the-windows-update-on-windows-10/
published: true
post_date: 2020-05-23 07:06:08
---
<ul class="toc">
 	<li><a href="#1">How to Reset the Windows Update on Windows 10?</a></li>
 	<li><a href="#2">Closure</a></li>
</ul>
<strong><span class="dcap">R</span><strong>eset Windows Update on Windows 10</strong>: </strong>Update provides the ability to download and install the latest updates with bug fixes, security patches, and drivers.

In this article, we will guide you with some simple methods to<strong> reset the Windows Update in easy steps.</strong>
<h2 id="1">How to Reset the Windows Update on Windows 10?</h2>
In two methods you can reset the Windows Update on Windows 10 with step by step procedure using this helpful article.
<h3>Method 1: Reset Windows Update using Command Prompt</h3>
<ul>
 	<li>Go to <strong>Start Menu, </strong>type<strong> Command Prompt </strong>in Search column.</li>
 	<li>Command Prompt appears at the top of the Start Menu,<strong> right-click</strong> on it and choose <strong>Run as administrator option.</strong></li>
 	<li>The <strong>User Account Control</strong> dialog box gets open, in that select the <strong>Yes option.</strong></li>
 	<li>To stop the Background Intelligent Transfer Service (BITS), Windows Update service, and Cryptographic service,<strong> copy and paste the following commands</strong> in your Command Prompt Window.</li>
</ul>
<pre><code>net stop bits
net stop wuauserv
net stop appidsvc
net stop cryptsvc</code></pre>
<strong>Note:</strong> Don't Forget to press Enter on each line of commands.

[caption id="attachment_310" align="aligncenter" width="1057"]<img class="wp-image-310 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_6-2.png" alt="To stop services command" width="1057" height="683" /> To stop services command[/caption]
<ul>
 	<li>To delete all the <strong>qmgr*.dat</strong> files created by BITS from your PC, simply <strong>copy and paste the below command</strong> and Type<strong> Y</strong> to confirm the deletion.</li>
</ul>
<code>Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"</code>
<ul>
 	<li><strong>Copy and paste the below mentioned commands</strong> one by one in your Command Prompt, To clear the Windows Update cache to allow Windows 10 re-download the updates, instead of using the files already downloaded on your system that might be damaged.</li>
</ul>
<pre><code>rmdir %systemroot%\SoftwareDistribution /S /Q
rmdir %systemroot%\system32\catroot2 /S /Q</code></pre>
<ul>
 	<li>To reset the <strong>BITS</strong> and <strong>Windows Update services</strong> to their default security descriptor, type the following commands.</li>
</ul>
<pre><code>sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)
(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)
(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)</code></pre>
<ul>
 	<li>Move to the System32 folder,<strong> copy &amp; paste</strong> the following command.</li>
</ul>
<pre><code>cd /d %windir%\system32</code></pre>
<ul>
 	<li>To register all the corresponding BITS and Windows Update DLL files on the Registry, just <strong>copy and paste the below commands</strong> in command prompt window.</li>
</ul>
<pre><code>regsvr32.exe /s atl.dll
regsvr32.exe /s urlmon.dll
regsvr32.exe /s mshtml.dll
regsvr32.exe /s shdocvw.dll
regsvr32.exe /s browseui.dll
regsvr32.exe /s jscript.dll
regsvr32.exe /s vbscript.dll
regsvr32.exe /s scrrun.dll
regsvr32.exe /s msxml.dll
regsvr32.exe /s msxml3.dll
regsvr32.exe /s msxml6.dll
regsvr32.exe /s actxprxy.dll
regsvr32.exe /s softpub.dll
regsvr32.exe /s wintrust.dll
regsvr32.exe /s dssenh.dll
regsvr32.exe /s rsaenh.dll
regsvr32.exe /s gpkcsp.dll
regsvr32.exe /s sccbase.dll
regsvr32.exe /s slbcsp.dll
regsvr32.exe /s cryptdlg.dll
regsvr32.exe /s oleaut32.dll
regsvr32.exe /s ole32.dll
regsvr32.exe /s shell32.dll
regsvr32.exe /s initpki.dll
regsvr32.exe /s wuapi.dll
regsvr32.exe /s wuaueng.dll
regsvr32.exe /s wuaueng1.dll
regsvr32.exe /s wucltui.dll
regsvr32.exe /s wups.dll
regsvr32.exe /s wups2.dll
regsvr32.exe /s wuweb.dll
regsvr32.exe /s qmgr.dll
regsvr32.exe /s qmgrprxy.dll
regsvr32.exe /s wucltux.dll
regsvr32.exe /s muweb.dll
regsvr32.exe /s wuwebv.dll</code></pre>
<ul>
 	<li>Copy and paste the below commands to<strong> reset the network configurations</strong> that might be part of the problem.</li>
</ul>
<pre><code>netsh winsock reset
netsh winsock reset proxy</code></pre>
<strong>Note:</strong> Don't restart your computer.

[caption id="attachment_311" align="aligncenter" width="1065"]<img class="wp-image-311 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_7-2.png" alt=" To reset the network configurations" width="1065" height="610" /> To reset the network configurations[/caption]
<ul>
 	<li>To<strong> restart the BITS, Windows Update, and Cryptographic services,</strong> type the following commands.</li>
</ul>
<pre><code>net start bits
net start wuauserv
net start appidsvc
net start cryptsvc</code></pre>
<ul>
 	<li>Now, <strong>Restart your computer.</strong></li>
</ul>
<h3>Method 2: Reset Windows Update using Troubleshooter</h3>
<ul>
 	<li>First, <a href="http://download.microsoft.com/download/F/E/7/FE74974A-9029-41A0-9EB2-9CCE3FC20B99/WindowsUpdateDiagnostic.diagcab"><strong>Download the Windows Update Troubleshooter.</strong></a></li>
 	<li>Simply clicking the above link the <strong>Troubleshooter</strong> will be <strong>downloaded</strong> at the bottom of the screen.</li>
 	<li><strong>Double click</strong> on the downloaded file.</li>
 	<li>Then, the <strong>Windows Update window</strong> gets open.</li>
 	<li>In that, select the <strong>Windows Update option</strong> and click <strong>Next.</strong></li>
</ul>
[caption id="attachment_308" align="aligncenter" width="950"]<img class="wp-image-308 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_4-3.png" alt="Windows Update" width="950" height="584" /> Windows Update[/caption]
<ul>
 	<li>Windows Update detecting problems.</li>
</ul>
[caption id="attachment_307" align="aligncenter" width="963"]<img class="wp-image-307 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_3-3.png" alt="Detecting Problems" width="963" height="596" /> Detecting Problems[/caption]
<ul>
 	<li>Click the <strong>Try troubleshooting as an administrator</strong> option and click <strong>close.</strong></li>
</ul>
[caption id="attachment_305" align="aligncenter" width="847"]<img class="wp-image-305 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_1-3.png" alt="Windows Update" width="847" height="585" /> Windows Update[/caption]
<ul>
 	<li>The <strong>Windows Update Troubleshoote</strong>r will get open again.</li>
 	<li>Then, select the <strong>Windows Networking Diagnostics </strong>option to resolve any networking issues preventing updates from downloading and click <strong>Next.</strong></li>
</ul>
[caption id="attachment_309" align="aligncenter" width="975"]<img class="wp-image-309 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_5-3.png" alt="Windows Update" width="975" height="581" /> Windows Update[/caption]
<ul>
 	<li>At last, click the <strong>close.</strong></li>
 	<li>Finally, <strong>restart your computer.</strong></li>
</ul>
<h2 id="2">Closure:</h2>
In this article, we will help you to <strong>Reset Windows Update on Windows 10</strong> using simple steps. Kindly share if any <strong>queries/suggestions</strong> in the below comment section and Don't forget to drop your worthwhile <strong>feedback.</strong>