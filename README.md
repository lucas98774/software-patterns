# Software Overview

## Purpose

The purpose of this repo is to document software patterns that I have learned so far, found useful/applicable to data science and give links or examples that I have done.

## List of Patterns

I will try to organize these patterns in order of usefulness but this is subject to change. Also there will be a usefulness rating provided as well on the scale from 1 to 5, 1 being very useful, 5 being rarely useful.


Pattern | Type | Usefulness Rating
--- | --- | ---
Dependency Inversion | ? | 1
Strategy | Behavioral | 2
Plugin | Behavioral | 2
Factory | Creation | 2
Builder | Creation | 2
Bridge | Behavioral | 3
Adapter | Behavioral | 4
Command | ? | ?
Facade | ? | ?

### Helpful Videos

To start learning about software design patterns, I started with youtube series and the author did a very good job. I would recommend these videos to anyone interesting in learning about software design. You can find the link to the series [here](https://www.youtube.com/watch?v=qR4-PBLUZNw&list=PLC0nd42SBTaNuP4iB4L6SJlMaHE71FG6N).

## Additional Note

This repo will also link code via submodules in git. If you are not familiar with those read [this](https://git-scm.com/book/en/v2/Git-Tools-Submodules). Submodules essentially allow repos inside of other repos which allow natural partitioning of projects into smaller projects which increases maintainability and organization. This does come with a few more git commands to learn and keeping the submodules straight but I hope is greatly worth it in terms of organization and code separation.

## Getting Started

The steps I am detailing here are laid out in the link on submodules in the previous section but I am detailing this in case anyone wants to get started without reading that yet. __To execute__ any code contained in a submodule, 2 commands must be run (both from that subdirectory) __after__ initially cloning this project:

1. git submodule init: this registers the directory as a submodule on your local config
2. git submodule update: this will actually grab the code




