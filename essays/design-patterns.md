---
layout: essay
type: essay
title: "JavaScript !== Java"
# All dates must be YYYY-MM-DD format!
date: 2022-12-01
published: true
labels:
  - Design Patterns
  - Development
---

<img width="400px" class="rounded float-start pe-4" src="../img/design-patterns/designpatterns.png">

## Creating something from nothing is hard (WIP)
In our modern world there are many luxuries that we take for granted, but we rarely think about all the trials and tribulations that went into creating new things like the clothes we wear, to the food we eat, even the computer used to write this. If you were to think about actually creating something as common as a T-shirt, you probably wouldn't even know where to start. Fortunately, someone else already figured out how to do it and you can just use their infrastructure to create a custom T-shirt by just giving them a design. This is an example of a Design Pattern, more specifically this design pattern is called a factory. A design pattern is just a common abstract solution to common problems. In the example above, the "factory" design pattern doesn't only work for T-shirts it could work for anything that has a common base with a sprinkling of customization on top.
The T-shirt factory can pump out infinite variations of a T-shirt by changing the design on it, but they all share the fact that they are all T-shirts. 

Now that we know what a design pattern is you might be wondering what other design patterns are out there. There are tons and they vary depending on what you are working on. Some examples of design patterns in web development are like the singleton or observer. More can be found out information about the specifics can be found [here](https://www.patterns.dev/posts/#design-patterns).

## Don't re-invent web development
Creating a website is a significant undertaking. Fortunately, for us modern developers, creating a website has been made infinitely easier thanks to all the previous developers who had to come up with useful design patterns for common problems. An example of a design pattern that I had to use is the singleton design pattern for the database. You don't want more than one database because if you update something one database, the other one won't be updated. The singleton design pattern solves this issue by only allowing one instance of the database.

<img width="300" class="rounded float-start pe-4" src="../img/design-patterns/singleton-comic-1-en.png">

Another example would be the observer. This was done to watch for state changes of an object to update the view.

Previous developers worked hard on developing solutions to common problems, so we might as well take advantage of it and spend our time developing instead of solving problems already that already have an accepted solution.
