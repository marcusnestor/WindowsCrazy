---
ID: 1614
post_title: 'List of Default Environment Variables in Windows 10!! (*Full List*)'
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1614-list-of-default-environment-variables-in-windows-10-full-list/
published: true
post_date: 2020-06-19 06:16:34
---
<ul class="toc">
 	<li><a href="#1">List of Default Environment Variables</a></li>
 	<li><a href="#2">Conclusion</a></li>
</ul>
<span class="dcap">D</span><strong>efault Environment Variables in Windows 10</strong>: Environment variables are dynamic named values that make it simple when specific parameters and standard directories need to be referenced. These variables include configuration values for the whole system as well as the current user.

Using the default environment variables, you can navigate to specific locations within the device. You can move on to a particular file or a folder. These variables can be used both in scripts and on the command line. In this article, we will look over the list of <strong>Default Environment Variables in Windows 10 </strong>that can be used to reference for standard directories and parameters.
<h2 id="1">List of Default Environment Variables:</h2>
<p id="note">Note: Some of the variables that include %COMPUTERNAME%, %PATHEXT%, %PROMPT%, %USERDOMAIN%, %USERNAME% are not location specific.</p>
<strong>Run Command:</strong>

You just need to open the <strong>Run command</strong> using the shortcut <strong>Windows key + R</strong>. After that, you can type any below-mentioned environment variable and hit <strong>Enter</strong> to access the particular location.
<table>
<thead>
<tr>
<th style="text-align: left;">ENVIRONMENT VARIABLES</th>
<th style="text-align: left;">WINDOWS 10</th>
</tr>
</thead>
<tbody>
<tr>
<td>%ALLUSERSPROFILE%</td>
<td>C:\ProgramData</td>
</tr>
<tr>
<td>%APPDATA%</td>
<td>C:\Users\{username}\AppData\Roaming</td>
</tr>
<tr>
<td>%COMMONPROGRAMFILES%</td>
<td>C:\Program Files\Common Files</td>
</tr>
<tr>
<td>%COMMONPROGRAMFILES(x86)%</td>
<td>C:\Program Files (x86)\Common Files</td>
</tr>
<tr>
<td>%CommonProgramW6432%</td>
<td>C:\Program Files\Common Files</td>
</tr>
<tr>
<td>%COMSPEC%</td>
<td>C:\Windows\System32\cmd.exe</td>
</tr>
<tr>
<td>%HOMEDRIVE%</td>
<td>C:\</td>
</tr>
<tr>
<td>%HOMEPATH%</td>
<td>C:\Users\{username}</td>
</tr>
<tr>
<td>%LOCALAPPDATA%</td>
<td>C:\Users\{username}\AppData\Local</td>
</tr>
<tr>
<td>%LOGONSERVER%</td>
<td>\\{domain_logon_server}</td>
</tr>
<tr>
<td>%PATH%</td>
<td>C:\Windows\system32;C:\Windows;C:\Windows\System32\Wbem</td>
</tr>
<tr>
<td>%PathExt%</td>
<td>.com;.exe;.bat;.cmd;.vbs;.vbe;.js;.jse;.wsf;.wsh;.msc</td>
</tr>
<tr>
<td>%PROGRAMDATA%</td>
<td>C:\ProgramData</td>
</tr>
<tr>
<td>%PROGRAMFILES%</td>
<td>C:\Program Files</td>
</tr>
<tr>
<td>%ProgramW6432%</td>
<td>C:\Program Files</td>
</tr>
<tr>
<td>%PROGRAMFILES(X86)%</td>
<td>C:\Program Files (x86)</td>
</tr>
<tr>
<td>%PROMPT%</td>
<td>$P$G</td>
</tr>
<tr>
<td>%SystemDrive%</td>
<td>C:</td>
</tr>
<tr>
<td>%SystemRoot%</td>
<td>C:\Windows</td>
</tr>
<tr>
<td>%TEMP%</td>
<td>C:\Users\{username}\AppData\Local\Temp</td>
</tr>
<tr>
<td>%TMP%</td>
<td>C:\Users\{username}\AppData\Local\Temp</td>
</tr>
<tr>
<td>%USERDOMAIN%</td>
<td>User domain associated with the current user.</td>
</tr>
<tr>
<td>%USERDOMAIN_ROAMINGPROFILE%</td>
<td>User domain associated with the roaming profile.</td>
</tr>
<tr>
<td>%USERNAME%</td>
<td>{username}</td>
</tr>
<tr>
<td>%USERPROFILE%</td>
<td>C:\Users\{username}</td>
</tr>
<tr>
<td>%WINDIR%</td>
<td>C:\Windows</td>
</tr>
<tr>
<td>%PUBLIC%</td>
<td>C:\Users\Public</td>
</tr>
<tr>
<td>%PSModulePath%</td>
<td>%SystemRoot%\system32\WindowsPowerShell\v1.0\Modules\</td>
</tr>
<tr>
<td>%OneDrive%</td>
<td>C:\Users\{username}\OneDrive</td>
</tr>
<tr>
<td>%DriverData%</td>
<td>C:\Windows\System32\Drivers\DriverData</td>
</tr>
<tr>
<td>%COMPUTERNAME%</td>
<td>Outputs the system name.</td>
</tr>
<tr>
<td>%PROCESSOR_IDENTIFIER%</td>
<td>Outputs processor identifier.</td>
</tr>
<tr>
<td>%PROCESSOR_LEVEL%</td>
<td>Outputs processor level.</td>
</tr>
<tr>
<td>%PROCESSOR_REVISION%</td>
<td>Shows processor revision.</td>
</tr>
<tr>
<td>%NUMBER_OF_PROCESSORS%</td>
<td>Outputs the number of physical and virtual cores.</td>
</tr>
<tr>
<td>%RANDOM%</td>
<td>Outputs random number from 0 through 32767.</td>
</tr>
<tr>
<td>%OS%</td>
<td>Windows_NT</td>
</tr>
</tbody>
</table>
<strong>Command Prompt:</strong>

Open the Command Prompt and run the below variables to view the output.
<table>
<thead>
<tr>
<th style="text-align: left;">ENVIRONMENT VARIABLES</th>
<th style="text-align: left;">WINDOWS 10</th>
</tr>
</thead>
<tbody>
<tr>
<td>%CD%</td>
<td>Shows the full path of the current directory.</td>
</tr>
<tr>
<td>%CMDCMDLINE%</td>
<td>Displays the command line used to launch the current Command Prompt session.</td>
</tr>
<tr>
<td>%CMDEXTVERSION%</td>
<td>Shows the number of current command processor extensions.</td>
</tr>
<tr>
<td>%DATE%</td>
<td>Shows the current date determined by Date command.</td>
</tr>
<tr>
<td>%TIME%</td>
<td>Show the current time.</td>
</tr>
<tr>
<td>%ERRORLEVEL%</td>
<td>Displays the number of defining exit status of the previous command.</td>
</tr>
</tbody>
</table>
<p id="note">Note: The above Environment Variables are listed for Windows 10. But, it will also work on Windows 7, Windows 8.x, and Windows Vista.</p>

<h2 id="2">Conclusion:</h2>
Hopefully, this article assisted you to learn the thorough list of  <strong>Default Environment Variables in Windows 10. </strong>It saves your time and effort as you don't have to search for any specific folder or file location. Don't forget to share your <strong>comments</strong> in the below section. We appreciate your presence in <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.