---
layout: essay
type: essay
title: Beating the Curve with Design Patterns
# All dates must be YYYY-MM-DD format!
date: 2022-04-27
labels:
  - Design patterns
---

<img class="ui large image" src="https://th.bing.com/th/id/R.c50da9403e121a2addaab319e9209ee8?rik=heY9M8DgbSlbJA&pid=ImgRaw&r=0">

Have you ever started learning something new and had someone experienced give you tips on how to more effectively complete what you’re trying to accomplish? The person, having gone through the same learning process you are going through at some point in their life, gives you helpful advice that reduces your learning curve. The advice they offer was gained through trial and error on their part, refined, and then shared with you. Essentially, the tip saves you the time of having to undergo the trial and error yourself. In the field of coding, a similar phenomenon can be observed with design patterns.

Design patterns offer a high level reusable strategy for common software design problems. These strategies typically involve interactions between classes or objects and are found by experts in the field through well-tested and proven development models. Through using patterns identified over time, the development process for anyone coding is sped up. Different design patterns are ideas of how to solve different problems, but are not specific implementation guides. One design pattern could have a million different implementations, for example. It is essentially a template. There are three main types of design patterns: creational, structural, and behavioral. 

Creational design patterns involve class instantiation and object creation. The factory method and Singleton are some creational design patterns. In the factory method, objects are created without their underlying logic exposed and additional dependent objects are not created. It is advantageous in that multiple objects from different classes can be returned and it can build additional objects. However, it is more complex than a class constructor to implement. The Singleton design pattern provides a ‘global variable’ in an object-oriented language that does not support global variables. It is easy to implement lazy initialization, but it is not thread-safe and global states are usually not recommended. 

Structural design patterns aim to create larger classes and functionality from the organization of different classes. An adapter pattern is one example. When two interfaces are incompatible but want to form a relationship, an adapter relationship is established between the two of them so that the relationship is possible. 

Behavioral design patterns identify communication patterns between objects. In this pattern, the algorithm, but not the algorithm structure, is modified to change the behavior of the application. Specifically, the source code cannot be modified, so a coder can add new code but not modify the existing code. 

In my coding experience, I have used design patterns in some projects, such as Akamy-Rent. Recently when using Meteor to create web pages, the observer design pattern was utilized to publish and subscribe data. This enabled a subscriber, whom are unknown to publishers, to register and receive notifications from a provider. In my ICS 613 projects, the provider is MongoDB and the notifications are collections. Collections fall under another design pattern, the Singleton, since they share data ‘globally’. Reactive data is another related design pattern. It’s similar to the Observer design pattern and it functions by re-runing code it involves referencing a cursor in a specific collection when a collection is updated. To handle users logging into the application, a front controller design pattern, FlowRouter in the Akamy-Rent application, was utilized. Front controller design patterns are a centralized request handling mechanism and handles any authentication or logging in, then passing the request to the relevant handler. 
