# [Wio Personal - Transfers: DDA Through Wio Personal Application](https://app.getguru.com/card/c7x9GRbi/Wio-Personal-Transfers-DDA-Through-Wio-Personal-Application)

<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="TLRdjB5WJRZG">
</p>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="pqNfA3IBc5bZ">
 🕜Important Timelines
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="CvngZX2sHL7I">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  This article includes information that will be available in the next releases; here's how you can identify them in order to correctly assist the customers:
 </strong>
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="P5ZdhbPlR056">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  MVP:
 </strong>
 Allowed for all customers - Means they can initiate a DDR request and it will be accepted by Wio - as we have the backend systems.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="pRuD7TJRDF5c">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Phase 2:
 </strong>
 Mid June - Application flows will be updated.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="f1jq356XDPj1">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Phase 3:
 </strong>
 End of June - more enhancements (Enable debit from SS + DDA closure from the app).
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="rPPvJuhrfJCj">
 Topic Overview
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="7o2Fx1e79Aev">
 The article explains the functionality and features of the DDA through Wio Personal Application, which is designed to help users manage their Direct Debit Authorities (DDAs). It outlines how customers can receive notifications related to DDAs, view transaction statuses, set nicknames for their DDAs, and choose backup payment methods for smooth transaction processing.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="Qi7XSNx45wdB">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Key points include:
 </strong>
</p>
<ol class="ghq-card-content__numbered-list" data-ghq-card-content-type="NUMBERED_LIST" start="1">
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM" id="85KN81bMniVi">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Notification Process:
  </strong>
  Customers are alerted about DDA requests initiated by their sponsoring bank, and subsequent steps for verifying and confirming these requests are provided.
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM" id="TxlQ9dh3xphF">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Managing DDAs:
  </strong>
  The application allows users to log in, view active DDAs, and manage their details, such as assigning nicknames and checking transaction statuses.
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM" id="G2HlXP5FjDnA">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Backup Payment Methods:
  </strong>
  Users can enable payments from their savings accounts if there are insufficient funds in their current accounts to cover DDAs.
 </li>
 <li class="ghq-card-content__numbered-list-item" data-ghq-card-content-type="NUMBERED_LIST_ITEM" id="vZpN6zXTnnyz">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Account Closure Procedures:
  </strong>
  How customers can close their accounts with active DDAs, detailing successful and failure scenarios encountered during the closure process.
 </li>
</ol>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="vnc5VHV7sxT5">
 Overall, the article serves as a guide for users to efficiently manage their DDAs through the Wio Personal Application.
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="bvc3zh8K1Bia">
 (MVP) Wio Personal Application: First-Time Notification, Viewing and Managing DDAs
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="tdNFaRL3BZ6n">
 The Direct Debit Authority (DDA) is automatically initiated by the sponsoring bank or entity, rather than Wio Bank. Most of the process is handled by the sponsoring bank,  Wio Bank's will notify the customer once the request is completed, here's how:
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="DVFrzSN5p95P">
  Once the customer and their sponsoring bank establish the Direct Debit Request (DDR), a notification is dispatched to Wio Bank's Back Office (BO) internal systems.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="1nIM4DLtQETY">
  The BO team then verifies the eligibility of the Wio Personal customer by checking:
 </li>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="TRiHNt6RbPvi">
   Wio account is active.
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="V9RnpTXuqqbo">
   There are no internal bank policies that could result in the rejection of the request.
  </li>
 </ul>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="hFNCbK3WzYb9">
  Following this, a DDA notification and email are sent to the customer, providing them with the relevant details.
 </li>
</ul>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="N7lGO79tjucd">
</p>
<h2 class="ghq-card-content__medium-heading" data-ghq-card-content-type="MEDIUM_HEADING" id="2xVB9kxtPgqz">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
   (MVP) Low-Balance Management for DDR Requests
  </span>
 </strong>
