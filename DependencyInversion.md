# Dependency Inversion

## Description

Dependecy Inversion is a principle that states that high level abstraction should not rely on concrete implementations. In simpler terms, the high level relationship between objects should not change across different subtypes. An overly simplified example is the relationship between a preprocessor and a model; the preprocessor always comes first cleans data before modeling occurs. 

## Links

[Here](https://www.pythontutorial.net/python-oop/python-dependency-inversion-principle/) is a good example on dependency inversion in python. 

## Takeaways

The main takeaway from this pattern (principle) is more of a focus on __connection__ between steps that should remain the same instead of the objects themselves. This is particularly useful in data science, at least in my personal experience, as this concept is often overlooked and the focus for each project is often a different model. This can lead to a hyper focus on the model itself without any attention on the big picture and how steps interact.

