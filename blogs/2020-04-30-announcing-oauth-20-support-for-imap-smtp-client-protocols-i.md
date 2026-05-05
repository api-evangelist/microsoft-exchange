---
title: "Announcing OAuth 2.0 support for IMAP, SMTP client protocols in Exchange Online"
url: "https://devblogs.microsoft.com/microsoft365dev/announcing-oauth-2-0-support-for-imap-smtp-client-protocols-in-exchange-online/"
date: "Thu, 30 Apr 2020 15:00:07 +0000"
author: "Sivaprakash Saripalli"
feed_url: "https://devblogs.microsoft.com/microsoft365dev/tag/exchange/feed/"
---
<p>Last year, we <a href="https://developer.microsoft.com/en-us/office/blogs/end-of-support-for-basic-authentication-access-to-exchange-online-apis-for-office-365-customers/">announced</a> that we would enable OAuth 2.0 support for IMAP, SMTP AUTH protocols and retire Basic Authentication access to Exchange Online mailboxes.</p>
<p>Today, we’re announcing the availability of <a href="https://docs.microsoft.com/en-us/exchange/client-developer/legacy-protocols/how-to-authenticate-an-imap-pop-smtp-application-by-using-oauth">OAuth 2.0 authentication for IMAP, SMTP AUTH protocols</a> to Exchange Online mailboxes. If you have an existing application that reads or sends email using one or more of these two protocols, the new OAuth authentication method will enable you to implement secure, modern authentication experiences for your users. This functionality is built on top of <a href="https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-overview">Microsoft Identity platform (v2.0)</a> and supports access to email of Microsoft 365 (formerly Office 365) users.</p>
<p>Detailed step-by-step instructions for <a href="https://docs.microsoft.com/en-us/exchange/client-developer/legacy-protocols/how-to-authenticate-an-imap-pop-smtp-application-by-using-oauth">authenticating to IMAP, SMTP AUTH protocols using OAuth</a> are now available for you to get started.</p>
<p>While you can use IMAP, SMTP AUTH to access Exchange Online mailboxes, Microsoft Graph continues to be the best way to access Microsoft 365. It provides a unified programmability model that you can use to access the tremendous amount of data in Microsoft 365. You can learn more at <a href="https://docs.microsoft.com/en-us/graph/overview">Microsoft Graph documentation</a>.</p>
<h3>What’s supported with this release?</h3>
<p>With this release, your app can use one of the following OAuth flows to authorize and get access tokens <em>on behalf of a user</em>.</p>
<ul>
<li><a href="https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow">OAuth2 authorization code flow</a></li>
<li><a href="https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-device-code">OAuth2 Device authorization grant flow</a></li>
</ul>
<p><a href="https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-client-creds-grant-flow">OAuth2 client credentials grant flow</a> that enables access without a user is <em>not supported</em>. If your application needs persistent access to ALL mailboxes in a Microsoft 365 organization, we recommend that you use the Microsoft Graph APIs, which allow <a href="https://docs.microsoft.com/en-us/graph/auth-v2-service">access without a user</a> in addition to access on behalf of a user, enable granular permissions, and let administrators <a href="https://docs.microsoft.com/en-us/graph/auth-limit-mailbox-access">scope such access to a specific set of mailboxes</a>.</p>
<p>We are in the process of rolling out OAuth 2.0 support for POP protocol and will update this blog whenthe rollout is complete.</p>
<p>What are you waiting for? Follow these <a href="https://docs.microsoft.com/en-us/exchange/client-developer/legacy-protocols/how-to-authenticate-an-imap-pop-smtp-application-by-using-oauth">detailed step-by-step instructions</a> to implement OAuth 2.0 authentication in your application to access IMAP and SMTP AUTH protocols in Exchange Online.</p>
<p>The Exchange Team</p>
<p>The post <a href="https://devblogs.microsoft.com/microsoft365dev/announcing-oauth-2-0-support-for-imap-smtp-client-protocols-in-exchange-online/">Announcing OAuth 2.0 support for IMAP, SMTP client protocols in Exchange Online</a> appeared first on <a href="https://devblogs.microsoft.com/microsoft365dev">Microsoft 365 Developer Blog</a>.</p>
