# [Wio Personal - International Payment Systems (SWIFT, Wise)](https://app.getguru.com/card/iARzkLBT/Wio-Personal-International-Payment-Systems-SWIFT-Wise)

<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Topic Overview
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  SWIFT Transfers
 </strong>
 are international money transfers conducted through the SWIFT (Society for Worldwide Interbank Financial Telecommunication) network, which allows banks to securely send and receive information about financial transactions.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Wise Transfer
 </strong>
 is a service provided by Wise (formerly known as TransferWise) that allows users to initiate outward international transfers in local currencies for over 40 countries.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 In this article you will learn about the SWIFT and Wise international payment systems.
</p>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 SWIFT Payment
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Key points:
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  We have 2 types of transaction limits i.e., one which is
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   source account
  </strong>
  payment limit, and the other one is
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   destination
  </strong>
  currency limit.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  If a customer wants to
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   make a payment in USD to a UAE bank account from their Wio USD account,
  </strong>
  they still need to
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   choose ‘International Payments’
  </strong>
  then proceed with the international payments flow, payment will be processed as a normal SWIFT payment (
  <a class="ghq-card-content__link" data-ghq-card-content-type="LINK" href="https://wiobank.atlassian.net/wiki/spaces/ADQFS/pages/552894469/Local+International+Transfers+Payment+Gateways-+Ops+FO#First-new-international-payment" rel="noopener noreferrer" target="_blank">
   First new international payment
  </a>
  )
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  If the customer chooses
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Local payment from their USD accounts
  </strong>
  , they will only see
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   AED currency
  </strong>
  option available.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  List of available countries:
  <a class="ghq-card-content__link" data-ghq-card-content-type="LINK" href="https://wiobank.atlassian.net/wiki/spaces/wpediasme/pages/768770260" rel="noopener noreferrer" target="_blank">
   SWIFT &amp; WISE Available Currencies and limits - OPS FO
  </a>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  Wio bank now have its own
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   SWIFT
  </strong>
  for sending/receiving international payments.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  No onboarding will be required to use
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   SWIFT;
  </strong>
  however, customer account needs to be fully activated.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  SWIFT system will support the 3 major currencies
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   (USD, EUR, GBP)
  </strong>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  Current
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   AED
  </strong>
  accounts or
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   multi-Currency
  </strong>
  accounts will have the same process to send a SWIFT transfer.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Correspondent bank fees for SWIFT transfers is 15.75 USD, EUR, GBP or AED 63
  </strong>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Wio transaction fee for Wio retail is AED 0 - Launch feature - subject to change
  </strong>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  Normal TAT for outward SWIFT payment would be
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   3 - 5 working days.
  </strong>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  WISE will still be available for
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <u class="ghq-card-content__underline" data-ghq-card-content-type="UNDERLINE" style="text-decoration:underline">
    sending
   </u>
  </strong>
  international payments for other currencies except
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   (USD, EUR,GBP) and for available countries, refer to
  </strong>
  <a class="ghq-card-content__link" data-ghq-card-content-type="LINK" href="https://wiobank.atlassian.net/wiki/spaces/wpediasme/pages/768770260" rel="noopener noreferrer" target="_blank">
   Universal - SWIFT &amp; WISE Available Currencies and limits - OPS FO
  </a>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  Currency exchange rate is locked to 5 minutes per transaction.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  SWIFT copies are sent to customers once payment is confirmed.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  Manual SWIFT copy requests will be handled through Wio care - assign case to
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Everyday banking Queue through ThinkOwl
  </strong>
  -
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   TAT
  </strong>
  within 1 working day.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   SWIFT
  </strong>
  OR
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   WISE
  </strong>
  payments will be determined (based on currency)
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  WISE will still be available for
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <u class="ghq-card-content__underline" data-ghq-card-content-type="UNDERLINE" style="text-decoration:underline">
    sending
   </u>
  </strong>
  international payments for other currencies except
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   (USD, EUR,GBP) and for available countries, refer to
  </strong>
  <a class="ghq-card-content__link" data-ghq-card-content-type="LINK" href="https://wiobank.atlassian.net/wiki/spaces/wpediasme/pages/768770260" rel="noopener noreferrer" target="_blank">
   Universal - SWIFT &amp; WISE Available Currencies and limits - OPS FO
  </a>
 </li>
