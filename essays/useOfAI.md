---
layout: essay
type: essay
title: "Reflecting on my Use of AI in Software Engineering"
# All dates must be YYYY-MM-DD format!
date: 2025-05-10
published: true
labels:
  - AI
  - Software Engineering
---
<img width="300" class="rounded float-start pe-4" src="../img/AI/AISoftwareEngineer.png">


## Introduction
Everyone's favorite topic in recent times is AI and how it is changing both education and computer science in particular. 
With the widespread use of things like chatGPT, Grok, Deepseek, and others, both of these fields, and certainly many more, will change greatly.
In education, AI offers a great opportunity to learn things quickly and easily, but also it makes cheating more available than it ever has been before.
In software engineering, it greatly increases the potential production of an individual engineer, but much like education, offers the opportunity to "cheat" and write code that the user does not understand. 
Code from AI may also have security vulnerabilities, inefficiencies, or may even not work entirely. 
My own experience has been limited almost totally to chatGPT and so I would like to expand some on the effects its use has had for me in software engineering for me personally. 

## Personal Experience with AI
While I will mostly discuss my experiences using chatGPT for my ICS 314 (Software Engineering) class, some of this does hold true for my coding outside of class as well.
In ICS 314, students were not only allowed but encouraged to use AI in assignments, and so I naturally made fairly heavy use of AI.
In fact, I would say this class is what caused me to begin using AI in my coding as I had not really considered it much before.
##### WODS
During the course of the class, we had several Workouts Of the Day (WODs) per week. Some were at home and others were in class. All of them were timed and had to be completed in the time limit for credit.
During the WODS, I mostly only used AI to help me with troubleshooting and understanding syntax for any of the new languages and frameworks I was learning. 
The pace we were asked to learn new languages and frameworks was extremely fast and so I almost never had a very good understanding of what syntax or library I needed to use, which resulted in a lot of exceptions.
ChatGPT was a very helpful tool for correcting errors that would have taken me possibly hours to get through with just the documentation.
I remember using chatGPT a lot during the react/Next.js WODs. I would ask it something like "How do I make this div centered" or "Why is my image not showing up" and then use the answer to correct the problem.
Overall, I personally chose not to use AI to outright solve entire WODs even though this would have been allowed. 
I felt that doing that would be cheating myself out of the educational aspect of the course and I occasionally did lose points or fail WODs because I chose not to just ask chatGPT to do it for me.
Even in hindsight, I stand by this decision.
##### Essays
We were allowed to use chatGPT to write essays for ICS 314 as well.
I genuinely enjoy writing and I have done a lot of it so I never really struggled with phrasing things the way I wanted to and did not want to miss out on the fun of writing the essays myself.
Ultimately I never used AI to help with essays in any way and I do not expect to change that habit in the future.
##### Final Project
The final project for the course was a web app that used a database on the back end.
I was forced to use AI quite a lot to get this project done. 
We were taught most of what we needed to know in order to do this, but between all the different frameworks, languages, server hosts, and networking quirks, it was genuinely beyond my abilities to get the entire project done on time without help. 
I used AI mostly to help understand why exceptions were happening or why things were not displaying as intended. 
I never had to ask chatGPT to write an entire web page, though I had to get it to teach me how many functions worked as well as how I could apply them to do what I needed.
This also showed me one of chatGPTs greatest weaknesses: it will almost never tell you a task is impossible. 
I spent at least 4 hours asking chatGPT to help me understand why my Github workflow could not correctly build the app, seed the database, and then run playwright tests that required the database to work.
While discussing this with my group in class, the professor happened to overhear and told me that it was not possible.
I suppose this proves that AI is still not a one stop source for all knowledge.
##### Learning a concept / tutorial, Coding Examples
This is actually my favorite use of AI, and I used it for this quite often. 
Whenever I ran into a new prisma function or standard library TypeScript function, I would ask chatGPT to show me an example of it and this greatly improved my understanding.
AI examples tend to be more comprehensive and informative than what you find on forums, in my opinion.
##### Answering a question in class or in Discord / Asking or Answering a smart-question
I never thought to use AI to answer someone else's questions. 
I suppose I assumed that anyone asking in the class Discord was unable to find an answer by looking it up or asking AI.
I certainly used it to answer my own questions a lot, as I described above.
##### Explaining code
Any time I ran into code that I did not understand, I always felt it was important to read it myself. 
I think doing things this way is a good learning tool and shows me how other people approach problems. 
Hypothetically, if I expected to already know how a segment of code works but did not have the time to read it myself, I could imagine using AI to summarize it quickly, but that has not happened to me yet.
##### Writing code
Similar to reading code, I can imagine doing this for simple segments where I do not expect to learn anything by writing it.
However, I generally do not have this problem and so I do not currently do this.
##### Documenting code
This thought had not occurred to me but I think I may try this in the future.
##### Quality assurance e.g. “What’s wrong with this code”
As I said previously, this was my most common use case for AI in ICS 314. 
I find that asking chatGPT is always faster than checking the documentation.
In fact, sometimes I would give chatGPT a link to some documentation and then ask if questions.
ChatGPT was also very good at detecting complex problems that occured between more than one framework/language.
During the final project, chatGPT actually helped me detect a problem in my schema.prisma file that was causing my TypeScript files not to compile.
##### Other uses in ICS 314 not listed
I cannot think of any other ways I used AI in ICS 314 specifically, but my favorite use of AI in other ICS classes has been in clarifying specifications for problems. 
In a lot of my classes, instructions are extremely vague and unclear, so I ask chatGPT to help me make sense of them.
Thankfully, in ICS 314 all the requirements were fairly clear so I did not have to do this.
This can also be helpful in algorithms class, where there will sometimes be a very long worded problem which is actually asking a somewhat straight forward question. 

