# Strategy


## Description

The strategy pattern is similar to the principle of Dependency Inversion but is easier to understand in implementation. The strategy pattern is often an abstract class that defines an api (abstract methods) that must be overridden by any subclass. This ensures that any subclass provides the required functionality while offering different implementations (customizability). This pattern is derived from the open/closed principle (Code should be open to _extension_, closed to _modification_). For clarity, the strategy pattern makes a family of objects through enforcing similar behavior.

## Links
[Here](https://medium.com/nerd-for-tech/strategy-design-pattern-python-896f2d38012d) if a good example of the strategy pattern.

## Takeaways

A quick example for this is implementing a new model that and making it adhere to sklearn's fit and predict methods. This way sklearn can enforce a similar syntax for using any of their models and also allow developers to subclass and _extend_ their models as well. Dependency inversion is a big picture goal, the strategy pattern is one (powerful) method of achieving that goal. 

