---
layout: default
title: Test
nav_order: 12
has_children: false
parent: Entities
categories: entity
---

# Test
This model was last updated on **08/03/2021**, this is version **0.1**

Draft
{: .label .label-red }

### Model created
01/02/2021

## Description
In the UK, official feed and food tests are carried out from [samples](sample.html) taken by certified professionals and processed at [approved laboratories](laboratory.html) using a method or technique that may be outlined in the appropriate legislation or [scheme](/enterprise-data-models/entities/scheme.html). The test result provides information on a specific food risk in a specific commodity.  

There are also some tests carried out by other competent authorities such as DEFRA and DEARA. These are done on live animals or crops, or within the harvest area i.e. soil or water before harvest, and can also determine if a commodity can enter the food or feed market.

Residual risk is the remaining risk after your control measures are in place. It is not possible to eliminate all the risks.  There will always be some level of residual risk, but it should be as low as reasonably possible. Some risks will remain at a certain level, and this is what residual risks are.  In instances like this there is a recommended Minimum Residual Level (MRL).  As long as the test results fall within the MRL then the risk being tested for in the commodity are deemed safe to enter the food/feed chain.  Please note, not all areas have a legal limit, therefore it is product dependent.

Testing for official controls will meet appropriate standards (accreditation and are validated).

There are three basic standards for 'quality of test'
-   Inter-lab validated
-   Single-lab validated
-   Not validated

Tests are often classified as being formal or informal, and it should be the scheme and activity under which the sample was taken that indiccates this.

### Related entities
A [sample](enterprise-data-models/entities/sample.html) is the subject of a test.
Tests are carried out by a [Laboratory](enterprise-data-models/entities/laboratory.html), which in data modelling terms, are a sub-class of [Service Delivery Organisation](/enterprise-data-models/entities/service-delivery-organisation.html).
Tests are often carried out as part of a [survey](), which we consider to be a sub-class of [scheme](/enterprise-data-models/entities/scheme.html)

### Entity relationship diagram
![test](/enterprise-data-models/entities/diagrams/test.png)

### Synonyms
*   A test can sometimes be referred to as analysis

### What it is not
Not all tests are used for testing of food safety interventions or investigations. Some businesses will initiate their own testing regime for various reasons that could include quality control.

## Properties, identifiers and reference data

### Key Properties
*   The sample reference is the unique identifier of the sample that was tested, but this can often vary across applications and services that hadle sample data  
*   The test reference is the reference number of the to identify the tests, which can often vary across applications and services  
*   The risk or hazard being tested for
*   The result, which is not always a simple pass or fail  
*   The method used to test the sample  
*   The accuracy of result, to what level is the result accurate  

### Contextual Properties
*   The minimum residual level is a contextual property as it is not always present
*   Any additional report or the opinion of the analyst, which is most useful when there are no minimum legal levels  

### Unique Identifiers
There are sample and test identifiers but they are not in a standard format or form part of a standardised taxonomy.

## External sources and further reading
