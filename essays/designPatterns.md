---
layout: essay
type: essay
title: "Design Patterns"
date: 2025-04-24
published: true
labels:
  - Software Engineering
  - Full Stack
---

## Something I Learned by Accident ##
A few months ago, I was exploring different python UI options for software tools I was developing for my internship.
I experimented with PySide6, PyQT5, PyQT6, and some others and while I felt that I was doing good enough work,
I thought it would be wise to ask a graduate student I knew, who previously made GUIs professionally,
what he recommended. He introduced me to the QT widget designer app, which allows you to make quality GUIs without
needing to write them programatically. This was excellent in and of itself, of course, but I accidentally learned an even
more important lesson without realizing. 

## QT Widget Designer ##
When QT Widget Designer creates a python file for you, it generates a script with a class which you can import and the class, when instantiated generates the GUI that you designed. 
It is possible to edit the GUI script itself to connect to the back end, of course, but the method the graduate student
showed me used another file, which imported and controlled both the backend and the front end. 
Of course, anyone with any experience is not amazed by this revalation because they have known to do this for years.
I, however, had never been exposed to this idea and without realizing it, I had just been taught the Model View Controller (MVC) design pattern.

## Design Patterns ##
For anyone unfamiliar, a design pattern in software engineering is something of a template for solving a commonly occurring problem. 
By using design patterns, an engineer can solve problems effectively without having to reinvent the wheel every time.
The Model View Controller pattern, has a controller object which interacts with a model (backend) and view (frontend).
The advantage of using this design pattern is that either the view or model can be modified without having to extensively rewrite the other or the controller itself.

## Design Patterns in my Work ##
Since being exposed to this idea of the MVC design pattern, I have been using it extensively without knowing that it had a name.
I have used it in multiple python programs for which I needed a GUI and also extensively in my recent web development experiences, where I have a web page front end and database back end.
Only recently did I stumble upon the formalized concept of design patterns, but I have already seen an incredible amount of utility in them and intend to learn more design patterns so that I can make better programs in the future.

No AI was used in making this essay.