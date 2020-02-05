---
layout: default
title: Management Under Controlled Scheme
nav_order: xx
has_children: false
---

This model was last updated on **04/02/2020**, this is version **0.1**

Experimental {: .label .label-yellow }

##### Model created
04/02/2020

## Description

Management under a control Scheme is the process of managing relationships, and activities between establishments and competent authorities within the Food and Feed sector.

### Related entities
Most activities are categorised as part of the `scheme` they belong to.

Management under a controlled scheme most frequently happen at an `establishment`.

 Management under a controlled scheme may have many `activities`.

Management under a controlled scheme is managed by one or multiple `Competent Authority`.

 Under Management under a controlled scheme `Interventions` may be sought by the relevent `Competent Authority`.

Under Management under a controlled scheme `Enforcement` action may be sought by the relevent `Competent Authority`.

Some activities will be entities in their own right.  For example, inspections are an activity, and there are key properties that are the same across all inspections, but there are also many different types of inspection which have their own unique properties, i.e., an inspection under the food hygiene ratings scheme looks for different things than one within the scope of meat hygiene but both are carried out at a premises which has an address

## Unique Identifiers
Where possible, lists of activities should be modelled as registers within the scope of a scheme and a code list created. The unique identifier should be the URI of the registry entry.

## What it is not
An activity is not a scheme but a scheme can have multiple activities.

## Synonyms
*   

## Key Properties
*   The Unique identifier (UID) that identifies the activity.
*   Links to the appropriate official controls where appropriate.

It is important to recognise that, ownership and administration of activities can span different competent authorities. See further information for examples.  

## Reference data
*   [activities register](https://data.food.gov.uk/codes/organisation/_activities)

## Further Information
