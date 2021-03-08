---
layout: default
title: Sample
nav_order:
has_children: false
parent: Entities
categories: entity
---

# Sample
This model was last updated on **05/03/2021**, this is version **0.1**

Draft
{: .label .label-red }

### Model created
22/02/2021

## Description
A sample is a physical portion of food or feed that is taken (or offered) to be subjected to a test. It is tested so that an assessment about the presence or absence of a hazard can be made or that certain characteristics or properties of the sample can be shown to be true or false.

A sample is commonly taken by an authorised officer or a regulatory support official, but can also be taken or offered by third-parties.

A sample can often be split into multiple parts to support sampling best practice. It is not uncommon for a sample to be split into three, one part for testing, one part as a control, and one part left with the establishment from which the sample was taken so that they may undertake testing should they wish.

### Related entities
A sample is always taken as part of a scheme. In the sampling domain, this is most commonly called a survey. In our data models we re-use the scheme entity as sampling can most often be thought of as an activity associated with a scheme. This is true even when the sample is given to a competent authority voluntarily, as it can be associated with a voluntary sample under the correct scheme.

A sample is usually (but not always) subjected to a test.

A sample usally (but not always) tested in order to draw a conclusion about the presence or absence of a hazard.

### Entity relationship diagram
![sample](/enterprise-data-models/entities/diagrams/sample.png)

### Synonyms


### What it is not
A sample is not the test, result, or the analysis. Some of the properties of the sample and these characteristics can appear interchangeable in some legacy systems.

## Properties, identifiers and reference data


### Key properties
The particulars of the product being sampled, which include:
*   Labelling information
*   Shelf life properties
*   Ingredients
*   Batch number
*   Country of origin

The sample information should always include details of when and where the sample was taken. It should also include details of why the sample was taken, but this is most often handled by expressing the scheme and activity the sample was taken within.

We should also record the hazard which is being sampled for. This is often also associated with the scheme and activity that the sample was taken for.

### Contextual properties
Some contextual properties most commonly associated with sample data include:

*   Conditions under which the sample was taken (temperature, relative humidity, etc.)
*   Conditions under which the sample should be stored or transported
*   The properties of any comparative sample
*   The point in the food chain at which the sample was taken

### Unique identifiers
There a no unique identifiers which are consistent across all samples, schemes, and tests. The following properties are often used as identifiers for samples, either alone or in combination with other properties.

*   Commodity codes for import
*   Existing legacy food classification taxonomies, like [this example](https://data.food.gov.uk/codes/enforcement-monitoring/sampling/_classifications).

It should be noted that products taken as samples can often be classified entirely using free-text fields.

### Reference data


## External sources and further reading
