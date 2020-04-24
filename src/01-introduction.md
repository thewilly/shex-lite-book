# Introduction
Why to create a language that allows you to validate data instances? We currently live in a world where we generate huge amounts of data every day and in most cases we need a mechanism to ensure that the data we are generating has specific properties or shape.

In order to solve this problem, the language of Shape Expressions (ShEx) was born and it allows to validate RDF instances against schemas.

So what is ShEx-Lite? ShEx-Lite is still a language, it represents a subset of the complete language and it is fully compatible with original ShEx compiler, but it also adds new functionalities such as automatically generating domain models in different programming languages, automatic schema creation from data in tabular format and a semantic analysis for the schemas.

But for the scope of this project we will focus only on the language and the ability to generate domain models in different programming languages.

The main idea behind this functionality is that anyone with defined schemas to validate instances can automatically obtain the objects that will represent the domain model of the data that they are validating. An example of application, is in the university research management system that is being developed within the framework of the European Hercules project. In this project, ShEx-Lite is the piece in charge of generating the domain model for the data instances of the system, through the schemas / ontology that was previously defined.