## Impact on Learning and Understanding
In ICS 314 in particular I think using AI allowed me to punch above my weight class, both for better and for worse. 
If this class had been held in such a way that looking up answers with AI or online were not possible, I think I would have needed at least double the amount of time I spent per week, and I spent an incredible amount of time.
I did get almost all of the work done in a way that I am satisfied with, but because of my AI use, I feel like I missed out on learning additional aspects of web development that I might have learned if I had been forced to do everything myself.
There were some segments of code I submitted for this class that I feel like I did not fully understand and I think that in many ways defeats the purpose of the assignments.

## Practical Applications
AI has quite a few great applications in real world software engineering problems. There are several projects I am doing for work which use AI for real world security purposes. 
There are many tasks for which I think a fully deterministic algorithm may not be possible, and so using LLMs or other machine learning methods may in fact be the only way to accomplish the task meaningfully. 
While I have not worked on this personally, I think image recognition in particular may be one of these.

## Challenges and Opportunities
The biggest limitations of AI that I encountered during this course are AI's occasional refusal to answer that a task is impossible, and its habit of rarely returning a wrong answer. 
In addition to the example I gave above with playwright tests, I have personally had some issues with AI failing to answer complex math questions and giving nonsense answers, though that did not happen in ICS 314.
A few times while I was working on something for the class, I got code that did not work or did not do what I wanted.
In fairness, this problem used to be much more severe and the reason I did not use AI much before this class was because I often got code that would not even compile as recently as a year ago.
Despite these limits, I think that AI is also a potentially very useful tool.
If used correctly, I think AI is a very good way to learn complex topics very quickly since it is a single source for a wide variety of information.

## Comparative Analysis
The greatest danger of using AI in software engineering education relative to traditional methods is that students may just get AI to solve all the problems for them and end up learning nothing without showing any signs of knowing nothing.
Most students, I think, do not have the concept of cheating themselves, or at least do not fully understand the consequences.
I have already been through many classes, computer science and otherwise, where students cheated through the course with AI and knew nothing at the end. 
In cases like these, the purpose of taking the class is completely defeated and the student spends 5 months of their time to achieve nothing. 
With traditional teaching methods, and if it is possible to eliminate the use of AI, a student who just wants to get a grade is still forced to learn something, even if they do not do it intentionally.
Of course, the cat is out of the bag now, and there is no putting it back in. 
On the other hand, someone who is motivated to learn and disciplined enough not to cheat when things get hard now has all the tools they need to learn almost anything with just an internet connection.
Students do not necessarily need books, do not need to spend long hours searching for learning resources, and have a study buddy available at all times.
Students who just want a grade will be able to cheat and learn nothing with no one to stop them, while students who want to learn will learn faster than before. 

## Future Considerations
I think as time goes on, software engineering students will be able to do more with less knowledge, for better or worse. 
I think the software engineering world has already seen that there are new developers who lack much understanding of what they are doing but still generally working software.
Uniquely motivated students will also now be able to learn much more than was ever possible before. 
AI represents both a powerful learning tool and a powerful cheating tool, and it will be used both ways.

## Conclusion
In conclusion, my favorite ways to use AI during this course and for coding in general are to troubleshoot and learn new syntax/libraries. 
There are probably even more good uses for AI in this field and I look forward to trying them out in the near future. 
In particular, I think using AI to create documentation might be very useful.
As for my thoughts about AI's effect on the future of software engineering education, I think it's both a blessing and a curse.
It will be important for students to resist the temptation to do things the easy way and force themselves to learn even when there is no pressure to do so.
For future iterations of ICS 314, I think it might be good to somehow prevent certain kinds of AI use during at least WODs just to give an extra push towards learning.