</h2>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="WtMnpRJFEzAL">
  In case the customer has insufficient funds in both current and savings combined, a notification will be sent to the customer stating the account balance is not enough and to top up their account before the same day at 3 PM.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="pPNtdAGw1RDr">
  The notification will be sent out once Wio receives the DDA request from the sponsoring bank.
 </li>
</ul>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="FST7PimdJzvv">
</p>
<h2 class="ghq-card-content__medium-heading" data-ghq-card-content-type="MEDIUM_HEADING" id="VXAL34I79zgv">
 Customer Steps: Upon Receiving a DDA Request Notification
</h2>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="AJFMBJKzrbLu">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  When a customer receives a Direct Debit Authority (DDA) request notification, here’s how to proceed:
 </strong>
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="D7lPkpPXAN5b">
 1. Log in to the Wio Personal application, then click on the notification, or navigate to the product hub and select "Send."
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="ZYDB3ZDxZq59">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Notifications:
  </strong>
  Customers will receive both an SMS and an EMAIL containing the DDA details.
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="nhx5ftTj5sJT">
 2.
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Direct Debit Introduction:
 </strong>
 Customers will be introduced to the new Direct Debit tab via the Send page:
 <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
  Access and manage your active direct debit requests at any time.
 </em>
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="YfIxtxURzxNJ">
 3. Direct Debit → Select "See All."
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="hXN86JtZFR9k">
 <span class="ghq-card-content__image-container">
  <img alt="image.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image.png" style="width:3154px" width="3154"/>
 </span>
</p>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="soYVX8wY5Fs6">
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="JQjRxL7vKBvf">
 4. On the Direct Debits main page, customers can view all their active direct debits, including their status, reference numbers, and transaction details.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="CZDH3TPOHf33">
 5.
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Setting a Nickname:
 </strong>
 Customers can assign a nickname to their DDAs if desired. To do this, click on the direct debit details and then select "Edit."
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="YXrTHQlrTWWc">
 6. Enter the new name for your direct debit and confirm the changes by clicking "Update."
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="71FN2br3F83t">
 7.
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  A confirmation message will appear:
 </strong>
 The Direct Debit nickname has been changed successfully.
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="vEhx2ZG9iNrT">
 <span class="ghq-card-content__image-container">
  <img alt="image.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image.png" style="width:3136px" width="3136"/>
 </span>
</p>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="POhv8tRnfC3j">
</p>
<section class="ghq-card-content__callout" data-ghq-card-content-type="CALLOUT" data-ghq-color="blue" id="Nl1kfMWLhvUD" style="background-color: #00bcd62b;">
 <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="HDjlJDJj1ZOQ">
  Email Template:
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Direct debit authorization request received
  </strong>
 </p>
 <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="FpFNViv9nbTZ">
  Hi {{name}},
 </p>
 <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="vrFdLHHjdhPg">
  We’ve received a direct debit authorization request from {{bankName}} for AED {{amount}} for the period {{fromDate}} to {{toDate}}. We will process this request.
 </p>
 <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="4ajrpzWBCdcI">
   Originator Name {{originatorName}}
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="EzEpcBzXQcAT">
   Primary Sponsoring Bank {{bankName}}
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="xriTxJ9BYxt8">
   DDA Purpose {{purpose}}
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="7StXEmH4P3PD">
   Issued for {{purpose}}
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="uPZkpG5PdTHy">
   Starts on {{fromDate}}
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="mZ0977dbRT53">
   Ends on {{toDate}}
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="iJ7eQ6n7r7Sw">
   Amount {{amount}}
  </li>
  <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="7FTM1alp4Re5">
   Payment frequency {{frequency}}
  </li>
 </ul>
 <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="GObJtGldhKh7">
  If you don’t recognize this request, call or WhatsApp our Wio Care team at 600 500 946.
 </p>
 <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="dnPtVn8pV9RX">
  Team Wio
 </p>
</section>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="zsh31HLXTIIc">
 (Phase 2) DDA Transaction Details
