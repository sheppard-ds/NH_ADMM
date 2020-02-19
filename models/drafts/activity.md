---
layout: default
title: Activity
nav_order: xx
has_children: false
---

This model was last updated on **04/02/2020**, this is version **0.2**

Experimental
{: .label .label-yellow }

##### Model created
07/01/2020

## Description
An activity is an action or power granted to food or feed businesses through registration, approval or compliance with specific regulatory `schemes`.

Some examples of activities include;

*   The list of activities which fall under the legislation of [approved food establishments](https://data.food.gov.uk/codes/organisation/_activities)
*   The list of activities which fall under the regulations for [animal feed](https://data.food.gov.uk/codes/business/animal-feed-establishments/_feed-activities)

### Related entities
All activities belong to a `scheme`, but a `scheme` is not a parent entity as they do not necessarily share a set of key properties.

Activities should be joined to `establishments`, not `premises`.

An `establishment` which undertakes activities does so under a `scheme` which grants them approval to do them or registers them as doing them. The combination of `establishment` and `scheme` is known as an `enrolment`.

## Unique Identifiers
Where possible, lists of activities should be modelled as registers within the scope of a scheme and a code list created. The unique identifier should be the URI of the registry entry.

## What it is not
An activity is not an action which forms part of the regulatory environment that monitors or enforces compliance within it. Those entities are `enforcement` and `intervention`.

## Synonyms
*   Approved activity
*   Business activity
*   Registered activity

## Key Properties
<<<<<<< HEAD
*   The URI of the registry entry for the activity
*   
*   Links to the appropriate official controls where appropriate
=======
*   The URI of the registry entry for the activity.
*   Links to the official controls where appropriate.
>>>>>>> f5c4efb61fe0fbcf592c34cfeadf42bf763e6f9e

It is important to recognise that, ownership and administration of activities can span different competent authorities. See further information for examples.  

## Reference data
*   [activities register](https://data.food.gov.uk/codes/organisation/_activities)

## Further Information

Enrolments in activities are concurrent and consecutive.  They have a start and end date and cannot be modified. If an establishment is removed from or no longer wishes to carry out a registered business activity, the status will be changed appropriately and an end date will be recorded.  Establishments can request to re-enroll provided they meet the criteria.  New enrollment documentation will be required and a new UID will be generated.  

An example of an activity; A slaughter house would require approvals to slaughter different types of animals.  If that slaughter house then wanted to process the carcasses they would require approval to carry out cutting activity, and if they wanted to have in house cold storage they would require further approval to carry out those activities too.

Examples of Enrolment for official controls include;
*   Approvals including, slaughter, cutting, storage of food produce
*   Registrations
*   Register a Food Business (RaFB)
*   Shellfish Farming and Harvesting
