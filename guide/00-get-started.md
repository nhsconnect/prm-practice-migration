---
layout: page_with_sidebar
permalink: /guide/get-started
title: Get started
subtitle: How to start your migration to another clinical system
previouspage: /guide
nextpage: /guide/kick-off
---

## The decision to migrate and funding {#decision-to-migrate-and-funding}

This guide offers guidance from the point at which the Clinical Commissioning Group (CCG) has approved the practice’s request to change their principal clinical system and is ready to start the migration process. 

Note: This is subject to the conditions described in the [CCG-Practice Agreement](https://www.england.nhs.uk/publication/terms-governing-the-provision-and-receipt-of-gpsoc-services-and-gp-it-services/)) 

Prior to this, there are a number of steps that will have been completed such as:

* Practice completes a [business justification template](https://www.england.nhs.uk/publication/business-justification-guidance-for-change-of-gp-it-futures-foundation-solution-template/) for a change of GP IT Future foundation solution.

* Clinical Commissioning Group (CCG) and any local boards approve the business case and secure funding. 

  -- _Note: there may be [further costs identified by the Technical Survey](/prm-practice-migration/guide/technical-survey) for replacing hardware_


* Practice and Clinical Commissioning Group (CCG) engage with their GP IT delivery partner (such as a Commissioning Support Unit)


Once the decision to migrate has been confirmed, the next steps are to:


### Agree a provisional Go Live date

A preferred Go Live date needs to be agreed between the Practice and the supporting functions  - usually the Clinical Commissioning Group (CCG) and a GP IT delivery partner (such as a Commissioning Support Unit). 

A proposed go-live date should be agreed between the practice, Clinical Commissioning Group (CCG) and GP IT delivery partner. 

This proposed date should be agreed with the new clinical system supplier.


{%- capture lesson_learnt_1 -%}
__Recommendation__ - Avoid busy periods for your practice and surrounding area and watch out for any periods with a high volume of staff on training or annual leave.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_1 accessibility_text="Lesson learnt" markdown=true -%}


### Register the migration on the Catalogue

The initial registration of the migration on the Catalogue is usually completed by the GP IT delivery partner (such as a Commissioning Support Unit) however this may differ by region.


#### Procure the new system

* Procurement documents are completed for the new supplier (target) and are “called off”/logged in the Catalogue
* The Clinical Commissioning Group (CCG) validates these procurement documents in the Catalogue

* The new supplier (target) is notified that the procurement documents have been submitted and validates them
<!-- need to specify what the target supplier is reviewing and validating if not a Schedule A -->
* The new supplier (target) will confirm the availability of the preferred Go-Live dates


{%- capture lesson_learnt_2 -%}
__Lesson learnt__ - Submodules of the new clinical system may need to be raised within the procurement documents and this activity can be missed. For example, appointments modules, document management, data entry forms.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_2 accessibility_text="Lesson learnt" markdown=true -%}


#### Decommission the existing/old system system

The same process happens for the decommissioning of the existing supplier (source), a _Schedule A_ is “called off”/logged in the Catalogue.


{%- capture lesson_learnt_3 -%}
__Lesson learnt__ - If the document necessary to decommission the existing supplier’s system (source) is not sent at this point the NHS will continue to pay for the service for longer than needed.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_3 accessibility_text="Lesson learnt" markdown=true -%}


### Request a data extract from your existing supplier {#request-data-extract}

A formal data extract request needs to be sent to the existing supplier (source) of the principal clinical system using the [steps detailed below](#steps-to-request-data-extract). This is a formal notification from the practice to the supplier for them to provide the data stored in the current clinical system. The extract will be used in the [Initial data production phase](initial-data-production).

__The request needs to be completed as early as possible__. The suppliers have varying lead times/notice periods to provide this data upon request; for example, a supplier may require up to 5 weeks' notice. __Any delays to giving notice may impact the migration timeline__.

This will also need to be completed for any other supplier who will need to migrate data. For example, any document management and scanning systems such as DocMan or anticoagulation management software such as INR Star.


#### Steps to requesting the data extract {#steps-to-request-data-extract}

1. A request is made to the existing supplier (source) to provide a ‘Data extract request form’ or similar. This is usually sent by the GP IT delivery partner (such as a Commissioning Support Unit) but this may differ by region. 
2. The existing supplier will send a ‘Data extract request form’ (or similar) directly to the practice 
3. The practice completes and returns the form to the existing supplier (source) along with the dates of when the extract is to be delivered as advised by the new supplier (Dates for the [Initial data production phase](initial-data-production)
4. The Source Supplier will ensure that the data is transferred to the new supplier (target) safely and securely.



{%- capture lesson_learnt_4 -%}
__Lesson learnt__ - __Any delays to requesting the data extract may impact the migration timeline__ if it’s not sent well in advance of the [initial data production day](/prm-practice-migration/guide/initial-data-production).
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_4 accessibility_text="Lesson learnt" markdown=true -%}


### Arrange your Kick-off and Technical Survey

Plan and book your [Kick-off meeting](/prm-practice-migration/guide/kick-off) and [Technical Survey](/prm-practice-migration/guide/technical-survey) to happen within a few days of each other.