</h1>
<div class="ghq-card-content__table-responsive-wrapper">
 <div class="ghq-card-content__table-scroller">
  <table class="ghq-card-content__table" data-ghq-card-content-is-full-width="true" data-ghq-card-content-type="TABLE" data-ghq-table-column-widths="462,493" data-ghq-table-header="false">
   <colgroup>
    <col style="width:462px"/>
    <col style="width:493px"/>
   </colgroup>
   <tbody class="ghq-card-content__table-body">
    <tr class="ghq-card-content__table-row" data-ghq-card-content-type="TABLE_ROW" id="TpnpRxj1DJp5">
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph">
       <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
        <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
         Details inside DDA transaction details will include:
        </span>
       </strong>
      </p>
      <ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="qtbnl0g3tM7T">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         Reference number
        </strong>
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="XWhDNjJWhVi5">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         Submission date
        </strong>
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="jTdOXzdlBvAI">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         Status:
        </strong>
        Processing / Active / Completed / Canceled
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="U9vrHbPNzbx9">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         OIC:
        </strong>
        Stands for
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         Originator Identification Code
        </strong>
        . It is used to identify specific originators in the context of Direct Debit Authority (DDA) and Direct Debit Request (DDR) transactions.
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="HFUoLVJtzZbm">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         Originator Name:
        </strong>
        DDR initiator
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="V1J29vgFiJZs">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         Sponsoring Bank:
        </strong>
        The DDA Sponsoring bank requestor
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="umWH3ZdesQxx">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         Issued for
        </strong>
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="g7RBd93h9jJr">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         Start date:
        </strong>
        DD/MM/YYYY
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="pGS8quLBj1if">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         End date:
        </strong>
        DD/MM/YYYY
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="JX39VnJohDvB">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         Amount type:
        </strong>
        Fixed/Variable
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="SvWHqtrP6Wrc">
        <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
         Payment frequency:
        </strong>
        Weekly/Monthly/Yearly/Etc…
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="ZtnnBdHJ21dl">
        Minimum - Maximum Amount
       </li>
       <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="NzrHvxdRGZng">
        DDA image Details, if any
       </li>
      </ul>
     </td>
     <td class="ghq-card-content__table-cell" data-ghq-card-content-type="TABLE_CELL">
      <p class="ghq-card-content__paragraph align-center" data-ghq-card-content-type="paragraph" data-text-align="center">
       <span class="ghq-card-content__image-container">
        <img alt="image.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image.png" style="width:341px" width="341"/>
       </span>
      </p>
     </td>
    </tr>
   </tbody>
  </table>
 </div>
</div>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="DJaJZzCCZP1Y">
 (MVP) DDA Transaction Status
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="vwtlGuTN65rP">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  DDA Transaction Statuses will be available through the transaction details page as follows:
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="9Pc4PLd4Vv6o">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
    Next payment on DD/MM/YYY:
   </span>
  </strong>
  For the upcoming payments.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="7rZVr3ZzinFG">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#bab0bf">
    In progress:
   </span>
  </strong>
  Payments still being processed within TAT with DDA reference number.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="cVBbCFOBrZB9">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#66a030">
    Completed:
   </span>
  </strong>
  For completed payments with DDA reference number.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="ipjpoiraVSbT">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
    Rejected:
   </span>
  </strong>
  <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#f7412d">
  </span>
  For rejected payments with DDA reference number.
 </li>
</ul>
<p class="ghq-card-content__paragraph align-center" data-ghq-card-content-type="paragraph" data-text-align="center" id="UX6DL5NNeVHo">
 <span class="ghq-card-content__image-container">
  <img alt="image.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image.png" style="width:678px" width="678"/>
 </span>
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="yPJ551fjEj3f">
 (Phase 2) Backup Method: Pay your direct debit from Saving Spaces
