# [Wio Personal - Accounts Restricted: Passport Upload](https://app.getguru.com/card/Txb5b6Kc/Wio-Personal-Accounts-Restricted-Passport-Upload)

<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Topic Overview
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 We need to capture our client's passports prior to enabling our clients to complete international transfers due to screening purposes. The objective is to prompt the client to upload a passport whenever certain actions are completed to avoid drop-offs at international transfers, as customers may need to provide passport and address. In this article you will learn about the account restricted status because of passport upload.
</p>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Wio Personal Accounts Restricted - Due to Passport Upload
</h1>
<h2 class="ghq-card-content__medium-heading" data-ghq-card-content-type="MEDIUM_HEADING">
 Internal only - Passport screening
</h2>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 Post uploading passport, if the passport new name has a hit and is flagged for screening
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  If there is a HIT, then the customer
  <u class="ghq-card-content__underline" data-ghq-card-content-type="UNDERLINE" style="text-decoration:underline">
   cannot complete the local or international transfer
  </u>
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF sanctioned
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF blacklist (do we need to re-screen blacklist)
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF local PEP
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF foreign PEP
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF adverse media
   <br/>
  </li>
 </ul>
</ul>
<h3 class="ghq-card-content__small-heading" data-ghq-card-content-type="SMALL_HEADING">
 Internal only: Onboarding &amp; Compliance Team Steps
</h3>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Hierarchy of alerts
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  First blacklist screening is completed via PassFort if there is no hit or a potential hit is discounted then the remaining name screening typologies are triggered on Napier (Sanctions, PEP, and Adverse Media)
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   If a client is a true positive hit for blacklist, their manual account close processes is kicked and Napier name re-screening process is not completed
  </li>
 </ul>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  Sanctioned hits will override PEPs (Local &amp; Domestic) and Adverse media hits
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   If the client is a potential Sanctions hit and PEP (Local or Domestic) client's account will still be restricted for debits
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   If the client is true positive for Sanctions, then no action is required on PEP alerts
  </li>
 </ul>
</ul>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Blacklist (internal screening)
  </strong>
 </strong>
 PASSFORT
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF there is no hit when completing blacklist screening, then no action is required on Passfort
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF there is a hit THEN add a tag on Passfort to identify Blacklist screening hit occurred and move to Compliance queue for review
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF Passfort task is pending THEN restrict debit remains
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF Passfort task is passed (false-positive) THEN restrict debit removed
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    IF Passfort task is failed (true-positive) THEN restrict debit remains, and manual account closure process is kicked-off
   </strong>
  </li>
 </ul>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Sanctions handling
  </strong>
 </strong>
 NAPIER
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF screening alert is unresolved, then restrict debit is applied (potential hit)
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF screening alert is discounted, then restrict debit is removed (false-positive)
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    IF screening alert is confirmed then the client's account remains debit-restricted, and manual account closure process is kicked off (true positive)
   </strong>
  </li>
 </ul>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   PEP (Domestic &amp; Foreign) handling
  </strong>
 </strong>
 NAPIER
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   As per the above, there is no account restricted applied for local &amp; foreign PEP even when the alert is under review or resolved
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    IF an alert for Local or Foreign PEP is
   </strong>
   <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
    confirmed
   </code>
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    THEN add EDD Task to Passfort Profile and assign it to Compliance Queue
   </strong>
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   Foreign PEP - Add Foreign PEP tag on Passfort and trigger
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    EDD
   </strong>
   task
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   Domestic PEP - Add Domestic PEP tag and no
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    EDD
   </strong>
   task required
  </li>
 </ul>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  <u class="ghq-card-content__underline" data-ghq-card-content-type="UNDERLINE" style="text-decoration:underline">
   Adverse Media handling
  </u>
 </strong>
 NAPIER
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   IF the screening alert is resolved (false positive) OR under review, THEN no action is required
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    IF the screening alert is confirmed (true positive) then the client's account remains debit-restricted, and the manual account closure process is kicked-off
   </strong>
  </li>
 </ul>
</ul>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
</h1>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 FAQs &amp; Smart Responses
</h1>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
</h1>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Related Articles
</h1>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
