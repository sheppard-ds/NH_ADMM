---
title: "User Guide"
permalink: /user-guide/
header:
  image: "images/commute.jfif"
toc: true
toc_label: "User Guide Navigation"
toc_icon: "cog"
---
## Introduction

This Repository contains all of the entity models used within the Food Standards agency. The creation of these models is an ongoing and evolutionary process so this repository does not contain a model for every entity used within the FSA.

## Creating the entity model file
When creating an entity model you should start by creating a copy of the [template file](/model/template.md). This file should be named according to the entity to be modeled. i.e. the shellfish entity model should be called shellfish.md

This file should be saved under [/model/draft](/model/draft) should a file already exist by the same name as the one you wish to create then an entity model is already a work in progress for this entity and that one should be updated instead. **There should only be one entity model for each entity** This lack of duplication extends to [/model/current](/model/current) as well as just the draft folder. If you wish to update an existing model in [/model/current](/model/current) then please follow the [updating an existing model instructions](/UpdatingAnExistingModel.md) Once you have made and renamed a copy of the template file please push this to the master branch.

[back to top](#introduction)

### Writing the draft entity model.

Writing the entity model is as simple as filling out the file which you already created. All fields should be filled in when possible and to the best of your abilities. When an entity is already in use in another system it is strongly advised to involve the owners of that system in the creation of the entity model. **All entity models must be submitted as a draft before becoming current.** Please note an entity model is describing the idea of the identity not an example of it.

The information that should be captured under each subheading can be found in the [entitymodel.md](/EntityModel.md) file. Should there be nothing relevant for capture in a field then that heading can be removed from the file. Please ensure that what is written in this file is valid markdown. The [linter](https://atom.io/packages/linter) and [linter-markdown](https://atom.io/packages/linter-markdown) packages for atom can help with this by highlighting any incorrect syntax.

Once the draft entity model has been created it should be pushed to the master branch within this repository. This can be done directly in the case of a new draft, or via a pull request when updating an existing draft for which you were not the original author.

Entity models in the draft folder can be updated as often as wanted both in terms of meaning and contents.

[back to top](#introduction)

### Moving a draft entity model to current.
Once happy with an existing entity model it needs to move to current in order for it to be usable. This must be done using a pull request following the process bellow. In order for an entity model to be added to current it must have existed in drafts.
1.   Create a new branch named after the entity model. the name should follow the following scheme:

  current + *entity name*. for Shellfish this would look like CurrentShellfish, for start date CurrentStartDate this should be written in [Camel case](https://en.wikipedia.org/wiki/Camel_case)

2.  Copy the entity in question from [/model/draft](/model/draft) to [/model/current](/model/current) do not make any changes to the file. If updates need to be made to the entity model make them in the draft folder before moving them. The pull request to move the entity model to current must also remove it from draft.

3.  Push your branch to origin if this was done locally.

4.  Create a pull request to merge your changes into master adding at least one other member of the data team to the pull request as a reviewer.

5.  Once the pull request has been approved by another member of the data team merge the request and delete the branch.

[back to top](#introduction)

## Update Entity Models

Firstly it is important to note that once an entity model is current we can only change the contents of the entity model file. We can no longer change the meaning of a file. Should we specify that the establishment field refers to a school establishment we cannot update the entity model to instead refer to business establishments. Its meaning is fixed. This is why it is important to get this right the first time. Should you wish to change the name of the entity then the current one would have to be retired to the [/model/retired](/model/retired) folder following the [how to retire an existing model](RetireAnExistingModel.md) instructions and a new model be created.

[back to top](#introduction)

### Current Model

In order to update a current entity model please do as follows:

1.  Create a new branch named after the entity model to be updated. You can only update one entity model per branch. The branch should be named as follows:

    Update + *entity name*. for Shellfish this would look like UpdateShellfish, for start date UpdateStartDate this should be written in [Camel case](https://en.wikipedia.org/wiki/Camel_case)

2.  Update the entity model in question within the branch. As said above you can change the contents of the file but not its meaning. You can also not change the name of the entity model in this way.

3.  Create a pull request to merge the updated model back into master. This pull request must be approved by **more than one** other members of the data team.
4.  Once enough members of the data team have approved the update the pull request should be merged and the branch deleted.

[back to top](#introduction)

### Draft Model
This is not required in order to update a draft entity model as these can be updated on an adhoc basis as they are still Work in progress

[back to top](#introduction)

### Retired Model
A retired model cannot be updated.

[back to top](#introduction)

##Retiring and Entity Model

Retiring a model is an extreme step to take and should only be performed when absolutely neccessary. In order to retire a model the following must all be true:

*   The Model is not in use anywhere within the FSA ecosystem
*   The model is not expected to return anywhere within the FSA ecosystem
*   Retiring the model which would allow a new model to be created with the same name will not cause confusion for our users.

A model should not be retired without unanimous approval within the data team. Should any of the above conditions not be met the data model cannot be retired.

[back to top](#introduction)

### How to retire the model.

In order to retire a current entity model please do as follows:

1.  Create a new branch named after the entity model to be Retired. You can only Retire one entity model per branch. The branch should be named as follows:

    Retire + *entity name*. for Shellfish this would look like RetireShellfish, for start date RetireStartDate this should be written in [Camel case](https://en.wikipedia.org/wiki/Camel_case)

2.  Move the entity model in question within the branch from [/model/current](/model/current) to [/model/retired](/model/retired) if no models have yet been retired this folder will need to be created. Should a model have already been retired by the same name please number the model i.e. shellfish1.md, shellfish2.md etc

3.  Update the model in question to add the following header "Model retired date" and "Model Retired Reason" These should be the first entries within the model and **Must** be populated.

3.  Create a pull request to merge the branch back into master. This pull request must be approved by **more than one** other members of the data team.

4.  Once enough members of the data team have approved the update the pull request should be merged and the branch deleted.

[back to top](#introduction)

## Entity Model template

### Name
What is the thing being modeled.

#### Model creation date
When was this entity model created.

#### Model last update date
When was this model last updated.

### Theme
what are the key themes to this entity.

### Unique Identifiers
What are the unique identifiers and is there a system for their creation/ generation.

### Definition
An establishment is a thing. Here is where we describe it.

### What it is not
It is important to call out what the entity isn't, things it is often confused for.

### Synonyms
Other names by which the entity is known, link out to other implementations if there is documentation for it but be careful here as it might give the wrong impression that synonym versions are okay, they ain't.

### Definition Adopted by
Who within the organisation chose this as the model for the entity, this where you would go to amend the definition not for updates to data using the definition.

### Definition source
The source for the definition of the entity that has been adopted. this could be a link to legislation or another source i.e. <https://www.w3.org/>

### Adoptee Information
Where should I go to talk about this definition.

### Owner
The person or organization that created the definition that has been adopted. This could be either internally within the FSA or a third party organisation i.e. <https://www.w3.org/>

### Source
The source for the definition of the entity that has been adopted. If the entity exist in one system link to docs if there are any.

### Reference data
Links to registers or reference data.

### Key Properties
The properties that would be shared across all implementations of this entity because they are fundamental to it. These can have a little more detail, and where possible should link out to data patterns in our data pattern library.

#### Controlled Vocabularies
This is always recorded in a certain way (i.e. Yes, No, Maybe) for a big Vocabulary you may want to link out or for small Vocabularies you may want to list them here.

#### Contextual Properties
The properties that are most common in specific implementations of the entity, might be best to link out to subclasses if the relationship is that strong i.e. Establishment > Approved Establishment

#### Model created by
Who wrote this entity model.

[back to top](#introduction)
