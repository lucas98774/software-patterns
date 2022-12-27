# Factory

## Description

The factory pattern looks to define a common interface for defining _related_ objects. The main objective of this is to separate the creation from the usage of the object(s). For instance, imagine creating a type Pet; pets have common attributes (names) regardless of the actual type of pet it is (animal).

## Links

[Here](https://realpython.com/factory-method-python/) is a thorough tutorial on the factory pattern. __NOTE__: I have a preference for realpython tutorials when I find them, they are usually more comprehensive. This tutorial is comprehensive and done well.

## Takeaways

There are many takeaways from the factory as this is a widely used pattern and is very flexible. Here's my current stab:

* Separate usage from creation
* Simplifies complex code structure
* Allows for combining features under common interface, supporting multiple implementations of the same feature, constructing related objects from external data
* Fosters flexibility and generalized code

