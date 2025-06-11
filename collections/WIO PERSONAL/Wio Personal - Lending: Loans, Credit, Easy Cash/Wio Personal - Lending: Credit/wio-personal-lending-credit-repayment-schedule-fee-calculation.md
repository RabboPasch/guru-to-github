# [🧮Wio Personal - Lending: Credit - Repayment Schedule & Fee Calculation      ](https://app.getguru.com/card/T4XpXjXc/Wio-Personal-Lending-Credit-Repayment-Schedule-Fee-Calculation-)

<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING">
 Topic Overview
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 The objective of this page is to illustrate what is the repayment schedule and how fees are calculated for the
 <a class="ghq-card-content__link" data-ghq-card-content-type="LINK" href="https://wiobank.atlassian.net/wiki/spaces/LendingDoc/pages/842530817/Revolving+credit+line+with+rollover+fee" rel="noopener noreferrer" target="_blank">
  personal revolving credit line
 </a>
 .
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h2 class="ghq-card-content__medium-heading" data-ghq-card-content-type="MEDIUM_HEADING">
 Repayment Schedule
</h2>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 Monthly repayment is required from customers. Customers can select the repayment day (also known as due date usually) through the Wio Personal app, after the credit limit is approved.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 Customer can repay anytime manually through the Wio Personal app, or set up auto pay which will use the fund in customers’ current account to repay on repayment day automatically.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 Customer can choose to pay full or part of the due amount. But 5% of the due amount is required as the minimum repayment.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 Unlike other traditional credit card, there is no separate statement date. The statement will be provided at the same day of due date.
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h2 class="ghq-card-content__medium-heading" data-ghq-card-content-type="MEDIUM_HEADING">
 Fee Calculation
</h2>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 There are two types of fees: roll over fee and late payment fee.
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  Roll over fee is charged monthly. It is calculated based on the outstanding principal
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  </strong>
  on the due date, after the auto pay. The calculation method is fee rate multiple outstanding. If the outstanding is fully repaid anytime from last due date (include the last due date) to this due date (only auto pay), the roll over fee is waived.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM">
  Late payment fee is a flat fee of AED 199 (incl. VAT).
 </li>