</h1>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="lQADJbpUTS5X">
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="7DphpZzyJlkJ">
 <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
  <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
    <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
     <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
      <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
       Enable payments from Saving Spaces as your backup:
      </span>
     </strong>
    </span>
   </span>
  </span>
 </span>
 If a customer lacks sufficient balance in their AED Current account and has consented to utilize funds from their savings space, the outstanding amount required for the Direct Debit Authorization (DDA) will be deducted from both the savings space and the current account to successfully process and complete the Direct Debit Request (DDR).
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="Khih4dxZNfaN">
 ﻿
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="jdwYrz598Tpb">
 <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
  <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
   <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
    <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
     <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
      <span class="ghq-card-content__text-color" data-ghq-card-content-type="TEXT_COLOR" style="color:#9013fe">
       Here's how to enable it from Wio Personal application:
      </span>
     </strong>
    </span>
   </span>
  </span>
 </span>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="AxtjthfKAQit">
  Log in to the Wio Personal application and navigate to the product hub. Select ‘Send’.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="CDJLHP7tDgdv">
  In the Send section, scroll down and choose ‘Direct Debits’.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="nFdgfpH1AVvn">
  Under Direct Debits, select the transactions you wish to manage payments for using the Saving Spaces option.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="p0JVwzxCfvCH">
  In the Direct Debit Transaction details, you will find a toggle to ‘enable payments from Saving Spaces as your bank’.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="xzJtPOKW2tBx">
  Click the toggle to activate or deactivate this feature.
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="JZitD5rhXiP9">
 <span class="ghq-card-content__image-container">
  <img alt="image.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image.png" style="-webkit-tap-highlight-color:rgba(0, 0, 0, 0);box-sizing:border-box;border:1px solid transparent;border-radius:4px;display:block;width:732.222px;min-width:1px;vertical-align:baseline;white-space:pre-wrap;word-break:break-word;height:auto;visibility:visible" width="2346"/>
 </span>
 ﻿﻿
 <br/>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="3PvoDtkZrltb">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   A hint will appear:
  </strong>
  <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
   If you don't have enough balance to cover the payment of a direct debit request, we'll use funds from your Saving Spaces. This will help prevent any negative impact on your credit score. Please note that this feature is only available for Flexi Saving Spaces, and not for Fixed Saving Spaces or Etihad Guest Saving Spaces.
  </em>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="lY5XFjvIELrn">
  Next, verify your identity to confirm the activation.
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="BRQ9J4ItNuw5">
  Done: A confirmation message will display the changes made.
 </li>
</ul>
<p class="ghq-card-content__paragraph align-center" data-ghq-card-content-type="paragraph" data-text-align="center" id="LqrvuGmnfiZG">
 <span class="ghq-card-content__image-container">
  <img alt="image.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image.png" style="-webkit-tap-highlight-color:rgba(0, 0, 0, 0);box-sizing:border-box;border:1px solid transparent;border-radius:4px;display:block;width:732.222px;min-width:1px;vertical-align:baseline;white-space:pre-wrap;word-break:break-word;height:auto;visibility:visible" width="626"/>
 </span>
 ﻿﻿
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="bVrd9pmzD3VD">
 Closing the Direct Debit - During Account Closure
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="jNftvDZENnfP">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Customer initiated account closure:
 </strong>
 If the customer chooses to close the account via the mobile App while having active DDA
</p>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="hL9GVtlXlpRA">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  For the full account closure process, refer to:
 </strong>
 <a class="ghq-card-content__guru-card" data-ghq-card-content-type="GURU_CARD" data-ghq-guru-card-id="TMe5Akoc" href="https://github.com/RabboPasch/guru-to-github/blob/main/collections/WIO%20PERSONAL/Wio%20Personal,%20Invest%20&amp;%20Credit%20-%20Account%20Closure/wio-personal-settings-in-app-account-closure.md" rel="noopener noreferrer" target="_blank">
  Wio Personal - Settings: In app account closure
 </a>
 ﻿
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="FFtl397vTF39">
  The customer will be instructed through the application to close their existing DDA's (eligible ones to be closed via the customer)
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="9N1PVnpBxNjp">
  Exception cases or cases which the customer can't close their DDA: they will receive a notification:
  <em class="ghq-card-content__italic" data-ghq-card-content-type="ITALIC">
   You have an &lt;individual DDA Status&gt; DDA from &lt;Bank name&gt; for &lt;Reason&gt;. Please close the DDA from the other bank.
  </em>
  <br/>
 </li>
