**Sprint 39:**
**EPICs:**
- {Ongoing} Kick- off two discovery projects with C4C team (Refund & CN (KU products) automation) 
- {Ongoing} Kick-off architectural discussions for OnBas project
- {Ongoing} Continue with Consumer Centric Transformation project
- {Ongoing} ES + PT: Export Bordereau before wednesday morning #1433 - new test on Sep 26. Bordereau reports to be extracted again.
- {New} D2C testing

Checkout re-design & order page:
- Line break is in the middle of the offer name in AEG web checkout #1452
- Order Page - transaction failed update #1455
- FE: Checkout Re-design (Payment Section) #1445

**Ops tasks:**
- {Ongoing} CMD Center: Extend FORCE CANCELLATION/WITHDRAWAL feature for Subscriptions #1447 - we couldn't complete it last week due to unplanned tasks.
- {New} DE: Cancellation (Refund in progress) email #1353
- {New} SE: SAP invoice with wrong amount #1383
- {New} SE: Missing invoices IN SAP #1372
- {New} QS: Add appliance purchase date field #1423
- {New} DE: R+C Update refund amount and T&C (Go live: 3rd Oct) #1422

**Sprint 38:**

**EPICs:**
- {Ongoing} Kick- off two discovery projects with C4C team (Refund & CN (KU products) automation) 
- {Ongoing} Kick-off architectural discussions for OnBas project
- {Ongoing} Continue with Consumer Centric Transformation project
- {Completed}ES + PT: Update offers Care + R&C #1437
- {Ongoing} ES + PT: Export Bordereau before wednesday morning #1433 - new test on Sep 26. Bordereau reports to be extracted again.

**Ops tasks:**
- <strike> CZ: Update VAT Inspection fee #1441
- SE: Swish refund failed #1431 </strike>
- {Ongoing} DE: Cancel order 195741 before 23 Sep #1428
- {Ongoing} IT: Close contracts in failed payments #1426

**Sprint 37:**

EPICs:
- <strike> Production release to enable iDeal payment method to go live in NL </strike>
- {Ongoing} Kick- off two discovery projects with C4C team (Refund & CN (KU products) automation) 
- {Ongoing} Kick-off architectural discussions for OnBas project
- {Ongoing} Continue with Consumer Centric Transformation project

Ops tasks: 
- <strike>Incorrect transaction timestamp data on QS #1363
- SE: New Json file #1418
- UK: Refund options in price segmentation offers #1427
- NL QS: Cannot see data on QS #1419
- FI : Add tax rate FPR to 24% #1390
- DE: New R+C and Care consumer list (by 13 Sep) #1424
- FR 136263 withdraw before 18 Sep #1382
- FE: Add Offering IDs in CCT (staging) #1429 </strike>
- {Ongoing} Set up access for Ash #1416

**Sprint 36:**
**EPICs:**
- <strike> ES+PT: Push Care + Repair and Care offers to Production #1399
- ES: Update name of FPR offer #1397
- ES+PT: Update sales commission and claims mgmt fee in Borderau. #1398
- FE(Mid August) - ES+PT: Update validation of Tax ID code #1309 </strike>

**Operational tasks:**
- <strike> Incorrect transaction timestamp data on QS #1363
- DE Bordereau incorrect date of policy inception #1360
- SE: Upload Json #1393 </strike>
 
** Ad-hoc tickets:**
 -<strike> HU: Update SN and push to Regulus #1417 </strike>
We also spent a long time prepping for a release of iDeal (there were a lot of dependencies).


**Sprint 34:**
**EPICs:**
- iDEAL
- Bankomat
- appliance-service 

**Operational tasks:**
- FI: FPR Refund scenarios #1368
- HU: Update KU prices (Go live Sep 1st) #1369
- SE: Update prices FPR (Go live Sep 1st) #1364
- ES + PT: Add IPT in Care + R&C products #1365
- FR 49875 UPM doesn't work (ASAP, no payment was charged in Jul) #1371


**Sprint 26:**
**EPICs:**
- UAT IT
- UAT Technician Sales Channel
- D2C Finalisation of the error messages

**Ops tasks: **
- Enable CZ for Nexure->C4C Integration #1312
- FR: Cancel order 157258 and 164274 #1311
- FR: migrate the visit outcome of open orders from the cut over #1303
- Category Mapping Update #1307
- Nexure->C4C Integration: remove "Inbound" flow starting from Nexure CCT on staging. #1301


**Sprint 25:**

**EPICs:**
Our main goal for this week is to run a successful SIT for the Nexure->C4C Integration project and complete system integration for D2C for next week's SIT. - Completed.


**As for operational tasks, here is the list:**
- <strike>Update T&Cs in the emails (payment link + payment confirmation)NL130622 T&C NL.pdf #1287
- New prices for UK FPR AEG + Zanussi #1285
- IT: Orde 178953 cannot be deleted even though we do not have transactions registered #1275
- CZ: Cancellation scenario not working for Care OOW with annual payment #1284
- IT: Update verification for Fiscal Code #1228
- W26 FR: R+C AEG price seg (27 Jun) #1235
- FE: ISP keyboard - showcase numerical instead of alphabetical #1280 </strike>



**Sprint 23: 
EPICS:**
- {Ongoing} D2C Integration - 2 tasks to be delivered this week:
- {Done}A list of PNCs to test with (interim solution)
- Endpoint for order creation
- {Ongoing} Nexure ->C4C Integration - Testing Phase
- {Ongoing}  BNL last changes before BGL - BNL BGL #1270
**Operational tasks:**
- {Bug}Re-trigger payment status/create certificate to Regulus #1273
- SE: Marketing consent (deactivate) #1274
- CZ & SK FPR- Update T&Cs #1268
- CZ+SK: Update logic for parsing address line coming from C4C #1265
- BNL: Give data access on QS #1269
- CZ: Cancel order 174740 and 175462 used for smoke testing #1264

