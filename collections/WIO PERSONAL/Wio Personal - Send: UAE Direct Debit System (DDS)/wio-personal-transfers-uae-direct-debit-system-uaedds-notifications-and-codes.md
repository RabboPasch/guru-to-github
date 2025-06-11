# [Wio Personal - Transfers: UAE Direct Debit System (UAEDDS) Notifications and Codes](https://app.getguru.com/card/ck9Lbdki/Wio-Personal-Transfers-UAE-Direct-Debit-System-UAEDDS-Notifications-and-Codes)

<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="TLRdjB5WJRZG">
</p>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="pqNfA3IBc5bZ">
 Topic Overview
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="CvngZX2sHL7I">
 This article details the direct debit system (DDS) notifications sent to Wio Bank customers, outlining the various event triggers (e.g., submissions, updates, cancellations) and corresponding messages sent via SMS, email, and push notifications to inform customers about their direct debit status and ensure proper account management.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="P5ZdhbPlR056">
 The codes table outlines various return codes used to describe the status of DDA account entries and their corresponding actions. UAE Direct Debit System (UAEDDS) Important Codes
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="f1jq356XDPj1">
 UAE Direct Debit System (UAEDDS) Notifications
</h1>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="75RTpzlYfWFh">
</p>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-is-full-width="true" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="312,507" data-ghq-table-header="true">
   <colgroup>
    <col style="width:312px"/>
    <col style="width:507px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="YDCFvIPqD4Bn">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event &amp; Trigger
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SMS, Email and Push
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="d3DxNIHb6tXn">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event:
       </strong>
       Submission of DDA
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Trigger:
       </strong>
       Once we receive a DDA request for a customer from Any other bank
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SMS Prod:
       </strong>
       7c6243eb-ec8d-4a2e-8b83-2c174fc46a15 ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We’ve received a request from {{bankName}} to set up a direct debit for {{purpose}}. We’ll process it shortly. If you didn’t request this, call or WhatsApp us 600 500 946.
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Email prod:
       </strong>
       d18224a6-6964-4b36-9847-7ed103877dc7 ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SL: Direct debit authorization request received
       </strong>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hi {{name}},
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We’ve received a direct debit authorization request from {{bankName}} for AED {{amount}} for the period {{fromDate}} to {{toDate}}. We will process this request.
      </p>
      <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="Al3W9fex3Td5">
        Originator Name {{originatorName}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="ZhfD5EA6DJ7Z">
        Primary Sponsoring Bank {{bankName}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="NpRtTp1hLZH1">
        DDA Purpose {{purpose}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="h5tjDe6x453d">
        Issued for {{purpose}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="p1V8ZVZTnpnk">
        Starts on {{fromDate}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="FrRRnTDp1eyh">
        Ends on {{toDate}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="IPlHuR1hZtOt">
        Amount {{amount}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="5TxhHDbJBn5n">
        Payment frequency {{frequency}}
       </li>
      </ul>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       If you don’t recognize this request, call or WhatsApp our Wio Care team at 600 500 946.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Team Wio
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="TlLXlNjZxyrr">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event:
       </strong>
       DDA rejection
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Trigger:
       </strong>
       in cases we reject
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SMS Prod:
       </strong>
       30238b29-ae8f-4698-a819-9f5e6f1c2dea ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your direct debit setup request has been rejected due to {{reason}}. For more details, please contact the bank where you made the request.
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Push prod:
       </strong>
       dfc46be3-ebed-4476-8b43-700d799b9bd2 ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Direct debit setup rejected
       </strong>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your direct debit setup request was rejected due to {{reason}}. For details, contact the bank where you made the request.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="7T8aYNZvsOpD">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event:
       </strong>
       Changes or Update in DDA
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Trigger:
       </strong>
       once we receive any update request for DDA
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Push: Direct debit details updated
       </strong>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your direct debit details have been updated. Tap to learn more.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="gFlnXJfv7sr0">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event:
       </strong>
       Changes or Update in DDA
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Trigger:
       </strong>
       once we receive any update request for DDA
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Email prod:
       </strong>
       3e55776b-ed89-41cb-88fb-ca7ad7abbb5e ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SL: Details Updated for Your Direct Debit Setup
       </strong>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hi {{name}},
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We've received an update request for your direct debit setup with Wio Bank. Your updated details are:
      </p>
      <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="FpgVDvVnlMar">
        Originator Name {{originatorName}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="QnIhkTFEryGP">
        Primary Sponsoring Bank {{bankName}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="PyNPnou1ZTVR">
        DDA Purpose {{purpose}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="jvfxGbjoSl2w">
        Issued for {{purpose}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="wHsNdjTJPtbz">
        Starts on {{fromDate}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="jop9bfyEJm3z">
        Ends on {{toDate}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="TKDdB7fRIp6v">
        Amount {{amount}}
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="UMbtPqNp04P9">
        Payment frequency {{frequency}}
       </li>
      </ul>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       If you didn’t request this update, call or WhatsApp us at 600 500 946.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Team Wio
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="p636f7DRS3uH">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event:
       </strong>
       Cancellation of DDA
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Trigger:
       </strong>
       if a cancellation is done by another bank or Wio bank
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SMS Prod:
       </strong>
       98334e57-6e8e-4303-ba36-eb7bcd43e498 ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your direct debit has been canceled by {{bankName}} due to {{reason}}.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="fdB3lProTJTH">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event:
       </strong>
       on receiving DDR request -
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        DDR_RECEIVED
       </code>
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Trigger:
       </strong>
       on receiving DDR from another bank
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Push prod:
       </strong>
       8696fdca-ebed-480d-832e-e6612d1868cf ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Debit request received
       </strong>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You’ve received a debit request from {{sender}} for AED {{amount}}. It’ll be processed shortly.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="mjpbdrNq9hMR">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event:
       </strong>
       on receiving DDR request But account balance is low.
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Trigger:
       </strong>
       on receiving DDR from another bank but current account balance is low.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SMS Prod:
       </strong>
       5db141e6-11c5-402e-aec1-652898306410✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your account has insufficient funds for a debit request of AED {{amount}}. Please add funds by 3 PM today to avoid any processing issues.
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Push prod:
       </strong>
       c5933a6b-ccf1-4c15-8839-a8ba523aa61a
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Low balance for debit request
       </strong>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You’ve received a debit request for AED {{amount}}. Make sure to add funds by 3 PM today to ensure it’s processed.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="hhFhQXBVsNmb">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event:
       </strong>
       DDR rejection due to insufficient funds MVP -
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       P0 -
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        DDR_VALIDATION_FAILED
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SMS Prod:
       </strong>
       a0d2fe08-79b1-4bfe-a832-4358c0851c7b ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We couldn’t process your direct debit of AED {{amount}} on {{transactionDate}} due to insufficient funds in your account. Add money to your account and retry the payment.
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Email prod:
       </strong>
       09b836a6-9742-4865-b01a-8b31134ebc36 ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SL:
       </strong>
       Direct debit payment unsuccessful
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hi {{name}},
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We couldn’t process your direct debit of AED {{amount}} on {{transactionDate}} because there weren’t enough funds in your account. This will impact your credit score.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       If you have any questions, call or WhatsApp us at 600 500 946.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Team Wio
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="xBdDbFPbhane">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event:
       </strong>
       DDR rejection due to other reason. -
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        DDR_REJECTED
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SMS Prod:
       </strong>
       d264a288-71f0-4d86-8a3f-6fd09256f883 ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We couldn’t process your direct debit of AED {{amount}} on {{transactionDate}} due to {{reason}}.
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Email prod:
       </strong>
       80b3b308-48aa-40b6-9999-1a500e2b2161 ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SL:
       </strong>
       Direct debit payment unsuccessful
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hi {{name}},
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We couldn’t process your direct debit of AED {{amount}} on {{transactionDate}} because {{reason}}.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       If you have any questions, call or WhatsApp us at 600 500 946
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="Z574BbWLQDDS">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event:
       </strong>
       On debit to customer MVP
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       P0 -
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        DDR_AMOUNT_WITHDRAWN
       </code>
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Trigger:
       </strong>
       once we successfully debit the customer
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SMS Prod:
       </strong>
       15acc784-4708-4b0d-8fe0-9397ac3f8905 ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your direct debit request for {{purpose}} has been processed successfully. AED {{amount}} has been debited from your account {{account_no}}
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Email prod:
       </strong>
       be00447b-6573-4ee2-a905-fc1322180dc4 ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        SL: Direct debit payment processed successfully
       </strong>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hi {{name}},
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your direct debit payment for {{purpose}} has been successfully processed. We've debited AED {{amount}} from your account {{account_no}} on {{transactionDate}}.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Team Wio
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="VJlbWnrFQZNU">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event:
       </strong>
       A day prior to Expected DDR request
      </p>
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Trigger:
       </strong>
       1 day prior to a fixed date DDR request
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Push prod:
       </strong>
       364b8761-f95f-4886-8f15-3a6a2730632b✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Upcoming direct debit request
       </strong>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You have an upcoming direct debit from {{sender}} for {{purpose}} of AED {{amount}}. Make sure you have enough funds in your account for it to be processed.
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="Qi7XSNx45wdB">
 UAE Direct Debit System (UAEDDS) Important Codes
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="1xLlLPxDVhTt">
 The table outlines various return codes used to describe the status of DDA account entries and their corresponding actions.
</p>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-is-full-width="true" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="100,310,522" data-ghq-table-header="true">
   <colgroup>
    <col style="width:100px"/>
    <col style="width:310px"/>
    <col style="width:522px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="retD9983hX09">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Code
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Description
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Account Entries
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="jdpBedwnje3h">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Accepted CLAIMED AMOUNT
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       DEBIT Entry
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="NBP2TpUoJ3Jd">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Accepted PARTIAL AMOUNT
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       DEBIT Entry
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="kW9XzmtDFHmj">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       A
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Account Closed
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       NO A/C ENTRY REQUIRED
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="BnTLiMTmjifa">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       C
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Compliance Issues
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       NO A/C ENTRY REQUIRED
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="T4hkJy5ro0BT">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       D
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payer Deceased
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       NO A/C ENTRY REQUIRED
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="xY7A90Ltlztf">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        E
       </del>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        Card Blocked
       </del>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        NO A/C ENTRY REQUIRED
       </del>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="XEZOGJRRKjhv">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        F
       </del>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        Card Expired
       </del>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        NO A/C ENTRY REQUIRED
       </del>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="137PB7x7Zxny">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        G
       </del>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        Card Cancelled
       </del>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        NO A/C ENTRY REQUIRED
       </del>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="QvFl6TlTy6JO">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       I
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Insufficient Funds
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       DEBIT Entry + CREDIT Entry. NO A/C ENTRY REQUIRED if: CREDIT CARD, or for SAVINGS ACCOUNT if the ENTITY’S CORE SYSTEM does not have the capability to overdraw and then reverse.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="XlnWVZyBfvKJ">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        L
       </del>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        Card Limit Exceeded
       </del>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
        NO A/C ENTRY REQUIRED
       </del>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="DHvMZwBCtNrT">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       N
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Dormant Account
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       NO A/C ENTRY REQUIRED
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="rL33xFdrGe2r">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       O
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       DDA Cancelled
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       DEBIT Entry + CREDIT Entry. NO A/C ENTRY REQUIRED if: CREDIT CARD, or for SAVINGS ACCOUNT if the ENTITY’S CORE SYSTEM does not have the capability to overdraw and then reverse.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="SJwjERk4hzn5">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       P
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment Not Honoured by Paying Bank – Payer to Contact Bank
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       DEBIT Entry + CREDIT Entry. NO A/C ENTRY REQUIRED if: CREDIT CARD, or for SAVINGS ACCOUNT if the ENTITY’S CORE SYSTEM does not have the capability to overdraw and then reverse.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="WvvvlusdMzj3">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       R
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       DDR details inconsistent with DDA details
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       NO A/C ENTRY REQUIRED
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="ydYnZO9grpI7">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       S
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment Stopped
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       DEBIT Entry + CREDIT Entry. NO A/C ENTRY REQUIRED if: CREDIT CARD, or for SAVINGS ACCOUNT if the ENTITY’S CORE SYSTEM does not have the capability to overdraw and then reverse.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="3NZbttVtwOrZ">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       T
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Technical Issues at Paying Bank – Auto No-Pay Response from UAEDDS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       DEBIT Entry + CREDIT Entry. NO A/C ENTRY REQUIRED if: CREDIT CARD, or for SAVINGS ACCOUNT if the ENTITY’S CORE SYSTEM does not have the capability to overdraw and then reverse.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="91VFduaEdBQ9">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       U
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Amount Is Not Yet Due
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       DEBIT Entry + CREDIT Entry. NO A/C ENTRY REQUIRED if: CREDIT CARD, or for SAVINGS ACCOUNT if the ENTITY’S CORE SYSTEM does not have the capability to overdraw and then reverse.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="jplmsdyKjUxz">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       V
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Account Closed – Mandated by CBUAE / Law Enforcement / Judiciary
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       NO A/C ENTRY REQUIRED
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="1777z8bRXA3G">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       W
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Account Closed – Internal Compliance / Commercial Issues
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       NO A/C ENTRY REQUIRED
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="jf93TTPgPLSN">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       X
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Account blocked by Judiciary
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       NO A/C ENTRY REQUIRED
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="2EnRFh9ZZhSD">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Y
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Account blocked by Law Enforcement Agency
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       NO A/C ENTRY REQUIRED
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="PdnT17CO6SXh">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Z
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Account blocked by Central Bank of the UAE
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       NO A/C EN
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="cNyKyj7roLkv">
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="tdNFaRL3BZ6n">
 DDA Rejection Reasons and Codes
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="xJlBi2Xj6hMX">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
   The rejection of a Direct Debit Authorization (DDA) request can occur for several reasons. Here are some common reasons for DDA request rejections:
  </span>
 </strong>
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM" id="3MRRWczK3TCb">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Signature Issues
  </strong>
  : Incorrect or missing signatures can lead to rejection (RR01 - Signature Incorrect, RR02 - Signature Missing/Additional Signature(s) Required).
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM" id="FFrBh9p1kiv7">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Account Issues
  </strong>
  :
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="3jfHnxzcks5I">
   Invalid account details (RR04 - Invalid Account) .
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="BHPUH5dJhby5">
   Account not denominated in AED currency (RR13 - Account not denominated in AED).
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="uJ53nPthjHPH">
   Account closed (RR07 - Account Closed).
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="J1piY6jp9FZ7">
   Dormant account status (RR12 - Dormant Account).
  </li>
 </ul>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM" id="gii9kdJrQBzr">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Compliance and Legal Restrictions
  </strong>
  :
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="zjLwZrsBczzn">
   Account blocked by judiciary or law enforcement (RR15 - Account blocked by Judiciary, RR16 - Account blocked by Law Enforcement Agency).
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="7hZitVoXr9Tf">
   Compliance issues (RR90 - Compliance Issues).
  </li>
 </ul>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM" id="Fzv910s5FBdB">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Bank Acceptance Issues
  </strong>
  :
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="HHsAf79ZqbGX">
   DDA not accepted by the paying bank (RR18 - DDA Not Accepted by Paying Bank).
  </li>
 </ul>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM" id="XHf7Q8DHxNdy">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Other Reasons
  </strong>
  :
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="hRRR9RjzpWil">
   Title mismatch (RR05 - Title Mismatch).
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="19PbNDd1xVlH">
   Payer deceased (RR06 - Payer Deceased).
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="XTvu5PjtLtl0">
   <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
    Card-related issues such as cancellation or expiration (RR08 - Card Cancelled, RR09 - Card Expired).
   </del>
  </li>
 </ul>
</ol>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="2xVB9kxtPgqz">
</p>
<h2 class="ghq-card-content__medium-heading" data-ghq-card-content-type="MEDIUM_HEADING" id="FpnQbHur5L5V">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  DDA Rejection Codes
 </strong>
</h2>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="FST7PimdJzvv">
 RR01 - Signature Incorrect
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="VXAL34I79zgv">
 RR02 - Signature Missing / Additional Signature(s) Required
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="AJFMBJKzrbLu">
 RR04 - Invalid Account
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="iW5ZgsdS97lF">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
    <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
     Account in Withdrawn state - Account does not exist/Invalid format
    </span>
   </em>
  </strong>
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="dzVcMXjPVNQi">
 RR05 - Title Mismatch
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="nhx5ftTj5sJT">
 RR06 - Payer Deceased
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="YfIxtxURzxNJ">
 RR07 - Account Closed
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="hXN86JtZFR9k">
 RR08
 <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
  - Card Cancelled
 </del>
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="soYVX8wY5Fs6">
 RR09
 <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
  - Card Expired
 </del>
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="JQjRxL7vKBvf">
 RR10
 <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
  - Card Blocked
 </del>
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="CZDH3TPOHf33">
 RR11
 <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
  - Invalid Card
 </del>
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="YXrTHQlrTWWc">
 RR12 - Dormant Account
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="71FN2br3F83t">
 RR13 - Account not denominated in AED
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
    -
   </span>
  </em>
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="mxsvdtphahdZ">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
    <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
     Account is in non-AED currency
    </span>
   </em>
  </strong>
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="POhv8tRnfC3j">
 RR14 - Signatory(ies) not authorized for the Mandate Amount
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="Nl1kfMWLhvUD">
 RR15 - Account blocked by Judiciary
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="kNyrF1btlJhv">
 RR16 - Account blocked by Law Enforcement Agency
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="zsh31HLXTIIc">
 RR17 - Account blocked by Central Bank of the UAE
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="wkCEmhJ7Alj7">
 RR18 - DDA Not Accepted by Paying Bank - Contact Your Bank
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#ffc200">
   </span>
  </em>
 </strong>
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
    -
   </span>
  </em>
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="9l2APTHI1XFd">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
    <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
     Joint account reason or
    </span>
   </em>
  </strong>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="u9HpxqvDPB7x">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
    <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
     SME Active Account
    </span>
   </em>
  </strong>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="Jmtr3FQjlnDz">
  <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
    <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
     FF
    </span>
   </span>
  </span>
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
    is disabled for customer
   </span>
  </strong>
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="DJaJZzCCZP1Y">
 RR18 - DDA Not Accepted by Paying Bank - OIC Blocked
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="z2XDMzkPfLZm">
  <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    Originator Identification Code (
   </strong>
  </span>
  <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
    <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
     OIC)
    </span>
   </span>
  </span>
  <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    is restricted
   </strong>
  </span>
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="L5trehzUJbDk">
 RR50 - Invalid Consumer Number
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="UX6DL5NNeVHo">
 RR54 - Rejected by Originator
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="ACVzd9Cfj9Rd">
 RR55 - Unable to obtain Originator confirmation
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="yPJ551fjEj3f">
 RR90 - Compliance Issues
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="Xtx9tnzqPKLB">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
    <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
     Account in Locked state, Debit Restricted, Credit Restricted, Frozen Status
    </span>
   </em>
  </strong>
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="7DphpZzyJlkJ">
 RR91 - Scanned DDA Unusable
</p>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="Khih4dxZNfaN">
</p>
<h2 class="ghq-card-content__medium-heading" data-ghq-card-content-type="MEDIUM_HEADING" id="jdwYrz598Tpb">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  No code DDA rejection reasons
 </strong>
</h2>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="9er5HzrGotfn">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  DDA is accepted, Validation passed:
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="8LEDcwofK7zP">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Customer has restriction “CREDIT“:
  </strong>
  DDA is Accepted, Validation Passed
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="tMB3rLG8fT3E">
  Account is active, however with negative balance
 </li>
</ul>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="wZnWJJxdXD1N">
</p>
