---
title: "Not Just Pretty Pictures"
date: 2023-04-01T10:02:34+01:00
draft: false
categories: [work]
tags: [tools]
featured_image: "images/models-diagrams.png"
---
# Diagramming versus Modelling
When I want to create a piece of software that is slightly more complex, I tend to analyse and design it first using models.
Implementation comes later (iteratively).

I can do this on a scrap of paper or a whiteboard. I can also draw that on a computer - creating a model (which I can turn into various diagrms or other output types).

Here, I am specifically talking about models and software/systems architecture.
I use tools that are good for this purpose. Why? Because what is in my head is only there: not very useful to others and my future self either.

From my engineering experience and practice, I know that a diagram is not a model, and for anything slightly more complex (or a system I expect to evolve), I need a model.
Back when I started my professional journey (1998), I used UML - it worked very well, especially when I needed to generate code (or carry out reverse engineering of an existing system). You do not have to use UML (though I would still use it for various reasons).

There are many modelling languages (some of those are DSLs - Domain Specific Languages) - and they are sometimes more appropriate for a given task.

> If you think that UML (or other modelling languages or DSLs are dead), we need to talk. I can show you how they are being used, why some of them are hidden and what amazing things are possible because of them. Happy to chat and show you how much more efficient you can be once you use them consciously!

What is important to me when contrasting diagramming and modelling is that a diagram is usually a static representation of a piece of a system, while a model is a generic collection of elements and relationships between them.
My preferred modelling tools allow to create various views of a model - with a varying level of detail (not necessarily showing everything at the same time).

Models are powerful because they can be manipulated and reasoned about by machines, e.g., for code generation, analysis, documentation, transforming and generating various outputs (like diagrams, slides, checklists, etc.).

It is important to separate the content from the presentation - and this is one of the reasons why I favour models as opposed to static pictures/diagrams.

These are useful videos to watch:
- [Visualising software architecture with the C4 model - Simon Brown, Agile on the Beach 2019](https://youtu.be/x2-rSnhpw0g)
- [Five Things Every Developer Should Know about Software Architecture • Simon Brown • GOTO 2020](https://www.youtube.com/watch?v=9Az0q2XHtH8)
- [Diagrams as Code 2.0 • Simon Brown • GOTO 2021](https://www.youtube.com/watch?v=Za1-v4Zkq5E)
- [C4 model example - what matters in a diagram](https://c4model.com/review/)

> If you are interested about software architecture, have a look at this link --> [click here](https://dariuszworks.co.uk/blog/posts/critical-thinking/#2-architecture).

# How do draw a diagram (not just for C4)
> This page is work in progress. If you want a demonstration, or you want me to show you more, please let me know.

As always, there are lots of tools out there, but my preference is yEd and PlantUML and C4.
Over the years, I have been usingSome tools that I have been using 

You will need JRE installed to run PlantUML jar file.

You will need to have a Java Runtime Environment installed and a plantuml.jar file (see the link below).

## More about C4

https://github.com/plantuml-stdlib/C4-PlantUML

If you want to understand where C4 came from (and you want to learn how to create software/systems architecture diagram - and not only):

- [C4 Model for Visualising Software Architecture - LeanPub - 2022](https://s3.eu-west-1.wasabisys.com/shared-content/ebooks/visualising-software-architecture.pdf)
- [Software Architecture for Developers - LeanPub - 2022](https://s3.eu-west-1.wasabisys.com/shared-content/ebooks/software-architecture-for-developers.pdf)
- [Visualising software architecture with the C4 model - Simon Brown, Agile on the Beach 2019](https://www.youtube.com/watch?v=x2-rSnhpw0g)  
- [236 Simon Brown, author of Software Architecture for Developers](https://www.youtube.com/watch?v=PLjVbjmGe5U)


## More about PlantUML

https://plantuml.com/


## More about yEd
This is a diagram editor that I started using more than 15 years ago, when I was interested in graph drawing and graph layouts (graph theoretical aspect of creating visually pleasing diagrams with vertices, edges, etc.).

I also use it for drawing colourful (or not) diagrams, with components, boxes, arrows and many more.

Benefits:
* free
* easy to use
* easy to store and version graphs (my format of choice is `gml` for my programmatic graph generation; though there are others, of course)
* easy to export to SVG (and if you want to quickly import to PowerPoint - that could be a good option)
* easy to generate very complex graphs programmatically (if you need to) - I have needed this for a long time, so out of many tools this is my tool of choice for visualising graphs

https://www.yworks.com/products/yed

## Diagrams - Diagram as Code
https://diagrams.mingrammer.com/