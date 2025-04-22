![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

Discover

Books

Articles

My library

Search

Discover

![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

# The Clean Coder

Back to Discover

[[book_md/the-clean-coder/preview|preview]]

  * [[book_md/the-clean-coder|the-clean-coder]]
  * Full Book Guide

    * [[book_md/the-clean-coder/chapter-1|chapter-1]]
    * [[book_md/the-clean-coder/chapter-2|chapter-2]]
    * [[book_md/the-clean-coder/exercise-follow-rule-2|exercise-follow-rule-2]]
    * [[book_md/the-clean-coder/chapter-3|chapter-3]]
    * [[book_md/the-clean-coder/exercise-estimate-using-the-pert-method|exercise-estimate-using-the-pert-method]]
    * [[book_md/the-clean-coder/chapter-4|chapter-4]]
    * [[book_md/the-clean-coder/chapter-5|chapter-5]]
    * [[book_md/the-clean-coder/exercise-reflect-on-meetings|exercise-reflect-on-meetings]]
    * [[book_md/the-clean-coder/chapter-6|chapter-6]]
    * [[book_md/the-clean-coder/appendix|appendix]]
  * [[book_md/the-clean-coder/highlights|highlights]]
  * [[book_md/the-clean-coder/community|community]]



Adding to Favorites 

Removing from Favorites 

## Appendix: Programming Tools

In the previous six chapters, we discussed the qualities and skills of professionals. In this appendix, we’ll explore some of the programming tools you can use as you work toward professionalism.

### Source Code Control/Version Control Tools

There are two main types of source control tools, open source and “enterprise.” Open source tools are usually better than “enterprise” ones because open source tools are built by developers (who know what features other developers need). Enterprise tools, on the other hand, are usually aimed to appeal to business people, and often they have extraneous features but lack the features developers require, especially speed.

Martin recommends the following open-source tools:

  * **Subversion** if you don’t need to branch
  * **git** if you do need to branch. git allows developers to keep a local copy of the entire project and then merge copies later.



If your company has an enterprise system, you can still use an open-source system—use the open-source system during iterations, and check the source code into the enterprise system at the end of iterations.

### Integrated Development Editors (IDEs)

IDEs all have their pluses and minuses:

  * **vi** is simple, fast, flexible, and easy to use.
  * **TextMate** is intuitive and easy to use. It’s slower than vi and less powerful than the editors below. Martin usually uses it for C++.
  * **Emacs** is powerful and features an internal lisp model. Martin considers it the best general-purpose code editor.
  * **IntelliJ and Eclipse** are powerful and have a good selection of features. They’re both better than Emacs for editing Java. The downsides: They’re hard to learn, they take a lot of computing power to run, and setting up a project is a lengthy process.



### Issue Tracking Tools

Use issue tracking systems to keep track of both bugs and to-dos including new tasks. **If your team is between five and 12 developers, you should have tens to hundreds of tasks and bugs, so you shouldn’t need anything particularly powerful.** (If you have thousands of tasks or bugs, you don’t need a more powerful tracker, you need to go back and fix whatever got you into this situation.)

Martin recommends starting with a manual system first. For example, divide a bulletin board into labeled sections (for example, “not yet started,” “in progress,” “finished”) and write tasks on cards. Pin the cards in the relevant section and move them as the task progresses. This will help you figure out what kind of digital tool will best meet your needs.

Here are some of the options once you’re ready to move to a digital tool:

  * **Pivot Tracker** is simple, allows for fast communication, and works with the iterative/Agile workflows.
  * **Lighthouse** is quick to learn and easy to use, but not as powerful as Pivot Tracker.
  * **Wikis** have a flexible structure, are easy to use, and are good for internal projects.



### Unified Modeling Language (UML)/Model Driven Architecture (MDA) Tools

UML and MDA are tools that theoretically allow developers to build diagrams that an engine will translate into code, rather than writing the code directly. These tools don’t do this job effectively because the goal is to abstract away details, but removing detail is unhelpful for two reasons:

  1. **Sometimes programmers _need_ access to the details.** For example, the two characters n and r both break a line of text, and over the years, one or the other (or both together in either order) were conventions. As a result, having the “wrong” one in a program can throw errors. UML isn’t detailed enough to solve this kind of problem.
  2. **Diagrams have their own details such as syntax and rules.**



[[book_md/the-clean-coder/chapter-6|chapter-6]]

Done

Go to home page 

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=513c1bc2-4c1e-4470-bc9c-ce9630a61455&sid=1711133063fa11eebdec89a8b8ae3bbc&vid=171147a063fa11eea7440fcfeb230d96&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fthe-clean-coder%2Fappendix&r=&lt=459&evt=pageLoad&sv=1&rn=406226)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



