---
layout: default
title: Tests
nav_order:
has_children: false
parent: Entities
categories: entity
---

# Premises
This model was last updated on **01/02/2021**, this is version **0.1**

Experimental
{: .label .label-yellow }

### Model created
01/02/2021

## Description
In the UK, official feed and food tests are carried out from [samples](samples.html) taken by certified professionals and processed at [approved laboratories](laboratory.html) using a method/technique that may be outlined in the appropriate legislation or [scheme](/enterprise-data-models/entities/scheme.html).  The test result provides information on a specific food risk in a specific commodity.  

Residual risk

Residual risk is the remaining risk after your control measures are in place. There will always be some level of residual risk, but it should be as low as reasonably possible.  It is not possible to eliminate all the risks.  Some risks will remain at a certain level, and this is what residual risks are.  In instances like this there is a recommended Minimum Residual Level (MRL).  And as long as the test results fall within the MRL then the risk being tested for in the commodity are deemed safe for consumption.  Please note, not all areas have a legal limit, so would be product dependent.

Testing for official controls will meet appropriate standards (Accreditation and validated).

Three basic standards for 'quality of test'
-   Inter lab validated
-   single lab validated
-   not validated

There are two main types of Tests
-   Formal Tests
-   Informal Tests

Examples of formal tests (or link to a register)
Examples of informal tests (or link to a register)

### Related entities
[Test type]() is the type of test that was performed.
[Sample]() is the sample that was tested.
[Sample frequency]() is the frequency of the sample outlined in the relevant Scheme. ***Covered under scheme??***
[Scheme](/enterprise-data-models/entities/scheme.html)

### Synonyms
-   laboratory testing.
-   laboratory tests.
-   laboratory analyses.
-   laboratory examination.
-   laboratory analysis.
-   lab test.
-   lab tests.   


### What it is not
Not all tests are used for testing of food safety interventions or investigations.  Some businesses will initiate their own testing regime for various reasons that could include quality control.

There are also some tests carried out by other competent authorities such as DEFRA and DEARA.

## Properties, identifiers and reference data

***Need to view list of reports to identify commonality***

### Key Properties
**Sample Reference** this is UID of the sample that was tested
**Test Reference** this is the reference number of the to identify the tests
**Risk/hazard tested** what are we looking for in the sample
**Result** What are the results of the test
**Laboratory** this is where the test took place ***Don't think this is key can be found by test reference***
**Product tested** the name of the product tested ***Don't think this is key as will relate to sample reference***
**Method used** what method was used to test the sample ***Don't think this is key***
**Accuracy of result** to what level is the result accurate ***Don't think this is key to all tests as standards***


### Contextual Properties

Each set of test results will be linked back to the sample the test was taken from.  It is important that this is recorded incase any follow up action is required or the results are queried.

Each set of test results will be linked back to the laboratory that carried out the tests.  It is important that this is recorded incase any follow up action is required or the results are queried.

Additional report/ opinion of labs on results. The Opinions of lab especially helps when there are no minimum legal levels.



### Unique Identifiers
Reference number

## External sources and further reading
