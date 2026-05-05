---
title: "Application Access Policy Support Added to Exchange Web Services in Exchange Online"
url: "https://devblogs.microsoft.com/microsoft365dev/application-access-policy-support-added-to-exchange-web-services/"
date: "Fri, 05 Feb 2021 22:39:56 +0000"
author: "Microsoft 365 Platform team"
feed_url: "https://devblogs.microsoft.com/microsoft365dev/tag/exchange/feed/"
---
<p><span>The Application Access Policy feature enables an administrator to enforce access control to an AppOnly app to a specific set of mailboxes. We previously introduced Application Access Policy support for Microsoft Graph, and we are now adding Application Access Policy support to Exchange Web Services (EWS) in Exchange Online, in response to customer feedback and as a mechanism to ease transition from EWS to Microsoft Graph.</span><span> </span></p>
<h4><span>Background</span><span> </span></h4>
<p><span>Some apps call EWS using their own identity and not on behalf of a user. These are usually background services or daemon apps that run on a server without the presence of a signed-in user. These apps make use of OAuth 2.0 client credentials grant flow to authenticate and are configured with application permissions (or AppOnly permissions). EWS supports AppOnly access via “full_access_as_app” scope. This scope enables a client application with EWS access to impersonate all the mailboxes within a customer’s organization. Without this new feature, administrators do not have a way to scope the EWS AppOnly application’s impersonation access to a specific set of mailboxes. Providing the ability to have more fine-grained EWS permission scopes is a common request that we’ve heard from our EWS partners.</span><span> </span></p>
<h4><span>Application Access Policy</span><span> </span></h4>
<p><span>With support for Application Access Policies in EWS, administrators can now limit an AppOnly app’s access to a specific set of mailboxes by specifying an inclusion or exclusion list.</span><span> Administrators who want to limit the 3</span><span>rd</span><span> party app access to a specific set of mailboxes can use the Application Access Policy PowerShell cmdlets to configure access control. The following pages describe the functionality of Application Access Policy feature in detail. </span><span> </span></p>
<ul>
<li><a href="https://docs.microsoft.com/graph/auth-limit-mailbox-access"><span>Scoping application permissions to specific Exchange Online mailboxes</span></a><span> </span></li>
<li><a href="https://docs.microsoft.com/powershell/module/exchange/organization/new-applicationaccesspolicy?view=exchange-ps"><span>New-ApplicationAccessPolicy</span></a><span> </span></li>
</ul>
<h4><span>No (Other) New Investments in EWS</span><span> </span></h4>
<p><a href="https://techcommunity.microsoft.com/t5/exchange-team-blog/upcoming-changes-to-exchange-web-services-ews-api-for-office-365/ba-p/608055"><span>We announced</span></a><span> in 2018 that there wouldn’t be any new feature updates to EWS. We added this support to address customer security concerns. </span><span> </span></p>
<p><span>As there are no new feature investments in EWS, we strongly </span><span>suggest migrating to Microsoft Graph to access Exchange Online data and gain access to the latest features and functionality. For more information and details on how to make the transition, please refer to the following articles: </span><span> </span></p>
<ul>
<li><a href="https://developer.microsoft.com/graph/docs/concepts/overview"><span>Overview of Microsoft Graph</span></a><span> </span><span> </span></li>
<li><a href="https://developer.microsoft.com/graph/docs/concepts/outlook-mail-concept-overview"><span>Overview of Outlook mail API on Microsoft Graph</span></a><span> </span></li>
</ul>
<p><span>While EWS and Microsoft Graph have mostly overlapping functionality, there are some differences. If you rely on an EWS API that does not have a Microsoft Graph counterpart, please let us know via </span><a href="https://officespdev.uservoice.com/"><span>UserVoice</span></a><span> of features needed for your app scenarios.  </span><span> </span></p>
<h4><span>Basic Authentication</span><span> </span></h4>
<p><span>This is also a good time to remind everyone that we are </span><a href="https://techcommunity.microsoft.com/t5/exchange-team-blog/basic-authentication-and-exchange-online-july-update/ba-p/1530163"><span>retiring Basic Authentication in Exchange Online</span></a><span>; if you are using EWS or any other email access protocol like POP, IMAP or EAS in combination with Basic Auth, you need to make sure you are using OAuth and not Basic Authentication. Furthermore, we strongly recommend that you modernize your apps and move to Microsoft Graph.</span><span> </span></p>
<h4><span>Getting Started</span><span> </span></h4>
<p><span>With the new Application Access Policy, you’ll be able to provide users a more secure experience using EWS. Learn more </span><a href="https://docs.microsoft.com/en-us/powershell/module/exchange/organization/new-applicationaccesspolicy?view=exchange-ps"><span>here</span></a><span>.</span><span> </span></p>
<p><span>The Exchange Team</span><span> </span></p>
<p>The post <a href="https://devblogs.microsoft.com/microsoft365dev/application-access-policy-support-added-to-exchange-web-services/">Application Access Policy Support Added to Exchange Web Services in Exchange Online</a> appeared first on <a href="https://devblogs.microsoft.com/microsoft365dev">Microsoft 365 Developer Blog</a>.</p>
