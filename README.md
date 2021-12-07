# google-tag-manager

Install Google Tag Manager for web pages 
Google Tag Manager is a tag management system that allows you to quickly and easily update tags and code snippets on your website. Launch Google Tag Manager.

This article describes Tag Manager installation for web pages. For other platforms, read the documentation for Android, iOS, or Server installations.

Tag Manager installation for web requires a small piece of code that you add to your web pages or mobile applications. This code enables Tag Manager to fire tags by inserting tags into web pages.

Standard web page installation
In most cases, the easiest way to get started is to find the code and instructions from within Tag Manager.

<ol>
<li>If you have not done so already,
<a href="https://support.google.com/tagmanager/answer/6103696">create a Google Tag Manager account and container</a>.</li>
<li>In Google Tag Manager, click <strong>Workspace</strong>.</li>
<li>Near the top of the window, find your container ID, formatted as
<code translate="no" dir="ltr">GTM-XXXXXX</code>. Click your container ID to launch the <strong>Install Tag Manager</strong>
window.<br>
<img src="https://developers.google.com//tag-platform/images/GTMID.png" alt="GTMID" width="80%" class="screenshot"> </li>
<li>Copy the code and install on all pages based on the instructions provided.
The first code block is best placed immediately after the web page's opening
<code translate="no" dir="ltr">&lt;head&gt;</code> tag, or as high in the <code translate="no" dir="ltr">&lt;head&gt;</code> as possible. This helps to ensure
that your Tag Manager configuration is available and ready when the rest of
the page loads.<br>
<img src="https://developers.google.com//tag-platform/images/installgtm.png" alt="Tag Manager installation screen" class="screenshot" width="80%"></li>
<li>Optional, but recommended: <a href="/tag-platform/tag-manager/web/datalayer">Install a data layer object</a>.
A data layer will enable more robust measurement for your tag configurations.</li>
<li><a href="https://support.google.com/tagmanager/answer/6107163">Publish</a> your container.</li>
</ol>
