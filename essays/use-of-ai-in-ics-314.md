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
       style="max-width: 60%; height: auto; box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.5); border-radius: 4px;" 
       alt="AI Anime Image">
</div>
<br>


## I. Introduction

Artificial Intelligence (AI) has emerged as a transformative tool in education, offering innovative ways to tackle complex fields, such as Software Engineering. Within ICS 314, AI tools like ChatGPT and Copilot significantly influenced my learning process. These technologies supported me in understanding challenging concepts, debugging code and boosting productivity. They helped me to address academic challenges efficiently and encouraged exploration of creative solutions that might not have been considered otherwise. This essay reflects upon my use of AI throughout ICS 314, highlighting specific applications utilized, challenges encountered and the lessons Ilearned about integrating AI effectively into the educational process.

## II. Personal Experience with AI
<br>

**1. Experience WODs (e.g., E18)**

For each Experience Workout of the Day (WOD), I started by attempting to complete the assignment entirely on my own without the assistance of AI. I believe that by using this initial strategy, it allowed me to focus on developing my problem-solving skills and improving my ability to analyze coding tasks independently. However, if I spent too much time on a single step, typically five to seven minutes, without making significant progress, I resorted to using AI tools like ChatGPT and Copilot for guidance. With AI’s assistance, I was able to get back on track quickly, implement the necessary components and ensure the program worked as intended. After overcoming the initial challenges, I would reset the timer and attempt the WOD again, this time using what I learned to improve my efficiency. On these second and subsequent attempts, I relied more on AI to ensure I was on the right track and assist me with completing specific tasks required for the WOD. AI became particularly valuable for debugging and resolving any issues that came up during the process. For example, when I encountered an unexpected runtime error while working on E50: Digits Part 2 (List Contacts Page), I had to ask ChatGPT, “How do I resolve this undefined error in order to get my webpage back up?” The explanations provided not only resolved the immediate issue but also deepened my understanding of how to prevent similar errors in the future.

By relying on AI more during reattempts, I could systematically validate my approach and refine the details of my implementation. AI tools helped me to debug efficiently, clarify doubts and fine-tune my code to ensure everything was functioning correctly. This process reduced uncertainties in how to proceed, helped me to identify areas for optimization and improved my overall completion time for each WOD task. Overtime, this combination of independent effort and targeted AI assistance strengthened my coding skills, increased my confidence and reinforced my understanding of key concepts.

## In-class Practice WODs

At first, I relied on using Copilot during the in-class Practice WODs because of its ability to provide suggestions by making use of internet-based resources. This was particularly helpful when working on the given tasks as Copilot would generate up-to-date solutions and relevant examples, which were especially useful when I was given tasks that involved new or unfamiliar concepts. For instance, during the History of Surfing in-class Practice WOD, I was tasked with creating a simple Hyper Text Markup Language (HTML) and Cascading Style Sheets (CSS) page featuring a centered heading, a background image, contrasting font colors, and Google Fonts. Additionally, I had to include an introductory and profile section that included images properly sized and floated of four professional surfers.

Initially, I had difficulty centering the heading and ensuring the images floated correctly with consistent spacing. I used Copilot to help resolve these issues. For example, by prompting Copilot, "How do I center an H1 heading in HTML and CSS while ensuring compatibility across browsers?,” Copilot was able to provide me with a solution that used text-align: center and ensure it worked within my stylesheet. Similarly, when I asked about image floats, Copilot suggested using float: left and adding margins for spacing. I adapted its suggestions, verified their results and used them to meet the assignment's requirements.

However, as the course progressed, I began to encounter limitations with Copilot. It maxed out at 30-messages, displayed errors when working on more advanced tasks and slowed response times hindered my workflow. Midway through the semester, I transitioned to using ChatGPT Plus (paying $20 for the subscription) due to its enhanced performance, unlimited messaging and improved accuracy when handling complex problems. For example, while working on the Aloha Beer Kaka’ako React-based WOD, I needed help integrating Bootstrap components for the navbar and aligning icons. I asked ChatGPT, "How can I use Bootstrap 5 in React to create a navbar with left-aligned text and right-aligned icons?" ChatGPT provided a detailed explanation that included using react-bootstrap components like Navbar, Nav and utility classes, such as ms-auto to push icons to the right. I was able to follow its guidance, resolve alignment issues and complete the task efficiently.

By shifting to ChatGPT, I was able to address the shortcomings I experienced with Copilot and maintained productivity during the in-class Practice WODs. While Copilot was useful early in the course for simpler tasks, utilizing ChatGPT, with its expanded capabilities, became a much better choice because it was a more reliable tool for debugging, refining code and understanding intricate web development concepts. This transition ultimately improved my ability to complete assignments within the time constraints while deepening my grasp of the fundamentals being taught within the class.

## Patterns in My Code Kitchen

Speaking from experience, design patterns have become indispensable tools when applying them in my own projects. For example, I implemented the <b>Singleton Pattern</b> during a VR project, which is often used to ensure that a single instance of a class exists throughout an application. I employed a singleton to manage global state, which ensured consistency across modules. While it was powerful, the pattern's pitfalls reminded me to use it sparingly.  This is similar when cooking with salt, since using too much can ruin the dish.

Another example is when I used the <b>Observer Pattern</b>, which played a crucial role in event-driven programming. When building a game mechanic, I used this pattern to notify multiple subsystems, such as, sore trackers, animations and sound effects, when a target was hit. The pattern’s flexibility allowed me to separate components, making the system more maintainable and scalable.

Lastly, the use of the <b>Model-View-Controller (MVC) Pattern</b> has been a cornerstone of my web development work. Separating data (model), presentation (view) and logic (controller) simplified collaboration within my team. Some groupmates focused on the front-end development of user interfaces while other groupmates focused on the back-end design that optimized the data models, all organized for a clean modular design.


## The Balancing Act

While design patterns provide immense value, they come with trade-offs. Overusing them can complicate code, just as over-spicing a dish can overwhelm its flavors. Some, like the Singleton, have even been labeled "anti-patterns" when misused. Yet, by understanding their strengths and limitations, developers can avoid common pitfalls and apply them cautiously.


## Closing Thoughts: Patterns as Foundations

Design patterns are more than technical solutions.  They're basically wisdom passed down through generations of developers. They allow us to build on the hard work, successes and failures of others, and help to avoid unnecessary reinvention. Whether you're a novice or a seasoned coder, patterns offer a foundation upon which great software is built.

If you could just consider design patterns as your own cookbook, it will be the best rules to live by the next time you encounter a coding problem. Just pick the recipe that fits the occasion, adapt it to your needs and create something remarkable. After all, every masterpiece, whether it be a meal, a roof or a software system, all begins with a well-crafted design.
