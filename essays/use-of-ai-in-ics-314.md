---
layout: essay
type: essay
title: "From Bugs to Breakthroughs: How AI Elevated My ICS 314 Journey"
# All dates must be YYYY-MM-DD format!
date: 2024-12-16
published: true
labels:
  - AI
  - Software Development
---

<div class="text-center">
  <img class="img-fluid" src="../img/difficulty/ai_anime.jpg" 
       style="max-width: 60%; height: auto; box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.4); border-radius: 4px;" 
       alt="AI Anime Image">
</div>
<br>


# What Are Design Patterns?

Imagine you’re hosting a dinner party. You want to create a memorable meal that impresses your guests or triggers a nostalgic childhood experience. Instead of inventing recipes from scratch, you reach for a trusted cookbook filled with tried-and-true dishes. Design patterns in software development are like those recipes, proven solutions crafted over time by experts to address recurring problems in software architecture.

## What Are Design Patterns?

The concept of design patterns was first introduced by architect <a href="https://www.designsystems.com/christopher-alexander-the-father-of-pattern-language/">Christopher Alexander</a> in 1977. He described in his book, <a href="https://arl.human.cornell.edu/linked%20docs/Alexander_A_Pattern_Language.pdf"><i>A Pattern Language</i></a>, patterns as solutions to problems that occur repeatedly, so that the solution could be used “a million times over, without ever doing it the same way twice.” In software, design patterns emerged in the 1990s, championed by the <a href="https://refactoring.guru/design-patterns/history">"Gang of Four"</a> (Erich Gamma, John Vlissides, Ralph Johnson, and Richard Helm) in their seminal book, <a href="http://www.uml.org.cn/c++/pdf/DesignPatterns.pdf"><i>Design Patterns: Elements of Reusable Object-Oriented Software</i></a>. This book incorporates years of trial and error into 23 reusable solutions for common software problems.

At their core, design patterns are templates for solving common challenges in software design. They help bridge the gap between beginner developers and seasoned veterans by breaking down complex problems into reusable solutions. Just as a novice chef benefits from the expertise of a seasoned executive chef when he bakes from a recipe, new developers gain confidence and efficiency by applying patterns that have stood the test of time.



## Learning From the Roofs Above Us

The evolution of design patterns could easily be compared similarly to that of an architectural journey. Just as architects have to consider numerous variables when developing standard roof types tailored to specific climates, such as, flat roofs are better suited for dry climates, and steep angular gables are better suited for heavy snowfall environments. A roof that works well in the Alaskan climate might collapse under Hawaiian heavy rainstorms. Software engineers had to consider numerous variables when they crafted patterns to address recurring challenges. Software patterns must be carefully chosen to fit the problem at hand in order to be effective.



## Patterns in My Code Kitchen

Speaking from experience, design patterns have become indispensable tools when applying them in my own projects. For example, I implemented the <b>Singleton Pattern</b> during a VR project, which is often used to ensure that a single instance of a class exists throughout an application. I employed a singleton to manage global state, which ensured consistency across modules. While it was powerful, the pattern's pitfalls reminded me to use it sparingly.  This is similar when cooking with salt, since using too much can ruin the dish.

Another example is when I used the <b>Observer Pattern</b>, which played a crucial role in event-driven programming. When building a game mechanic, I used this pattern to notify multiple subsystems, such as, sore trackers, animations and sound effects, when a target was hit. The pattern’s flexibility allowed me to separate components, making the system more maintainable and scalable.

Lastly, the use of the <b>Model-View-Controller (MVC) Pattern</b> has been a cornerstone of my web development work. Separating data (model), presentation (view) and logic (controller) simplified collaboration within my team. Some groupmates focused on the front-end development of user interfaces while other groupmates focused on the back-end design that optimized the data models, all organized for a clean modular design.


## The Balancing Act

While design patterns provide immense value, they come with trade-offs. Overusing them can complicate code, just as over-spicing a dish can overwhelm its flavors. Some, like the Singleton, have even been labeled "anti-patterns" when misused. Yet, by understanding their strengths and limitations, developers can avoid common pitfalls and apply them cautiously.


## Closing Thoughts: Patterns as Foundations

Design patterns are more than technical solutions.  They're basically wisdom passed down through generations of developers. They allow us to build on the hard work, successes and failures of others, and help to avoid unnecessary reinvention. Whether you're a novice or a seasoned coder, patterns offer a foundation upon which great software is built.

If you could just consider design patterns as your own cookbook, it will be the best rules to live by the next time you encounter a coding problem. Just pick the recipe that fits the occasion, adapt it to your needs and create something remarkable. After all, every masterpiece, whether it be a meal, a roof or a software system, all begins with a well-crafted design.