**Sprint 22, 2022 Review:**
**EPICs:**
- {Ongoing} D2C Integration 
- {Ongoing}  Nexure ->C4C Integration
- <strike> Bordereau fixes: we are done with the mitigation of all invoices. Last step: extract payment notifications & add it to Bordereau-service. It's aimed to be completed today; We are planning to extract April reports for HU, PL,DE & IT tomorrow morning. If not, we will go with our Plan B and extract "old" version Bordereau reports on Wednesday. </strike>

**As for the operational tasks, here is the list:**

- <strike>  Update insurance premium % #1224
- ES: Bug - Cancellation of order triggers the failed payment email #1257
- PL: Configure ticket for Smoke test #1260
- PT: Care offer email configurations are the Italian ones #1237
- DE PayPal: turn up to 100% #1252
- FE: Price Segmentation #1218
- FI: Setup new FPR offering #1262 - waiting for additional info. from @Peter Nordenstedt 
- ES+PT: Set up repair and care offer #1210 - waiting for additional info from @Sofie Lang 
- W22 FR: FPR AEG price seg (7 Jun) #1235 - Newlaunch date. Planned on Monday, June 13.</strike> 



**Sprint 20, 2022 Review:**
EPICs:
- {Ongoing} D2C Integration 
- {Ongoing} Nexure ->C4C Integration
- {Done} Bordereau: planned to be released in W22
1. Bordereau fixes #1219
2. Fix Italian invoices #391
3. Bordereau / Invoice Fixes #1214
- </strike> PL Smoke Test - Wave 2 Roll-out
- PL Invoicing Flows </strike>

As for the operational tasks, here is the list:
- </strike> BNL: Move offerings to production #1230
- BNL - Insurance Policy #1231
- FE: Unable to go to next page when browsing the offers in Staging #1232
- [BE] Offering API: simple API version for creating new FPR/II/FIS offerings #1148
- SE: Failed refund on Swish payment #1233 </strike>



**Sprint 17, 2022 Review:**
EPICs:
- <strike> Release of the price segmentation for the Inbound Flow (External System)
-  SECO finalisation
- Adyen Tokenization </strike>
- {Ongoing} Nexure->C4C Integration
- {New} D2C Transformer Kick-off

**Operational tasks:**
- <strike>SE: Update FPR/inspection pricing (Go live May 1st) #1191
- QS: Add parameter "created in warranty" #1156
- Datalake: Adding full refund field to the weekly beat funnel #1198
- QS/ CCT: PL expired contracts shown as Active? #1190 
- DE: switching old/new RSP offer (tentative date: 2 May) #1200
- DE: Cancel order 63955 by 30 Apr #1194
- FR 131048 withdraw by 1 May #1171
- IT: Cancel order 58809 (In failed payments) #1202
- IT: Add Care offer with price 11,90 to substitute terminated R&C's. #1130
- FR - 144468: Agent sold RS close to appliance eligibility expiration #1199 </strike>
- {Ready for the PR review}BE+NL: Manual claims #1189

**Sprint 16, 2022 Review:**

- {Ongoing} Price Segmentation 
- {Ongoing} FR SMoke Test Support
- {Ongoing} SECO
- {Ongoing} Nexure->C4C Integration

Operational tasks:
- CZ: Two PoM booked as FPR? #1187 - Need input from BizDev team
- BE+NL: Manual claims #1189 - Moved to W17
- <strike> FR: Consumer double monthly payment #1125
- FR 131048 withdraw by 1 May #1171 
- PL: Change 3Y order status (Active-> Withdrawn) #1158
- IT: Revert order 158436 back to active (next payment April 30) #1161
- QS: Give dataset access to Installed Base Team #1192
- DE subledger Care upfront fee #1157</strike>

**Sprint 15, 2022 Review:**

- {Ongoing} Price Segmentation 
- {Ongoing} MongoDB Upgrade
- {Ongoing} SECO
- {Ongoing} Nexure->C4C Integration

**Operational tasks:**
- SMOKE test testing for CEE/FR markets - add ticket + consumer IDs #1129 - we will set the code this week and are awaiting for the Ticket ID from the ConCent Team.
- <strike>  IT: Investigate why there's two payments in March for order: 89951 #1173
- SE: Failed refund on Swish payment #1168 
- BE CEE: Copy "Street" string from C4C as it is to "Address" field in Nexure CCT #1146
- FE CEE: Remove the validation for the "Street Number" in Nexure CCT #1146 #1147
- CZ: Update T&Cs for Care + R&C #1162
- CZ: Actiavte offers for WEB channel (to complete before W17) #1100 </strike>


**Sprint 14, 2022 Review:**
- {Ongoing} Price Segmentation 
- {Ongoing} MongoDB Upgrade
- {Ongoing} SECO
- {New} Nexure->C4C Integration
- {New} Adyen Tokenization

**Operational tasks:**
- <strike>SMOKE Test Merchant Account Configuration: SK, IE, BE, NL #1153
- IT: Add Care offer with price 11,90 to substitute terminated R&C's. #1130
- FR: 123971 Cancel order by 5 Apr #1150
- FR: 123971 Cancel order by 5 Apr #1150
- IT: no payments being charged to active order 81633 #1136
- SE: Failed refund on Swish payment #1139
- DE: Update appliance purchase date #1144</strike>


**Sprint 13, 2022 Review:**

