---
layout: page_with_sidebar
permalink: /guide
title: Get started
subtitle: How to start your migration to another clinical system
nextpage: /guide/kickoff
---

## Introduction

This guide aims to help Practices, Delivery partners (e.g. Commissioning Support Units) and Commissioning Clinical Groups (CCGs) plan and prepare their migration from one core clinical system to another. 

Approaches to migrating can differ by region. This guide contains a collection of common phases and strategies aimed at reducing the impact to Practice staff and minimising the amount of manual data re-entry which is a common problem when migrating systems.

The guide does not cover everything that may need to happen in your migration but it will cover the key activities and make suggestions on how to act on them. 


## How long does a migration take?

Migrations on average take between 12-16 weeks. This is from the point of registering the intent to migrate in the Tracking Database (detailed on this page) to the end of the Post Go Live activity is complete.


## Overview of key phases

Migrations take a lot of planning and effort from Practice staff, breaking this activity into smaller incremental steps will help ease the pressure and make the migration effort more sustainable.

Here is an overview of the key phases...


| Phase                                                    | Estimated timeline |
|----------------------------------------------------------|--------------------|
| __[Procurement](#ready-to-get-started)__ <br>Securing funding and the notification / agreement with the Target supplier (New) and the Source Supplier (Old) via the [Tracking Database](#register-the-migration-on-the-tracking-database) | 1 to 2 weeks |
| __[Kickoff](/prm-practice-migration/guide/kickoff)__ <br>Gathering all the key people who will be involved in your migration to discuss the end to end process of migrating your system    | 1 day |
| __[Technical survey](/prm-practice-migration/guide/technical-survey)__ <br>Checking the existing hardware and software at the Practice for compatibility | 1 day |
| __[Early preparation and planning](/prm-practice-migration/guide/early-prep-and-planning)__ <br>Critical activities Practices can start doing to get ahead and prepare for the later stages such as cleaning existing data, notifying 3rd Party services and patients | 1 to 2 weeks |
| __[Initial data production (IDP)](/prm-practice-migration/guide/initial-data-production)__ <br>The Initial Data Production is the point at which a copy of the existing clinical system data is provided to the new supplier, who import it into the new system. The Practice then test the new system to make sure that the Patient data is accurate and the new system is working as expected. | 1 day |
| __[Data checking](/prm-practice-migration/guide/initial-data-production#data-checking)__ <br>The Practice test the new system to make sure that the Patient data is accurate and the new system is working as expected. | 3 days to 3 weeks |
| __[Data recheck and sign off](/prm-practice-migration/guide/initial-data-production#data-checking)__ <br>Rechecking the data after the Target Supplier has amended any issues found before signing off that the data is accurate and the Practice is satisfied with the quality of the data | 1 to 5 days |
| __[Cut-over planning and preparation](/prm-practice-migration/guide/planning-for-cut-over)__ <br>Preparation and activities to reduce the impact of the Cut-over & data re-entry | - |
| __[Final data production](/prm-practice-migration/guide/cutover-and-go-live#final-data-production)__ <br> Practice staff cease to use Source system or continue using source system knowing that the data entered will not be migrated. The final data extract is provided to the new supplier, who import it into the new system.| 1 day |
| __[Cut-over period](/prm-practice-migration/guide/cutover-and-go-live)__ <br> Manual processes are put in place whilst the Practice check the data accuracy on the new system and receive training | 3 days to 2 weeks |
| __[Go Live](/prm-practice-migration/guide/cutover-and-go-live#sign-off-go-live-data)__ <br> The point at which the Practice signs off that the data is accurate and starts to use the new system as the primary system | 1 day |
| __[Post Go Live](/prm-practice-migration/guide/post-go-live)__ <br> Practice staff re-enter data for Appointments, Prescriptions etc that took place during the Cut-over period | 5 days to 2 weeks |
| __[End of migration](/prm-practice-migration/guide/end-of-migration)__ <br> The point at which all data has been re-entered, training received and the Practice is comfortably using the new system. Access to the old system has ended and the new system has been officially signed off by the practice| - |



## Ready to get started?

Once the Practice and Clinical Commissioning Group have agreed that the Practice will migrate to a new Clinical System the first step is to agree a Go Live date, register the migration on the Tracking Database and informing both the current and new suppliers of the intended change.


### Agree a provisional Go Live date

A preferred Go Live date needs to be agreed between the Practice and the supporting functions  - usually the Commissioning Support Unit (CSU) and the Clinical Commissioning Group (CCG)


{%- capture lesson_learnt_1 -%}
__Lesson learnt__ - Avoid busy periods such as Flu season, QOF or holiday periods and watch out for any periods with a high volume of staff on training or annual leave.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_1 accessibility_text="Lesson learnt" markdown=true -%}


### Register the migration on the Tracking Database

The initial registration of the migration on the [Tracking Database](https://digital.nhs.uk/services/tracking-database) is usually completed by the Commissioning Support Unit (CSU) however this may differ by region.


#### Procure the new system

* A _Schedule A_ document is completed for the Target Supplier service and is “called off”/logged in the Tracking Database

* The Clinical Commissioning Group (CCG) accepts the _Schedule A_ in the Tracking Database

* The Target Supplier receives the _Schedule A_ notification and accepts it

* The Target Supplier will confirm the availability of the preferred Go live dates


{%- capture lesson_learnt_2 -%}
__Lesson learnt__ - Submodules of the new clinical system may need to be raised in a _Schedule A_, this activity can be missed. E.g. Appointments, Docman
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_2 accessibility_text="Lesson learnt" markdown=true -%}


#### Decommission the existing/old system system

The same process happens for the decommissioning of the Source Supplier, a _Schedule A_ is “called off”/logged in the Tracking Database.


{%- capture lesson_learnt_3 -%}
__Lesson learnt__ - If the _Schedule A_ to decommission the source supplier’s system is not sent at this point the NHS will continue to pay for the service for longer than needed.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_3 accessibility_text="Lesson learnt" markdown=true -%}

Important - At this point, you should think about submitting a [formal data extract request to the Source Supplier](/prm-practice-migration/guide/early-prep-and-planning#request-a-data-extract-from-your-existing-supplier) to avoid any delays to your migration.

The Source Suppliers have varying lead times/notice periods to provide this data upon request (for example, a supplier may require up to 5 weeks notice). 


{%- capture lesson_learnt_4 -%}
__Lesson learnt__ - __Any delays to requesting the data extract may impact the migration timeline__ if it’s not sent well in advance of the [Initial Data Production day](initial-data-production).
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_4 accessibility_text="Lesson learnt" markdown=true -%}
