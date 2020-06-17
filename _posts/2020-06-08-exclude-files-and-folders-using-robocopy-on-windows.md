---
ID: 1088
post_title: >
  Exclude files and folders using Robocopy
  on Windows !!
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1088-exclude-files-and-folders-using-robocopy-on-windows/
published: true
post_date: 2020-06-08 13:10:34
---
<ul class="toc">
 	<li><a href="#1">Exclude file and folder using Robocopy</a></li>
 	<li><a href="#2">Exclude folder using Robocopy</a></li>
 	<li><a href="#3">Exclude file using Robocopy</a></li>
 	<li><a href="#4">Verdict</a></li>
</ul>
<strong><strong><strong><span class="dcap">H</span><strong>ow to Exclude files and folders using Robocopy on Windows? </strong></strong></strong></strong>Robocopy is a <strong>powerful file management</strong> command-line tool. It has options to<strong> transfer files and folders</strong> to another location faster and more reliably than using <strong>File Explorer.</strong> The tool includes the least<strong> two options,</strong> which you can use to <strong>exclude files and folders</strong> from a copy process. By default, Robocopy transfers everything on a given path, which may not be ideal in every scenario as you may have <strong>specific files and folders in a location </strong>that you don’t want to copy.

In the article, we describe some steps to <strong>Exclude files and folders using Robocopy on Windows</strong> in simple ways.
<h2 id="1">Exclude file and folder using Robocopy:</h2>
Follow the below steps to Exclude file and folder using Robocopy in simple steps.
<ol>
 	<li>Go to the <strong>Start Menu.</strong></li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li>Then, the icon appears at the top of the start menu.</li>
 	<li>Right-click and select the <strong>Run as Administrator option.</strong>

[caption id="attachment_1094" align="aligncenter" width="485"]<img class="wp-image-1094 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_3-4.png" alt="Start Menu" width="485" height="772" /> Start Menu[/caption]</li>
 	<li>To<strong> copy the files and folders</strong> excluding certain files and folders to another drive.</li>
 	<li>Now,<strong> copy and paste the below commands</strong> in your command prompt.</li>
 	<li>Then press <strong>Enter.</strong>
<pre><code>robocopy C:\source\folder\path\ D:\destination\folder\path\ /E /Z /ZB /R:5 /W:5 
/TBD /NP /V /XD "C:\source\folder\path\to\exclude-folder" /XF 
"C:\source\folder\path\to\folder\filename.extension"</code></pre>
[caption id="attachment_1091" align="aligncenter" width="1222"]<img class="wp-image-1091 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_1-6.png" alt="Commands" width="1222" height="825" /> Commands[/caption]</li>
 	<li>After completion of the above steps, all the content will be copied to the new location except those files and folders you excluded in the command using the <strong>/XD and /XF switches.</strong></li>
</ol>
<h2 id="2">Exclude folder using Robocopy:</h2>
Use the steps to Exclude folder using Robocopy.
<ol>
 	<li>Go to the<strong> Start Menu.</strong></li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li>Then, the icon appears at the top of the start menu.</li>
 	<li>Right-click and select the<strong><strong> Run as administrator option.</strong></strong>

[caption id="attachment_1094" align="aligncenter" width="485"]<img class="wp-image-1094 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_3-4.png" alt="Start Menu" width="485" height="772" /> Start Menu[/caption]</li>
 	<li>To <strong>copy the files and folders</strong> excluding a specific folder to another location.</li>
 	<li>Type the <strong>following commands</strong> in the command prompt and press <strong>Enter.</strong>
<pre><code>robocopy C:\source\folder\path\ D:\destination\folder\path\ /E /Z /ZB /R:5 /W:5
/TBD /NP /V /XD "C:\source\folder\path\to\exclude-folder"</code></pre>
[caption id="attachment_1092" align="aligncenter" width="1221"]<img class="wp-image-1092 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_2-6.png" alt="Commands" width="1221" height="869" /> Commands[/caption]</li>
 	<li>The below command excludes a <strong>specific folder</strong> using Robocopy.
