---
layout: default
title: Operator
nav_order: 1
has_children: false
parent: Establishment
grandparent: Entities
categories: entity
---

# Operator
This model was last updated on **X**, this is version **0.x**

Experimental
{: .label .label-yellow }

### Model created
14/02/2020

## Description
At it's simplest, an Operator is the person or legal entity responsible for running a food business. When considered in tandem with `Premises`, the combined entity is an `Establishment`.

The operator can be a `physical person` or a `legal person` and we sometimes use these terms to distinguish between the two. In data terms, these entities should be considered children of Operator, as they have different contextual properties.

As the Operator can be a legal entity, such as a limited company, it is not appropriate for example to use the Operator entity if you were building an inspection service or similar. It can sometimes be necessary to identify a separate `Contact` entity.

### Related entities
`Physical person`, `Legal person` and `Contact` are considered child entities of person.

### Synonyms
-   Food Business Operator
-   Trader

### What it is not
The operator in this context is the entity which is associated with the `Establishment` which is being regulated under a scheme. Frequently operators can be owned by other entities. These entities are not the operator.

## Properties, identifiers and reference data

### Key properties
When registering an establishment, the operator is assigned the registration identifier

### Contextual properties

### Unique identifiers

### Reference data

## External sources and further reading
