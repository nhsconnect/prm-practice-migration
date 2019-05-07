---
layout: page_with_sidebar
permalink: /guide/pre-migration-tasks
title: Pre-migration tasks
subtitle: Things to start doing to get ahead
nextpage: /guide/initial-data-production
previouspage: /guide/technical-survey
breadcrumbparent: /guide
---

This is the time to start completing the items discussed in the Kick-off.


## Request a data extract from your existing supplier {#request-data-extract}

Ahead of the [Initial data production phase](initial-data-production), a formal data extract request needs to be sent to the Source Supplier (Existing/old supplier of the GP Core System) using the steps detailed below. This is a formal notification from the data owner (the practice) to the supplier for them to provide the current data stored in the current clinical system.

This will also need to be completed for any other supplier who will need to migrate data, for example any document management and scanning systems such as DocMan or anticoagulation management software such as INR Star.

__The request needs to be completed as early as possible__. The Source Suppliers have varying lead times/notice periods to provide this data upon request; for example, a supplier may require up to 5 weeks notice. __Any delays to giving notice may impact the migration timeline__ if it’s not sent prior to the [Initial data production day](initial-data-production).


### Steps to requesting the Data extract

1. A request is made to the Source Supplier to provide a ‘Data extract request form’ or similar. This is usually sent by the Commissioning Support Unit (CSU) but this may differ by region. 
2. The Supplier will send a ‘Data extract request form’ (or similar) directly to the Practice as the Practice is the Controller of the data
3. The Practice completes and returns the form to the Source Supplier along with the dates of when the extract is to be delivered (the Initial data production day)
4. The Source Supplier liaises with the Target Supplier to transfer the data safely and securely.

## Clean up the current system data

The Target supplier (providing the new clinical system) or Commissioning Support Unit (CSU) can advise the Practice on any common/known data issues when migrating to the new system (these may vary from system to system). 

Rectifying the data early and before the [Initial data production phase](initial-data-production) will reduce the amount of work the Practice needs to complete during later phases.


### Tasks include...

* The appropriate management of duplicate, orphaned records or deceased patients which will not migrate to the new system


* Complete an information cleansing exercise to ensure only current letter templates and data entry templates are kept. Note; letter and data entry templates will need to be manually copied over. Completing this exercise will make it easier to identify which templates you need in the new system


* Clearing down the practice inboxes, outstanding workflows and all open communication tasks, for example pathology and registration; as you approach the Initial data production day, you will want to have the least amount of tasks outstanding 



## Data checking preparation {#data-checking-prep}

The Target Supplier will provide a set of test criteria for data checking following the [Initial data production day](initial-data-production). The Practice will be asked to find a series of patient records that match this criteria (usually up to 20 records) and a selection of random records. Usually, the Target Supplier or Commissioning Support Unit (CSU) will assist with the initial selection of records before asking the Practice to complete finding the remaining patient records unaided.

The Practice will need to detail the selected patient records in a document provided by the Target Supplier. The list of selected patient records will need to be available on the [Initial data production day](initial-data-production).


### Is a reconciliation needed?

A reconciliation may be completed between Personal Demographics Service (PDS) through an Additional Service Request (ASR) to force a patient list synchronisation.

{%- capture lesson_learnt_1 -%}
__Recommendation__ The Personal Demographic Service and NHAIS can get out of sync, thus the reconciliation and any outstanding registration for any patient needs to be done before Go Live, otherwise patient information can be lost and it could also cause issues during data migration.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_1 accessibility_text="Lesson learnt" markdown=true -%}


## Notification of 3rd parties and links

Refer back to the list created at the Kick-off of all the supporting/connecting systems and community services that the Clinical system or the practice works with, such as

* Electronic Prescription Service (EPS)

* Pathology and test labs

* Pharmacies

* Subsidiary/Third party software/system suppliers, for example DocMan or Apollo Scan for document scanning and management

__Give notice to them of your system change__. The notice period required will vary, for example, the Electronic Prescription Service may require 5 weeks, whereas another may require 5 days. 

If you use any third party software as part of your clinical system, please be aware that reconfiguration work may be required by them after you have migrated to the new clinical system [Post Go Live](post-go-live).


## Notification of Patients
Start to display posters within the surgery advising of any disruption to services such as the ability to book appointments online and that patients may also be required to re-register on your new online service system (if applicable). 

## Schedule any training

Schedule your training plan and book rooms. [Read more about training](training). 

## Check hardware and software deployment timelines

If the [Technical Survey](technical-survey) identified any additional hardware / software requirements, make sure to check in on the current status.
