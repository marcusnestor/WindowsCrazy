---
ID: 1368
post_title: >
  Check if Network Traffic is using DNS
  resolver you set!!
author: Eva
post_excerpt: ""
layout: post
permalink: >
  https://windowscrazy.com/1368-check-if-network-traffic-is-using-dns-resolver-you-set/
published: true
post_date: 2020-06-15 15:30:33
---
<ul class="toc">
 	<li><a href="#1">Test your DNS settings on Windows 10</a></li>
 	<li><a href="#2">Test your DNS settings using Router</a></li>
 	<li><a href="#3">Test your DNS settings using DNSleaktest.com</a></li>
 	<li><a href="#4">Verdict</a></li>
</ul>
<strong><strong><strong><span class="dcap">H</span><strong>ow to Check if Network Traffic is using DNS resolver you set?</strong></strong></strong></strong> It is abbreviated as <strong>Domain Name System.</strong> It is a resolver service that can translate friendly domain names into IP addresses which aren’t easy to remember. <strong>Internet Service Provider (ISP)</strong> always provides these settings automatically. <strong>DNS</strong> resolvers that are faster, reliable, and more secure, including from CloudFlare, Google, and Cisco. Changing the <strong>DNS</strong> settings there isn’t an obvious way to test if the network traffic is passing through the servers you configured.

In this article, you can get clarity on <strong>How to check if Network Traffic is using DNS resolver you set </strong>in different ways.
<h2 id="1">Test your DNS settings on Windows 10:</h2>
Follow the steps to Test your DNS settings on Windows 10 using a simple way.
<ul>
 	<li>Go to the<strong> start menu.</strong></li>
 	<li>In the search column, type as <b>Command Prompt.</b></li>
 	<li><strong>Tap</strong> it which appears at the top of the start menu.</li>
 	<li>Now, the<strong> command prompt</strong> window gets open.</li>
 	<li>Copy and paste the following command and press Enter.
<pre><code>nslookup</code></pre>
[caption id="attachment_1405" align="aligncenter" width="1220"]<img class="wp-image-1405 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_1-19.png" alt="Command Prompt nslookup" width="1220" height="442" /> Command Prompt nslookup[/caption]

<strong>Image Source:</strong> <em>pureinfotech.com</em></li>
 	<li>Then under the Default Server field, you will notice the name of the <strong>DNS</strong> service you are using.</li>
 	<li>The <strong>Address</strong> field will also indicate the DNS address that your computer is using to route the network traffic.</li>
 	<li>That's all.</li>
</ul>
<h2 id="2">Test your DNS settings using Router:</h2>
Follow the steps to Test your DNS settings using Router in simple steps.
<ul>
 	<li>Go to the <strong>official</strong> web browser.</li>
 	<li>Then, Sign in to your router portal using its<strong> IP address.</strong></li>
 	<li><strong>Browse</strong> to the network tools.</li>
 	<li>Now, select the <strong>nslookup</strong> option as the test method.

[caption id="attachment_1407" align="aligncenter" width="1334"]<img class="wp-image-1407 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_2-18.png" alt="ASUS router nslookup tool" width="1334" height="783" /> ASUS router nslookup tool[/caption]

<strong>Image Source:</strong> <em>pureinfotech.com</em></li>
 	<li>The <strong>nslookup</strong> result should be able to determine the TCP/IP address the router is using to route the traffic.</li>
 	<li>That's all.</li>
</ul>
<h2 id="3">Test your DNS settings using DNSleaktest.com:</h2>
Follow the steps to Test your DNS settings using DNSleaktest.com in simple steps.
<ul>
 	<li>Go to the official <a href="https://www.dnsleaktest.com/"><strong>DNSleaktest.com</strong> </a>website.</li>
 	<li>Select the <strong>Standard test</strong> button.

[caption id="attachment_1409" align="aligncenter" width="1330"]<img class="wp-image-1409 size-full" src="https://windowscrazy.com/wp-content/uploads/2020/06/Screenshot_3-15.png" alt="DNS leak test" width="1330" height="798" /> DNS leak test[/caption]

<strong>Image Source:</strong> <em>pureinfotech.com</em></li>
 	<li>Then, check the <strong>ISP</strong> column to see the name of the DNS service.</li>
</ul>
<h2 id="4">Verdict:</h2>
In the above article, you can get a piece of brief information on <strong>How to check if Network Traffic is using DNS resolver you set </strong>by using different methods with clear cut<strong> screenshots.</strong> Kindly share the <strong>suggestions/queries</strong> in the below comment box and drop your worthwhile <strong>feedback.</strong>