# [Wio Personal - Notifications: Cards Related](https://app.getguru.com/card/cp7yoL9i/Wio-Personal-Notifications-Cards-Related)

<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Topic Overview
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 This article details various notification messages for retail card transactions, including successful payments, withdrawals, refunds, and declines due to insufficient funds or card issues, using customizable placeholders.
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Notifications for Retail Card transactions
</h1>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-is-full-width="false" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="287,480,333,116" data-ghq-table-header="true">
   <colgroup>
    <col style="width:287px"/>
    <col style="width:480px"/>
    <col style="width:333px"/>
    <col style="width:116px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Description
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Notification Message(With placeholder)
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Notification Event Name
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Channel
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Successful (POS / Ecom)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment of {{original_currency}} {{original_amount}} {{#if billing_currency}}({{billing_currency}} {{billing_amount}}) {{/if}}was done at {{merchant_name}} using your Wio Personal card {{debitcard_no}} with {{SourceOfFunds}}
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_SUCCESS_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Successful (POS / Ecom)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ✅ Payment
       <br/>
       {{original_currency}} {{original_amount}} {{#if billing_currency}}({{billing_currency}} {{billing_amount}}) {{/if}} at {{merchant_name}} using your Wio Personal card {{debitcard_no}} with {{SourceOfFunds}}
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_SUCCESS_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM - Successful Cash Withdrawal
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cash withdrawal of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} using card ending with {{debitcard_no}}.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_WITHDRAWAL_SUCCESS_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM - Successful Cash Withdrawal
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ✅ Cash withdrawal
       <br/>
       {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} using card ending with {{debitcard_no}}.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_WITHDRAWAL_SUCCESS_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Successfull refund or online credit
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}by {{merchant_name}} has been refunded to your card ending with {{debitcard_no}}.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       REFUND_ONLINE_CREDIT_SUCCESS_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Refund for Transaction
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} was cancelled and the amount has been credited back to your card ending with {{debitcard_no}}.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_REFUND_SUCCESS_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM - Refund for withdrawal
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cash withdrawal of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} was cancelled and the amount has been credited back to your card {{debitcard_no}}.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_WITHDRAWAL_REFUND_SUCCESS_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Decline Insufficient Funds
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} with your card ending with {{debitcard_no}} was declined due to insufficient funds.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_INSUFFICIENT_FUNDS_DECLINE_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Decline Insufficient Funds
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Payment was declined
       </strong>
       <br/>
       Click to top up your account
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       + deeplink
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        wio-retail://app/dashboard/add-money
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_INSUFFICIENT_FUNDS_DECLINE_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Decline Insufficient Funds (CREDIT MONEY)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment of {{original_currency}} {{original_amount}} {{#if billing_currency}}({{billing_currency}} {{billing_amount}}) {{/if}}at {{merchant_name}} using your Wio Personal card {{debitcard_no}} was declined due to insufficient Credit money.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_TRANSACTION_INSUFFICIENT_FUNDS_DECLINE_CREDITMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Decline Insufficient Funds (CREDIT MONEY)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Payment was declined
       </strong>
       <br/>
       Click 'Pay credit' to top up your Credit account
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       + deeplink
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        wio-retail://app/lending/credit-dashboard
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_TRANSACTION_INSUFFICIENT_FUNDS_DECLINE_CREDITMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM - Decline Insufficient Funds
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cash withdrawal of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} with your card ending with {{debitcard_no}} was declined due to insufficient funds.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_INSUFFICIENT_FUNDS_DECLINE_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card transaction - Generic decline for purchase
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} with your card ending with {{debitcard_no}} was declined.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_GENERIC_PURCHASE_DECLINE_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM - Generic decline
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cash withdrawal of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} with your card ending with {{debitcard_no}} was declined.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_GENERIC_DECLINE_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Expired auth hold
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Purchase of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} from {{auth_date}} was cancelled and the amount has been credited back to your card {{debitcard_no}}.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_EXPIRED_HOLD_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM - Expired auth hold
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cash withdrawal of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} from {{auth_date}} was cancelled and the amount has been credited back to your card {{debitcard_no}}.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_EXPIRED_HOLD_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Account successful verification message
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Verification of your card ending with {{debitcard_no}} by {{merchant_name}} was successful.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ACCOUNT_VERIFICATION_SUCCESS_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Account failed verification message
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Verification of your card ending with {{debitcard_no}} by {{merchant_name}} failed.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ACCOUNT_VERIFICATION_FAILED_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card transaction - Settlement without authorisation (offline POS)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment of {{original_amount}} {{original_currency}} with card ending {{debitcard_no}} at {{merchant_name}} on {{auth_date}} was charged.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_SETTLEMENT_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Decline Incorrect PIN
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} with your card ending with {{debitcard_no}} was declined due to incorrect PIN.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_INCORRECT_PIN_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Decline Incorrect PIN
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Payment was declined
       </strong>
       <br/>
       Click to see the PIN of your Wio card {{debitcard_no}}
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       + deeplink
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        wio-retail://app/spend/settings?card-id=1337AB...
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_INCORRECT_PIN_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM - Decline Incorrect PIN
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cash withdrawal of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} with your debit card ending with {{debitcard_no}} was declined due to incorrect PIN.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_WITHDRAWAL_INCORRECT_PIN_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM - Decline Incorrect PIN
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Cash withdrawal was declined
       </strong>
       <br/>
       Click to see the PIN of your Wio card {{debitcard_no}}
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       +deeplink
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        wio-retail://app/spend/settings?card-id=1337AB...
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_WITHDRAWAL_INCORRECT_PIN_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Decline due to set card limit
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} with your card ending with {{debitcard_no}} was declined due to set card limit.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_DECLINE_CARD_LIMIT_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Transaction - Decline due to set card limit
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Payment was declined
       </strong>
       <br/>
       Click to review or reset the spending limit for your Wio card {{debitcard_no}}
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       + deeplink
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        wio-retail://app/spend/settings?card-id=1337AB...
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_DECLINE_CARD_LIMIT_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM - Decline due to set cash limit
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cash withdrawal of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} with your card ending with {{debitcard_no}} was declined due to set cash limit.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_WITHDRAWAL_DECLINE_CASH_LIMIT_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM - Decline due to set cash limit
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Cash withdrawal was declined
       </strong>
       <br/>
       Daily cash withdrawal limit has been exceeded. You will be able to withdraw up to 20,000 AED tomorrow.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_WITHDRAWAL_DECLINE_CASH_LIMIT_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card transaction  - Declined due to Card is blocked
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} with your card ending with {{debitcard_no}} was declined as the card is blocked.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_DECLINE_CARD_BLOCKED_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card transaction  - Declined due to Card is blocked
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Payment was declined
       </strong>
       <br/>
       Click to unfreeze your Wio card {{debitcard_no}}
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       + deeplink
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        wio-retail://app/spend?card-id=1337AB...
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_DECLINE_CARD_BLOCKED_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM  - Withdrawal declined due to Card is blocked
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cash withdrawal of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} with your card ending with {{debitcard_no}} was declined as the card is blocked.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_WITHDRAWAL_DECLINE_CARD_BLOCKED_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM  - Withdrawal declined due to Card is blocked
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Cash withdrawal was declined
       </strong>
       <br/>
       Click to unfreeze your Wio card {{debitcard_no}}
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       + deeplink
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        wio-retail://app/spend?card-id=1337AB...
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_WITHDRAWAL_DECLINE_CARD_BLOCKED_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM  - Withdrawal declined due to Cash withdrawal disabled by customer
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Cash withdrawal was declined
       </strong>
       <br/>
       Click to enable Cash withdrawal for your Wio card {{debitcard_no}}
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       +deeplink
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        wio-retail://app/spend/settings?card-id=1337AB...
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ATM_WITHDRAWAL_DECLINE_WITHDRAWAL_DISABLED_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Ecom transaction declined due to Ecom transactions disabled by customer
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Payment was declined
       </strong>
       <br/>
       Click to enable Online transactions for your Wio card {{debitcard_no}}
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       +deeplink
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        wio-retail://app/spend/settings?card-id=1337AB...
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_DECLINE_ECOM_DISABLED_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Ecom transaction declined due to wrong CVC
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Payment was declined
       </strong>
       <br/>
       Click to see correct Details of your Wio card {{debitcard_no}}
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       + deeplink
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        wio-retail://app/spend?card-id=1337AB...
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_DECLINE_WRONG_CVC_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Ecom transaction declined due to wrong expiry date
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ⚠️
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Payment was declined
       </strong>
       <br/>
       Click to see correct Details of your Wio card {{debitcard_no}}
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       + deeplink
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        wio-retail://app/spend?card-id=1337AB...
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_DECLINE_WRONG_EXPIRY_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
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
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Notifications for Retail Card Lifecycle Management
</h1>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="237,111,275,480" data-ghq-table-header="true">
   <colgroup>
    <col style="width:237px"/>
    <col style="width:111px"/>
    <col style="width:275px"/>
    <col style="width:480px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Notification channel
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Event Name
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Notification Message (With placeholder)
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Physical card order: Send notification once Plastic ordered
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        INITIATE_PHYSICAL_CARD_REQUEST_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We have started to work on your Physical Wio Card ending with {{debitcard_no}}. Once Plastic is ready for delivery we will notify you.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Physical card on delivery: Send notification once card collected by Aramex courier
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        PHYSICAL_CARD_PICKED_BY_COURIER_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Great news! Your Physical Wio Card ending with {{debitcard_no}} is on delivery now. Courier will get in touch with you soon. Please keep your Emirates ID with you to receive card.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Activate your card: Send notification to user upon notification from Aramex, that card has been delivered.
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        PHYSICAL_CARD_DELIVERED_BY_COURIER_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your Wio Card ending with {{debitcard_no}} has been delivered and ready for activation.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card activation via Mobile App
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        PHYSICAL_CARD_ACTIVATED_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your Wio card ending with {{debitcard_no}} is successfully activated ✅
       <br/>
       If it wasn't you call us on 600 500 946.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card Activated (SMS): Card activation via Mobile App
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        PHYSICAL_CARD_ACTIVATED_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your Wio Card ending with {{debitcard_no}} has been successfully activated. If it wasn't you call us on 600 500 946.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card activation reminder: Card has been delivered to the customer, but not activated in 3 days
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        PHYSICAL_CARD_NOT_ACTIVATED_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Activate your Wio Card and start exploring benefits of using it. Visit Wio App to activate card ending with {{debitcard_no}}.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Virtual card created: Card has been successfully created in Pty
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        VIRTUAL_CARD_CREATED_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Virtual card{{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} has been successfully created. If it wasn't you, freeze this card in the App and contact us immediately.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Virtual card created: Card has been successfully created in Pty
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       PUSH
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        VIRTUAL_CARD_CREATED_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Virtual card has been created ✅
       <br/>
       New Virtual card{{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} has been created. If it wasn't you, click to freeze the card and contact us.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       + deeplink wio-retail://app/spend?card-id=1337AB...
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Virtual card created: Card has been successfully created in Pty
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Email
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        VIRTUAL_CARD_CREATED_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       New Virtual card created
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hi {{customer_name}},
       <br/>
       New Virtual card{{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} has been created.
       <br/>
       If you didn’t initiate this activity, kindly follow these steps:
       <br/>
       Freeze your card immediately on your Wio Personal app.
       <br/>
       Contact us to investigate this case.
       <br/>
       Team Wio
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Change card pin (SMS)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_PIN_UPDATED_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       New PIN for your Wio Card ending {{debitcard_no}} has been set successfully. If it wasn't you call us on on 600 500 946
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card will expire in 5 days
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_EXPIRE_SOON_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card expires in 5 days ⚠️
       <br/>
       Your Wio card {{#if virtualcard_fullname}}"{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} will expire in 5 days. Get a new card in just a few clicks to continue making purchases.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card will expire in 5 days
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       InApp Inbox
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_EXPIRE_SOON_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card {{#if virtualcard_fullname}}”{{virtualcard_fullname}} "{{/if}}expires in 5 days.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your Wio card {{debitcard_no}} will expire in 5 days. Get a new card in just a few clicks to continue making purchases.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card expired
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_EXPIRED_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card has expired ⚠️
       <br/>
       You are no longer able to spend with your card {{#if virtualcard_fullname}}"{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} because it has expired.
       <br/>
       Get a new card in a few clicks in Wio App
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card expired
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       InApp Inbox
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_EXPIRED_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card {{#if virtualcard_fullname}}”{{virtualcard_fullname}} "{{/if}}has expired
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You are no longer able to spend with your card {{debitcard_no}} because it has expired.
       <br/>
       Get a new card in a few clicks in Wio App
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card replacement
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_REPLACEMENT_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Wio Personal card replaced! ✅
       <br/>
       Your new card ending with {{debitcard_no}} is active and available in the App.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card replacement
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       InApp Inbox
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_REPLACEMENT_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card {{#if virtualcard_fullname}}”{{virtualcard_fullname}} "{{/if}}has been replaced
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your new card ending with {{debitcard_no}} is active and available in the App.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card blocked by support
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_BLOCKED_SUPPORT_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       We've blocked your Wio Card ending with {{debitcard_no}} for security purposes⚠️ Call us on 600 500 946 to get it unblocked.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card unblocked by support
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_UNBLOCKED_SUPPORT_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your Wio Card  ending with {{debitcard_no}} is unblocked and can be used for Purchases.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       OTP to activate card token
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_ACTIVATION_OTP_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You've requested to add a Wio card{{#if name}} "{{name}}"{{/if}} to {{wallet_name}}. Please use the One Time Password (OTP) {{token_activation_otp}} to complete the activation for the card ending with {{debitcard_no}}. Your OTP is valid for 30 minutes. Don’t share this code with anyone. If it wasn’t you, freeze this card in the App and contact us immediately at 600 500 946.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Token activation reminder: Notification from Paymentology received in 24 hours of card has beed added to Wallet ()
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_TOKEN_ACTIVATION_REMINDER_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your Wio Card ending with {{debitcard_no}} is waiting for activation in {{wallet_name}}. Check Apple Wallet App to request One Time Password for activation.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card added to Wallet: TRN from Paymentology received at the end of digitization
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_ADDED_WALLET_SUCCESS_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your Wio Personal card ending with {{debitcard_no}} has been added to {{wallet_name}}. If it wasn’t you, freeze this card in the App and contact us immediately at 600 500 946.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card added to Wallet: TRN from Paymentology received at the end of digitization
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_ADDED_WALLET_SUCCESS_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card added to{{wallet_name}}.
       <br/>
       Your Wio Personal card ending with {{debitcard_no}} has been added to {{wallet_name}}. If it wasn’t you, freeze this card in the App and contact us immediately at 600 500 946.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card added to Wallet: TRN from Paymentology received at the end of digitization
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Email
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_ADDED_WALLET_SUCCESS_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your Card has been added to {{wallet_name}}
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hi {{customer_name}},
       <br/>
       Your Wio Personal card ending with {{debitcard_no}} has been added to {{wallet_name}}. If you didn’t initiate this activity, kindly follow these steps:
       <br/>
       Freeze your card immediately on your Wio Personal app.
       <br/>
       Contact us on 600 500 946 to remove card from the device.
       <br/>
       Team Wio
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Card blocked due to PIN/CVV retries: Customer changes automation to Auto Credit
       <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
        (Cashback to CurrAcc)
       </em>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_BLOCKED_INCORRECT_C_PIN_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your Wio Card ending with {{debitcard_no}} is blocked due to multiple incorrect PIN attempts. ⚠️ Tap to reset your PIN and unblock your card.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback set to be received on CurrAcc
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        SET_CASHBACK_TO_CURRENT_ACCOUNT_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback will be credited!🎉
       <br/>
       First day of the month cashback will be credited to your account
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback set to be received on Saving Space: Customer changes automation to Auto Save
       <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
        (Cashback to Saving Space)
       </em>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        SET_CASHBACK_TO_SAVING_SPACE_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback will be saved! 🎉
       <br/>
       First day of the month cashback will be credited to selected Saving Space.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback set to be invested in Stocks: Customer changes automation to Auto Invest
       <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
        (Cashback to purchase Stocks)
       </em>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        SET_CASHBACK_TO_INVEST_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback will be invested! 🎉
       <br/>
       First day of the month we will buy stocks you’ve selected for the cashback amount.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback credited to CurrAcc
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CREDITED_CASHBACK_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your {{Month}} cashback is here! 🎉
       <br/>
       Get ready to smile! We’ve credited {{Currency}} {{Amount}} cashback to your account.
       <br/>
       <br/>
       ✈️ Open Etihad Guest Fixed Saving Space to stay miles ahead on your savings!
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback credited to CurrAcc
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       InApp Inbox
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CREDITED_CASHBACK_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your {{Month}} cashback is here! 🎉
       <br/>
       Get ready to smile! We’ve credited {{Currency}} {{Amount}} cashback to your account.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback credited to CurrAcc
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CREDITED_CASHBACK_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You’ve earned {{Currency}} {{Amount}} cashback for {{Month}}. It is now credited to your account.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback credited to Saving Space
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        SAVED_CASHBACK_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your {{Month}} cashback is here! 🎉
       <br/>
       Get ready to smile! We’ve credited {{Currency}} {{Amount}} cashback to your saving space "{{ss_name}}"
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       ✈️ Open Etihad Guest Fixed Saving Space to stay miles ahead on your savings!
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback credited to Saving Space
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       InApp Inbox
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        SAVED_CASHBACK_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your {{Month}} cashback is here! 🎉
       <br/>
       Get ready to smile! We’ve credited {{Currency}} {{Amount}} cashback to your saving space "{{ss_name}}"
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback credited to Saving Space
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        SAVED_CASHBACK_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You’ve earned {{Currency}} {{Amount}} cashback for {{Month}}. It is now credited to your saving space "{{ss_name}}"
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback Invested in Stocks
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        INVESTED_CASHBACK_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your {{Month}} cashback is here! 🎉
       <br/>
       We’ve credited {{Currency}} {{Amount}} cashback to your USD account. Stocks you've selected will be purchased once market is open!
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback Invested in Stocks
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       InApp Inbox
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        INVESTED_CASHBACK_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your {{Month}} cashback is here! 🎉
       <br/>
       We’ve credited {{Currency}} {{Amount}} cashback to your USD account. Stocks you've selected will be purchased once market is open!
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Cashback Invested in Stocks
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        INVESTED_CASHBACK_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You’ve earned {{Currency}} {{Amount}} cashback for {{Month}}. Stocks you've selected will be purchased once market is open!
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Interest on Saving Space credited
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CREDITED_INTEREST_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your interest for {{month}}
       <br/>
       You’ve earned {{currency}} {{amount}} as interest on your saving space "{{ss_name}}"
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Interest on Saving Space credited
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       InApp Inbox
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CREDITED_INTEREST_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your interest for {{month}} is here! 🎉
       <br/>
       You’ve earned {{currency}} {{amount}} as interest on your saving space "{{ss_name}}"
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Interest on Saving Space credited
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CREDITED_INTEREST_SMS_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You’ve earned {{currency}} {{amount}} as interest on your saving space "{{ss_name}}"
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Switch card spend from Own funds to Credit money: Customer change routing for his card from Current account to Credit account
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        SWITCH_SPENDING_MODE_TO_CREDIT_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Spending mode change
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your Wio Personal card{{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} will use Credit money for purchases
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Switch card spend from Credit money to Own funds: Customer change routing for his card from Credit account to Current account
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        SWITCH_SPENDING_MODE_TO_OWN_FUNDS_MYMONEY
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Spending mode change
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Your Wio Personal card{{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} will use Own funds for purchases
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Shared card notifications
</h1>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="352,114,217.5,480" data-ghq-table-header="true">
   <colgroup>
    <col style="width:352px"/>
    <col style="width:114px"/>
    <col style="width:217.5px"/>
    <col style="width:480px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Notification channel
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event Name
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Notification Message (With placeholder)
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       OTP to confirm Trusted person’s mobile number: Account owner confirms mobile number of Trusted person in the App
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SHARED_CARD_OTP_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Greetings from Wio Bank! {{customer_name}} has requested to share a Wio Personal card with you. To complete card creation, please send the One Time Password (OTP) {{shared_card_otp}} to {{customer_name}}. This OTP is valid for 30 minutes.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Shared card created (for Account Owner): Shared card has been created / mobile number for existing shared card has been updated
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SHARED_CARD_CREATED_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       {{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} card is ready for sharing ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Share card credentials in a secure way, so {{trusted_person_name}} can start using the card!
       <br/>
       Once a payment is made, both you and {{trusted_person_name}} will receive an SMS notification.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Shared card created (for Account Owner): Shared card has been created / mobile number for existing shared card has been updated
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Email
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SHARED_CARD_CREATED_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hi {{customer_name}},
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You've created a card{{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} for sharing with {{trusted_person_name}}.
       <br/>
       Please share card credentials in a secure way, so {{trusted_person_name}} can start using the card!
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Here are some important reminders:
       <br/>
       • Your account will be debited once  {{trusted_person_name}} pays with the card
       <br/>
       • You will be liable for all transactions made with the shared card {{debitcard_no}}
       <br/>
       • You are not sharing the card with minors under 13 years old
       <br/>
       • Once a payment is made, both you and {{trusted_person_name}} will receive an SMS notification
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       If you wish to stop sharing the card with {{trusted_person_name}}, please terminate the card in Wio App. Once sharing is stopped, card is getting terminated, and no more transactions will be approved with this card.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Wio team
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Shared card created (for Trusted Person): Shared card has been created for Trusted person / mobile number for existing shared card has been updated
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SHARED_CARD_CREATED_MYMONEY_SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hello from Wio Bank! {{customer_name}} has created a shared card{{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} for you. Ask {{customer_name}} to send you the card credentials, so you can start using the card!
       <br/>
       Once you make a payment, an SMS notification will be sent to your mobile number at +971{{trusted_person_mobile_number}}.
       <br/>
       Enjoy using Wio products!
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Shared card terminated (for Account Owner): Send notification once Shared card has been terminated
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SHARED_CARD_TERMINATED_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       {{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} card is terminated ✅
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       {{trusted_person_name}} will no longer be able to spend with the card {{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} and receive SMS notifications.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Shared card terminated (for Account Owner): Send notification once Shared card has been terminated
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Email
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SHARED_CARD_TERMINATED_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hi {{customer_name}},
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You've stopped sharing your card{{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} with {{trusted_person_name}}.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Here are some important things to know:
       <br/>
       • Any new transaction with this card will be declined
       <br/>
       • {{trusted_person_name}} is no longer able to spend with this card and receive SMS notification.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       If you wish to resume sharing a card with {{trusted_person_name}}, please create a new card for sharing in Wio App.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Wio team
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Shared card terminated (for Trusted Person): Send notification once Shared card has been terminated
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SHARED_CARD_TERMINATED_MYMONEY_SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Hello from Wio Bank! {{customer_name}} has terminated a shared card{{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}}.
      </p>
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       You are no longer able to spend with this card and receive SMS notifications.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Shared card expires in 5 days (for Trusted Person): Send notification 5 days before Shared card expiry
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_EXPIRE_SOON_MYMONEY_SMS_TRUSTED_PERSON
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Shared card {{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} will expire in 5 days. Ask {{customer_name}} to issue a new card for you.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Shared card expired (for Trusted Person): Send notification once Shared card has expired
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <code class="ghq-card-content__code-snippet" data-ghq-card-content-type="CODE_SNIPPET">
        CARD_EXPIRED_MYMONEY_SMS_TRUSTED_PERSON
       </code>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Shared card {{#if virtualcard_fullname}} "{{virtualcard_fullname}}"{{/if}} {{debitcard_no}} has expired. You are no longer able to spend with this card and receive SMS notifications. Ask {{customer_name}} to issue a new card for you.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Bank card level limit reached: Decline due to Bank card level limit
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       CARD_TRANSACTION_DECLINE_SHARED_CARD_BANK_LIMIT_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Payment of {{original_amount}} {{original_currency}} {{#if billing_currency}}({{billing_amount}} {{billing_currency}}) {{/if}}at {{merchant_name}} with your card ending with {{debitcard_no}} was declined due to bank's card limit.
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Notifications for Payroll
</h1>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="365,109,219,630" data-ghq-table-header="true">
   <colgroup>
    <col style="width:365px"/>
    <col style="width:109px"/>
    <col style="width:219px"/>
    <col style="width:630px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Notification channel
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Event Name
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Notification Message (With placeholder)
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Salary credit:
       </strong>
       Send notification once amount has been posted to customer account.
       <br/>
       Notification should be sent during working hours
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Push
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SALARY_CREDIT_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       🎉 Your salary is here
       <br/>
       You've received {{currency}} {{amount}} in your account.
       <br/>
       Let your money work for you! Earn interest by depositing into the Saving Space.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Salary credit:
       </strong>
       Send notification once amount has been posted to customer account.
       <br/>
       Notification should be sent during working hours
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SMS
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       SALARY_CREDIT_MYMONEY
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Salary credit of {{currency}} {{amount}} has been credited to your account.
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