</ul>
<h2 class="ghq-card-content__medium-heading" data-ghq-card-content-type="MEDIUM_HEADING" id="BRleOcru1tPt">
 (Phase 2) Success: Closing the Direct Debit - During Account Closure
</h2>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="DvDYWgPH7rh3">
  During account closure process, customer will be instructed to close their active DDA's, if any
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="yGDSDX8ZdhiU">
  Customer to proceed with closing the active DDA's if eligible
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="GPM37PH1PYvr">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Success scenarios:
  </strong>
  customer will be able to close their DDA's and get an instant confirmation through the application, they will be able to continue with the steps needed to complete the account closure.
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="9rCUhbRlR3ZT">
 <span class="ghq-card-content__image-container">
  <img alt="image.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image.png" style="-webkit-tap-highlight-color:rgba(0, 0, 0, 0);box-sizing:border-box;border:1px solid transparent;border-radius:4px;display:block;width:732.222px;min-width:1px;vertical-align:baseline;white-space:pre-wrap;word-break:break-word;height:auto;visibility:visible" width="3926"/>
 </span>
 ﻿﻿
 <br/>
 <br/>
</p>
<h2 class="ghq-card-content__medium-heading" data-ghq-card-content-type="MEDIUM_HEADING" id="x3AW915luz9p">
 (Phase 2) Failure: Closing the Direct Debit - During Account Closure
</h2>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="ZX0NjSnb1VPb">
  During account closure process, customer will be instructed to close their active DDA's, if any
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="9x2jvfDjuDt7">
  Customer to proceed with closing the active DDA's if eligible
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="BHJGtJNhbAaj">
  <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
   Failure scenarios:
  </strong>
  customer will not be able to close their DDA's if it requires initiator bank approval and will be instructed to contact the other bank in order to close their current DDA.
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="ndVDsZ1ZXzzH">
 <span class="ghq-card-content__image-container">
  <img alt="image.png" class="ghq-card-content__image" data-ghq-card-content-image-filename="image.png" data-ghq-card-content-type="IMAGE" src="/collections/WIO PERSONAL/resources/image.png" style="-webkit-tap-highlight-color:rgba(0, 0, 0, 0);box-sizing:border-box;border:1px solid transparent;border-radius:4px;display:block;width:732.222px;min-width:1px;vertical-align:baseline;white-space:pre-wrap;word-break:break-word;height:auto;visibility:visible" width="3136"/>
 </span>
 ﻿﻿
</p>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="bzF7FnaXFSLd">
 Frequently Asked Questions (FAQs)
</h1>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="vzXHJuNInt03">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  What is the Direct Debit Authority (DDA) and how is it managed through the Wio Personal Application?
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="PxtRfFZdZQJN">
  The Direct Debit Authority (DDA) allows users to authorize recurring payments directly from their bank accounts. Through the Wio Personal Application, users can manage their DDAs by logging in, viewing active DDAs, checking transaction statuses, and assigning nicknames to their DDAs.
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="pyDBHNJpHotF">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  How will I be notified when a DDA request is initiated?
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="jBQcnpTN83N7">
  Customers receive notifications via SMS and email when a DDA request is initiated by their sponsoring bank. The notification will detail the DDA request, including information such as the amount, start date, end date, and purpose.
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="BVJ91RjpR3Px">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  What happens if my account balance is insufficient for a DDR request?
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="x0ZNXLh1n93R">
  If you have insufficient funds in both your current and savings accounts combined when a Direct Debit Authorization (DDA) request is received, you will receive a notification alerting you that your account balance is not sufficient. This notification will inform you to top up your account before 3 PM on the same day to avoid any issues with the DDR request.
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="6R9h9ZjP7nL1">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  What should I do if I receive a DDA request notification but do not recognize it?
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="dbjZWhR5bVXE">
  If you do not recognize the DDA request notification, you should contact the Wio Care team through 600500946 for assistance.
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="YTdBrgPQvcHP">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  Can I set a backup payment method for my DDAs if my current account balance is insufficient?
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="7jNkrlC094g9">
  Yes, customers can enable payments from their Saving Spaces as a backup method if their current account lacks sufficient funds. This feature can be activated through the Wio Personal Application by accessing the Direct Debit transaction details and toggling the option for using Saving Spaces.
 </li>
