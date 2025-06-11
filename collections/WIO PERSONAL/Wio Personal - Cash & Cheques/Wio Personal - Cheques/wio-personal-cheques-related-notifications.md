# [Wio Personal - Cheques: Related Notifications](https://app.getguru.com/card/iaeBR9jT/Wio-Personal-Cheques-Related-Notifications)

<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Topic Overview
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 This article details the notifications triggered during various cheque deposit and withdrawal processes, including updates on cheque processing, failures, and balance alerts, ensuring customers are informed throughout.
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Notifications: Trigger, type, Content
</h1>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="168,225,140,381" data-ghq-table-header="true">
   <colgroup>
    <col style="width:168px"/>
    <col style="width:225px"/>
    <col style="width:140px"/>
    <col style="width:381px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Notification
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Trigger
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Notification type
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Content updated
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cheque Deposit ATM submission
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        Trigger a notification to the customer once the cheque is deposited by customer in the FAB ATM
       </li>
      </ul>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Cheque received
       </strong>
       <br/>
       Your cheque ending in {{cheque_no}} was deposited in
       <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
        <mark class="ghq-card-content__highlight" data-ghq-card-content-type="HIGHLIGHT" style="background-color:#fde892">
        </mark>
       </span>
       <mark class="ghq-card-content__highlight" data-ghq-card-content-type="HIGHLIGHT" style="background-color:#fde892">
        a FAB CDM machine
       </mark>
       . It’ll be processed within 3 business days.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cheque deposit TG scan the cheque
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        Trigger a notification when the TG team scans the cheque to present the check to the other bank for clearing
       </li>
      </ul>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Cheque processing update
       </strong>
       <br/>
       Your cheque ending in {{cheque_no}} is now being processed. The money will be credited to you shortly.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cheque deposit failure
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        trigger a notification if the check is rejected by the other bank with content that the physical cheque will be returned to the customer.
       </li>
      </ul>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push, SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push:
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Cheque returned
       </strong>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your cheque ending in {{cheque_no}} was rejected by the other bank due to {{reason}}. The physical cheque will be returned to you.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS:
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your cheque ending in {{cheque_no}} was rejected by the other bank due to {{reason}}. We’ll contact you to arrange the return of the physical cheque.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cheque Withdrawal submission by other bank with sufficient funds in account
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        trigger when the cheque is deposited by other bank for money withdrawal
       </li>
      </ul>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Cheque withdrawal request
       </strong>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We’ve got a request to withdraw {{original_currency}} {{original_amount}} from your cheque ending in {{cheque_no}}. It’ll be processed today.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cheque Withdrawal with low balance account critical
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        trigger if the cheque is deposited and account balance is low.
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        Send information to refill the account till 3 pm so that there will be no impact on the AECB score
       </li>
      </ul>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push and critical
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push:
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Cheque withdrawal request
       </strong>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We’ve got a cheque withdrawal request for {{original_currency}} {{original_amount}}. Tap here to top up your account before
       <mark class="ghq-card-content__highlight" data-ghq-card-content-type="HIGHLIGHT" style="background-color:#fde892">
        3 PM
       </mark>
       today to avoid a cheque bounce and protect your credit score.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS:
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We’ve got a cheque withdrawal request for {{original_currency}} {{original_amount}} for cheque ending in {{cheque_no}}. Make sure you have enough funds in your account by 3 PM today to avoid a cheque bounce and protect your credit score.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cheque withdrawal bounce
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        if the cheque withdrawal gets bounced due to any reason.
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        if it is due to a low balance, we should communicate the impact on AECB score.
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
        for the remaining reasons, we should mention the reason to the customer.
       </li>
      </ul>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Email, Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SL: Cheque clearance failed due to
       <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
        <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
         insufficient funds {{reason}}
        </span>
       </span>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hi {{name}},
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your cheque number {{cheque_no}} from account {{account_no}} didn't go through due to
       <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
        <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
         insufficient funds {{reason}}
        </span>
       </span>
       .
       <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
        This may impact your credit score.
       </span>
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Keep in mind – according to regulations, if this happens more than four times within a 12-month period, your cheque deposit service will be suspended. From the fifth bounced cheque onward, all cheques will be returned, and your account will be closed.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Make sure your account has enough money before your cheques are deposited to avoid this happening again.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Team Wio
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push:
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Cheque clearance failed
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Inward clearance | Cheque honored
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cheque amount has been deducted from the account against a cheque that is issued.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Pre: f3f64f2a-edf2-4cf4-a46f-0ae2cb663bc0
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SL: Your cheque has been cleared
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hi {{name}}
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       {{original_currency}} {{original_amount}} has been deducted from your account number {{account_no}} against cheque number {{cheque_no}} with the reference number {{transaction_ID}}.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Any questions? Please contact us on 600 500 946 for more information.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Regards,
       <br/>
       Team Wio
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
