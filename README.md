# This is a documentation for creating a blueprint in facets.

In Facets Folders play a major role in defining a blueprint. The blueprint is collection of building blocks of an product, we call the Intents.

## Intents

Intents are the specification of a job to be achieved by the stakeholder without going into the nitty gritties of implementation. For example defining an autoscaling microservice can be an intent expressed by a developer, or a qa suite to be executed for a service can be another intent by the QA team. Similarly there are a bunch of intents supported by facets. 

Each Intent belongs to a folder. And it has some central specifications and an instances folder, where you can keep adding intents of each type.

## How to read this documentation?

You can get the sense of supported intent by reading the folder name inside which you will find schema files defining all the options available in that intent.

## Schema level configurations
### Filename 
stack.json
### Schema
```
{
"$schema": "https://docs.facets.cloud/schemas/stack.schema",
}
```
