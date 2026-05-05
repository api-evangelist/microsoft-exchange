---
title: "Update to Exchange callback tokens for Outlook add-ins"
url: "https://devblogs.microsoft.com/microsoft365dev/important-announcement-update-to-exchange-callback-tokens-for-outlook-add-ins/"
date: "Thu, 26 Oct 2023 16:00:48 +0000"
author: "Akhilesh Shah"
feed_url: "https://devblogs.microsoft.com/microsoft365dev/tag/exchange/feed/"
---
<p><span>Learn how to prepare for the upcoming change to Exchange callback tokens and avoid any disruptions in your Outlook add-ins.</span><span> </span></p>
<h2><span>What is changing and why?</span><span> </span></h2>
<p><span>We&#8217;re updating Exchange callback tokens used by Outlook add-ins to call REST APIs or Exchange Web Services (EWS). Specifically, these callback tokens are returned by the </span><a href="https://learn.microsoft.com/javascript/api/outlook/office.mailbox?view=outlook-js-preview#outlook-office-mailbox-getcallbacktokenasync-member(1)"><span>getCallbackTokenAsync(options, callback)</span></a><span> and </span><a href="https://learn.microsoft.com/en-us/javascript/api/outlook/office.mailbox?view=outlook-js-preview#outlook-office-mailbox-getcallbacktokenasync-member(2)"><span>getCallbackTokenAsync(callback, userContext)</span></a><span> methods. The update is part of continual improvements to maintain a more secure environment for Exchange users and resources such as mailbox and calendar.</span><span> </span></p>
<p><span>If your Outlook add-in doesn’t rely on the token format, and it just uses the token to access Exchange resources, it will not be affected by this change. If your add-in parses the token, or relies on anything inside the token string, it might be impacted. </span><span> </span></p>
<p><span>The change will take effect on January 1, 2024. After that date, any Outlook add-ins that rely on the internal format of the token will be affected. It is important that you update your add-ins to avoid any dependency on the token format before that date.</span><span> </span></p>
<h2><span>Recommended action</span><span> </span></h2>
<p><span>The token format is opaque, and your Outlook add-in should not parse or rely on anything inside the token string. The format might change again in the future. We recommend that you check your Outlook add-in to make sure that it doesn&#8217;t parse or rely on the content of the token string.</span><span> </span></p>
<p><span>Thank you.</span></p>
<p>The post <a href="https://devblogs.microsoft.com/microsoft365dev/important-announcement-update-to-exchange-callback-tokens-for-outlook-add-ins/">Update to Exchange callback tokens for Outlook add-ins</a> appeared first on <a href="https://devblogs.microsoft.com/microsoft365dev">Microsoft 365 Developer Blog</a>.</p>
