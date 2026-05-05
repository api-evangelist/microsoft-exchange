---
title: "Updates on deprecating legacy Exchange Online tokens for Outlook add-ins"
url: "https://devblogs.microsoft.com/microsoft365dev/updates-on-deprecating-legacy-exchange-online-tokens-for-outlook-add-ins/"
date: "Wed, 14 Aug 2024 17:34:06 +0000"
author: "David Chesnut, Paul Inverso"
feed_url: "https://devblogs.microsoft.com/microsoft365dev/tag/exchange/feed/"
---
<p>We want to share an update on the timeline and plans for deprecating legacy Exchange Online <a href="https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/authentication#exchange-user-identity-token">user identity tokens</a> and <a href="https://learn.microsoft.com/office/dev/add-ins/outlook/authentication#callback-tokens">callback tokens</a>. If your Outlook add-in uses legacy tokens to make calls to Exchange, then this information applies to you.</p>
<p>On April 9, 2024 the Office Platform Team made two major announcements:</p>
<ol>
<li>We launched the public preview of Nested App Authentication (NAA), which provides simple authentication and top tier identity protection through APIs designed specifically for add-ins in Office hosts.</li>
<li>We announced that <strong>legacy Exchange </strong><a href="https://learn.microsoft.com/office/dev/add-ins/outlook/authentication#exchange-user-identity-token"><strong>user identity tokens</strong></a><strong> and </strong><a href="https://learn.microsoft.com/office/dev/add-ins/outlook/authentication#callback-tokens"><strong>callback tokens</strong></a><strong> will be turned off by default for all Exchange Online tenants </strong>as part of <a href="https://blogs.microsoft.com/on-the-issues/2023/11/02/secure-future-initiative-sfi-cybersecurity-cyberattacks/">Microsoft’s Secure Future Initiative</a> to protect organizations in the current threat landscape. If your add-in uses legacy tokens to make calls to Exchange, you need to migrate from Exchange tokens to using NAA and Entra ID tokens as soon as possible.</li>
</ol>
<h2>Timeline for turning off legacy Exchange tokens</h2>
<p>In April, we announced that Exchange tokens will be turned off by default for all tenants in October 2024. This has been updated and you should have more time to move your Outlook add-ins from Exchange tokens to NAA. The following tables list the key milestones based on which channel customers are using. Note that the general availability (GA) date for NAA will vary based on channel. We&#8217;ll provide tooling for administrators to reenable Exchange tokens for tenants and add-ins if those add-ins are not yet migrated to NAA.</p>
<h3>Current Channel</h3>
<table style="width: 100%;">
<tbody>
<tr>
<td style="width: 23.4931%;"><strong>Date</strong></td>
<td style="width: 76.5069%;"><strong>Action</strong></td>
</tr>
<tr>
<td style="width: 23.4931%;">October 2024</td>
<td style="width: 76.5069%;">NAA is GA for Current Channel.</p>
<p>Exchange online tokens are turned off by default for new tenants and existing tenants known not to be using Exchange tokens.</p>
<p>The administrator can choose to reenable Exchange tokens on tenants or add-ins as needed.</td>
</tr>
<tr>
<td style="width: 23.4931%;">January 2025</td>
<td style="width: 76.5069%;">Exchange online tokens are turned off by default for <strong>all tenants</strong>.</p>
<p>The administrator can choose to reenable Exchange tokens on tenants and add-ins as needed.</td>
</tr>
<tr>
<td style="width: 23.4931%;">June 2025</td>
<td style="width: 76.5069%;">The ability for the administrator to reenable Exchange online tokens is removed. If a tenant or add-in needs Exchange tokens reenabled, the administrator must contact Microsoft.</td>
</tr>
<tr>
<td style="width: 23.4931%;">October 2025</td>
<td style="width: 76.5069%;">Exchange online tokens are turned off for all tenants and add-ins, including any that were reenabled.</td>
</tr>
</tbody>
</table>
<h3></h3>
<h3>Monthly Enterprise Channel</h3>
<table style="width: 100%;">
<tbody>
<tr>
<td style="width: 24.4204%;"><strong>Date</strong></td>
<td style="width: 75.5796%;"><strong>Action</strong></td>
</tr>
<tr>
<td style="width: 24.4204%;">November 2024</td>
<td style="width: 75.5796%;">NAA is GA for Monthly Enterprise Channel.</p>
<p>Exchange online tokens are turned off by default for new tenants and existing tenants known not to be using Exchange tokens.</p>
<p>The administrator can choose to reenable Exchange tokens on tenants or add-ins as needed.</td>
</tr>
<tr>
<td style="width: 24.4204%;">February 2025</td>
<td style="width: 75.5796%;">Exchange online tokens are turned off by default for <strong>all tenants</strong>.</p>
<p>The administrator can choose to reenable Exchange tokens on tenants and add-ins as needed.</td>
</tr>
<tr>
<td style="width: 24.4204%;">June 2025</td>
<td style="width: 75.5796%;">The ability for the administrator to reenable Exchange online tokens is removed. If a tenant or add-in needs Exchange tokens reenabled, the administrator must contact Microsoft.</td>
</tr>
<tr>
<td style="width: 24.4204%;">October 2025</td>
<td style="width: 75.5796%;">Exchange online tokens are turned off for all tenants and add-ins, including any that were reenabled.</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<h3>Semi-annual Channel</h3>
<table style="width: 100%;">
<tbody>
<tr>
<td style="width: 24.1113%;">Date</td>
<td style="width: 75.8887%;">Action</td>
</tr>
<tr>
<td style="width: 24.1113%;">January 2025</td>
<td style="width: 75.8887%;">NAA is GA for Semi-annual Channel.</p>
<p>Exchange online tokens are turned off by default for <strong>all tenants</strong>.</p>
<p>The administrator can choose to reenable Exchange tokens on tenants and add-ins as needed.</td>
</tr>
<tr>
<td style="width: 24.1113%;">June 2025</td>
<td style="width: 75.8887%;">The ability for the administrator to reenable Exchange online tokens is removed. If a tenant or add-in needs Exchange tokens reenabled, the administrator must contact Microsoft.</td>
</tr>
<tr>
<td style="width: 24.1113%;">October 2025</td>
<td style="width: 75.8887%;">Exchange online tokens are turned off for all tenants and add-ins, including any that were reenabled.</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<h3>Semi-annual Channel Extended</h3>
<table style="width: 100%;">
<tbody>
<tr>
<td style="width: 24.4204%;">Date</td>
<td style="width: 75.5796%;">Action</td>
</tr>
<tr>
<td style="width: 24.4204%;">June 2025</td>
<td style="width: 75.5796%;">NAA is GA for Semi-annual Channel Extended.</p>
<p>The ability for the administrator to reenable Exchange online tokens is removed. If a tenant or add-in needs Exchange tokens reenabled, the administrator must contact Microsoft.</td>
</tr>
<tr>
<td style="width: 24.4204%;">October 2025</td>
<td style="width: 75.5796%;">Exchange online tokens are turned off for all tenants and add-ins, including any that were reenabled.</td>
</tr>
</tbody>
</table>
<h2>Next steps for developers</h2>
<p>Get started migrating your add-in from Exchange tokens to NAA. Refer to the original blog post: <a href="https://devblogs.microsoft.com/microsoft365dev/new-nested-app-authentication-for-office-add-ins-legacy-exchange-tokens-off-by-default-in-october-2024/">New Nested App Authentication for Office Add-ins: Legacy Exchange tokens off by default in October 2024 (microsoft.com)</a>. It includes the following information:</p>
<ul>
<li>How to determine if your add-in is using Exchange online legacy tokens.</li>
<li>How to adopt NAA in your add-in.</li>
</ul>
<h2>More resources</h2>
<p>For questions, issues, or bugs, find us on GitHub and put “NAA” in your issue title: <a href="https://github.com/OfficeDev/office-js/issues">Issues · OfficeDev/office-js (github.com)</a></p>
<p>We&#8217;ll also be sharing updates on our <a href="https://learn.microsoft.com/office/dev/add-ins/overview/office-add-ins-community-call">monthly community call</a>.</p>
<h2>Articles and samples</h2>
<ul>
<li>NAA public preview blog: <a href="https://aka.ms/NAApreviewblog">https://aka.ms/NAApreviewblog</a></li>
<li>NAA docs to get started: <a href="https://aka.ms/NAAdocs">https://aka.ms/NAAdocs</a></li>
<li>NAA FAQ: <a href="https://aka.ms/NAAFAQ">https://aka.ms/NAAFAQ</a></li>
<li>NAA Outlook sample: <a href="https://aka.ms/NAAsampleOutlook">https://aka.ms/NAAsampleOutlook</a></li>
<li>NAA Word Excel PowerPoint sample: <a href="https://aka.ms/NAAsampleOffice">https://aka.ms/NAAsampleOffice</a></li>
</ul>
<p>The post <a href="https://devblogs.microsoft.com/microsoft365dev/updates-on-deprecating-legacy-exchange-online-tokens-for-outlook-add-ins/">Updates on deprecating legacy Exchange Online tokens for Outlook add-ins</a> appeared first on <a href="https://devblogs.microsoft.com/microsoft365dev">Microsoft 365 Developer Blog</a>.</p>
