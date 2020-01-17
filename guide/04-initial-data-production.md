---
layout: page_with_sidebar
permalink: /guide/initial-data-production
title: Initial data production & data checking
subtitle: 
nextpage: /guide/planning-for-cut-over
previouspage: /guide/pre-migration-tasks
breadcrumbparent: /guide
---

## What is the initial data production?

The initial data production is the point at which a copy of the existing clinical solution data is provided to the new supplier, who import it into a test solution. 

The initial data production activity enables [data checking](#data-checking) to begin - the practice to perform data checking tasks in the test solution to make sure that the imported Patient data matches how it was when it was taken from the existing solution and the test solution is working as expected.


## Who is involved in the initial data production & data checking?

* The existing supplier (source)  - who provide the data extract from the existing solution
* The new supplier (target) - who import the data into a test solution and visit the practice help them prepare for the data checking phase
* The practice staff - who test the data and in the test solution
* The GP IT delivery partner (such as a Commissioning Support Unit) - who support the practice and work with the suppliers (the level of support available can vary by region)



## Setup access to the new solution

As part of the initial data production phase, the practice should be given access to the new solution. The new supplier (target) will setup admin users (usually up to three).

The new supplier (target) or GP IT delivery partner (such as a Commissioning Support Unit) should provide basic training on the new solution including how to login, change passwords and how to change the access rights for users.

{%- capture lesson_learnt_1 -%}
__Lesson learnt__ - try to make sure that more than one member of staff attend the basic training and are set up with access as the practice may be called upon by the new supplier (target) to log into the new solution and perform basic checks at later phases or reset passwords. Failing to do this has been known to cause delays to migration timelines.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_1 accessibility_text="Lesson learnt" markdown=true -%}


## Data checking {#data-checking}

### Preparation

The following activities should have been completed in advance…

* The [data extract has been requested from the existing supplier in advance](/prm-practice-migration/guide/get-started#request-data-extract))
* The practice has identified the patient records matching criteria provided by the new supplier (target) for testing ([see Pre-migration tasks](/prm-practice-migration/guide/pre-migration-tasks#data-checking-prep))
* Rooms have been booked for initial data production meetings, training and data checking activities

### Data checking phases

Data checking generally happens in 2-3 phases:

1. Initial data checking and reporting of any issues
2. Rechecking the data after the new supplier (target) has amended any issues found
3. In some circumstances a third phase is required if further issues were found in the recheck, however, most migrations do not require this further recheck of the data.

* * * 
**_SLA:_** To make sure that any errors are fixed promptly, you must inform your new supplier (target) of any initial data check issues within 5 working days.<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 14)</em>
* * *
<!-- [UPLIFT] added approximate reference to the Step 9 SLA from Ancillary Document p. 14 -->

### Timeline for data checking

All parties should agree on a timeline and target date for when the data checking tasks will be completed.

We advise you to plan for between 3-5 days for each data checking phase. However, the rechecking phases may not take as long as the initial data checking.

Clinical input will be required and the level of input may vary per practice. Please bear in mind that the Lead clinician will be responsible for signing off the data checking phase.

The new supplier (target) should assist the practice on the first day of Phase 1 Initial data checking. 

{%- capture lesson_learnt_2 -%}
__Lesson learnt__ - You will need to block out time and dedicated staff to complete the data checking activity as any delays in completing this phase will impact the Go Live date.{%- endcapture -%}

{%- include inset.html content=lesson_learnt_2 accessibility_text="Lesson learnt" markdown=true -%}

{%- capture lesson_learnt_3 -%}
__Lesson learnt__ - If possible, try to arrange access to additional support from the new supplier (target) or the GP IT delivery partner to answer any questions and remove any uncertainty that could block or delay the data checking phase.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_3 accessibility_text="Lesson learnt" markdown=true -%}


## What to test

The new supplier (target) should provide a complete list of data checking activities.

The majority of testing will be focused on the identified patient records matching the criteria supplied by the new supplier (target) along with the random patients.

Alongside checking the identified patient records, the practice will be asked to check and compare reports such as QOF reports and indicator points, cytology and immunisation target reports, capitation figures and remapping local codes.

The data checking is a manual process; ideally, the practice staff will complete the activity with the use of two monitors side-by-side, one displaying the existing solution and the other displaying the test version of the new solution. Staff will cross-reference the two to check their consistency.


### Reporting issues with data {#reporting-issues-with-data}

We recommend that issues are logged and reported to the new supplier (target) as soon as they are found.

Each new supplier (target) will have a set method of how they would like the issues to be reported. The Supplier should provide you with this information before or at the start of the initial data checking day.

At the end of each data checking phase, there will be a period whereby the new supplier (target) will review and address the issues found, this may vary depending on the complexity of the issues reported.

The new supplier (target) will notify the practice when the issues have been fixed and the practice will then need to check the issue.


## Signing off the data checking {#signing-off-the-data-checking}

Once all issues have been addressed and all data checking tasks have been rechecked, the practice will be asked to ‘Sign off’ that the data is accurate and the practice is satisfied with the quality of the data.

Before signing off the data, the practice should ensure that they understand the impact of any data that cannot be migrated in terms of how they will manage it and the volume of work involved.
<!-- [UPLIFT] added this second last sentence based on user feedback -->

The CCG may ask the practice to sign a document to this effect.
<!-- [UPLIFT] added this last sentence based on user feedback -->