**EPICS:**
- <strike> Bordereau - Tuesday, March 29th. (Shout-out to @Inam ur Rehman @Gustaf Rydholm @Cristian Vergallo 
- Chargeback Handling - (Preliminary) Thursday. (Shout-out to @Anton Österberg @Carl-Johan Larsson). We need to wait at least 48hrs to ensure Bordereau release goes smoothly. In case of issues, we might postpone chargeback handling to next week. FYI: @Ashley Chong @Peter Nordenstedt @Sofie Lang. (B
Other than these releases, our major focus this week is to continue development of price segmentation project, start looking into ISP Reporting in QS and complete MongoDB upgrade.</strike>

**Here are our operational tickets:**
- <strike>{In progress} IT: Buy now pay later, payment link doesn't work and tickbox missing #1111
- {In progress} SE: Access rights for Electrolux Admin likely does not include uploading payment ingestion file #1106
- IT: Add Care offer with price 11,90 to substitute terminated R&C's. #1130
- FR/C4C: Set up FPR partial refund button on CCT on Staging for testing #1133 </strike>
- {Ongoing}Wave 2 (SK + IE) Market Releases #1128 - Waiting for SK domain in prod. environment.

**Sprint 12, 2022 Review:**

**Epics: Price Segmentation** {In progress} 
- Hacky - Pricing Segmentation #1121 @Bizdevs, we need support with product category mapping for their markets. 
- Master Data: ingest latest products/product categories #1120
- Price Segmentation: available categories in Offerings #1113

**Bordereau Revamp Project #1027** - Testing completed. To be released on March 29th.
** Improved Chargeback Handling #1026** - Completed. (Preliminary) release planned on Thursday. We need to wait at least 48hrs to ensure Bordereau release goes smoothly. In case of issues, we might postpone chargeback handling to next week.
As for the operational tasks, here is the list:
- <strike> IT: C4C ticket mashup is not working #1115
- QS: Reporting showing wrong "Team" #1112
- BE/NL: Update sender adress #1107
- SE: Cancel cancellations emails sent to operationsupport #1101
- FR/C4C: Street number imported incorrectly #1109
- CZ: Actiavte offers for WEB channel #1100
- New Permission: concent-tickets #1122
- FR: UPM not working #1110
- DE 76912 cannot trigger pending cancellation on CCT (before mid Apr) #1088
- FE AEG/Zanussi checkout: Change colors #1108 </strike>
- {In progress, moved to W13}SE: Access rights for Electrolux Admin likely does not include uploading payment ingestion file #1106
- {In progress, moved to W13}IT: Buy now pay later, payment link doesn't work and tickbox missing #1111

**Sprint 10, 2022 Review:**
**EPICS:**
- {In progress}Bordereau Revamp Project #1027 - Final testing by BizDevs to be completed on 24th of March. Might require changes in the premium sheet for IPT calculations.
- {In progress} Improved Chargeback Handling #1026 - Deadline: W11 - Release date: March 30.

**Ops Tickets:**
- <strike> HU: Pricing/T&C update - Deadline 12:00 28/2 #1052
- FR: Update R+C contract expiry age #1054
- PL: Cancel transaction (Deadline 28/2) #1065
- FR: Service material update for R+C and Care #1060
- IT: Update T&C for FPR & Care #1056
- DE: PayPal - open to 50% of consumers #1066
- IT: Investigate why order 141765 goes directly to withdrawn instead of pending cancellation. #1067
- IT: Change purchase date of appliance #1058 </strike>

**Ad-hoc:**
- <strike> CMD Center: re-trigger failing ConCenT calls #1044
- Issue to open Nexure CCT from C4C (WIP) #1086 </strike>




**Sprint 9, 2022 Review:**
**EPICS:**
- {In progress}Bordereau Revamp Project #1027 - Deadline: W9 - Almost completed, need to run testing internally & BizDevs. 
- {In progress} Improved Chargeback Handling #1026 - Deadline: W11 - Development is going as planned.

**Ops Tickets:**
- <strike> HU: Pricing/T&C update - Deadline 12:00 28/2 #1052
- FR: Update R+C contract expiry age #1054
- PL: Cancel transaction (Deadline 28/2) #1065
- FR: Service material update for R+C and Care #1060
- IT: Update T&C for FPR & Care #1056
- DE: PayPal - open to 50% of consumers #1066
- IT: Investigate why order 141765 goes directly to withdrawn instead of pending cancellation. #1067
- IT: Change purchase date of appliance #1058 </strike>

**Ad-hoc:**
- <strike> CMD Center: re-trigger failing ConCenT calls #1044
- Issue to open Nexure CCT from C4C (WIP) #1086 </strike>


**Sprint 6, 2022 Review:**

- <strike> Remove search function in sales script (CCT) - nobody's using it #1030
- SE: technicians filling in claims details. Pre-fill the ONLY option they can select #1031
- DE: 56926 system stopped charging for 7 months #1024
- IT: Launch of new R&C / FPR offers for partial refund #1019
- SAP invoice search not working in CMD #1018
- IT: EW sold for 140506 with an appliance out of eligibility -> Expired #1022 </strike> 



**#Sprint 3, 2022 Review** 

EPICS: ConCent Wave 2 Launch Tickets:

- {On Hold} BE: Offers to be setup (recurring ticket) #862 - moved back to BIZDEV backlog for Peter to QA and let us know if any changes are required + add final prices.
- {On Hold}NL setup (Recurring) #916 - moved back to BIZDEV backlog for Peter to QA and let us know if any changes are required + add final prices.
- {On Hold}ConCent W2, CZ (Jan 10-11): VAT Support for FPR Product #919
- {On Hold} C4C CEE: configure CEE countries to switch from Regulus to C4C integration #969: waiting for claim service update from C4C.
- <strike>  SK: Setup offer + email templates #941
- IE: Set up FPR offering #904
- C4C FR: configure FR to switch from Gestech to C4C integration #968
- IE: User communication emails (recurring ticket) #905 <strike> 


**CDC Integration:** 
- {In progress} CDC integration #335 - in reivew, minor changes to be implemented due to last minute flow updates from the CDC team.
- {In progress} CDC initial ingestion: Consumer+Product Export #954 - in reivew, minor changes to be implemented due to last minute flow updates from the CDC team.

**Operational Tasks:**
- </strike> Quicksite data: Get info if the product is bought IW/OOW #973
- AWS SMS: not receiving text messages in Staging/DEV #975
- FR: Cancel orders in Pending Cancellation #963
- (FIX before Jan 20)BE: initial offset is set to 30 days for IW + migration for the existing ones #70 
- IT: Deactivate SEPA as a payment method for new customers (except for MOTO payments) #294 </strike>
- {In progress} Complete external settlement task #1103
- {In progress}  CZ: 56343 Can't cancel order after binding is over (By 14 Jan) #948 
- {In progress} IT: Activate Paypal as payment method #743
- {In progress}  FR: update payment reminder email schedule #492


**#Sprint 2, 2022**

**EPICS:**
**ConCent Wave 2 Launch Tickets:**
- {In progress} IE: User communication emails (recurring ticket) #905
- {In progress} BE: Offers to be setup (recurring ticket) #862
- {In progress}  NL setup (Recurring) #916
- {In progress} ConCent W2, CZ (Jan 10-11): VAT Support for FPR Product #919
- {In progress} SK: Setup offer + email templates #941
- {In progress} IE: Set up FPR offering #904
- {In progress} C4C CEE: configure CEE countries to switch from Regulus to C4C integration #969
- {In progress} C4C FR: configure FR to switch from Gestech to C4C integration #968

**CDC Integration:**
- CDC integration #335
- CDC initial ingestion: Consumer+Product Export #954

**Operational Tasks:**
- {To-do) Quicksite data: Get info if the product is bought IW/OOW #973
- {In progress} AWS SMS: not receiving text messages in Staging/DEV #975 
- {In progress}  FR: Cancel orders in Pending Cancellation #963
- {In progress} (FIX before Jan 20)BE: initial offset is set to 30 days for IW + migration for the existing ones #70
- {In progress} CZ: 56343 Can't cancel order after binding is over (By 14 Jan) #948
- {In progress}  FR: update payment reminder email schedule #492
- {In progress}  IT: Activate Paypal as payment method #743
- {In progress}  IT: Deactivate SEPA as a payment method for new customers (except for MOTO payments) #294
- {In progress} Complete external settlement task #1103

**#Sprint 49**
- <strike> AWS Service Upgrade </strike>
- [In progress] CDC Migration - delivery planned on W51. Testing in Jan 2022.
- [In progress]  SE Invoicing - 
- [QA]  BE Launch 
- [QA] Ireland Launch
- [QA]  Netherlands Launch. Missing Email IDs
- <strike>[ Cancellation button implementation </strike>

**Here are the list of operational tasks for this week:
**
- <strike> PL(Mon): Change name on promotional offerings #909
- HU (Mon): Update pricing on 2 offers (xmas discount) Dec6th?! #899
- SE (W49-50): Cancel order (before end of the year) #915
- SE (W49-50):: Update pricing #914 </strike>



#Sprint 48
- [In progress]AWS Service Upgrade
- [In progress] Cancellation button implementation - @Tommy Ljungberg to complete FE 
- [In progress] CDC Migration 
- [In progress] BE Launch - @Peter Nordenstedt the tickets are in the QA for you to review & for us to fix, if there are any issues.
- [In progress] SE Invoicing - @Peter Nordenstedt can you share the ticket you want us to pick up for this project?

**Operational tasks:**
- <strike> DE: Withdraw order 98469 before 5 Dec #864
- Update VAT rate for Iberia for reporting #879 </strike>
- DE: Error in subledger #828
- IT: Update prices FPR and R&C #842 - Done. Waiting for the C4C team to update prices in their side. Once the prices are updated, we will run an E2E test and release to production

**Ad-hoc:**

- FE: AaaS login upgrade to Auth0 #921 (AaaS)
- DEV: set a dedicated Tenant up #874
- FE: Checkout UI Material update #872
- FE: Auth0 config in Command Center #894


# Sprint 47
- [In progress] BE Launch - @Peter Nordenstedt to reivew tickets in QA
- [In progress] IE Launch - to be picked up W49
- [In progress] AWS Service Upgrade - @Carl-Johan Larsson @Anton Österberg to kick-off the project this week.
- [In progress] Cancellation button implementation - @Tommy to pick up FE tickets
- [In progress] Breeze UI Material Update - @Tommy Ljungberg is done, needs to merge.



**Operational tickets:**
- <strike> FR: FPR - Implement Partial refund for <24 hr cancellation #865
- ConCent Wave 2: FR/CZ/PL + IE QA links #860
- Iberia: Block users in ES #861
- SE: Cancel order #858
- DE: new UPM 68850  # 867 </strike>


# Sprint 46
**EPICs:**
- [In progress]  Implementation of the Cancellation Button in the Monitoring Tool for Orders. To be completed in W47
-  <strike> CDC PoC (Web Channel) @Anton Österberg  @Tommy Ljungberg. Demo completed on Nov 18 </strike> 
- [In progress]  BE Roll-out @Inam ur Rehman
- [In progress]  Breeze UI Material Update. Done, needs merging.


**Operational tickets:**
- [In progress]IT: activate "Buy now, pay later" option to Care without AD in Italy #655. Final review to be done W47.
- <strike> SE: Cancel order #846
- FR: cancel order 86845 by 18 Nov #801
- DE: Withdraw order 87135 97968 111098 before 19 Nov #788
- DE: Withdraw order 112072 by 22 Nov #821
- DE: Update product info #780
- PL: Update orders (not needed to send to Regulus) #800 
- SE: SAP invoices/credit notes missing #845 </strike> 


# Sprint 45
**EPICs:**
- [In progress] Implementation of the Cancellation Button in the Monitoring Tool for Orders @Gustaf Rydholm @Tommy Ljungberg. Release planned on W46
- [In progress] CDC PoC (Web Channel) @Anton Österberg  @Tommy Ljungberg . Release planned on W46. Co-dependency w. CDC team
- [Delay]AWS Upgrade Investigation @Carl-Johan Larsson . Was postponed to W46. Had no time to kick-off the project.
-  <strike>  BE Roll-out @Inam ur Rehman 
- BE: Setup environment #826 
- BE: User Communication Emails (W45) #827
- Breeze UI Material Update @Tommy Ljungberg </strike>

**Operational tickets:**
- <strike> DE: w45 Cancel 98690 by 9 Nov #759
- DE Chargeback Cases #690
- DE: 57755 - Need new UPM by 4 Nov (Chargeback Case) #798
- Add productPrice as a variable to templates #820
- IT: Activate Paypal as payment method (11th Nov) #743
- All - Exit survey in QS #616
- SE: Resend invoice to SAP #799 </strike>
- [In progress]IT: activate "Buy now, pay later" option to Care without AD in Italy #655. Moved to W46.


**Ad-hoc:**
- <strike> Update amount of partial refund for Iberia #833
- [FR] Order in wrong state: 39658 #829
- [FR] Order in active state with several failed payments: 39287 #832
- [FR] Broken order state: 39611 #830 </strike>


# Sprint 44
- <strike> FR: Care offering update (1 Nov) #546
- DE: Cancel order 104938 before 4 Nov #786
- SE: Cancel orders #738
- DE: Cancel order 110151 107739 before 12 Nov #792
- FR: w45 cancel 84452 by 9 Nov #774
- IT: cancel order 99183 prior to 8/11 #769
- IT: Cancellation of order prior to 5 nov #784
- FR: Cancel 70549 by 16 Nov #778 </strike>



# Sprint 43
- All - Exit survey in QS #616 - @Peter Nordenstedt to review if we want to move forward with this ticket (the data seems unreliable)
- <strike>PL: Update orders #677
- IT: Add external agent to GAP contact centre #763
- SE: New station (Deadline 26th Oct) #767
- [BUG]German order is not terminated #750
- [BUG] Order is in FAILED_PAYMENT instead of ACTIVE #749 </strike>
- FR: Update Inspection fee T&Cs #777 - needs re-planning. 


Ad-hoc:
- <strike> German order is not terminated #750
- C4C is down - All calls are failing #783
- Order is in FAILED_PAYMENT instead of ACTIVE #749 </strike>



# Sprint 42
- All - Exit survey in QS #616 - the data seems unreliable, hence we might skip this ticket altogether
- <strike> FR: Partial refund for FPR + T&Cs update #670
- DE: Care order age on staging (18 Oct) #760
- DE: Ops ticket (w41 by 23 Oct) #739
- DE Chargeback Cases #690
- FR: Ops ticket w42 (By 19 Oct) #721
- Iberia: Attach T&Cs for PT + ES #766 </strike>
- [Pending Review]SE: Investigate payment reminder emails #615 - CJ to review W43


# Sprint 36

**Ops Tickets:**

<strike> - ES: Update AEG domain (aeg.com.es instead of aeg.es). #639
- Iberia: set "Identification number" as mandatory field in Nexure for both PT + ES #637
- PL: Ops (w36) #638
- FR: Ops ticket (w36( (By 8 Sep) #636
- FR: Activate MOTO on CCT #591
- All - Exit survey in QS #616 - @Peter Nordenstedt in order for us to review this ticket, we need more specs. It is specified in the ticket. </strike> 


# Sprint 35

- [IN PROGRESS Re-deploy all masters in dev env (using latest tag) by pressing a button in command-center #15
- [IN PROGRESS  Ingestion-service #244
- [IN PROGRESS Create endpoints to store claims in claim-service #596
- [IN PROGRESS  Phase 1 - Deploy Claim Repository and migrate data #4

**TO DO W36:**
- Split out claims from order-service into a "claim-service" #243
- Phase 2 - Claim service is the master of old claims #5
- Phase 3 - Attach ingestion service and implement claim factories in claim-service #
- Phase 4 - Migration from old claim model to new claim model #7
- Phase 5 - Publish internal claim events and process them in order-service #8 

**Ops Tickets:**
<strike> CZ: Update pricing on Care and R&C #617 - 12 new offers need to be setup to support new pricing.
- UK: Update Partial refund amount #612
- UK: Update T&C for e-mails #613
- FR: Ops ticker (w35, Complete by 3 Sep) #610
- SE: Cancel orders #608 </strike> 




# Sprint 28

- <strike> HU: FIS Implementation - Regulus integration #540
- HU: FIS Implementation - Offerings  # 538
- HU: FIS Implementation - Emails  # 537 
- PL: Update Policy Info #553
- SE: CN Generation #551
- DE: Change order state from "Terminated" to "Active" #552
- DE: Ops ticket (w28) #547
- Quicksight: Net sales report #499
- IT: integration issue to C4C 84029 #541 </strike> 

Ad-hoc:
- <strike> DE: Order 77793 - Transaction is not reflected in the order page in CCT #556
- PL + IT : Order State is not updated #550
- SE - Claims/Survey Reporting Improvement (tracking change from IW to OOW) #390 </strike> 


# Sprint 27

- <strike> DE: Set up trigger for automated payment reminder #424
- Bug: CCT shows mulitple payment reminder emails sent to consumer on the same day #510
- State Machine: Country & Product Isolation #777 </strike> 
- [IN PROGRESS] Sentry Cleanup and Investigation #450
- [IN PROGRESS] Null agent ID (end of the month) #462
- [IN PROGRESS] Script to set the SendGrid template IDs up #507
- [IN PROGRESS] DE Subledger fix #456. Done. To be released in end of July.

**EPICS Roadmap tickets:**
- <strike>  BaS: Configure PROD URLs for UK #529
- UK: Make Emails configurable by Sales Channel #521
- UK: Configure new merchant accounts (live) #483 </strike> 

**Ops tickets:**
- <strike>  FR: Ops ticket w27 #517
- PL: Extract list of users #519
- HU: Update T&Cs #525
- PL: Update Certificate #526
- DE: Ops ticket w28 #523
- Quicksight: Net sales report #499
- Adyen PT+FI+NO Account Setup #524
- SE: Disable refund scenarios #528
- FE: Notifications - Banner for System messages #514
- PL - Push certificate to Regulus #512
- SE - Claims/Survey Reporting Improvement (tracking change from IW to OOW) #390 </strike> 
- [IN PROGRESS] 3rd Environment #530


# Sprint 25

**Ops Tasks:**
- <strike> UK: Add manager's account #494
- IT: Ops Ticket #478
- DE: Ops ticket (w25) #481
- FR: Ops ticket (w25) #480
- FE HU:Add Appliance purchase price to CCT #493
- BE AaaS: fix the LeasingDetails update for a LeasedAppliance #489
- SE: generate invoices for Skatteverket #391 </strike>
- [IN PROGRESS] DE Subledger fix #456 - Almost completed. Will be done W26
- [IN PROGRESS] UK: Email IDs setup #498. Will be done W26

**Ad-hoc tickets added W24. All are completed now:**
- <strike> FE: enable SSO for the latest C4C countries #495
- Configure and test SSO for UK (Inbound) #486
- FE BaS: zipCode validation on checkout page #485
- BE+FE AaaS: update the endpoints to support auth calls #488
- Order detailed visuals not showing amount Eur from 23 May #4
- IT: Activate "Report a claim" field in CCT Order Page #482 </strike>


# Sprint 24

**EPICS W23:**
- <strike> CZ OOW: Orders are setup. The team needs additional 2 days to implement a new state for Monthly/Yearly Orders, which are outside of the binding period and are cancelled. The solution is being currently investigated.
-  UK - Book-a-service project. The testing merchant account is created and testing has began. </strike>
-  a) BE: UK BaS define dedicated endpoints to create Orders by C4C data #417


**Ops Tasks:**
- <strike> FR: Ops tickets (w24) #476
- DE: Ops tickets (w24) #474
- IT Grace Period - Deactivate for Garanzia Estesa Easy & Family IW offers only #475
- HU: Add basic offerings #446DE: Set up trigger for automated payment reminder #424. Required to handle missing payments for DE (+Nordics) market(s) post-ISP visit. </strike>
- [IN REVIEW]  SE: generate the excel invoice for Skatteverket #391. Dependent on the SAP release for IT. 
- [IN PROGRESS]  Better Tracking of Payment Failures (Phase 1 of Resillient Schedulling) #81
- [IN PROGRESS]  Regulus monthly operational #453. _The orders have been reviewed and some require intervention from the local market._ @Peter Nordenstedt
- [ON HOLD] Italian T&Cs for Garanzia Estesa Premium Easy + Family #473. _Moved to W25. Still awaiting for T&Cs._

If we have time, we will pick up the following ticket for ConCent Wave launch: 
<strike>  
- ConCent Iberia + Nordics - Email IDs #394 </strike>

Ad-hoc ticket (added last week):
- <strike> FE AaaS: make LeasedAppliance search pageable #469 </strike>

# Sprint 23

**EPICS:**
- [IN PROGRESS]CZ OOW. _Orders are setup. The team needs additional 2 days to implement a new state for Monthly/Yearly Orders, which are outside of the binding period and are cancelled._
- [IN PROGRESS] UK - Book-a-service project - The testing merchant account is created and the testing has began. 


- - BE: UK BaS define dedicated endpoints to create Orders by C4C data #417- _Completed. In testing stage._
- - <strike> FE: UK BaS - checkout page #416 </strike>

**Ops Tasks W23:**
- [IN PROGRESS] Regulus monthly operational #453. _The orders have been reviewed and some require intervention from the local market. @Peter Nordenstedt_ 
- [Moved Back to Backlog] SE: Setup new master account #448. _The eng. team needs to investigate the complexity of setting up a master account prior to its implementation_. _After some investigation, it was concluded that giving access to a manager across all environments will be a large task and we will wait until authorization scheme is in place for ISP channels in August/Sep._
- <strike> Set up a web checkout for IT with the offer with AD (IW & OOW) #408. These offers are required for the outbound marketing campaigns we will run with Central Team at the end of June. </strike>
- DE: Set up trigger for automated payment reminder #424. Required to handle missing payments for DE (+Nordics) market(s) post-ISP visit. _Due to insufficient info. regarding the task, The ticket has been pushed to this week. _
- [IN PROGRESS] SE: generate the excel invoice for Skatteverket #391. Dependent on the SAP release for IT. 
-  <strike> FE: AaaS LeasedAppliances export #442
- FE AaaS: add currency code to LeasingDetails #463  </strike>


**AD-HOC Tickets**
- <strike> IT Web Order - Error description message missing #455. The bug fix is released, but we are reviewing various possible solutions for this issue.
- HU- Push certificate to Regulus #457
- IT: C4C ticket - Nexure order misalignments investigation #458
- Failed Recurring Payments #464 </strike>


# Sprint 22

**EPICS:**

1) <strike> Italy IW Launch: </strike>
-  <strike>[IN PROGRESS]  IT: Updated Prices + New Offering Name for Care Offer with AD. #444 </strike>
- <strike> IT SAP Invoicing Flow for new offers - Care with AD. </strike>

 2) CZ: OOW Offering #449 </strike>. Still in to-do. Will be picked up W23.

3)) <strike> IN PROGRESS]  CZ IW Offering #430 </strike> Demo is scheduled on Friday, June 11.

4)) [IN PROGRESS] UK - Book-a-service project, covering the following tickets.
- BE: UK BaS define dedicated endpoints to create Orders by C4C data #417
- FE: UK BaS - checkout page #416

Still pending as we are awaiting for the merchant account(s) to be activated for us to run E2E testing.

**Ops Tasks W22:**
- <strike> DE: Ops tickets (w22) #445 </strike>
- <strike> PL - Update Agent ID </strike>
- <strike> (SE) Create Amazon Account for Bruno (Central) to access SA details folder #436 </strike>
- <strike> ALL - QuickSight [order_detailed] to include lcct_id and offer_name #410 </strike>
- [BE] UK BaS: payment-service adjustments #202
- <strike> [BE] PL: Segmentation of FPR pricing #447 </strike>
- <strike> [FE] PL: Segmentation of FPR pricing #451 </strike>. Completed, needs to be released.
- (Testing) FE: AaaS LeasedAppliances export #442. Completed, testing in staging now.
- (In progress) Regulus monthly operational #453. The orders have been reviewed and some require intervention from the local market. 
- <strike> DE: Update invoice template for tax-deductible purpose #422 </strike>

**Ad-hoc**
- <strike> IT - Claim Update does not reflect in CCT Backoffice or in transaction report #423 </strike>
- <strike> QuickSight: align reports to reflect the latest price changes  #443 </strike>
- (In progress) SE: SAP invoicing flows to map by action #267. Dependent on the release & merge of the IT SAP Changes #456




# Sprint 21

EPICS:
- <strike> [IN PROGRESS]  Preparing for the release in production environment. </strike>
- CZ IW Offer. In progress. Demo is schedule W22.
 
[IN PROGRESS] UK - Book-a-service project, covering the following tickets:
- BE: UK BaS define dedicated endpoints to create Orders by C4C data #417
- FE: UK BaS - checkout page #416

**Ops Tasks to be covered this week:**
- <strike> SE - Invoice/Credit Note problems #431 </strike>
- DE: Update invoice template for tax-deductible purpose #422. 
- <strike> DE - Ops ticket (w21) #419 </strike>
- <strike> DE: Reset CCT manager user password #425 </strike>
- CZ - Add cancellation scenario to R&C #432. In Testing Phase. Should be completed W22.
- <strike> PL - Update policy #412 </strike>
- <strike>[IN PROGRESS] FE: AaaS configure validation for LeasingDetails #434 </strike>
- <strike>[IN PROGRESS] FE: AaaS apply translations handling #435 </strike>
- <strike> [IN PROGRESS]  DE - Ops ticket (w20) #409. </strike>
- [IN PROGRESS] SE: generate the excel invoice for Skatteverket #391. In Testing Phase. Should be completed W22.
- <strike> [IN PROGRESS] Test: Paypal Activation #162. First round of successful tests completed. Plan to run one round of additional tests mid-this week before closing the ticket. </strike>

**AD-HOC TICKETS:**
We had 3 ad-hoc tickets, which were added during the week, and were not a part of the planned sprint:

- <strike>  IT - Claim Update does not reflect in CCT Backoffice or in transaction report #423 </strike>
- <strike> QuickSight: align reports to reflect the latest price changes #443 </strike>
- (IN REVIEW) SE: SAP invoicing flows to map by action #267



# Sprint 20 Review

**EPICS:**
- [IN PROGRESS]  Preparing for the release in production env. planned on May 25.

[IN PROGRESS] UK - Book-a-service project, covering the following tickets
- UK BaS define dedicated endpoints to create Orders by C4C data #417. Opened a PR; needs a review. 
- UK BaS - checkout page #416. Waiting for endpoints from the BE team.

**Ops Tasks to be covered this week:DE - Ops ticket (w20) #409**
- <strike> CZ - Cancel contract #413 </strike>
- <strike> FR - cancel contracts (updated) #397 </strike>
- <strike> IT: Cancel the order 61969 #407 </strike>
- <strike>[IN PROGRESS] UK: Service Material Handling #403. Task is completed, needs to be reviewed and released.</strike>
- <strike>[IN PROGRESS] [ FE: Configure BO to support new C4C countries #396.</strike>

- <strike> [IN PROGRESS]  FE: new temp UI for internal AaaS #350. It is an on-going project & will take several weeks to complete.</strike>
- [IN PROGRESS] SE: generate the excel invoice for Skatteverket #391. Backend implementation is complete, just need to determine correct values in few of the fields in the excel invoice. Awaiting for a response from SE team regarding those fields.
- [IN PROGRESS] Test: Paypal Activation #162. First round of successful tests completed. Plan to run one round of additional tests mid-this week before closing the ticket.Didn't have time to pick it up in W20.
- [IN PROGRESS] Better Tracking of Payment Failures (Phase 1 of Resillient Schedulling) #81





# Sprint 19 Review

EPICS:

[IN PROGRESS]  Preparing for the release in production env for the following tickets:
- Pricing Service - apply the price logic to each service #381
- Product Offering Model refactoring to handle IW Price switch #355FE: Price handling #392Ops 
 
Tasks to be covered this week:
- <strike> DE: Invoicing Issues with Dates #404 </strike>
- <strike> HU - Update T&C and pricing for FPR by morning May 12th #399 </strike>
- <strike> PL - Outbound list extract #400 </strike>
- <strike> PL: Update policy 54052 #401 </strike>
- [IN PROGRESS] UK: Service Material Handling #403. Task is completed. Testing is pending before the final release.
- [ON HOLD] SE: generate the excel invoice for Skatteverket #391. Backend implementation is complete, just need to determine correct values in few of the fields in the excel invoice. Awaiting for a response from SE team regarding those fields.
- [IN PROGRESS] FE: Configure BO to support new C4C countries #396. Final configurations left to implement this week. Will require half a day for Tommy.
- [ON HOLD] Operational DE - pending actions #334  @Liang Hiah, to get back to us on the missing info for order # 54140.
- <strike> [IN PROGRESS] DE Consumer paid 2x for initial payment using SEPA #375. </strike>
- [IN PROGRESS]  FE: new temp UI for internal AaaS #350 
 
If we have time, we will pick up on:
- [IN PROGRESS] Test: Paypal Activation #162. First round of successful tests completed. Plan to run one round of additional tests, after IT Demo, before closing the ticket.
- [IN PROGRESS] Better Tracking of Payment Failures (Phase 1 of Resillient Schedulling) #81



# Sprint 18 Review

**EPICS:**

-[IN PROGRESS]  IT: continue with the price differentiation setup for IW & OOW development:
- <strike> Internal demo scheduled this week. External demo on May 6. </strike> _Successfully completed. Next step: release all changes in the production environment._
 
**Ops Tasks:**
- <strike> PL - Update policy 71660 #393PL: Issue with the agent IDs #359 </strike>
- <strike>  PL: Issue with the agent IDs #359 </strike>
- <strike> IT: Move from "terminated" to "failed payments" #382 </strike>
- <strike> Ingress and infra #365 </strike>
- [ON HOLD] SE: generate the excel invoice for Skatteverket #391. _Backend implementation is complete, just need to determine correct values in few of the fields in he excel invoice_._Waiting for a response from SE team regarding those fields._
- [IN PROGRESS] FE: Configure BO to support new C4C countries #396. _Almost completed. Final configurations left to implement this week. Will require half a day for Tommy._
- [ON HOLD] Operational DE - pending actions #334  @Liang Hiah, to get back to us on the missing info for order # 54140.
- [IN PROGRESS] [DE] Consumer paid 2x for initial payment using SEPA #375. _The issue with this consumer is resolved, however, the bug is still being investigated_.
- [IN PROGRESS] Test: Paypal Activation #162. _First round of successful tests completed. Plan to run one round of additional tests, after IT Demo, before closing the ticket._
- [IN PROGRESS]  FE: new temp UI for internal AaaS #350 [IN PROGRESS] Better Tracking of Payment Failures (Phase 1 of Resillient Schedulling) #81




# Sprint 17 Review

**EPICS:**
- [IN PROGRESS] IT: continue with the price differentiation setup for IW & OOW development. Internal demo scheduled this week. External demo on May 6.
- [ON HOLD] HU IW: awaiting price update + new T&Cs. 
- [ON HOLD] PL kick-off: Still awaiting green-light from PL to kick-off the project. 
- [IN REVIEW] CZ IW: requirements received and to be reviewed by the product + Daniele on Wed, April 28. @Peter Nordenstedt I'll get back to you straight after. _Reviewed the development and estimated time needed for delivery to @Peter._

**Ops Tasks:**
- [ON HOLD] Operational DE - pending actions #334  @Liang Hiah, to get back to us on the missing info for order # 54140.
-  <strike> DE Operational Fixes (many fixes) #369. To be completed this week. </strike>
- [IN PROGRESS] [DE] Consumer paid 2x for initial payment using SEPA #375. _The issue with this consumer is resolved, however, the bug is still being investigated._
- [IN PROGRESS] Test: Paypal Activation #162. First round of tests completd._ Need to run one round of additional tests before closing the ticket._
- <strike> [IN PROGRESS] IT: Chargeback list of cases with a claim reported #372 </strike>
- <strike> ConCent: NO, FI, ES + PT Create staging environment for testing #376 </strike>
- <strike> ConCent ES+PT: set up the offer in staging environment #378 </strike>
- <strike> ConCent: NO + FI: set up the offering in staging environment identical to IT #374 </strike>
- <strike> AaaS FE: batch features #388 </strike>
- [IN PROGRESS]  FE: new temp UI for internal AaaS #350 
- [IN PROGRESS] Better Tracking of Payment Failures (Phase 1 of Resillient Schedulling) #81




# Sprint 16 Review

**EPICS Tasks:**
- [IN PROGRESS]IT: continue with the price differentiation setup for IW & OOW development. 
- [ON HOLD] HU IW: awaiting price update + new T&Cs. 
- [ON HOLD] PL kick-off: given the latest discovery about dotpay not supporting recurring payments, we are waiting for the green-light from PL to kick-off the project. 

__**Ops Tasks to be covered this week:**__
- [IN PROGRESS]Test: Paypal Activation #162. We need to clarify a few open ponts with Adyen; potentially, we might have some development to plan for.
- [ON HOLD] Operational DE - pending actions #334  @Liang Hiah, please provide the claim info missing for us to close the ticket. 
- [NEW, IN PROGRESS] [DE] Consumer paid 2x for initial payment using SEPA #375
- [NEW, IN PROGRESS] Better Tracking of Payment Failures (Phase 1 of Resillient Schedulling) #81
- [IN PROGRESS]DE Operational Fixes (many fixes) #369, to be completed this week
- <strike>  HU - Operational Update T&Cs for FPR #368 </strike>
- <strike>  IT: Chargeback list of cases with a claim reported #372 </strike>
- [DEPRIORITIZED]Ingress and infra #365
- [IN PROGRESS]  FE: new temp UI for internal AaaS #350 







# Sprint 15 Review

**EPICS Tasks:**
- [IN PROGRESS]IT: continue with the price differentiation setup for IW & OOW development. Internal demo scheduled for April 27, 2021.
- [ON HOLD] HU IW: awaiting price update + new T&Cs. @Peter Nordenstedt if you receive the info. during the week, create a ticket, ping me & we can pick it up this week.
- [ON HOLD] PL kick-off: given the latest discovery about dotpay not supporting recurring payments, we are waiting for the green-light from PL to kick-off the project. @Peter Nordenstedt, if you get the approval this week, create tickets, ping me & we might be able to pick up some tickets this week as well.

__**Ops Tasks to be covered this week:**__
- [IN PROGRESS]Test: Paypal Activation #162
- <strike> [[DE - Operational Fixes #363] </strike>
- <strike> PL: Update PNC # for Order 68027 to 916098218. #364 </strike>
- <strike> [FR] : Review Claims Submitted #361 </strike>
- <strike> [FR] : UpdateContract web-service is not called #362 </strike>
- <strike> FE: Skatteverket json approval ingester #366 </strike>
- <strike> (SE?) SendGrid templates not updating every hour #271 </strike> Note: needs to be released in prod.
- [DEPRIORITIZED, PLANNED W16]Ingress and infra #365
- [IN PROGRESS] FE: new temp UI for internal AaaS #350
