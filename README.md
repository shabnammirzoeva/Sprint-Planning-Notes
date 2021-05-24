# Sprint 20 Review

**EPICS:**
- [IN PROGRESS]  Preparing for the release in production env. planned on Mayb 25.

UK - Book-a-service project, covering the following tickets
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
- [IN PROGRESS] Test: Paypal Activation #162. First round of successful tests completed. Plan to run one round of additional tests mid-this week before closing the ticket.
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