</ul>
<p class="ghq-card-content__paragraph" data-ghq-card-content-type="paragraph" id="7kNrJEDtWFHB">
 <strong class="ghq-card-content__bold" data-ghq-card-content-type="BOLD">
  What happens to my active DDAs if I want to close my account?
 </strong>
</p>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="fgUV7l16c5hJ">
  When initiating account closure, customers will be instructed to close their active DDAs. Successful closure of eligible DDAs will provide an instant confirmation through the application. However, if a DDA requires approval from the initiating bank to close, customers will need to contact the other bank for closure.
 </li>
</ul>
<hr class="ghq-card-content__horizontal-rule" data-ghq-card-content-type="DIVIDER"/>
<h1 class="ghq-card-content__large-heading" data-ghq-card-content-type="LARGE_HEADING" id="d3JpXMPX9PAr">
 Related articles
</h1>
<ul class="ghq-card-content__bulleted-list" data-ghq-card-content-type="BULLETED_LIST">
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="bBhjTB4jzj7P">
  <a class="ghq-card-content__guru-card" data-ghq-card-content-type="GURU_CARD" data-ghq-guru-card-id="142ffbcb-b0a5-4253-b571-9b24d0714aaf" href="https://github.com/RabboPasch/guru-to-github/blob/main/collections/WIO%20PERSONAL/Wio%20Personal%20-%20Send:%20UAE%20Direct%20Debit%20System%20(DDS)/wio-personal-transfers-understanding-uae-direct-debit-system-uaedds-through-wio.md" rel="noopener noreferrer" target="_blank">
   Wio Personal - Transfers: UAE Direct Debit System (UAEDDS)
  </a>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="T5DhfrNzKf5H">
  <a class="ghq-card-content__guru-card" data-ghq-card-content-type="GURU_CARD" data-ghq-guru-card-id="7ff812b5-6347-4de3-9dca-b7e31eb85ec5" href="https://app.getguru.com/card/T5xqRync/Wio-Personal-Transfers-UAE-Direct-Debit-System-UAEDDS-Definitions-and-FAQs" rel="noopener noreferrer" target="_blank">
   Wio Personal - Transfers: Introduction to the UAE Direct Debit System (UAEDDS)
  </a>
 </li>
 <li class="ghq-card-content__bulleted-list-item" data-ghq-card-content-type="BULLETED_LIST_ITEM" id="NQzLnfq54hrd">
  <a class="ghq-card-content__guru-card" data-ghq-card-content-type="GURU_CARD" data-ghq-guru-card-id="023faa45-a416-45c8-88de-33936bf1e0d6" href="https://app.getguru.com/card/ck9Lbdki/Wio-Personal-Transfers-UAE-Direct-Debit-System-UAEDDS-Notifications-and-Codes" rel="noopener noreferrer" target="_blank">
   Wio Personal - Transfers: UAE Direct Debit System (UAEDDS) Notifications and Codes
  </a>
 </li>
</ul>
<p class="ghq-card-content__paragraph ghq-is-empty" data-ghq-card-content-type="paragraph" id="7G5zMh5VD9an">
</p>
