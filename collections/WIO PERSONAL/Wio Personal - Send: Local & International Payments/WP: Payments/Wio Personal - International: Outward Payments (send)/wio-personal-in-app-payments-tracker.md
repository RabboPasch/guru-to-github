# [Wio Personal - In app: Payment's Tracker](https://app.getguru.com/card/i6RXRrgT/Wio-Personal-In-app-Payments-Tracker)

<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Topic Overview
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 A
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Payment's Tracker
 </strong>
 is a tool used to monitor and manage the status of various payment transactions, including local and international transfers, cheques, and SWIFT transactions. It helps in tracking the progress and resolution of payment-related issues, ensuring compliance, and handling escalations effectively. In this tracker you will learn about In App Transactions Tracker.
</p>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 In App Transactions Tracker
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Expectation
 </strong>
 :
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Feature assists customers in tracking transaction status and credit confirmation.
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Updates provided until the transaction reaches the recipient's bank.
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  40% of transactions go to banks not on GPI tracking, lacking final credit confirmation.
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Relevant details provided to customers on the tracker for unsupported transactions.
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Educational communications and FAQs will be updated post-feature rollout for targeted customer segments.
 </li>
</ol>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Feature Description
 </strong>
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Transaction tracker for International Transfer
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Transaction Tracker Feature
  </strong>
  :
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   Available in application transaction history after transaction initiation.
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   Supports tracking for Swift transactions in USD, EUR, and GBP accounts.
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   Not available for local transfers or Wise transactions (coming in future releases).
  </li>
 </ul>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Tracking Details
  </strong>
  :
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   Customers can view status of outward transactions initiated on Citi.
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   Tracker available for transactions initiated after December 16, 2023.
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   Each transaction status includes a specific description, date, and sub-description.
  </li>
 </ul>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Status Levels for International Transactions
  </strong>
  :
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    Processing
   </strong>
   : Until transaction exits the network (Ack_received).
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    Sent
   </strong>
   : Changes to Send after receiving Ack_received.
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    Completed
   </strong>
   : Status changes to Completed upon customer credit acknowledgment.
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    Canceled
   </strong>
   : If rejection occurs before remittance.
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    Refunded
   </strong>
   : If rejection or refund occurs post-debit, linked to original transaction reference.
  </li>
 </ul>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  You may share the below video to customers over WhatsApp
 </strong>
</p>
<section class="ghq-card-content__callout" data-ghq-card-content-type="CALLOUT" data-ghq-color="blue" style="background-color: #00bcd62b;">
 <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
  <a class="ghq-card-content__file" data-ghq-card-content-filename="undefined" data-ghq-card-content-type="FILE" href="https://content.api.getguru.com/files/view/28051d24-5db8-4c75-ad4d-60a45b891fc7" rel="noopener noreferrer" target="_blank">
   Payments tracker v8.mp4
  </a>
 </p>
</section>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Status on Swift transactions
 </strong>
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <a class="ghq-card-content__link" data-ghq-card-content-type="LINK" href="https://wiobank.atlassian.net/wiki/spaces/PA/pages/957087758/Transaction+tracker#Feature-Description" rel="noopener noreferrer" target="_blank">
  Transaction tracker | Feature Description
 </a>
</p>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Event &amp; Status on App
 </strong>
</p>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="239,219,160,241,207,185">
   <colgroup>
    <col style="width:239px"/>
    <col style="width:219px"/>
    <col style="width:160px"/>
    <col style="width:241px"/>
    <col style="width:207px"/>
    <col style="width:185px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        DRAFT_CREATED
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        TRANSFER_SUBMITTED
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        SCREENING_INITIATED
       </li>
      </ul>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
       <span class="ghq-card-content__image-container">
        <img alt="image-20240124-155606.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20240124-155606.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20240124-155606.png" style="width:272px" width="272"/>
       </span>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
        <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
         SCREENING_COMPLETE
        </li>
        <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
         UNITY_TRANSFER_SENT
         <span class="ghq-card-content__image-container">
          <img alt="image-20231026-071259.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20231026-071259.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20231026-071259.png" style="width:430px" width="430"/>
         </span>
        </li>
       </ul>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ACK_RECEIEVED
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
       <span class="ghq-card-content__image-container">
        <img alt="image-20240124-155700.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20240124-155700.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20240124-155700.png" style="width:195px" width="195"/>
       </span>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Once the transaction is out of our correspondent bank network
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
       <span class="ghq-card-content__image-container">
        <img alt="image-20240124-155731.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20240124-155731.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20240124-155731.png" style="width:209px" width="209"/>
       </span>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Due to any reason if transaction is canceled before we debit the customer, we should show cancelled by wio.
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
       <span class="ghq-card-content__image-container">
        <img alt="image-20240124-155820.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20240124-155820.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20240124-155820.png" style="width:269px" width="269"/>
       </span>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       NAK_RECEIVED
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
       <span class="ghq-card-content__image-container">
        <img alt="image-20240124-155846.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20240124-155846.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20240124-155846.png" style="width:320px" width="320"/>
       </span>
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 <undefined class="ghq-card-content__undefined" data-ghq-card-content-type="undefined">
 </undefined>
</h1>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="196,184,191,251,229,190">
   <colgroup>
    <col style="width:196px"/>
    <col style="width:184px"/>
    <col style="width:191px"/>
    <col style="width:251px"/>
    <col style="width:229px"/>
    <col style="width:190px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       If transaction is returned by our
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        correspondent bank
       </strong>
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
       <span class="ghq-card-content__image-container">
        <img alt="image-20240124-155924.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20240124-155924.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20240124-155924.png" style="width:222px" width="222"/>
       </span>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       If transaction is returned by
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        recipient bank
       </strong>
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
       <span class="ghq-card-content__image-container">
        <img alt="image-20240124-155942 (1).png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20240124-155942 (1).png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20240124-155942 (1).png" style="width:220px" width="220"/>
       </span>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       If there is a hit in napier system, we need to show additional information required
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
       <span class="ghq-card-content__image-container">
        <img alt="image-20240124-160021.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20240124-160021.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20240124-160021.png" style="width:284px" width="284"/>
       </span>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       If a query is received on
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        inward MT199 from Citi
       </strong>
       :
       <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
        Additional info required
       </em>
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
       <span class="ghq-card-content__image-container">
        <img alt="image-20240124-160120.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20240124-160120.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20240124-160120.png" style="width:244px" width="244"/>
       </span>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       If we receive any Query from any bank on inward MT199 which is not our correspondent bank
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
       <span class="ghq-card-content__image-container">
        <img alt="image-20240124-160235.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20240124-160235.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20240124-160235.png" style="width:190px" width="190"/>
       </span>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Refund in progress state
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Credit to recipient
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
       <span class="ghq-card-content__image-container">
        <img alt="image-20240124-155516.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image-20240124-155516.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image-20240124-155516.png" style="width:654px" width="654"/>
       </span>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <mark class="ghq-card-content__highlight" data-ghq-card-content-type="HIGHLIGHT" style="background-color:#fde892">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         DRAFT - DO NOT USE
        </strong>
       </mark>
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 <undefined class="ghq-card-content__undefined" data-ghq-card-content-type="undefined">
 </undefined>
</h1>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 FAQs &amp; Smart Responses
</h1>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 <undefined class="ghq-card-content__undefined" data-ghq-card-content-type="undefined">
 </undefined>
</h1>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Related Articles
</h1>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
