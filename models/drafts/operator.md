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
This model was last updated on **18/02/2020**, this is version **0.1**

Experimental
{: .label .label-yellow }

### Model created
14/02/2020

## Description
Operator is the person or legal entity responsible for running a food business. When considered in tandem with `Premises`, the combined entity is an `Establishment`.

The operator can be a `physical person` or a `legal person` and we sometimes use these terms to distinguish between the two. In data terms, these entities should be considered children of Operator, as they have different contextual properties.

As the Operator can be a legal entity, such as a limited company, it is not necessarily appropriate to use the Operator entity if you were building an inspection service or similar. It can sometimes be necessary to identify a separate `Contact` entity.

### Related entities
`Physical person` and `legal person` are child entities of operator.

`Contact` is a related to operator as we sometimes need to identify a named person when arranging inspections or other visits to the premises associate with the establishment.

### Synonyms
-   Food Business Operator
-   Trader

### What it is not
The operator in this context is the entity which is associated with the `Establishment` which is being regulated under a scheme. Frequently operators can be owned by other legal entities. These entities are not the operator.

## Properties, identifiers and reference data

### Key properties
When registering an establishment, the operator is assigned the registration identifier, for example, the `approved premises reference number`.

The operator has an `address` and a `contact`.

### Contextual properties
Operators can have a different address to the premises with which they are associated. This is most common when another company owns and runs the business, or when a sole trader lists their home address as the location for correspondence.

### Unique identifiers
When the Operator is a limited company, we should include the `Company Reference Number` from Companies House in order to link to richer sources of data about the company and improve interoperability.

### Reference data

## External sources and further reading
