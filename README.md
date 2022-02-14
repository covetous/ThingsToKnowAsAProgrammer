# Things To Know As A Programmer #
A collection of links to and thoughts about being a good programmer. I make no claim to this being the ultimate guide. It is merely my own thoughts on the subject and others thoughts that I agree with to some or the full extent.

## README files ##
Readme files are an essential explenation of your software and most projects will have one. At least if they are public. Please do no be afraid to use them in private repos as well. Include anything that is needed to get started with the project and explaining the perticular aspects of the project. Why have you made designdecissions and such. Tailor the readme to the target. If you have a library focus on how to use the library. If it's an internal repo with multiple developers explain how to continue developing the project and how to test and run it.
Most README files are written in Markdown (.md). This is a nice way to make it more readable.

Included in the repo is the file markdown_cheatsheet.md copied from https://github.com/tchapi/markdown-cheatsheet/blob/master/README.md .

Links to other sections.
| [Code review](code_review.md) |

## Things for a junior dev ##
### Or any devs really ###
https://twitter.com/ClayDowling/status/1375891016453136384

### On being a developer, or working at all ###
Being a developer is not just hacking code, or writing tests, or doing documentation. It's a process where you take responcebility for the everything around you. Do not for a second think that you have to do everything, but you have a responsebility to enable it. That can be anything from moving desks when you need to reorganize your landscape to leading a software architecture meeting as a unior dev. Always do your best from the level you are at. Always remember that to advance to the next level you have to learn and experience. Everyone who is more experienced have gone through the same process so don't be intimidated by them. And this is part of your responsability, to learn and expand within your field. 
And whatever you do, remember that you can only do your best and if you fail and get blamed for it, they did not help you set up the stage to succeed.

Blogs & Books
=====
## Clean Code and Uncle Bob ##
Uncle Bob (or Robert C. Martin) is a legend within programming and as much of a must to read that there is. Even if you do not agree with him you should read his books to know what other people are talking about.
### Books: ###
#### Clean Code ####
(ISBN-13: 978-0132350884) This is his most iconic book. The book explain what makes good code that doesn't smell. The book is in some ways contradictory to what other things you might have learned.
#### The Clean Coder ####
(ISBN 978-0132542883) What makes a good, professional coder? This books aims to give the reader some answers to those questions.
#### Clean Architecture ####
(ISBN 9780134494166) The follow up to Clean Code where the reader learns to take a more birds eye view and create architecture insted of just code.
## Domain Driven Design Quickly ##
(ISBN 978-1-4116-0925-9) The most complicated aspect of large software projects is not the implementation, it is the real world domain that the software serves. Domain Driven Design is a vision and approach for dealing with highly complex domains that is based on making the domain itself the main focus of the project, and maintaining a software model that reflects a deep understanding of the domain. The vision was brought to the world by Eric Evans in his book "Domain Driven Design". Eric's work was based on 20 years of widely accepted best practices in the object community, as well as Eric's own insights.  Domain Driven Design Quickly is a short, quick-readable summary and introduction to the fundamentals of DDD. A special interview with Eric Evans on the state of Domain Driven Design is also included

https://www.infoq.com/minibooks/domain-driven-design-quickly
## Blogs ##
- [Uncle Bob](https://blog.cleancoder.com/)
- https://medium.com/@marinithiago/
## Youtube ##
[Continuous Delivery](https://www.youtube.com/watch?v=wyABTfR9UTU)
Talks about CI / CD, mostly. Also talks about some other topics. A bit dry but very knowledgable.

Architecture
====
## Architecture ##
### Microservices vs Monoliths ###
https://medium.com/@marinithiago/monolith-microservices-and-architectural-quanta-c1327428d652

## Testing ##
### Charactirization tests vs Unit Tests ###
https://michaelfeathers.silvrback.com/characterization-testing

### TDD - Test Driven Development ###
TDD is the process of first writing test, then writing code that makes the test to pass.
http://butunclebob.com/ArticleS.UncleBob.TheThreeRulesOfTdd

## Git ##
Git is a tool developed by Linus Torvalds (yeah Linux guy). It is the defacto version control system today, but there are alternatives ou there. 
### Learnign git ###
TDD is a methodology where you first write a small failing test and then write the code that makes it pass. You then modifie the test to include more require
[https://www.w3schools.com/git/default.asp](https://www.w3schools.com/git/default.asp)

#### Branching in Git ####
[https://learngitbranching.js.org/](https://learngitbranching.js.org/)
Working is a big thing in Git and here is a good guide to how it works.

### Oh shit moments ###
If you ever have problems with git. Maybe something you did or you don't understand what's happening. The following links are really good.

[https://ohshitgit.com/](https://ohshitgit.com/)

[https://firstaidgit.io/](https://firstaidgit.io/)

### Git Tools ###
#### Beginner tools ####
- [https://desktop.github.com/](https://desktop.github.com/)
- [https://www.sourcetreeapp.com/](https://www.sourcetreeapp.com/)

#### Intermediat tools ####
- [https://tortoisegit.org/](https://tortoisegit.org/)

#### Advances tools ####
- [https://cli.github.com/](https://cli.github.com/)

### About commit messages ###
Writing good commit messages is actually hard. Make sure you have a uniformed way of writing them in your team / organization.

#### What tense should git messages be in? ####
[https://www.danclarke.com/git-tense](https://www.danclarke.com/git-tense) 
A lot of people prefere imperetive form on the commit messages and here's a discussion on how people reason.

## Useful software ##
A list of free useful tools. This includes everything from testing to hosting, monitoring and so on.
[https://freestuff.dev/](https://freestuff.dev/)

### Awesome IDEs ###
#### Visual studio Code ####
[https://code.visualstudio.com/](https://code.visualstudio.com/)
First of Visual Studio Code might be the most popular editor now days. It's a generic IDE that handles language support by plugins. It have a large community behind it making plugins for pretty much anything. Microsoft is also adding plugins and continiously releasing new version.

#### PyCharm ####
[https://www.jetbrains.com/pycharm/](https://www.jetbrains.com/pycharm/)
One of the most populair python IDEs out there. Also support some front end and have lot's of features.

[Code Reviews](code_reiew.md)
====
The benefits of code reviews was absolut in the early 20th centry but as technology advances it have come under question. What actually benefit does it do. As of wrighting this 2021 it is stil considered something that brings benefit to the software quality. But as tools increase in complexity and functionality code review might be a thing of the past.

Misc Links
=====
1. Some nice quotes https://codeburst.io/50-quotes-for-better-coding-76bdac3fc234
