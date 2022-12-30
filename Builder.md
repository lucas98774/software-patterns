# Builder

## Description

A builder is a creational pattern that assembles complex objects. This pattern, similar to the factory pattern, separates creation from usage for an object. The different is the factory pattern is used for a related set of objects which are simplisitic to build (usually one step) but the builder assembles (often multi-step) an object. A simplified example is a car, to build a car you would need an engine, a frame, wheels, etc and to put them together in a specific order. Another example closer to prgramming is programmatically assembling sql queries, there is some similarity but this would be difficult to do in a single step.

## Links

[Here](https://towardsdatascience.com/3-great-design-patterns-for-data-science-workflows-d3bf162d74e6) is a link for the builder pattern (also includes dependency injection and decorator as well).

## Takeaways

This pattern is almost an extension to the factory pattern but instead of supporting creation of multiple objects, it supports creation of a single (maybe multiple) complex object. This would be useful to join related steps of a process that require flexibility and can be added onto. 

