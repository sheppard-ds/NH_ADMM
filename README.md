# FSA data Entities and Patterns

This Repository contains the enterprise data models and data patterns designed by the Data Team for use by anyone in the Agency (or outside if you like :+1:)

We've also turned it into a [GitHub pages site](https://foodstandardsagency.github.io/enterprise-data-models/) to make it easier to browse.

These models and patterns are foundational to the architectural principle of data convergence over time. We aim to converge our data across services towards the definitions and entities used throughout the business. We do this by first providing repeatable patterns and templating.

### Data Entities

Data entities model an FSA business concept. They define how the entity exists within the scope of the business, explains the key properties, and gives guidance on implementing that entity in services. Key properties of an entity do not include all of an entities' properties, just those whose absence would make the entity inoperable.

The creation of these models is an ongoing and evolutionary process so this repository does not contain a model for every entity used within the FSA.

You are welcome to take a look at our [template for our entity models](/EntityModel.md).

### Data Patterns

Data patterns are the smallest unit of best practice in the data design system.

They are repeatable patterns for data components which often work at the field level or across multiple fields for elements that work better in that way.

Some of the patterns are industry best practice, put into context for the FSA, some are FSA specific, and some are cross-government or cross-sector and represent our view of working with those data elements within our domain.

Everyone who works on services for the FSA should be aware of the data patterns and use them. By doing this we begin to converge new and legacy services on established patterns which helps to reduce development time and increases data interoperability.
