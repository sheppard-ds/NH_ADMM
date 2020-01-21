---
title: "Activity"
date: 2020-01-07
categories:
    - Enrolment
tags:
    - Enrolment  
    - Competent Authority
    - Approval
    - Registration
    - Activity
    - Establishment

excerpt: "In the context of the Food Standards Agency enrolment for an activity is the process of getting permission for an establishment to carry out certain actions."
---
# Activity

This model was last updated on **2020-01-20**, this is version **1.0**

##### Model created
2020-01-07

### Description
In the context of the Food Standards Agency enrolment for an activity is the process of getting permission for an establishment to carry out certain actions.  

### Unique Identifiers
There are a number of identifiers for activity. The preferred unique identifier for in the FSA is the activity number.

The activity Number is made up two parts
1. A numeric field of two digits in the format `00`, this is the number associated with an activity type
2. A numeric field of two digits in the format `00`, this is the number associated with an activity of the activity type

### What it is not
Not all activity numbers are for establishments to carry out an activity.  Some activity codes will be for internal use only.

### Synonyms
*   Activity
*   Activity Number
*   Activity Registration

## Key Properties
*   The Unique identifier (UID) that identifies the activity.
*   Identify to person, business and establishment.
*   Records the activity / scheme being enrolled into
*   Links to the appropriate official controls.

It is important to recognise that, ownership and administration of activities can span different competent authorities. See further information for examples.  

## Reference data
*   [activities register](https://data.food.gov.uk/codes/organisation/_activities)
*   [Establishment Types](https://data.food.gov.uk/codes/business/rafb/_establishment-type) with name, UID and descriptors
*   [establishment](https://data.food.gov.uk/codes/_business)
*   [Competent Authorities register](https://data.food.gov.uk/codes/) WIP

## Further Information

Enrolments in activities are concurrent and consecutive.  They have a start and end date and cannot be modified. If an establishment is removed from or no longer wishes to carry out a registered business activity, the status will be changed appropriately and an end date will be recorded.  Establishments can request to re-enroll provided they meet the criteria.  New enrollment documentation will be required and a new UID will be generated.  

An example of an activity, a slaughter house would require individual approvals to slaughter different types of animals.  If that slaughter house then wanted to process the carcasses they would require cutting approval for those animals and if they wanted to have in house cold storage they would require further approval to carry out those activities too.

Examples of Enrolment for official controls include;
*   Approvals including, slaughter, cutting, storage of food produce
*   Registrations
*   Register a Food Business (RaFB)
*   Shellfish Farming and Harvesting