</ul>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  In general, the sequence of activities from the repayment day T is:
 </strong>
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Get the outstanding principal amount
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   K
  </strong>
  as of
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   the beginning of
  </strong>
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   T
  </strong>
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
    +1
   </del>
  </strong>
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Get the auto pay amount
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   A
  </strong>
  by multiplying
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   K
  </strong>
  with customer selected auto pay percentage
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   a% (A = K × a%)
  </strong>
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Get the overdue amount from previous cycle
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   O*
  </strong>
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Debit amount
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   A + O*
  </strong>
  from customers' current account. If there is not enough balance in customers current account, debit all the balance amount
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   A
  </strong>
  *. (
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   A
  </strong>
  is always greater than
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   A
  </strong>
  *)
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Credit amount
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   A + O*
  </strong>
  or
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   A
  </strong>
  * to the credit account.
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Get the latest outstanding principal amount
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   L = K - A or L = K + O* - A* which ever is greater
  </strong>
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Calculate the roll over fee amount by multiplying
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   L
  </strong>
  with the fee rate
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   f%
  </strong>
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   (F = L × f%)
  </strong>
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Determine if the roll over fee
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   F
  </strong>
  above can be waived:
 </li>
 <ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
  <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
   If the outstanding is fully repaid anytime from
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    T of previous month (including T)
   </strong>
   to
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    the moment of step 5 on T
   </strong>
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
     +1
    </del>
   </strong>
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    of current month
   </strong>
   , roll over fee
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    F
   </strong>
   will be waived.
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    F
   </strong>
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    → 0
   </strong>
  </li>
  <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
   Otherwise roll over fee
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    F
   </strong>
   remains the same
  </li>
 </ol>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Debit amount
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   F
  </strong>
  from customers' current account. If there is not enough balance in customers current account, debit all the balance amount
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   F
  </strong>
  *. (
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   F
  </strong>
  is always greater than
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   F
  </strong>
  *)
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Get the customers' current cycle’s total normal repayment
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   R
  </strong>
  from
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   T
  </strong>
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
    +1
   </del>
  </strong>
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   of previous month (including T
  </strong>
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
    +1
   </del>
  </strong>
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   )
  </strong>
  to
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   the moment of step 5 on T
  </strong>
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
    +1
   </del>
  </strong>
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   of current month
  </strong>
  ,
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <u class="ghq-card-content__underline" data-ghq-card-content-type="UNDERLINE" style="text-decoration:underline">
    <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
     <u class="ghq-card-content__underline" data-ghq-card-content-type="UNDERLINE" style="text-decoration:underline">
      <u class="ghq-card-content__underline" data-ghq-card-content-type="UNDERLINE" style="text-decoration:underline">
       excluding repayment to cover outstanding carried from previous cycle, such as auto pay, repayment to overdue outstanding of previous cycle. autopay and fees of previous cycle.
      </u>
     </u>
    </del>
   </u>
  </strong>
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Get minimum required repayment amount
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   M
  </strong>
  by multiplying
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   K
  </strong>
  with
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   5% (M = K × 5%)
  </strong>
  .
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Depending on the repayment behavior, there will be different scenarios:
 </li>
 <ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
  <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
   If STEP 9
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    R ≥ M &amp;
   </strong>
   STEP 8
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    F is fully paid,
   </strong>
   account is normal and moves to the next cycle.
  </li>
  <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
   If STEP 9
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    R ≥ M &amp;
   </strong>
   STEP 8
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    F is not fully paid,
   </strong>
   account will be considered as DELINQUENT. Late payment fee may apply depending on following behaviors:
  </li>
  <ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
   <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
    If customers repay amount
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     D
    </strong>
    before
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     T+5 of current month
    </strong>
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     (including T+5)
    </strong>
    to cover full roll over fee
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     F (F*+D ≥ F)
    </strong>
    , account will be back to normal and move to next cycle.
   </li>
   <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
    Otherwise late payment fee
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     P
    </strong>
    will
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    </strong>
    apply. Overdue roll over fee and penalty will be carried to the next cycle. The carried total overdue amount
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     O = P + F - F* -D(if any)
    </strong>
   </li>
  </ol>
  <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
   If STEP 9
   <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    R &lt; M
   </strong>
   , account will be considered as DELINQUENT. Late payment fee and account locking may apply depending on following behaviors:
  </li>
  <ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
   <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
    If customers repay amount
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     D
    </strong>
    before
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     T+5 of current month
    </strong>
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     (including T+5)
    </strong>
    to cover minimum repayment requirement
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     M
    </strong>
    and full roll over fee
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     F (R+D ≥ M+F)
    </strong>
    , account will be back to normal and move to next cycle.
   </li>
   <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
    Otherwise late payment fee
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     P
    </strong>
    will
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
    </strong>
    apply and account will be locked. Overdue roll over fee and penalty will be carried to the next cycle. The carried total overdue amount
    <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
     O = P + F - F* -D(if any)
    </strong>
   </li>
  </ol>
 </ol>
</ol>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Repayment hierarchy is late payment fee &gt; roll over fee &gt; principle.
 </strong>
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h2 class="ghq-card-content__medium-heading" data-ghq-card-content-type="MEDIUM_HEADING">
 Scenarios
</h2>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 Below are different scenarios which will illustrate the fee calculation in details. Assume the customer has credit limit of AED 25K and
 <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
  26
 </del>
 27th is the repayment day. Actual auto pay will happen at the
 <del class="ghq-card-content__strikethrough" data-ghq-card-content-type="STRIKETHROUGH" style="text-decoration:line-through">
  beginning of
 </del>
 6pm of 27th. 3.25% is the monthly roll over fee rate.
</p>
<h3 class="ghq-card-content__small-heading" data-ghq-card-content-type="SMALL_HEADING">
</h3>
<h3 class="ghq-card-content__small-heading" data-ghq-card-content-type="SMALL_HEADING">
 Example 1 - 100% auto pay
