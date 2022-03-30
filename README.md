[![Build Status](https://travis-ci.org/eliostvs/clean-architecture-delivery-example.svg?branch=master)](https://travis-ci.org/eliostvs/clean-architecture-delivery-example)

## Docs:
- https://sarada-sastri.medium.com/software-architecture-principles-practices-styles-a0263aa11530
-  https://developer.ibm.com/articles/eda-and-microservices-architecture-best-practices/

# Clean Architecture Example

[![Clean Architecture](https://github.com/sanogotech/clean-architecture-delivery-example/blob/master/docs/clean-architecture-svg.png)](https://github.com/sanogotech/clean-architecture-delivery-example/blob/master/docs/clean-architecture-svg.png)


[![Clean Architecture Base](https://github.com/sanogotech/clean-architecture-delivery-example/blob/master/docs/CleanArchitectureBase.jpg)](https://github.com/sanogotech/clean-architecture-delivery-example/blob/master/docs/CleanArchitectureBase.jpg)

[![Flow Architecture](https://github.com/sanogotech/clean-architecture-delivery-example/blob/master/docs/simplearchiflow.png)](https://github.com/sanogotech/clean-architecture-delivery-example/blob/master/docs/simplearchiflow.png)



[![Clean Architecture](https://github.com/sanogotech/clean-architecture-delivery-example/blob/master/docs/PackagingCleanArchitecture.png)](https://github.com/sanogotech/clean-architecture-delivery-example/blob/master/docs/PackagingCleanArchitecture.png)



## Description

The architecture of the project follows the principles of Clean Architecture. It is a simple food delivery app. One can list stores, cousines, products and create food orders. JWT it is used for authentication.

## Running

`./gradlew bootRun`

## Architecture

The project consists of 3 packages: *core*, *data* and *presenter*.

### *core* package

This module contains the domain entities and use cases.
This module contains the business rules that are essential for our application.
In this module, gateways for the repositories are also being defined.
There are no dependencies to frameworks and/or libraries and could be extracted to its own module.

### *data* package

### *presenter* package

## Diagram

Here is a flow diagram of the payment of an order.

![c4 component](./docs/c4-component.png)
