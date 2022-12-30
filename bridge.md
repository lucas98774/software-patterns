# Bridge

## Description

The bridge is a structural design pattern that focuses on how objects are related. There is a distinction between how objects are related and how they interact. This pattern is more complicated and abstract compared to others but it easier to grasp with an example: Image the relationship between a pet and its owner. Some of this relationship does not depend on what specific type of pet the owner has, only that the owner has a pet. So the bridge aims to define a relationship between two different family of objects.

## Links

[Good Link](https://medium.com/design-patterns-in-python/bridge-pattern-in-python-e2b7a731423d)

<br>
The link above is good, read the intro it does a nice job of setting up the similarity to the adapter but also detailing what the bridge does better.

## Takeaways

The bridge is an extension to the adapter that, in my eyes, offers a lot more power. A good example for this is the relationship between preprocessors and models. It does not always matter what model or preprocessor one implements, the preprocessor will always come first and feed "cleaned" data to the model. Furthermore, defining interactions for every combination of preprocessor and model would be tedious.

