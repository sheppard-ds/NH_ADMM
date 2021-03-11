---
layout: default
title: Survey
nav_order: 2
has_children: false
parent: Scheme
categories: entity
---

# Survey
This model was last updated on **11/03/2021**, this is version **0.1**

Stable
{: .label .label-green }

### Model created
11/03/2021

## Description
A survey is specific type of [scheme](/enterprise-data-models/entities/scheme.html) within the food and feed sampling domain.

A survey differs from other schemes within our models by virtue of the types of actions that happen within the scope of it.

Schemes may have [activities](/enterprise-data-models/entities/activity.html), [interventions](/enterprise-data-models/entities/intervention.html), or [enforcements](/enterprise-data-models/entities/enforcement.html) within the scope of their context, but surveys only have interventions. In data terms, the actions associated with sampling are all interventions.

A survey has some specific parameters associated with it which may or may not be inherited from the scheme which is it's parent, and some surveys will not have a parent scheme at all, especially if the basis for sampling is more surveillance based than formal sampling. The parameters of a survey are discussion in the key properties section.

### Related entities
A survey has one or more [interventions](/enterprise-data-models/entities/intervention.html) associated with it.

A survey entity is a child of a the scheme entity, which means there is often an association between a scheme and a survey, but it is not mandatory.

### Entity diagram
![survey](/enterprise-data-models/entities/diagrams/survey.png)

### Synonyms


### What it is not
A survey is characterised by being an intervention based scheme, and while some enforcement actions can happen as a result of interventions made within the scope of the survey, they should be associated with the broader scheme, legislative or otherwise, rather than the survey entity.  

## Properties, identifiers and reference data

### Key properties
There are some key properties of surveys which mostly define their scope and context. These include:

*   What is being sampled? This can include specific products or a broader subdomain (e.g. shellfish)  
*   The time period over which the survey is in effect (this might be different to the period in which samples are taken)  
*   The geogrpahic area(s) over which you are taking samples   
*   The hazard(s) being sampled for  
*   Who owns the survey - this can be a a single or multiple competent authorities and it may be useful to call out which part of the organisation owns the survey in some cases  
*   The "scope" of the survey, often expressed as formal, informal, or surveillance

### Contextual properties
In cases where sampling activity is happening in response to a specific incident, then the survey will likely contain additional information about specific batches of a product that will be samples, and the compositional detail of products based on their specification.

## Reference data

## External references and further reading