<pre><code>robocopy C:\source\folder\path\ D:\destination\folder\path\ /E /Z /ZB /R:5 /W:5 
/TBD /NP /V /XD exclude-folder-1</code></pre>
</li>
 	<li>The following command excludes a <strong>folder</strong> using the Robocopy<strong> wildcard option.</strong>
<pre><code>robocopy C:\source\folder\path\ D:\destination\folder\path\ /E /Z /ZB /R:5 /W:5 
/TBD /NP /V /XD exclude-fold*</code></pre>
</li>
 	<li>The below command excludes <strong>multiple folders</strong> using Robocopy.
<pre><code>robocopy C:\source\folder\path\ D:\destination\folder\path\ /E /Z /ZB /R:5 /W:5
/TBD /NP /V /XD "C:\source\folder\path\to\exclude-folder-1" 
"C:\source\folder\path\to\exclude-folder-2"</code></pre>
</li>
 	<li>After the completion of the above steps, all the data from the path will be copied over <strong>excluding the folders</strong> you specified in the command <strong>exclude_folder_file_robocopy.</strong></li>
</ol>
<h2 id="3">Exclude file using Robocopy:</h2>
Follow the below steps to Exclude file using Robocopy in simple steps.
<ol>
 	<li>Go to the <strong>Start Menu.</strong></li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li>Then, the icon appears at the top of the start menu.</li>
 	<li>Right-click and select the<strong><strong> Run as administrator option.</strong></strong>

[caption id="attachment_1094" align="aligncenter" width="485"]<img class="wp-image-1094 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_3-4.png" alt="Start Menu" width="485" height="772" /> Start Menu[/caption]</li>
 	<li>To <strong>copy the files and folders</strong> excluding a specific file to another location.</li>
 	<li>Type the following commands in the command prompt and press <strong>Enter.</strong>
<pre><code>robocopy C:\source\folder\path\ D:\destination\folder\path\ /E /Z /ZB /R:5 /W:5
/TBD /NP /V /XF "C:\source\folder\path\to\folder\filename.extension"</code></pre>
[caption id="attachment_1093" align="aligncenter" width="1222"]<img class="wp-image-1093 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_8.png" alt="Commands" width="1222" height="737" /> Commands[/caption]</li>
 	<li>The below command excludes a <strong>file</strong> using Robocopy.
<pre><code>robocopy C:\source\folder\path\ D:\destination\folder\path\ /E /Z /ZB /R:5 /W:5 
/TBD /NP /V /XF filename-1.extension</code></pre>
</li>
 	<li>The following command excludes a <strong>file</strong> using the Robocopy <strong>wildcard option.</strong>
<pre><code>robocopy C:\source\folder\path\ D:\destination\folder\path\ /E /Z /ZB /R:5 /W:5 
/TBD /NP /V /XF filena*</code></pre>
</li>
 	<li>The below command excludes <strong>multiple files</strong> using the Robocopy option.
<pre><code>robocopy C:\source\folder\path\ D:\destination\folder\path\ /E /Z /ZB /R:5 /W:5 
/TBD /NP /V /XF "C:\source\folder\path\to\folder\filename-1.extension" 
"C:\source\folder\path\to\folder\filename-2.extension</code></pre>
</li>
 	<li>After the completion of the above steps, now Robocopy will copy all the files and folders from a particular location excluding the files you specified in the command using the<strong> /XF switch.</strong></li>
</ol>
<strong>Image Source:</strong><em> </em><em>pureinfotech.com</em>
<h2 id="4">Verdict:</h2>
In the above article, you can get a piece of brief information on <strong>How to Exclude files and folders using Robocopy on Windows</strong><strong>.</strong> Kindly share the <strong>suggestions/queries</strong> in the below comment box and drop your worthwhile <strong>feedback.</strong>