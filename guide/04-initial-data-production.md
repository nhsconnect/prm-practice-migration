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

The initial data production is the point at which a copy of the existing clinical system data is provided to the new supplier, who import it into a test system. 

The initial data production activity enables [data checking](#data-checking) to begin - the practice to perform data checking tasks in the test system to make sure that the imported Patient data matches how it was when it was taken from the existing system and the test system is working as expected.


## Who is involved in the initial data production & data checking?

* The existing supplier (source)  - who provide the data extract from the existing system
* The new supplier (target) - who import the data into a test system and visit the practice help them prepare for the data checking phase
* The practice staff - who test the data and in the test system
* The GP IT delivery partner (such as a Commissioning Support Unit) - who support the practice and work with the suppliers (the level of support available can vary by region)



## Setup access to the new system

As part of the initial data production phase, the practice should be given access to the new system. The new supplier (target) will setup admin users (usually up to three).

* * * 
**_SLA:_** The new supplier has two working days following loading of the data to make a test system trial environment available to your users.<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 14)</em></br>
* * *
<!-- [UPLIFT] added reference to the Step 9 SLA from Ancillary Document p. 14. Do we want a specific reference to the Ancillary doc within the guide? -->

The new supplier (target) or GP IT delivery partner (such as a Commissioning Support Unit) should provide basic training on the new system including how to login, change passwords and how to change the access rights for users.

{%- capture lesson_learnt_1 -%}
__Lesson learnt__ - try to make sure that more than one member of staff attend the basic training and are set up with access as the practice may be called upon by the new supplier (target) to log into the new system and perform basic checks at later phases or reset passwords. Failing to do this has been known to cause delays to migration timelines.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_1 accessibility_text="Lesson learnt" markdown=true -%}
<!-- [GAP] Why isn't this 'lesson learnt' showing up correctly? -->


## Data checking {#data-checking}
<!-- [GAP] Why isn't this heading 'Data Checking' showing up correctly? -->
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
**_SLA:_** You have up to five working days to complete the initial data check and report any issues to your new supplier.<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 14)</em></br>
* * *
<!-- [UPLIFT] added reference to the Step 9 SLA from Ancillary Document p. 14 -->

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

The data checking is a manual process; ideally, the practice staff will complete the activity with the use of two monitors side-by-side, one displaying the existing system and the other displaying the test version of the new system. Staff will cross-reference the two to check their consistency.


### Reporting issues with data {#reporting-issues-with-data}

We recommend that issues are logged and reported to the new supplier (target) as soon as they are found.

Each new supplier (target) will have a set method of how they would like the issues to be reported. The Supplier should provide you with this information before or at the start of the initial data checking day.

At the end of each data checking phase, there will be a period whereby the new supplier (target) will review and address the issues found, this may vary depending on the complexity of the issues reported.

* * * 
**_SLA:_** There should not be a need for any more than five separate iterations of data extracts, whether full, partial or deltas. If you find that you need to transform your data more than five times, contact your Chief Clinical Information Officer, who will escalate the issue to NHS.<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 14)</em></br>
* * *
<!-- [UPLIFT] added reference to the Supplier SLA in terms of responding to queries from a Migration Management Agent -->
<!-- [GAP] the Ancillary Document tells practices to escalate to a 'Migration Management Agent' but we don't yet know how practices are expected to contact this 'Agent'. Placeholder text instructs practices to contact their CCIO, who will escalate on their behalf-->

The new supplier (target) will notify the practice when the issues have been fixed and the practice will then need to check the issue.


## Signing off the data checking {#signing-off-the-data-checking}

Once all issues have been addressed and all data checking tasks have been rechecked, the practice will be asked to ‘Sign off’ that the data is accurate and the practice is satisfied with the quality of the data.

* * * 
**_SLA:_** From the time you request data extracts from your old supplier, the whole process of checking and transforming your data should take no longer than six weeks.<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 14)</em></br>
* * *
<!-- [UPLIFT] added reference to last sentence within Steps 7-9 SLA, p. 14 Ancillary Document -->
