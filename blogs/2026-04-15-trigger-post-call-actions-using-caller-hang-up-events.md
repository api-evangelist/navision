---
title: "Trigger post-call actions using caller hang-up events"
url: "https://www.microsoft.com/en-us/dynamics-365/blog/it-professional/2026/04/15/trigger-post-call-actions-using-caller-hang-up-events/"
date: "Wed, 15 Apr 2026 20:44:32 +0000"
author: "Hemang Shah and Lily Shelke"
feed_url: "https://www.microsoft.com/en-us/dynamics-365/blog/feed/"
---
<div class="cloudblogs">
<p class="wp-block-paragraph">In contact centers,&nbsp;a&nbsp;voice&nbsp;conversation does&nbsp;not end when the call disconnects. That’s when critical work begins – logging outcomes, updating systems, triggering workflows, and ensuring compliance. Yet today, post-call actions are often delayed, inconsistent, or dependent on manual&nbsp;or external&nbsp;processes.&nbsp;<br />&nbsp;<br />With caller hang-up event support in Dynamics 365 Contact Center&nbsp;and Copilot&nbsp;Studio, we are changing that.&nbsp;</p>



<p class="wp-block-paragraph">This capability enables real-time, event-driven post-call automation by raising precise caller hang-up events to voice agents. Post-call actions happen immediately, reliably, and at scale. </p>



<h2 class="wp-block-heading" id="why-this-matters">Why this matters </h2>



<p class="wp-block-paragraph">Post-call actions today often require custom implementations and are not always easy to configure or consistently reliable.&nbsp;</p>



<p class="wp-block-paragraph">Organizations frequently depend on external orchestration or complex workflows, which can leave gaps, especially when a caller disconnects unexpectedly in the middle of a flow. </p>



<p class="wp-block-paragraph">For example, when a caller&nbsp;hangs up&nbsp;mid-flow, records can remain locked or reflect stale or incomplete data in downstream systems.&nbsp;</p>



<p class="wp-block-paragraph">As a result, organizations face:&nbsp;</p>



<ul class="wp-block-list">
<li class="wp-block-list-item">Missed or delayed post-call actions  </li>
</ul>



<ul class="wp-block-list">
<li class="wp-block-list-item">Inconsistent or stale data updates  </li>
</ul>



<ul class="wp-block-list">
<li class="wp-block-list-item">Gaps in reporting and operational workflows  </li>
</ul>



<p class="wp-block-paragraph">This creates friction across automation and downstream&nbsp;operations.&nbsp;</p>



<h2 class="wp-block-heading" id="what-s-new"><strong>What’s&nbsp;new</strong>&nbsp;</h2>



<p class="wp-block-paragraph">Voice agents can now listen to <strong>end-of-conversation </strong>events and take action based on how the call ended – directly within their Copilot Studio flow. </p>



<p class="wp-block-paragraph">For example, you can trigger workflows specifically when:&nbsp;</p>



<ul class="wp-block-list">
<li class="wp-block-list-item">The customer hangs up  </li>
</ul>



<ul class="wp-block-list">
<li class="wp-block-list-item">The call is transferred to an external phone number  </li>
</ul>



<ul class="wp-block-list">
<li class="wp-block-list-item">The call is escalated to customer service representatives in Dynamics 365 Contact Center  </li>
</ul>



<p class="wp-block-paragraph">This capability is exposed through&nbsp;<strong>activity-based triggers in Copilot Studio</strong>, enabling makers to configure post-call logic within their voice agent&nbsp;flow&nbsp;in Copilot Studio.&nbsp;</p>



<h2 class="wp-block-heading" id="how-it-works">How it works </h2>



<p class="wp-block-paragraph">At the end of every conversation, the platform emits a structured&nbsp;event:&nbsp;</p>



<ul class="wp-block-list">
<li class="wp-block-list-item">Activity type: <em>End of conversation</em>  </li>
</ul>



<ul class="wp-block-list">
<li class="wp-block-list-item">Context: <em>Conversation.EndReason</em> (for example, CUSTOMER_HANGUP)  </li>
</ul>



<p class="wp-block-paragraph">Makers can configure triggers such as:&nbsp;</p>



<ul class="wp-block-list">
<li class="wp-block-list-item">When activity = End of conversation  </li>
</ul>



<ul class="wp-block-list">
<li class="wp-block-list-item">AND EndReason = CUSTOMER_HANGUP  </li>
</ul>



<ul class="wp-block-list">
<li class="wp-block-list-item">Execute post-call workflow </li>
</ul>



<p class="wp-block-paragraph">This creates a&nbsp;<strong>deterministic and reliable event model</strong>&nbsp;for post-call automation.&nbsp;</p>


<figure class="wp-block-image size-full"><img alt="post-call actions triggered by caller hang-up events in Dynamics 365 Contact Center" class="wp-image-201965 webp-format" src="https://www.microsoft.com/en-us/dynamics-365/blog/wp-content/uploads/2026/04/image-1.webp" /></figure>



<h2 class="wp-block-heading" id="key-benefits">Key benefits </h2>



<ul class="wp-block-list">
<li class="wp-block-list-item"><strong>Immediate and reliable execution</strong>: Post-call workflows trigger as soon as the caller disconnects, eliminating delays and missed actions.</li>
</ul>



<ul class="wp-block-list">
<li class="wp-block-list-item"><strong>Foundation for governance and insights</strong>: Accurate call termination signals enable organizations to implement compliance, auditing, and data policies while building custom telemetry, reporting, and customer experience insights.</li>
</ul>



<h2 class="wp-block-heading" id="real-world-scenarios">Real-world scenarios </h2>



<ul class="wp-block-list">
<li class="wp-block-list-item"><strong>Automated record updates and follow-ups</strong>: Update or unlock CRM records and trigger SMS, email, or callback workflows immediately after the customer disconnects, ensuring the latest state is captured and acted on without delay.  </li>
</ul>



<ul class="wp-block-list">
<li class="wp-block-list-item"><strong>Drop-off detection and recovery</strong>: Identify when customers exit during critical flows (such as payment or authentication) and initiate appropriate recovery or risk handling actions.  </li>
</ul>



<ul class="wp-block-list">
<li class="wp-block-list-item"><strong>Operational insights and optimization</strong>: Leverage precise end-of-conversation signals to improve data accuracy, escalation tracking, and overall customer experience. </li>
</ul>



<h2 class="wp-block-heading" id="learn-more">Learn more</h2>



<p class="wp-block-paragraph">To learn more about post-call actions, read the documentation: <a href="https://learn.microsoft.com/en-us/microsoft-copilot-studio/voice-post-call-actions" rel="noreferrer noopener" target="_blank"><a href="https://learn.microsoft.com/en-us/microsoft-copilot-studio/voice-post-call-actions" rel="noreferrer noopener" target="_blank">Configure post-call action topics &#8211; Microsoft Copilot Studio | Microsoft Learn</a></a> </p>
<p>The post <a href="https://www.microsoft.com/en-us/dynamics-365/blog/it-professional/2026/04/15/trigger-post-call-actions-using-caller-hang-up-events/">Trigger post-call actions using caller hang-up events </a> appeared first on <a href="https://www.microsoft.com/en-us/dynamics-365/blog">Microsoft Dynamics 365 Blog</a>.</p>
</div>
