# Adapter

## Description

An adapter is a behavioral design pattern that works as a bridge between two incompatible interfaces. In simpler terms, it is a translation between two different apis. One example for this is in computer vision there are different ways to store the bounding box of an object in an image (4 corners vs 2 corners and length and width), and an adapter could simply be converting from one format to another for differnet apis.

## Links

[Simple Example](https://levelup.gitconnected.com/design-patterns-in-python-adapter-pattern-a5e53ed2c85d).

__NOTE__: Forgive me on this link, I had trouble finding an example I liked ...

## Takeaways

This pattern is simpler that others covered in this repo but is still very useful. This pattern should be more clear on when it should be used as you will directly run into two incompatible apis and will need a method of reorganizing the information to connect the two. 