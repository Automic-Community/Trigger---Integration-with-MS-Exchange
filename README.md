*Trigger - Integration with MS Exchange*
=============


This package contains a tool that notifies a Dollar Universe node upon a mail reception on a Exchange mailbox.
http://github.com/Automic-Community/Trigger---Integration-with-MS-Exchange

<!-- List of attached files -->
Contents of Solution Package:

						
								*Dollar_Universe-Email_Notifier.zip
								
								*Dollar_Universe-Email_Trigger.pdf
								
						


Documenation and Instructions
---

<p><span>Description</span></p>
<p><br /> This package contains a tool that notifies a Dollar Universe node upon a mail reception on a Exchange mailbox. This allows you to start a new Dollar Universe workflow based on a mail. The main properties of the mail are transmitted to the workflow).<br />From a technical standpoint, the tool can be run as a standalone application or can be installed as a Windows Service (to allow an external supervision tool to monitor its status).<br />The tool connects to the MS Exchange server through its Web Service Managed APIs (EWS).<br />We also provide in a separate package the C# library (and its source code) that you can use in your own applications.</p>
<p>Prerequisites</p>
<ul class="bbc">
<li>Exchange Server 2007 Service Pack 1 (SP1) or above. This includes Exchange Online (Office 365).</li>
<li>The .NET Framework 4 must be installed</li>
<li>This package has been developed and tested on Windows 7 SP 1 (x64); also tested on Windows Server 2008 R2 SP1 (x64)</li>
<li>The Windows Service / binary file : DUAS_email_notifier_service.zip (to get the source code : DUAS_email_notifier_service_src.zip)</li>
<li>The C# libraries (.dll files) : DUAS_csharp_DLLs.zip (to get the source code : DUAS_csharp_DLLs_scr.zip)</li>
</ul>
<p><strong class="bbc">Note </strong>: The Newtonsoft.Json.dll is open source. See home page at : <a class="bbc_url" title="External link" href="http://james.newtonking.com/json" rel="nofollow external">Json.NET</a></p>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
