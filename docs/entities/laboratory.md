---
layout: default
title: Laboratory
nav_order: 2
has_children: false
parent: Service Delivery Organisation
grand_parent: Entities
categories: entity
---

# Laboratory
This model was last updated on **15/03/2020**, this is version **0.1**

Draft
{: .label .label-red }

### Model created
10/03/2020

## Description
In the UK, official feed and food laboratories are Public and Agricultural Analyst and Microbiology laboratories (Food Examiners) that undertake work for Local Authorities or undertaking Official Controls in specified areas for the Food Standards Agency (FSA), and Local Authorities.

Official laboratories must employ staff who possess qualifications which are defined by national legislation. In addition, laboratories must have a Public / Agricultural Analyst (formally appointed by a Local Authority) or a qualified Food Examiner in order to be designated as an Official Control Laboratory.

### Related entities
In data modelling terms, a Laboratory is a child of the [Service Delivery Organisation](/enterprise-data-models/entities/service-delivery-organisation.html) entity. It differs from an SDO by virtue of narrower of scope (it only handles interventions rather than activities and enforcements) and some additional contextual properties which are described below.

### Synonyms
*   Lab

### What it is not
A Laboratory is not a [Competent Authority](/enterprise-data-models/entities/competent-authority.html), and does not own or administer schemes in the way the one would (in terms of the FSA's data domain).

Neither is it an [establishment](/enterprise-data-models/entities/establishment.html), even though it has an [operator](/enterprise-data-models/entities/operator.html) and a [premises](/enterprise-data-models/entities/premises.html).

## Properties, identifiers and reference data

### Key Properties
Laboratories tend to not have key properties outside of their name, as the main purpose is to be able to dereference and confirm the existence of the laboratory.

### Contextual Properties
Laboratories are often accredited to carry out test within specific subdomains, and these accreditations should be recorded.

Likewise, they can be accredited to complete tests using certain specific methods.

### Unique Identifiers
FSA approved laboratories have an associated URI in their register.

## External sources and further reading
A list of [FSA Approved Laboratories](http://data.food.gov.uk/codes/controlled-establishments/laboratories/approved-laboratory)

A list of [Laboratory Analyst Types](http://data.food.gov.uk/codes/controlled-establishments/laboratories/analyst-type)
