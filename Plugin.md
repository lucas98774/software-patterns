# Plugin

## Description

A plugin is a behavioral design pattern which enforeces the open/close principle: open to _extension_, __closed__ to _modification_. This pattern allows users to adhere to predefined standards to __add__ functionality to an existing procedure. The procedure that (usually) is a standalone program is called the "core" system while the part that the user can add is called the "plugin". An example of this is allowing for a new type of standardization function into a modeling procedure. Where the standardization will occur will not change, but how it is done may can be modified. 


## Links

* [Official Docs](https://packaging.python.org/en/latest/guides/creating-and-discovering-plugins/)
* [Simple Example](https://alysivji.github.io/simple-plugin-system.html)
* [Advanced Example](https://mwax911.medium.com/building-a-plugin-architecture-with-python-7b4ab39ad4fc)

## Takeaways

This is another pattern (behavioral) that focuses on the __connection__ between two steps in a process and allows a user to inject customization into a specific part of the program. This seems to be a very powerful pattern as it allows users that do not have to know about the internals of the core system to customize the system. With this added power, comes additional setup and risk though.