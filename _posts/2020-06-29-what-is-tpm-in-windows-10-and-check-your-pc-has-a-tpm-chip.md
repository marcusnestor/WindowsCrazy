---
ID: 2071
post_title: >
  What is TPM in Windows 10 and Check your
  PC has a TPM chip?
author: Isabella Nestor
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/2071-what-is-tpm-in-windows-10-and-check-your-pc-has-a-tpm-chip/
published: true
post_date: 2020-06-29 05:03:39
---
<ul class="toc">
 	<li><a href="#1">What is TPM?</a></li>
 	<li><a href="#2">Check TPM chip via Manager</a></li>
 	<li><a href="#3">Confirm TPM chip -Using Settings</a></li>
 	<li><a href="#4">Check TPM chip via BIOS/UEFI</a></li>
 	<li><a href="#5">Closure</a></li>
</ul>
<span class="dcap">T</span><strong>PM in Windows 10</strong>: <strong>Trusted Platform Module (TPM)</strong> technology is an international standard that is designed to secure hardware by means of integrated cryptographic keys.

In this tutorial, we will illustrate clearly <strong>what is TPM</strong> <strong>in Windows 10 </strong>and how to check if your computer has a TPM chip.
<h2 id="1">♦What is TPM?</h2>
<ul>
 	<li>TPM is required for BitLocker disk encryption on Windows.</li>
 	<li>It generally combined into the motherboard but not always.</li>
 	<li>TPM is a chip on your PC's motherboard that assists allow tamper-resistant full-disk encryption without the need for very long passphrases.</li>
 	<li>It provides a safe environment to store and secure the encryption keys with the use of BitLocker.</li>
 	<li>Most of the time, the chip is available but it will be disabled in the motherboard's firmware.</li>
 	<li>In recent times, many computers come with a TPM version 1.2, 2.0 or higher.</li>
</ul>
<h2 id="2">♦Check TPM chip via Manager:</h2>
<ol>
 	<li>Go to the <strong>Start</strong> menu.</li>
 	<li>In the search box, you have to type '<strong>tpm.msc</strong>' and hit <strong>Enter</strong>.

[caption id="attachment_2086" align="alignnone" width="1329"]<img class="size-full wp-image-2086" src="https://windowscrazy.com/wp-content/uploads/2020/06/tpm.msc_.png" alt="tpm.msc" width="1329" height="884" /> tpm.msc[/caption]</li>
 	<li>It will open the <strong>Trusted Platform Module (TPM) Management</strong> tool.</li>
 	<li>You can see the <strong>Status</strong> that shows the presence of TPM.

[caption id="attachment_2085" align="alignnone" width="1256"]<img class="size-full wp-image-2085" src="https://windowscrazy.com/wp-content/uploads/2020/06/Status-TPM.png" alt="Status - TPM" width="1256" height="819" /> Status - TPM[/caption]</li>
 	<li>If it shows Compatible TPM cannot be found, then it states that the TPM chip is disabled in the BIOS or UEFI or your computer does not include a compatible TPM.</li>
</ol>
<h2 id="3">♦Confirm TPM chip - Using Settings:</h2>
<ol>
 	<li>Use this shortcut <strong>Windows key + I</strong> to open the <strong>Settings</strong>.</li>
 	<li>Next, you have to click on the <strong>Update &amp; Security</strong> option.

[caption id="attachment_2087" align="alignnone" width="1324"]<img class="size-full wp-image-2087" src="https://windowscrazy.com/wp-content/uploads/2020/06/Update-Security.png" alt="Update &amp; Security" width="1324" height="815" /> Update &amp; Security[/caption]</li>
 	<li>In the left pane, you have to choose <strong>Device encryption</strong>.</li>
 	<li>If you can find the Device encryption option in your system, then it indicates the presence of TPM so you can utilize BitLocker on your system.</li>
</ol>
<p id="note"><strong>Note:</strong> The Device encryption option will only available if your computer has a TPM version 2 with Modern Standby support.</p>

<h2 id="4">♦Check TPM chip via BIOS/UEFI:</h2>
If your system is a Basic Input Output System (BIOS) or Unified Extensible Firmware Interface (UEFI) based, then you have to follow the below steps.
<h3>BIOS:</h3>
<ol>
 	<li>Turn on your computer.</li>
 	<li>Then, you have to click one of the function keys <strong>F1, F2, F3, F10, or F12, the ESC or Delete key</strong>.</li>
 	<li>Now, you have to look for <strong>security options</strong> in the <strong>BIOS</strong>.</li>
 	<li>Make sure that your computer has a <strong>TPM</strong> chip. If it is available but disabled, then you have to enable it so it will appear on Windows 10.</li>
</ol>
<h3>UEFI:</h3>
<ol>
 	<li>Use this shortcut <strong>Windows key + I</strong> to open the <strong>Settings</strong>.</li>
 	<li>Next, you have to click on the <strong>Update &amp; Security</strong> option.

[caption id="attachment_2087" align="alignnone" width="1324"]<img class="size-full wp-image-2087" src="https://windowscrazy.com/wp-content/uploads/2020/06/Update-Security.png" alt="Update &amp; Security" width="1324" height="815" /> Update &amp; Security[/caption]</li>
 	<li>Proceed to click on the <strong>Recovery</strong> option in the left pane.

[caption id="attachment_2083" align="alignnone" width="1321"]<img class="size-full wp-image-2083" src="https://windowscrazy.com/wp-content/uploads/2020/06/Recovery.png" alt="Recovery" width="1321" height="827" /> Recovery[/caption]</li>
 	<li>Now, you have to tap on <strong>Restart now</strong> button under the <strong>Advanced startup</strong> section.

[caption id="attachment_2084" align="alignnone" width="1329"]<img class="size-full wp-image-2084" src="https://windowscrazy.com/wp-content/uploads/2020/06/Restart-now.png" alt="Restart now" width="1329" height="831" /> Restart now[/caption]</li>
 	<li>Click on <strong>Troubleshoot -&gt; Advanced options -&gt; UEFI Firmware Settings</strong>.</li>
 	<li>After that, you have to tap on the <strong>Restart</strong> button.</li>
 	<li>Now, you have to look for <strong>security options</strong> in the <strong>firmware interface</strong>.</li>
 	<li>You have to confirm that your device has a TPM. If it is available but disabled, then you have to enable it so it will appear on Windows 10.</li>
</ol>
<h2 id="5">♦Closure:</h2>
We hope that this tutorial assisted you to know <strong>what is TPM</strong> <strong>in Windows 10 </strong>and how to check if your computer has a TPM chip. The simple steps let you verify the presence of TPM in your system instantly. Kindly share your <strong>queries/comments</strong> in the below box. We appreciate your presence in <a href="https://windowscrazy.com/"><strong>Windows Crazy</strong></a>.
<h2>Read Ahead:</h2>
<ul>
 	<li><a href="https://windowscrazy.com/1506-digital-license-vs-product-key-on-windows-10-simple-guide/">Digital License vs Product Key on Windows 10!! [Simple Guide]</a></li>
 	<li><a href="https://windowscrazy.com/940-how-to-check-if-the-windows-10-fall-creators-update-is-installed/">How to Check If the Windows 10 Fall Creators Update is Installed?</a></li>
 	<li><a href="https://windowscrazy.com/1526-reset-pc-keeping-personal-files-on-windows-10/">Reset PC Keeping Personal Files on Windows 10!!</a></li>
</ul>