</h3>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-is-full-width="false" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="100,117,102,122,123,117,109,114,150" data-ghq-table-header="true">
   <colgroup>
    <col style="width:100px"/>
    <col style="width:117px"/>
    <col style="width:102px"/>
    <col style="width:122px"/>
    <col style="width:123px"/>
    <col style="width:117px"/>
    <col style="width:109px"/>
    <col style="width:114px"/>
    <col style="width:150px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Date
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding prior txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Use Credit
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Repay
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding post txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied auto pay principle
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied rollover fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied late payment fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Comments
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       First transaction
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       15-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       500
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       500
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       500
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       500 (auto pay)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       500
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Assume today is 20 September
 </strong>
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Create loan account with 20 statement date and 100% payment %
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1000 on 1 September
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay 500 on 3rd September
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay (autopay) 500 today 20 September
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Apply Fee should be 0
 </li>
</ol>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h3 class="ghq-card-content__small-heading" data-ghq-card-content-type="SMALL_HEADING">
 Example 2 - 5% auto pay
</h3>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="100,119,104,136,120,121,118,118,178" data-ghq-table-header="true">
   <colgroup>
    <col style="width:100px"/>
    <col style="width:119px"/>
    <col style="width:104px"/>
    <col style="width:136px"/>
    <col style="width:120px"/>
    <col style="width:121px"/>
    <col style="width:118px"/>
    <col style="width:118px"/>
    <col style="width:178px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Date
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding prior txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Use Credit
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Repay
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding post txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied auto pay principle
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied rollover fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied late payment fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Comments
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       First transaction
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50 (auto pay)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee waived for this cycle
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,050
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       161.75 (auto pay)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       100
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       61.75
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee applies after auto pay
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Assume today is 20 September:
 </strong>
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Create loan account with 20 statement date and 5% payment %
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1000 on 1 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay (Autopay) 50 on 20th August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1050 on 25 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay (Autopay) 100 on 20 September
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Apply fee should be 61.75
 </li>
</ol>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h3 class="ghq-card-content__small-heading" data-ghq-card-content-type="SMALL_HEADING">
 Example 3 - 5% auto pay but 100% manual repayment before due date
</h3>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="100,123,108,142,136,137,110,119,176" data-ghq-table-header="true">
   <colgroup>
    <col style="width:100px"/>
    <col style="width:123px"/>
    <col style="width:108px"/>
    <col style="width:142px"/>
    <col style="width:136px"/>
    <col style="width:137px"/>
    <col style="width:110px"/>
    <col style="width:119px"/>
    <col style="width:176px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Date
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding prior txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Use Credit
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Repay
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding post txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied auto pay principle
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied roll over fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied late payment fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Comments
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       First transaction
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50 (auto pay)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee waived for this cycle
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,050
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       161.75 (auto pay)
       <br/>
       (principle 100, fee 61.75)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       100
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       61.75
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee applies after auto pay
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Full repayment manually
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       15-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50 (auto pay)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee waived due to the full repayment on 1-Oct
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Assume today is 20 September
 </strong>
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Create loan account with 20 statement date and 5% payment %
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1000 on 1 July
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay (Autopay) 50 on 20th July
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1050 on 25 July
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay(autopay) 100 on 20 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Apply fee 61.65 on 20 August (repayment shud happen via MPO of 61.65)
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay 1900 on 25 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1000 on 28 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay Autopay 50 20 September
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Run fee calculation should be 0 (because full payment on 25 august 1900 amount)
 </li>
</ol>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h3 class="ghq-card-content__small-heading" data-ghq-card-content-type="SMALL_HEADING">
 Example 4 - Minimum repayment (5%) not made on the due date and paid within the tolerance period (5 business days)
