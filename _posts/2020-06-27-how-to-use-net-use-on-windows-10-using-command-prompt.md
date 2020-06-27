---
ID: 2006
post_title: 'How to use &#8220;Net Use&#8221; on Windows 10 Using Command Prompt?'
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/2006-how-to-use-net-use-on-windows-10-using-command-prompt/
published: true
post_date: 2020-06-27 09:43:04
---
<ul class="toc">
 	<li><a href="#1">To map a network drive by using Command Prompt</a></li>
 	<li><a href="#2">Verdict</a></li>
</ul>
<strong><span class="dcap">H</span>ow to use Command Prompt to map a network drive on Windows 10? </strong>By using different ways we can<strong> map a network drive</strong> to access files stored on another PC in the network.

In this guide, you can get clarity on<strong> How to use Command Prompt to map a network drive on Windows 10.</strong>
<h2 id="1">To map a network drive by using Command Prompt:</h2>
Follow the below steps to map a network drive by using Command Prompt.
<ul>
 	<li>First, before using these commands you have to know the<strong> UNC path</strong> of the shared folder.</li>
 	<li>Go to the <strong>start menu.</strong></li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li><strong>Right-click</strong> on the Command Prompt and select<strong> Run as administrator</strong> option which appears at the top of the start menu.

[caption id="attachment_759" align="aligncenter" width="488"]<img class="size-full wp-image-759" src="https://windowscrazy.com/wp-content/uploads/2020/05/Screenshot_4-8.png" alt="Start Menu" width="488" height="768" /> Start Menu[/caption]</li>
 	<li>The <strong>drive letter Z</strong> can be used to map a network drive that <strong>isn’t password-protected.</strong></li>
 	<li><strong>Type</strong> the following command and press <strong>Enter</strong>.</li>
 	<li>Here, the following command is to map a network drive using <strong>Z as the drive letter </strong>that is<strong> password protected.</strong></li>
 	<li><strong>Copy and Paste</strong> the following command and press <strong>Enter</strong>.
<pre><code>net use z: \\networkShare\files</code></pre>
</li>
</ul>
[caption id="attachment_2022" align="aligncenter" width="665"]<img class="size-full wp-image-2022" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_Kw1PgWROTs.png" alt="Net use command" width="665" height="220" /> Net use command[/caption]
<ul>
 	<li>By using the username and password of your shared folder, is below command is to <strong>remember to replace userName and PaZZw0wd.</strong></li>
 	<li>Type the<strong> following command</strong> and press <strong>Enter</strong>.
<pre><code>net use z: \\networkShare\files /user:userName PaZZw0rd</code></pre>
</li>
</ul>
[caption id="attachment_2021" align="aligncenter" width="866"]<img class="size-full wp-image-2021" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_Hm3t0LJeIB.png" alt="Net use command with username and password" width="866" height="252" /> Net use command with username and password[/caption]
<ul>
 	<li>By using the above commands, when you <strong>restart your computer</strong> the maps will be automatically<strong> removed.</strong></li>
 	<li>When you specify to be <strong>persistent</strong>, the <strong>map</strong> will stay connected <strong>after rebooting.</strong></li>
 	<li>Then, <strong>follow</strong> the below command.</li>
 	<li>Press <strong>Enter</strong>.
<pre><code>net use z: \\networkShare\files /P:yes</code></pre>
</li>
</ul>
[caption id="attachment_2020" align="aligncenter" width="705"]<img class="size-full wp-image-2020" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_4AoYGqQPMZ.png" alt="Net use persistent command" width="705" height="202" /> Net use persistent command[/caption]
<ul>
 	<li>Here, <strong>/P</strong> switch indicates that the connection to the network share will be persistent.</li>
 	<li>When you use<strong> Z as the drive letter</strong> to map a network drive, then if you want <strong>to remove, disconnect, or delete.</strong></li>
 	<li>Type the<strong> following command</strong> and press <strong>Enter</strong>.
<pre><code>net use z: /Delete</code></pre>
</li>
</ul>
[caption id="attachment_2019" align="aligncenter" width="607"]<img class="size-full wp-image-2019" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_7Fh1E0hKbv.png" alt="Net use delete mapped network drive" width="607" height="219" /> Net use delete mapped network drive[/caption]
<ul>
 	<li>When using <strong>more than one network drive</strong> mapped on your computer, you can <strong>disconnect them all</strong> by using the <strong>following command.</strong></li>
 	<li>Press <strong>Enter</strong>.
<pre><code>net use * /Delete</code></pre>
</li>
</ul>
[caption id="attachment_2018" align="aligncenter" width="596"]<img class="size-full wp-image-2018" src="https://windowscrazy.com/wp-content/uploads/2020/06/chrome_pZ1kq5twG7.png" alt="Net use delete all mapped network drive" width="596" height="203" /> Net use delete all mapped network drive[/caption]
<ul>
 	<li>That's all.</li>
</ul>
<strong>Image Source:</strong> <em>pureinfotech.com</em>
<h2 id="2">Verdict:</h2>
This guide assisted you in <strong>How to use Net Use on Windows 10 Using Command Prompt</strong> in clear-cut steps. Kindly share if any case of q<strong>ueries/suggestions</strong> in the below comment section and drop your valuable <strong>feedback</strong>.