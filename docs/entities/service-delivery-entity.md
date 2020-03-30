---
layout: default
title: Service Delivery Entity
nav_order: 8
has_children: false
parent: Entities
categories: entity
---

# `Service Delivery Entity`
This model was last updated on **30/03/2020**, this is version **0.3**

Experimental
{: .label .label-yellow }

### Model created
08/03/2020

## Description
A Service Delivery Entity is designed to bridge the gap between what is legislatively correct the organisation(s) that deliver official controls or other schemes. It has been created for the purpose of mitigating some of the problems we have representing these entities in services and data when the concept is not formally reocgnised in legislation or policy.

A Service Delivery Entity delivers the functions, or some of the functions of a scheme on behalf of a Competent Authority.

A Service Delivery Entity most often appears as a shared service entity, commonly providing services for one or more Local Authorities. It can only discharge the duties assigned to it by the Competent Authorities that create or sponsor it, within the scope of the scheme(s) it is assigned. Most enforcement action must still be carried out by a recognised Competent Authority, but this is determined by the scheme.

### Related entities
Service Delivery Entities are associated with at least one [Competent Authority](/enterprise-data-models/entities/competent-authority.html), but often two or more.

Service Delivery Entities undertake a range of [interventions](/enterprise-data-models/entities/intervention.html) on behalf of Competent Authorities, these interventions form part of a [scheme](enterprise-data-models/entities/scheme.html).

Service Delivery Entities frequently operate over `Service Delivery Areas` which cover one or more geographic areas associated with Competent Authorities, parts of, or any custom geographic area.

### Entity diagram
![SDP](/enterprise-data-models/entities/diagrams/SDP.png)

### Synonyms
-   Shared service

### What it is not
A Service Delivery Entity is not, and can never be a Competent Authority. The root of a Competent Authority's powers and duties are legislative and/or given by a radioactive spider. No Service Delivery Entity is recognised in legislation, if it were, it would be a Competent Authority.

## Properties, identifiers and reference data

### Key properties
A Service Delivery Entity will be handled in the same way as Competent Authorities within the FSA data ecosystem, with a register on our registry platform.

For this reason the majority of properties can be retrieved and cached by services as they are needed, but we would recommend storing the following as a reference table in legacy service and relational databases;

-   Name of the entity
-   The code (notation) of the entity
-   The full URI of the entity in the registry

### Contextual properties
Any other property of a Service Delivery Entity which is available from the registry can be used in various contexts. The most common properties will be start and end dates for the existence or powers of the Service Delivery Entity, if they are time limited.

### Unique identifiers
The unique identifier for a Service Delivery Entity is the URI of it's registry entry. Though this can be shortened to the notation property when the preceding part of the URI is treated as a namespace.

### Reference data
A register for this entity is currently in development.
