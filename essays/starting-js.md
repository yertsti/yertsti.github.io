---
layout: essay
type: essay
title: "JavaScript !== Java"
# All dates must be YYYY-MM-DD format!
date: 2022-08-30
published: true
labels:
  - JavaScript
  - Learning
---

<img width="100px" class="rounded float-start pe-4" src="../img/starting-js/JavaScript-logo.png">
## Accidentally Learning JavaScript
My introduction to JavaScript was quite the interesting one. When I was younger I did not have much interest in programming, but I did play a concerning amount of video games, one of which being Minecraft.  I wanted to make a mod for Minecraft, but to do so I first had to figure out what language Minecraft was made from. In my infinite wisdom I thought Minecraft was built from JavaScript because I saw a single JSON (JavaScript Object Notation) file in the Minecraft directory. So, I went on the standard programming self study course of Youtube tutorials and websites like *freecodecamp.com*. Eventually, I thought that I knew enough to creat a mod for Minecraft, but it all came crashing down when it turns out, Minecraft is written in Java not JavaScript. Without wind in my sails, I put down programming for half a decade until I decided to major in Computer Science. The first lanague I learned was Java and now JavaScript

## Whats the Difference?
### The Typing
Even though they both have "Java" in their name, the two langauges are quite different. The most jarring change when I learned JavaScript coming from a Java background  is that JavaScript is not a strongly typed langauge. This means that the data type of a variable can change. The ability for variables to dynamically change throughout the program can be useful, but, in my opinion, it often leads to unforseen bugs that may be hard to find.

### The Syntax
#### Java
```ruby
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello world");
    }
}

```

#### JavaScript
```ruby
console.log("Hello world");
```
Without any knowledge of either language, just looking at a simple program that prints "Hello world" to the console, it is clear that JavaScript's readability is way better than the verbose syntax of Java. This emphasis of readbilty and simplicty is prevelant throughout all of all of JavaScript. This is especially true after the advent of ES6. ES6 added many features like the arrow function that simplifies the creation of functions to a single line or for of loops that easily lets you iterate through an iterable object like an array.

## Which One is Better?
With all that said it seems like JavaScript is the clear winner because it is more readable, the syntax is cleaner and is easier to learn with no programming experience. However, Java does have some advantages. The strictness of Java can help build good programming habits that you might be able to get away with in JavaScript. fortunately, learning Java or JavaScript are not mutually exclusive, so the real question is why not learn both?