</h3>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="100,121,106,165,135,131,119,115,183" data-ghq-table-header="true">
   <colgroup>
    <col style="width:100px"/>
    <col style="width:121px"/>
    <col style="width:106px"/>
    <col style="width:165px"/>
    <col style="width:135px"/>
    <col style="width:131px"/>
    <col style="width:119px"/>
    <col style="width:115px"/>
    <col style="width:183px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Date
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding prior txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Use Credit
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Repay
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding post txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied auto pay principle
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied roll over fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied late payment fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Comments
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       First transaction
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50 (auto pay)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee waived for this cycle
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,050
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,065
       <br/>
       (principle 2,000, fee 65)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       100
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       65
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee applies after auto pay, minimum repayment not made
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,065
       <br/>
       (principle 2,000, fee 65)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       165 (manual pay) (principle 100, fee 65)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Minimum repayment made, fees paid first before principle
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       15-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       100
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       161.75 (auto pay)
       <br/>
       (principle 100, fee 61.75)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       100
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       61.75
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Assume today is 20 September
 </strong>
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Create loan account with 20 statement date and 5% payment %
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1000 on 1 July
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay (Autopay) 50 on 11th July
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1050 on 25 July
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Apply fee 65 on 20 August (Disable MPO as we want to not deduct amount) (no auto pay or fee pay happened here)
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay 165 on 25 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 100 on 28 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay Autopay 100 on 20 September
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Run fee calculation should be 61.75 (on 1900)
 </li>
</ol>
<h3 class="ghq-card-content__small-heading" data-ghq-card-content-type="SMALL_HEADING">
</h3>
<h3 class="ghq-card-content__small-heading" data-ghq-card-content-type="SMALL_HEADING">
 Example 5 - Minimum repayment (5%) not made on the due date and not made within the tolerance period (5 business days)
</h3>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="100,167,104,120,177,121,116,114,338.99999999999994" data-ghq-table-header="true">
   <colgroup>
    <col style="width:100px"/>
    <col style="width:167px"/>
    <col style="width:104px"/>
    <col style="width:120px"/>
    <col style="width:177px"/>
    <col style="width:121px"/>
    <col style="width:116px"/>
    <col style="width:114px"/>
    <col style="width:338.99999999999994px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Date
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding prior txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Use Credit
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Repay
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding post txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied auto pay principle
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied roll over fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied late payment fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Comments
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       First transaction
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50 (auto pay)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee waived for this cycle
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,050
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,065
       <br/>
       (principle 2,000, fee 65)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       100
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       65
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee applies after auto pay, minimum repayment not made
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,065 (principle 2,000, fee 65)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,264 (principle 2,000, fee 65, late payment fee 199)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       199
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Assume no holiday between 27-Sept and 2-Oct, 2-Oct is T+5 from 27-Sept. At the beginning of 2-Oct late payment fee will apply and account will be locked.
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,264 (principle 2,000, fee 65, late payment fee 199)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       64
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,265(principle 2,000, fee 130, late payment fee 135)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       100
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       65
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Principal does not change after auto pay, same roll over fee applies based on outstanding principal.
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Assume today is 20 September
 </strong>
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Create loan account with 15 (5 days before current date) statement date and 5% payment %
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1000 on 1 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay (Autopay) 50 on 15th August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1050 on 20 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Apply fee 65 on 15 September (Disable MPO as we want to not deduct amount) (no auto payment or fee settlement happened)
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Webhook should be listened and 199 fee applied on 21 September
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Evaluate principal balance and fee balance and how much mambu will autopay next month
 </li>
</ol>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h3 class="ghq-card-content__small-heading" data-ghq-card-content-type="SMALL_HEADING">
 Example 6 - Minimum repayment (5%) partially made on the due date and rest made within the tolerance period (5 business days)
