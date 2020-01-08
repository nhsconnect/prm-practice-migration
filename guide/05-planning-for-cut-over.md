---
layout: page_with_sidebar
permalink: /guide/planning-for-cut-over
title: Planning for cut-over
subtitle: Preparation and activities to reduce the impact of the cut-over & data re-entry
nextpage: /guide/cutover-and-go-live
previouspage: /guide/initial-data-production
breadcrumbparent: /guide
---

## What is the cut-over?

‘Cut-over’ is the period between final data production from the existing solution and the Go Live in the new solution. 


### During the cut-over

* Data entered into the old solution will not be migrated to the new solution. Practices may still enter data but it will not be migrated. The practice will need to keep a record of any data entered into the old solution for manual re-entry after Go Live and when the cutover ends


* The new supplier (target) will import the data into the new solution


* The practice will test and sign off the data



## Planning for the cut-over

During the ‘Planning for the cut-over’ phase, you should gather all the key people who will be involved in your cut-over period to discuss how you are going to run the practice activities during this time. 

The objective is to decide what processes to follow during cut-over to ensure the practice runs smoothly and how you will approach data re-entry (and how to minimise the amount of re-entry needed). 


## General preparation

* [Notify all the 3rd parties](/prm-practice-migration/guide/kick-off#notification-of-3rd-parties-and-links)  and services to switch off links/communications 1-2 days prior to final data production day. As highlighted in the Kick-off and Pre-migration tasks stages
 <!-- [UPLIFT] changed location of hyperlink -->
* Ensure plans are in place for any migration or changes to Subsidiary suppliers, for example DocMan or Apollo Scan for document scanning and management ([see information in Pre-migration planning phase](/prm-practice-migration/guide/pre-migration-tasks#subsidiary-suppliers))

* Export any letter templates and clinical templates to Microsoft Word from the existing solution (source) to be able to import them to the new supplier solution (target) after the go-live date

* Clear down any inboxes and outstanding workflows and all open communication tasks, such as pathology and registration. At the point of the [Final data production day](/prm-practice-migration/guide/cutover-and-go-live#final-data-production), you will want to have zero tasks outstanding 

* Ensure that all users are logged off the existing supplier solution (source) so that the supplier can do the data extraction



## Best practices and tactics for reducing the cut-over impact

### Appointments:  


* Put breather slots in the rotas for the first couple of days post go-live if your clinicians are not familiar with the new supplier solution (target). Ensure that these slots are placed in the existing solution rotas so you will be reminded to configure them in the new solution


* Build rotas on the test solution before the cut-over. Don't put the rotas onto the existing solution for further in advance than two weeks post go live with the new solution as all booked appointments will need to be manually transferred


* If possible reschedule data rich chronic disease clinics so that these are not taking place during the cutover period. 



### Consultations: 
 
* Carry on as normal entering notes in the old solution and manually transfer these to new principal clinical solution (target) as part of the data re-entry process once you have gone live  


* Patient consultations details can be printed off and stored in a folder (separate folder for each day) for re-entry after Go Live


  -- Some practices choose to copy and paste notes from the old solution to the new
  
  -- Some practices choose to retype the notes from the printouts



### Home visits:  

* Keep a record of requested visits so that you know which patients have data that need transferring once you are in the Post Go Live phase  


### Telephone calls to patients

* GPs and nurses need to ensure that all telephone calls to a patient are entered on to the new clinical solution


* Ask them to keep a record of the name of the patient and the date they were called so that the records can be easily found during data re-entry


* In order to negate the risk of missed information, create a rota in the existing supplier solution (source), if possible, so that all the calls made can be logged there.  


### Prescriptions: 

* Within the Electronic Prescribing System (ePS), repeat dispensing prescriptions are issued individually by the prescribing system and signed and sent individually to Spine as required for the patient. There is a dependency on the prescribing system to retain the information after a migration as it needs to continue generating prescription issues for the authorised period.

  -- Any outstanding repeat dispensing issues held on the Spine for a patient will therefore need to be cancelled and re-issued after Go Live. This is also a good time to advise the partner pharmacies in your area so they could also prepare for this.
<!-- [GAP] need to add information re: post-dated scripts. Need to investigate how this works on EPS -->

  -- A report can be run within the practice to identify patients likely to be affected, as this will allow any new or remaining issues to be lined up with cutover. For example a patient who has a six monthly set of issues could have their last issue of six due in the period covering cutover, so they will not need a re-issue of these until after Go Live.
 
* Keep a record of all prescription requests made/issued during the ‘cut-over’ period. Ideally batch all the repeat prescription requests together by date order. If any requests are taken by phone/over the counter/any other method, you will need to make a note of those and add them to the batched information  

* To reduce the amount of effort re-entering prescription data, some practices choose to:  


  -- Issue two prescriptions (either post-dated or by amending the quantity) from the month before the ‘cut-over’ begins until a week after Go-Live. Note: Do not post-date prescriptions sent via Electronic Prescription Service (EPS)


  -- For Electronic Prescription Service (EPS) repeat prescriptions, practices can revert back to issuing FP10 forms from the month before the ‘cut-over’ begins until a week after Go-Live. Changing the option from EPS to FP10 forms needs to happen on an individual patient basis. This can be done at the point of ordering all medications


* With either of these options it is important that patients and pharmacies are informed of this change at the earliest opportunity to avoid any confusion


### Links:

* Recommended cut off periods for Registration and Pathology links will have been advised by the new solution supplier, ensure that you know who will be notifying the services. 

* The backlog of pathology results should be sent electronically once you are live on the new solution but you will need to confirm with your local provider. 


### Referrals: 
 
* If possible, reduce referrals to urgent only cases


* Print an extra copy of any referrals done during cut-over period. These can then be scanned into the new supplier (target) solution when you are live


### Scanning:
  
* Everything that comes in during the cut-over period will need to be scanned into the target solution’s supplier once you are live. You need to make sure that you keep all the incoming letters together


### Screening services:  

* If you have any screening services that send results electronically directly to the clinical system, ask the service to stop sending messages from two days before cut-over starts until after go-live
<!-- [UPLIFT] this section was made more generic so that it could include breast screening, diabetic retinopathy etc -->

### 111 messages/Incoming clinical correspondence:  {#one-one-one-messages}

* Leave all the messages received during the cut-over period in the generic mailbox as they can be picked up from there and dropped into the target solution once you are live


* You may want to print copies for your GPs to view


### Out of hours: {#out-of-hours}  

* The ‘Out of hours’ reports will continue to come into the existing solution (source) during cut-over 
* You will need to keep a copy of each for scanning into the target solution once live


### Summarisation and routine data entry:  {#summarisation}
* Any summarisation and routine data entry during the 'cut-over' period will not be transferred to the new solution and will need to be re-entered post Go live



{%- capture lesson_learnt_2 -%}
For any of the above, you may need to arrange for emergency/urgent activities to be done manually, for example, urgent test results can be posted and the lab notify the practice by phone
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_2 accessibility_text="Lesson learnt" markdown=true -%}


## Additional notes:  

* The exisitng supplier solution (source) maintenance support will continue for 3 months post go-live and you will have access to the solution/data it for this period

* Any patients (other than deceased) deducted before your final data production won't migrate

* We strongly recommend that practices draft in additional support/cover so that there is dedicated people/time for testing and re-entry