</ul>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Wise Transfer
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  What is Wise?
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  A partner of Wio to initiate outward international transfers in local currencies for +40 countries.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  Formerly known as TransferWise
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Wise help Centre:
  </strong>
  <a class="ghq-card-content__link" data-ghq-card-content-type="LINK" href="https://wise.com/help/" rel="noopener noreferrer" target="_blank">
   Hi, how can we help? | Wise Help Centre
  </a>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Internal only:
  </strong>
  Wise onboarding (sign-up) will only happen in the backend system and doesn't require any action from customer side.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  In case
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   WISE
  </strong>
  rejected the customer account for any reason, an email will be sent to the customer.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  For
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   WISE
  </strong>
  rejected customers, they can still use SWIFT payment for outward transfers (USD, GBP, EUR) currencies only will be available.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   SWIFT
  </strong>
  OR
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   WISE
  </strong>
  Transfers will be determined (based on currency)
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  WISE will still be available for
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <u class="ghq-card-content__underline" data-ghq-card-content-type="UNDERLINE" style="text-decoration:underline">
    sending
   </u>
  </strong>
  international transfer for other currencies except
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   (USD, EUR, GBP) and for available countries, refer to
  </strong>
  below links for more information about currency specific availability for each country.
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   Only refer to
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    SWIFT
   </strong>
   available currencies
   <a class="ghq-card-content__link" data-ghq-card-content-type="LINK" href="https://wiobank.atlassian.net/l/cp/4y79QzZQ" rel="noopener noreferrer" target="_blank">
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     SWIFT &amp; WISE Available Currencies and limits - OPS
    </strong>
   </a>
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   Refer to
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    WISE
   </strong>
   Available Currencies and limits Currency coverage and limits
  </li>
 </ul>
</ul>
<section class="ghq-card-content__callout" data-ghq-card-content-type="CALLOUT" data-ghq-color="blue" style="background-color: #00bcd62b;">
 <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
  <a class="ghq-card-content__file" data-ghq-card-content-filename="undefined" data-ghq-card-content-type="FILE" href="https://content.api.getguru.com/files/view/1061f418-169b-49f7-adbe-24deee2e292b" rel="noopener noreferrer" target="_blank">
   Currency coverage and limits (1) (2).xlsx
  </a>
 </p>
</section>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  Currency exchange rate is locked to 5 minutes per transaction.
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Internal only - Wise sheet - to be used for Wise related queries:
 </strong>
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 Link:
 <a class="ghq-card-content__link" data-ghq-card-content-type="LINK" href="https://docs.google.com/spreadsheets/d/1N4OXPTL9VwQbvMmz66UUUdyAS_euKiTObSORF-A3qFE/edit#gid=1340615662" rel="noopener noreferrer" target="_blank">
  Wise Currencies Sheet
 </a>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Email
  </strong>
  :
  <a class="ghq-card-content__link" data-ghq-card-content-type="LINK" href="mailto:roman.empires2021@gmail.com">
   roman.empires2021@gmail.com
  </a>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   PW:
  </strong>
  weeyoW@2024
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Note
 </strong>
 : Don’t use the
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  global currencies
 </strong>
 sheet within the Wise sheet, only advise customer of the currencies available in the Wio application.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Fees &amp; Charges:
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Wise Charges:
  </strong>
  varies
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  </strong>
  from 0.40% to 4.5%
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Wio Bank charges:
  </strong>
  No bank charges, Only Wise charges are applicable.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   TAT for both WISE &amp; SWIFT:
  </strong>
  up to 3 - 5 working days, should be displayed in the payment confirmation page.
 </li>
</ul>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
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