</h3>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="150,217.5,150,217.5,217.5,150,150,150,217.5" data-ghq-table-header="true">
   <colgroup>
    <col style="width:150px"/>
    <col style="width:217.5px"/>
    <col style="width:150px"/>
    <col style="width:217.5px"/>
    <col style="width:217.5px"/>
    <col style="width:150px"/>
    <col style="width:150px"/>
    <col style="width:150px"/>
    <col style="width:217.5px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Date
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding pior txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Use Credit
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Repay
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding post txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied auto pay principle
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied roll over fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied late payment fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Comments
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       First transaction
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50 (auto pay)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee waived for this cycle
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,050
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,013.375
       <br/>
       (principle 1,950, fee 63.375)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       100
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       63.375
       <br/>
       (based on 1,950 = 2,000-50)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee applies after auto pay, minimum repayment not made
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,013.375
       <br/>
       (principle 1,950, fee 63.375)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       113.375 (manual pay) (principle 50, fee 63.375)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Minimum repayment made, fees paid first before principle
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       15-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       100
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       161.75 (auto pay)
       <br/>
       (principle 100, fee 61.75)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       100
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       61.75
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Case-1: checking no late fee as 5% repayment done
 </strong>
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Assume today is 20 September
 </strong>
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Create loan account with 15 statement date and 5% payment %
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1000 on 1 Sep
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Apply fee 63.5 on 15 Sep (Disable MPO as we want to not deduct amount)
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay 113.5 (63.5 fee + 50 =&gt; 5% of 1000 ) on 18 Sep (min repayment happening)
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  check webhook on 21 September no late fee
 </li>
</ol>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Case-2: Assume today is 20 September
 </strong>
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Create loan account with 20 statement date and 5% payment %
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1000 on 1 July
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay (Autopay) 50 on 20th July
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1050 on 25 July
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay 50 partial autopay on 20 August 11
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Apply fee 63.5 on 20 August (Disable MPO as we want to not deduct amount)
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay 113.5 (63.5 fee + 50 pending principal) on 23 August (min repayment happening)
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 100 on 28 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay Autopay 100 11 September
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Run fee calculation should be 61.75
 </li>
</ol>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h3 class="ghq-card-content__small-heading" data-ghq-card-content-type="SMALL_HEADING">
 Example 7 - Fees carried from previous month
</h3>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="100,153,107,121,190,125,111,113,380" data-ghq-table-header="true">
   <colgroup>
    <col style="width:100px"/>
    <col style="width:153px"/>
    <col style="width:107px"/>
    <col style="width:121px"/>
    <col style="width:190px"/>
    <col style="width:125px"/>
    <col style="width:111px"/>
    <col style="width:113px"/>
    <col style="width:380px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Date
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding prior txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Use Credit
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Repay
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Outstanding post txn
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied auto pay principle
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied roll over fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Applied late payment fee
       </strong>
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        Comments
       </strong>
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       First transaction
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Aug
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50 (auto pay)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       50
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee waived for this cycle
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       950
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,050
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       26-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2,000
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       100
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       27-Sept
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,900
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,961.75
       <br/>
       (principle 1,900, fee 61.75)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       95
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       61.75
       <br/>
       (based on 1,900)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       0
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Roll over fee applies after auto pay, minimum repayment 95 not made
      </p>
     </td>
    </tr>
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2-Oct
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       1,961.75
       <br/>
       (principle 1,900, fee 61.75)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       2160.75 (principle 1,900, fee 61.75, late payment fee 199)
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       199
      </p>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       Assume no holiday between 27-Sept and 2-Oct, 2-Oct is T+5 from 27-Sept. At the beginning of 2-Oct late payment fee will apply and but account will not be locked. Total fee of 216.75 (roll over fee 61.75 + late payment fee 199) will be carried to next cycle.
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Assume today is 20 September
 </strong>
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Create loan account with 15 (5 days before current date) statement date and 5% payment %
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1000 on 1 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay (Autopay) 50 on 15th August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Disburse 1050 on 20 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Repay 100 on 25 August
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Apply fee 61.75 on 15 September (Disable MPO as we want to not deduct amount) (no auto payment or fee settlement happened)
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Webhook should be listened and 199 fee applied on 21 September
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM">
  Evaluate principal balance and fee balance and how much mambu will autopay next month
 </li>
</ol>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
</p>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph">
</p>
