<img src="https://v4.loopback.io/img/global/loopback-full-logo-blue.svg">

# Build a store with [LoopBack 4](https://v4.loopback.io/)

A tutorial for building an ecommerce store backend with  [LoopBack 4](https://v4.loopback.io/)
-----
***Get Started***

*I'm a developer using [Node.js](https://nodejs.org) ^8 & [npm](https://www.npmjs.com) ^6*

Then you might want to just get started:

Install the LoopBack 4 CLI
'npm i -g @loopback/cli'

-----
***Learn More***

*What is LoopBack?*

LoopBack [version 4](https://strongloop.com/strongblog/loopback-4-ga) is an easily extended [open-source](https://github.com/strongloop/loopback-next) [Node.js](https://nodejs.org) framework for [rapidly creating API based microservices which can be generated from existing backend data sources](https://loopback.io/doc/en/lb4/Crafting-LoopBack-4.html#background). 

*What is LoopStore?*

[LoopStore](https://github.com/loopstore/loopstore) is public fork on GitHub of (https://github.com/strongloop/loopback4-example-shopping), which was created and is manintained by [Strongloop](https://github.com/strongloop).
[LoopStore](https://github.com/loopstore) is not officially connected with the [Strongloop](https://github.com/strongloop) organisation.

*What is LoopStore Tutorial*

LoopStore Tutorial demonsrates how LoopBack could be used to create an API based backend for a functional ecommerce store, our [LoopStore](https://github.com/loopstore/loopstore). We're going to be selling downloadable Loops of anything, well, Loopy!

We'll be quickly scaffolding the key components of our app using LoopBack's generators, connecting it up to a database and other external services like card payments, adding some authentication and deploying it all to the cloud using free-tier services. We'll be able to manage our Product and Cutomer data using a REST API, provide customers with a ShoppingCart, accept payment for an Order and give the customer authorised access to their downloads once they've paid. 

Of course this is just a tutorial, so to keep it simple we won't be implementing everything you would need to for a proper commercial store.

The real aim of this tutorial is to:

- Introduce [**Key Concepts**](https://loopback.io/doc/en/lb4/Concepts.html) in LoopBack 4

- Provide **How-Tos**: examples of how to acheive certain tasks such as [migrating existing data](https://loopback.io/doc/en/lb4/Database-migrations.html) or [exposing your APIs as GraphQL](https://loopback.io/doc/en/lb4/exposing-graphql-apis.html)

- Examine [**Best Practices**](https://loopback.io/doc/en/lb4/Best-practices.html) for working with LoopBack.

We'll be taking it step-by-step and just covering a few Key Concepts, How-Tos and Best Practices at a time. You can download the code for each tutorial, or jump straight to [the end]()  
