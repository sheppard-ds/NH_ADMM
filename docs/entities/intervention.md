---
layout: default
title: Intervention
nav_order: 5
has_children: false
parent: Entities
categories: entity
---
# Intervention

This model was last updated on **25/02/2020**, this is version **0.2**

Experimental
{: .label .label-yellow }

### Model created
10/02/2020

## Description
An `intervention` is used by a `Competent Authority` to monitor and record the compliance of an establishments within a `scheme`.

Often, the available interventions under the scope of a scheme will be laid out in the legislation or policy documentation.

Some examples of interventions include;
*   Sampling visits
*   Inspections and audits
*   Verification and surveillance
*   Advice and education visits
*   Information/intelligence gathering

As types of intervention are frequently common across schemes, i.e., an inspection, therefore it is important to try to use a common list of interventions and also record the scheme under which they were taken.

### Related entities
Interventions form part of a `scheme`.

An intervention happens to an `establishment`, `premises`, `operator` or a `person` depending on the specific intervention action.

### Synonyms
*   Audit
*   Sampling
*   Inspections
*   Surveillance
*   Educational visits

### What it is not
An Intervention is not an `enforcement` although like an `enforcement` it forms part of the regulation of a scheme.  Neither is it an `activity`, but all are associated with a `scheme`.

## Properties, identifiers and reference data

## Key Properties
*   The URI of the registry entry for the intervention action
*   Name of the intervention

## Contextual Property
When applying Intervention actions it is important to record the following;

The name of the `establishment` the intervention was applied to. This will help build up a picture of how the `establishment` is performing and help schedule future interventions and possibly impact on possible `enforcements`.

By recording the `Reason` for the Intervention along with the `Competent Authority` that carried out the intervention will help build the picture and ascertain trends and allow Competent Authorities to focus on area's for further `interventions`, or build a case for  `enforcement` action.

The name of the `Competent Authority` that implemented the enforcement, because the establishment may have intervention action taken by multiple `competent authorities` for the same `reason` and or same period.  It also gives other Competent Authorities a place to go to for further information for future interventions and enforcements.

It is important that the `start-date` of the enforcement is recorded as it can determine `end-date` of an enforcement action. It can also help identify cases of production during a period of time when the business shouldn't have been operating, and by having start and end dates of enforcement actions makes the task of identifying produce processed within these dates easier.

A history of `interventions` and enforcements occurring within an `Establishment` will help build a picture and could impact on the severity of future enforcements by looking at the `establishments` history and looking for trends.

### Unique Identifiers
Where possible, lists of interactions should be modelled as registers within the scope of a scheme and a code list created. The unique identifier should be the URI of the registry entry.

### Reference data
[Intervention Type](https://data.food.gov.uk/codes/enforcement-monitoring/_intervention-type)
