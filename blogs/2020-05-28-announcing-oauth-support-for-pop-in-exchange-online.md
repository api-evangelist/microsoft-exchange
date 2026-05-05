---
title: "Announcing OAuth Support for POP in Exchange Online"
url: "https://devblogs.microsoft.com/microsoft365dev/announcing-oauth-support-for-pop-in-exchange-online/"
date: "Thu, 28 May 2020 18:11:49 +0000"
author: "Office Extensibility team"
feed_url: "https://devblogs.microsoft.com/microsoft365dev/tag/exchange/feed/"
---
<p>At the end of April we <u><a href="https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdeveloper.microsoft.com%2Fen-us%2Fgraph%2Fblogs%2Fannouncing-oauth-2-0-support-for-imap-smtp-client-protocols-in-exchange-online%2F&amp;data=02%7C01%7Cv-chgrav%40microsoft.com%7Cd82d50aee8c1464a883008d8032dcc41%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637262842517772151&amp;sdata=bKyIl0H9OQMdO5njoK7tXbeLQQRWHpKNfjG8lpODW4A%3D&amp;reserved=0">announced OAuth 2.0 support for IMAP, SMTP client protocols in Exchange Online</a>. </u>Today we’re happy to announce that OAuth support for POP in Exchange Online is also available.</p>
<p>Application developers who have built apps that send, read or otherwise process email using these protocols can implement secure, modern authentication experiences for their users. This functionality is built on top of <a href="https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-overview">Microsoft Identity platform (v2.0)</a> and supports access to email of Microsoft 365 (formerly Office 365) users.</p>
<p>Detailed step-by-step instructions for <a href="https://docs.microsoft.com/exchange/client-developer/legacy-protocols/how-to-authenticate-an-imap-pop-smtp-application-by-using-oauth">authenticating to IMAP, POP and SMTP AUTH protocols using OAuth</a> are now available for you to get started.</p>
<p>What’s supported?</p>
<p>With this release, apps can use one of the following OAuth flows to authorize and get access tokens <u>on behalf of a user</u>.</p>
<ol>
<li><a href="https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow">OAuth2 authorization code flow</a></li>
<li><a href="https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-device-code">OAuth2 Device authorization grant flow</a></li>
</ol>
<p><a href="https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-client-creds-grant-flow">OAuth2 client credentials grant flow</a> that enables access without a user account is <u>not supported</u>. If your application needs persistent access to all mailboxes in a Microsoft 365 organization, we recommend that you use the Microsoft Graph API’s which allow <a href="https://docs.microsoft.com/en-us/graph/auth-v2-service">access without a user</a> in addition to access on behalf of a user, enable granular permissions and let administrators <a href="https://docs.microsoft.com/en-us/graph/auth-limit-mailbox-access">scope such access to a specific set of mailboxes</a>.</p>
<p>Follow these <a href="https://docs.microsoft.com/exchange/client-developer/legacy-protocols/how-to-authenticate-an-imap-pop-smtp-application-by-using-oauth">detailed step-by-step instructions</a> to implement OAuth 2.0 authentication if your in-house application needs to access IMAP, POP and SMTP AUTH protocols in Exchange Online, or work with your vendor to update any apps or clients that you use that could be impacted.</p>
<p>The Exchange Team</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>The post <a href="https://devblogs.microsoft.com/microsoft365dev/announcing-oauth-support-for-pop-in-exchange-online/">Announcing OAuth Support for POP in Exchange Online</a> appeared first on <a href="https://devblogs.microsoft.com/microsoft365dev">Microsoft 365 Developer Blog</a>.</p>
