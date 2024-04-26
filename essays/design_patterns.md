---
layout: essay
type: essay
title: "Coding = Cooking??"
# All dates must be YYYY-MM-DD format!
date: 2024-04-25
published: true
labels:
  - Reflection
  - Design Patterns
  - Javascript
  - React
  - Bootstrap
---

## Coding = Cooking??

So first of all, what are design patterns? Design patterns are a fundamental part of software development, as they provide typical solutions to commonly recurring problems in software design. Rather than providing specific pieces of software, design patterns are merely concepts that can be used to handle recurring themes in an optimized way (<a href="https://www.patterns.dev/vanilla">www.patterns.dev/vanilla</a>).

Here’s an easy way to picture this concept by comparing it to cooking.

1. Recipe (Design Pattern): In a cookbook, a recipe provides step-by-step instructions for preparing a particular dish. Similarly, a design pattern provides a blueprint for solving a specific software design problem.
2. Ingredients (Components): In a recipe, you have a list of ingredients needed to make the dish. In software development, components are the “ingredients” used to implement a design pattern.
3. Cooking Techniques (Pattern Implementation): Recipes often include specific cooking techniques like sautéing, roasting, or something as simple as frying an egg. Similarly, design patterns involve specific techniques and practices for structuring and organizing code to achieve desired outcomes.
4. Variations (Pattern Instances): Just as you can customize a recipe by adding or excluding certain ingredients or adjusting cooking times, design patterns can be tailored to fit the specific requirements of a software project.
5. Cookbook (Pattern Catalog): A cookbook contains a collection of recipes for different dishes. Similarly, a pattern catalog or reference book contains a collection of design patterns for solving various software design problems.
6. Experienced Chef (Experienced Developer): Experienced chefs can adapt recipes to suit their preferences or troubleshoot problems that arise during cooking. Likewise, experienced developers can apply design patterns effectively, modify them as needed, and recognize when to use them in different situations

## Cookin’ up some code myself??

There are a few design patterns that I have used such as factory patterns, flyweight patterns as well as some rendering patterns such as islands architecture. Last semester in my ICS 212 class, for our final project the flyweight patterns were plentiful. Our task was to create a basic library system where we could add books, delete books, search up books and its information, and a function to view all the books in the system. My team and I did not want to create a new book instance each time if there are multiple copies of the exact same book. So we coded a function that searches the database for any matches and if there was a match, the system would output the message, “Book already in database”.

## Cooking up a main dish: ProfTCG

My most current coding final project is for the class ICS 314 Intro to Software Engineering. We get put in a team and assigned a website idea to try to create. My team created some template page mockups that we could follow and have a foundation to code around. We ended up using the rendering pattern: <a href="https://www.patterns.dev/vanilla/islands-architecture">Islands Architecture</a>.
