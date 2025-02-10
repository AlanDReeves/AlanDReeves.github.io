---
layout: essay
type: essay
title: "The Standard is the Standard"
# All dates must be YYYY-MM-DD format!
date: 2025-02-10
published: true
labels:
  - Coding standards
  - Coding
  - Coursework
---
## "The Standard is the Standard"
<img width="474" class="rounded float-start pe-4" src="../img/mikeTomlin.jpg">


When it comes to coding style, many college professors seem to take a page out of the Pittsburgh Steelers’ Mike Tomlin’s playbook. 
They say that the standard is the standard and no deviation is allowed. Certainly there seem to be some good reasons to enforce certain elements of style standards, but I feel like in many cases readability is actually decreased by following preset rules so strictly. 

## "The Case for a Standard"

The greatest argument I can think of for having style standards is that it ensures any given member of a team can read any other given member’s code without spending overly long trying to figure it out. 
In a project where the pieces each member makes may depend on the implementation of another member’s code, it may be vitally important that everyone understands everyone else’s code. 
If you do not have a written style standard, it is possible that you may have a member who writes perfectly functional code that does not make any sense to another person. 

There is also a good argument from the professor’s perspective. 
By imposing one style on everyone, he ensures that he can actually read all his students’ code well enough to grade it, or at least that the TAs will not have to spend every hour of their weekends grading. 
Additionally, by requiring a certain style, the professor can prevent students from just directly copying code they find online. 
If students have to edit the code in some way, they at least have to read it even if they do copy, and then hopefully they will understand it some, too.


## "The Case Against"

As someone who has taken a good amount of college courses on coding, across a few different languages, I have personally had many experiences where I found a standard either very strange or inconvenient. 
The first example of this that comes to mind was during a course called program structure, which involved coding in C. One of the coding rules in this class was that each function must have only one return statement. 
This seemed reasonable generally, but it made switch statements or anything with long if else logic statements difficult both to write and to read. 
This class also had a rule forbidding the use of any break statements. These things combined would practically obscure the purpose of functions that could have been very simple. 

A smaller example of this kind of thing comes from my software engineering class, which I am currently taking at the time of writing.
Large parts of this class use TypeScript, and one feature of TypeScript is that semicolons are optional at the end of statements. 
They can be included if you like them but are not inherently required by the language. 
However, one of the many coding standards that the professor requires is to use a semicolon at the end of every line. 
While this was not the end of the world by any means, most of my coding is done in Python, a language where using a semicolon at the end of the line causes a syntax error. 
In this case, the coding standard took away a useful feature of the language, which was designed specifically to appeal to people with my background. 


## "The verdict"
 
While I tend to complain about coding style standards, it does not make sense to remove them completely. 
The benefits of readability simply outweigh the inconvenience of having to change one’s own individual style. 
However, I think that many standards go much too far in what kinds of rules they contain. 
If one set of rules must be forced on all circumstances, then it had better be extremely well thought out. 
For cases that the standard maker could not have thought of, there should be some flexibility for the individual to make adaptations to the rules so that they do not conflict with best practice or readability. 
I think by balancing things in this way you can prevent both the edge case of having completely unreadable code, and the edge case of having the coding style prevent code from being more readable.  

No AI was used in making this essay.
