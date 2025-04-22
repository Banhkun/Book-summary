![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

Discover

Books

Articles

My library

Search

Discover

![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

# The Mythical Man-Month

Back to Discover

[[book_md/the-mythical-man-month/preview|preview]]

  * [[book_md/the-mythical-man-month|the-mythical-man-month]]
  * Full Book Guide

    * [[book_md/the-mythical-man-month/exercise-create-a-schedule-for-your-project|exercise-create-a-schedule-for-your-project]]
  * [[book_md/the-mythical-man-month/highlights|highlights]]
  * [[book_md/the-mythical-man-month/community|community]]



![](/img/tutorial-fonts.175b2111.svg)

##### Change text options

Here you can change the font, text size, and reading screen to just how you like it. 

Next

  *   *   *   *   * 


![](/img/tutorial-menu.4c76dd27.svg)

##### Table of contents

Here you’ll find everything else, including the full chapter-by-chapter guide, your highlights, PDF downloads, and book discussions. 

Next

  *   *   *   *   * 


![](/img/tutorial-player.d25b1afb.svg)

##### Audio

Every guide has an audio narration so you can listen on the go. 

Next

  *   *   *   *   * 


![](/img/tutorial-favorite.b948300a.svg)

##### Add to Favorite

Mark your favorite guides here. You can find your favorites on your homepage. 

Next

  *   *   *   *   * 


![](/img/tutorial-night.ddd7fb5c.svg)

##### Night Mode

Like a darker look when you read? Turn dark mode on here. 

Finish

  *   *   *   *   * 


Adding to Favorites 

Removing from Favorites 

## 1-Page Summary

_The Mythical Man-Month_ offers guidance to managers leading large teams, especially teams coordinating detail-oriented projects with lots of moving parts. Its advice centers on reducing _complexity**—** the_ _number of people and components that need to work in coordination.**By reducing complexity, you can make complicated projects much more manageable.**_

Frederick P. Brooks led the division of IBM that programmed computer operating systems in the 1960s. He managed over 100 employees to create cutting-edge programs that required an intense degree of coordination: If all the parts didn't work together correctly, his operating system wouldn't work. Brooks found that the more parts he needed to coordinate with each other, the more opportunities there were for errors.

High complexity, and the errors that came with it, caused his projects to fall behind schedule and go over budget as his team members were forced to fix error after error. In response, he developed a variety of strategies for reducing complexity while **coordinating large teams, keeping lengthy projects on schedule, and managing the errors that inevitably occur in detail-oriented work.**

Published in 1975, _The Mythical Man-Month_ was originally a guide for Brooks’s fellow managers in the computer industry. However, it quickly became a business classic as managers found it useful in a wide range of industries.

Our guide will take you through Brooks’s ideas in four parts.

  * **Part #1: The Problem of Complexity** examines the obstacles Brooks faced in creating operating systems and how those challenges shaped his management philosophy.
  * **Part #2: Managing Teams** explains Brooks's advice for getting every worker on a large team to coordinate their actions precisely.
  * **Part #3: Managing Time** explores**** Brooks's strategies for keeping long-term projects on schedule.
  * **Part #4: Managing Errors** discusses Brooks's advice for debugging software and leading teams through the final stages of testing and repair.



Our guide explores Brooks’s management strategies while updating them with comparisons to today’s management advice. We also discuss how his thinking evolved over the years alongside the rapidly changing computer industry.

### Part 1: The Problem of Complexity

When managing his team to create operating systems, Brooks found his main obstacle was _complexity_ —the number of people and components that _need to coordinate with each other for the program to work._ Because each interaction between components creates an opportunity for poor coordination, **the more complex a program becomes, the more errors it likely will have.**

Brooks also found that the relationship between complexity and errors is _exponential_ rather than _linear_.**** In other words, **with each new person or component, you're not just _adding_ the potential for error: You're _multiplying_ it**. Therefore, the more complex a project becomes, the more time it takes to test and repair all its errors.**** Once**** Brooks realized that his teams spent _most_ of their time repairing errors, he set out to simplify his processes, teams, and program designs to prevent sinking vast amounts of effort into testing and repair.

(Shortform note: Understanding the difference between exponential and linear growth can clarify Brooks's ideas. Linear growth occurs when each value in a sequence has an _equal difference_ between them. However, exponential growth occurs when each value has an _equal ratio_. For example, the sequence "3, 6, 9" is linear because each value has an _equal difference_ of three. Whereas the sequence "3, 9, 27" is exponential because each value has an _equal ratio_ of being three times the previous value. Therefore, if complexity has an exponential relationship to errors, each new component or worker introduced has the power to _significantly_ multiply errors and time spent testing and repairing.)

> **Reducing Human Error**
> 
> As we'll continue to discuss throughout this guide, Brooks's core strategy for reducing errors is to simplify your processes. However, you may not always be in a position to change your company’s entire process. Those decisions might be out of your purview, or you may have to work within other logistical constraints. In that case, you might try these three smaller, targeted strategies for reducing errors in complex, detail-oriented tasks:
> 
> **1\. Identify where in the process errors are most likely to occur.** Audit your mistakes and try to spot the pattern. If you know where most errors happen, you can implement a better system for prevention.
> 
> **2\. Automate error-prone processes when possible.** Often, human errors are introduced during rote tasks like data entry that can be handled by software instead. Automating these tasks can eliminate the possibility of human error.
> 
> **3\. Create checklists.** With checklists, your workers no longer need to rely on their own fallible memories for every single detail of a process. Checklists are used in detail-oriented work across industries from engineering to medicine.

#### Complexity at IBM in the 1960s

While much of Brooks's advice for streamlining projects applies broadly across industries, understanding the specific logistical challenges he sought to overcome at IBM in the 1960s will ground our understanding of his strategies. He notes three challenges in particular: coordination between IBM components, limited feedback and testing resources, and coordination between programmers.

##### Challenge #1: High Level of Coordination With Other IBM Components

Brooks’s operating systems needed to work perfectly in tandem with multiple pieces of software and hardware. This is because an operating system manages a computer's memory and works as a "go-between" with the computer's hardware and software. Therefore, Brooks also had to coordinate his efforts with the teams that made IBM's hardware and software.

> **Brooks’s Major Contributions to Computing: IBM’s System 360 and OS/360**
> 
> Brooks managed the development of the IBM System 360 family of computers and the OS/360, the operating system that ran them.
> 
> Originally released in 1965, the IBM System 360 family of computers made an important step forward in the development of general-use computers. They were the first computers designed to accommodate both commercial and scientific purposes. They were also the first suite of computers varying in power and size that could all run on the same set of instructions. This meant a client could upgrade from a small, low-power computer to a large, high-power computer without learning new instructions. Brooks’s systems not only had a high need for coordination, but they were also _an advancement in coordination_ beyond what computer companies had dealt with before.
> 
> Brooks received several major accolades for his contributions to the development of computing technology, including membership in the National Academy of Engineering (1976), The National Medal of Technology (1985), and the Turing Award (1999).

##### Challenge #2: Limited Feedback and Testing Resources

Brooks explains that, because computers were rare and expensive, his programmers weren't able to work on their own individual computers. **Therefore,** **all of their code was written by hand and tested on just a few computers—a tedious process that often created significant testing backlogs.** This made testing much more time-consuming and errors more difficult to catch. Working without immediate feedback, programmers would have no way of knowing if they had made an error earlier in the process that could compromise their subsequent work.

> **How Delayed Feedback Loops Slow Production**
> 
> To clarify how limited testing resources slowed down Brooks’s workflow, let’s explore the effect that delayed feedback can have on product development. Traditional product development loops have three steps:
> 
>   * **Building the prototype**
> 
>   * **Testing the prototype**
> 
>   * **Learning from the results of those tests and applying their lessons to build a second prototype, starting the cycle all over again.**
> 
> 

> 
> The technological limitations on IBM's development process created a “delayed feedback loop,” or a significant delay between steps one and three—between building a prototype and learning whether it works. Within this delay, there are only two courses of action you can take:
> 
> **1\. Have your product developers wait for feedback.**
> 
> **2\. Have your product developers keep working on the next stages of the project without feedback.** However, this second course of action risks reproducing errors. Because your developers haven't received feedback about their previous errors, they may continue making the same errors in their subsequent work.
> 
> Both of these courses of action inevitably lead to further project delays. Thus, product development experts stress the importance of an efficient and accelerated development loop.

##### Challenge #3: High Need for Coordination Between Programmers

Standardization is crucial in software development because **all the parts must work together seamlessly for the program to run.** This created a challenge at IBM when working in large teams, because each programmer was working independently on their own software components.

This challenge was further compounded by the fact that, in the 1960s, computer companies custom-made all of their hardware and software in-house. This meant that they couldn't rely on standardized coding languages to streamline the process. Instead, they relied on detailed company instruction manuals for each component, as well as managers tightly coordinating programmers' efforts to ensure that all the components from all the programmers would fit together.

> **What Defines a “System”?**
> 
> The challenge Brooks faced in coordinating his programmers was one of creating **_systems_**. In _Thinking In Systems_ , Donella H. Meadows defines a “system” as a set of elements interconnected to achieve a function. Every system, she argues, is made of these three core components: (1) the elements or individual things in a system, (2) the interconnections and relationships between those elements, and (3) a purpose or function.
> 
> Out of these three elements, the _interconnections_ in Brooks's operating system were the sites of misalignment that produced errors. Because these sites of interconnection joined software components made by different programmers, they often wouldn't work together in perfect coordination. Therefore, Brooks's strategies for reducing errors lay in creating systems with a limited number of interconnections and standardizing relationships.

#### The Difference Between Fundamental and Incidental Complexity

While technological advances have eliminated many of the specific logistical problems Brooks faced, **he warns that the problem of complexity can never be completely solved**.**** To understand why, we first need to explore Brooks’s distinction between two types of complexity: fundamental and incidental.

  * **Fundamental complexity:** Creating a functioning software program is an inherently complex endeavor. No matter how advanced technology becomes, Brooks argues that creating an elegant, high-functioning program will always require a high level of _conceptual thinking and coordination_.
  * **Incidental complexity:** Incidental complexity is caused by the logistical challenges of _translating your programming concept into an actual program_. This could include limitations in memory, challenges in coordinating with other programs, or limited functions in the programming language.



**Brooks argues that advances in technology are able to resolve _incidental_ complexity, but they are unable to resolve _fundamental_ complexity.** Creating software still requires high-level conceptual thinking and coordination.

(Shortform note: History has partially borne out Brooks's assertion that technological advances can solve _incidental_ complexity but not _fundamental_ complexity. Over the years, as many of the logistical hurdles of early computer programming have been resolved, programs have become much more complex and still require high-level conceptual thinking to design. Solving _incidental_ complexity has simply allowed us to create _fundamentally_ complex programs at a greater scale. For example, the OS360, Brooks's signature operating system, used only 400kb of memory, roughly one-tenth the size of an average 4mb song on iTunes. In comparison, the largest storage drive for managing big data is currently 100tb, about 250 million times larger.)

##### No Single Solution to the Problem of Complexity

Brooks argues that, while complexity cannot be completely solved, **project complexity can be managed and reduced.** The rest of our guide will focus on Brooks's strategies for managing and reducing complexity in your projects. First, we'll explore his strategies for managing teams. Then we'll discuss his advice on time management and keeping large projects on track. Finally, we'll cover his strategies for managing the errors that inevitably arise in detail-oriented work.

> **Is Managing the Development of Complex Software a "Wicked Problem”?**
> 
> Experts have created a name for the type of problem Brooks describes—one that cannot be solved, only managed. They define this challenge as a "wicked problem" and describe several hallmarks.
> 
> **1\. Difficulty in defining the problem.** A wicked problem cannot be clearly or succinctly defined because it is often a set of overlapping problems interacting with each other.
> 
> **2\. Solutions are relative.** A solution to a math problem is either true or false. A solution to a wicked problem is simply better or worse than other solutions.
> 
> **3\. You can't immediately test solutions.** With wicked problems, solutions are often working in tandem with other solutions and have delayed results. This makes it difficult to assess whether any particular solution actually helped.
> 
> **4\. Every wicked problem is unique.** The strategies that succeeded most at solving one wicked problem may not necessarily work for another.
> 
> **5\. The search for solutions never stops.** You can't quite tell when you've reached a solution to a wicked problem—there's always another problem, another area for improvement.

### Part 2: Managing Teams

Large teams inherently introduce a lot of complexity by multiplying the possibilities for miscommunication exponentially. The higher the number of workers, the more opportunities they have to misunderstand each other. Brooks demonstrates this relationship with the formula: **n(n-1)/2.** Here, n equals the number of employees. They can each communicate with n-1 other employees (because they won't communicate with themselves). Each miscommunication involves two people, so you then divide the figure by two. When graphed, this formula displays an exponential growth curve. While five employees can miscommunicate 10 times, 100 employees can miscommunicate 4,950 times. Therefore, Brooks argues, many strategies that succeed with small teams won’t scale up to larger teams.

![mythical-man-month.png](https://media.shortform.com/images/mythical-man-month.png)

(Shortform note: Brooks's ideas about the relationship between workers and productivity **ran counter to a lot of assumptions about management at the time**.**** Many managers used a unit of measurement called a “man-month” that allegedly represented the amount of work a worker could get done in a month. This led some to believe you could speed up any project simply by adding more workers. However, in Brooks's thinking, productivity has less to do with the _quantity_ of workers, and more to do with the _quality_ of processes. Therefore, Brooks declares the "man-month" a _myth_ with the title of his book: _The Mythical Man-Month_.)

In this section, we'll discuss two strategies for managing teams and solving the problems of complexity: reducing the need for communication and documenting processes.

#### Strategy #1: Reduce the Need for Communication

Brooks's first strategy for reducing errors is to **cut down on the need for employees to communicate with each other.** The fewer employees involved in a decision, the less discussion there needs to be about it. In this section, we'll cover Brooks’s three core tactics for reducing the need for communication: specializing roles, limiting the number of designers, and letting skilled workers take the lead.

##### Technique #1: Specialize Roles

Brooks advises you to **narrow and distinguish your employees' roles within the company.** This allows employees to carry out their individualized tasks without the need for collaboration or joint decision-making—reducing the need to communicate and with it, the potential for miscommunication.

For example, at IBM Brooks gave his programmers full responsibility over their programs until they were submitted for testing. Then the testing managers would have full responsibility. This reduced the need for collaboration because the project was out of the programmers’ hands once it reached the tester. To make this system work, Brooks separated his staff into a wide range of specialized roles, including tool makers, schedule keepers, and manual updaters.

(Shortform note: While Brooks highlights the benefits of role specialization in reducing the need for communication, economic theory demonstrates that role specialization also leads to greater company efficiency. When each employee specializes in one task, they can devote more time and energy to mastering and performing that skill. Therefore, the more specialized your company's roles become, the more proficient your employees can become at each stage of production. This also gives an enormous advantage to large companies and even large economies with more workers: The more employees you have, the more tasks can be split up into separate specializations.)

##### Technique #2: Limit the Number of Designers

Brooks also reduced the complexity of his programs by **limiting the number of people who designed them.** He explains that programs designed by large committees tend to have more functions, but are less coordinated, more complex, and more error-prone than programs designed by only a few people. Brooks argues that the costs of the extra functions outweigh their benefits.

To limit the number of people giving input on the design,**Brooks calls for a strict separation of designers from programmers.** This ran counter to management practices common at the time he was writing, when the programming team helped design the software. Instead, Brooks advocates a process similar to building construction, in which the architects and construction crews are on separate teams. This reduces the complexity created by extra people introducing new ideas.

He concedes that designers and programmers still need to communicate _a little_ to keep designers within practical limitations of money and memory. Therefore, at IBM, he allowed programmers to give input but left the ultimate decision-making authority to designers.

> **When Might You Want _More_ People Making a Decision?**
> 
> Brooks's strategy of limiting the number of people making decisions stands in contrast to the popular management strategy of seeking diverse perspectives during decision-making. Andrew Grove (_Only the Paranoid Survive_) advocates this strategy, maintaining that business leaders need to get as many perspectives as they can on an issue to cut down on their blindspots. However, this isn’t to say there’s a _best_ way to make decisions—Brooks and Grove sought to solve _different problems_ :
> 
>   * Grove’s largest problem was _uncertainty._ Responsible for high-level strategic decision-making, he spent three years making one large decision when the _entire future_ of the company was at stake. Therefore, he solicited as many perspectives as he could to lower the odds of getting this decision wrong.
> 
>   * As we’ve discussed, Brooks’s largest problem was _complexity._ Managing the daily operations of a programming team, he had to make hundreds of little decisions every day and didn't have time to discuss all of them in depth.
> 
> 

> 
> In deciding which approach is best for your business, consider which is a greater threat to your company, _uncertainty_ or _complexity_. If the costs of getting one choice wrong are very high, try soliciting many different points of view to reduce the odds of getting it wrong. If the costs of getting choices wrong are diffused across hundreds of little decisions, try the Brooks approach of narrowing decision-making authority.

##### Technique #3: Let Skilled Workers Take the Lead

Brooks’s third technique for reducing communication is organizing programming teams so that they are **led by a single master programmer, who makes most of the decisions but _also does most of the work_** **while other programmers take on a supportive role as assistants.** This stands in contrast to a collaborative approach of shared responsibilities as well as a traditional hierarchical team that divides management from labor. Brooks makes two arguments in favor of his approach.

First, Brooks contends that programmers vary widely in skill level.**** Therefore, you will get the best results by identifying the most skilled programmers to do the heavy lifting and having the rest support them. Second, this will also **reduce the number of people who need to coordinate with each other.** If each team functions under the decision-making of one mind, then you only need to worry about errors of poor coordination between team leaders, rather than between all of the programmers on the staff.

(Shortform note: In the 1960s, major computer companies like IBM **often promoted skilled programmers into management,_where they no longer programmed_**. (Brooks himself began his career as a programmer before moving into management.) This was likely based on the idea that management was a "higher" position, and therefore appropriate to a company's best employees, though these promotions often took workers away from the tasks they did best. Since then, the strategy Brooks advocates has become widely adopted. In later editions of the book, Brooks praises 1980s tech startup culture for creating roles focused on programming for their most skilled programmers.)

#### Strategy #2: Coordinate Understanding Through Documentation

In addition to reducing the need for communication, Brooks argues that you can better coordinate your employees’ work by creating standardized instruction manuals.**If every programmer on the team can consult a manual with precise, agreed-upon definitions and protocols, you reduce the risk of programmers diverging.** This also creates an easier way to settle disputes between employees about protocols, as they will be able to find clear answers to their questions of procedure.

Brooks advised managers at IBM to create a written record of all their managerial decisions, large and small. **These decisions could then be copied into manuals and become protocols to inform future decision-making across the company.** While some considered his manuals excessive, Brooks emphasized they weren’t intended to be read cover to cover. Rather, he advised employees to treat manuals like an encyclopedia or a dictionary—a reference to be consulted as needed.

> **How Brooks's Thinking Changed With New Technology**
> 
> Later in life, Brooks changed his mind about the need for everyone in the company to have an encyclopedic instruction manual. He revised his thinking after the widespread adoption of _high-level programming languages_.
> 
> **A _high-level_ programming language is designed to be user-friendly to programmers and bundles combinations of instructions into simple commands**. For example, let's say a programmer wants to find the largest value in a data set. A modern programmer using Python doesn’t have to know the math their computer does behind the scenes—they simply have to remember the command: "max()." The set of instructions to carry out that function have been pre-programmed into the coding language.
> 
> However, in the 1960s, IBM programmers were working with a _low-level_ coding language, designed to meet the needs of the machine rather than those of the programmer. These languages typically lack easy-to-remember commands and require programmers to write one instruction at a time, rather than bundling sets of instructions. To find the largest value in a data set, a programmer not only needs to understand the math required to do so, but they also need to tell the computer how to do it one step at a time.
> 
> Besides making things easier, **high-level programming languages also create _standardization._** Every programmer using Python's “max()” command will call up a function with the same set of instructions as every other programmer. Brooks's programmers, writing their instructions one at a time, could all come up with slightly different functions, which is why they relied on granular instruction manuals to standardize their work.

### Part 3: Managing Time

Now that we've discussed tactics for reducing excess communication, we'll turn our attention to one of Brooks’s most daunting challenges in overseeing complex projects: **completing them on schedule**. Even with teams optimized to reduce miscommunication, any long-term project can fall behind schedule. In this section, we'll discuss Brooks’s insights on why managers often create inaccurate time estimates for their projects, factors that throw projects off schedule, and how to keep projects on track.

#### Why Managers Create Inaccurate Estimates

Sometimes projects go off schedule because the schedule itself is a poor estimate of how long they will take. Brooks identifies two reasons why managers create inaccurate estimates.

##### Reason #1: Desire to Please the Client

When clients ask for a specific deadline, **managers may be tempted to fit timing estimates to their clients' goals instead of their team's capacities.** Managers may be even more tempted to overpromise when they're pressured by a competitor promising an even faster time—whether the competitor can meet those promises or not.

Brooks offers two solutions to the temptation of overpromising. First, managers must **be honest with their clients, and estimate projects with integrity**. As a manager, you need to stick to your professional opinion, even when it disappoints a client. Second, he argues **companies should publicly release data on their productivity—including things like past project completion times**. This will give clients an accurate understanding of project times and therefore, they will make fewer unrealistic demands. This, in turn, will lower managers’ temptation to make unrealistic promises.

(Shortform note: While overpromising to please a client may offer short-term gains, studies show this can lead to disappointment, conflict, and loss of long-term gains. Research on customer conflict with companies shows that companies that promise more than they can deliver face greater backlash and have to spend more time managing conflicts with customers than companies that make realistic promises. Furthermore, companies that foster personalized relationships with their customers face even greater backlash than those that keep things strictly business, as this increases customer expectations, heightening their sense of betrayal in response to broken promises.)

##### Reason #2: Underestimating the Time to Repair Errors

Brooks argues that managers often make poor scheduling estimates **because they are too optimistic.** He considers computer programmers to be particularly optimistic by nature—as he notes, people drawn to the cutting edge of technology often like imagining a better future. This optimism often leads them to underestimate the time they will spend testing, repairing, and correcting errors.

Brooks advises programmers to take a more realistic view and plan for errors. He offers his own estimates as a guideline for allotting time to each stage of the process.

  * 1/3 for designing
  * 1/6 for programming
  * 1/4 for testing and repairing components individually
  * 1/4 for testing and repairing the system as a whole



Notice that testing and repairing take up half the schedule, while programming itself takes up the least amount of time.

> **The Planning Fallacy**
> 
> Brooks's scheduling advice focuses heavily on the field of software development. However, the problem of underestimating project times is much more widespread. In fact, **this tendency afflicts so many people that psychologists have given it a name: "_the planning fallacy_."** Some believe this is a self-serving tendency in which we overestimate our productivity to maintain a favorable self-impression. Others attribute it to wishful thinking: You want to accomplish something quickly, so you imagine you will. Psychologists have found three proven strategies for overcoming the planning fallacy:
> 
> **1\. Take the outside view.** One of the most useful tools in creating accurate estimates is knowing how long others spent on similar tasks, or how long these tasks have taken in the past. This will ground how much time you imagine it will take for you.
> 
> **2\. Break up your goal into smaller tasks.** You may underestimate how long your project will take because you simply haven't considered all the required steps. Breaking down your project into smaller goals can lead to more accurate estimates.
> 
> **3\. Take a more pessimistic view.** By expecting things to go wrong, you may be able to counterbalance your optimistic underestimation. Try brainstorming a list of problems that will delay your project, and make these delays part of your estimate.

#### The Consequences of Poor Scheduling Estimates

Brooks identifies three ways poorly estimated schedules can hinder your project:

1\. Inaccurate scheduling ensures your project comes in late.

(Shortform note: While Brooks doesn't explicitly spell this out, finishing a project behind deadline damages your company's relationships with your clients. If they were counting on your project by a certain deadline, delay interrupts _their_ operations too, guaranteeing strain on your relationship.)

2\. Missed deadlines demoralize your employees, who feel like they're failing even when they're working productively.

(Shortform note: Business experts note that chronically missing deadlines can also lower productivity by leaving your employees with the impression that their deadlines don't actually matter. As a result, even if you start creating realistic deadlines, they might not be motivated to hit them.)

3\. Inaccurate schedules lower efficiency. Because many projects require your teams to complete steps sequentially, inaccurate scheduling can create bottlenecks in your workflow.

(Shortform note: Project management experts shed further light on how inaccurate scheduling creates bottlenecks. A bottleneck results when input exceeds capacity. In other words, tasks are assigned to a worker, team, or machine at a faster rate than they can be completed. This is where inaccurate scheduling comes in. If you _underestimate_ the amount of time a step will take, then you will _overestimate_ the amount of work you can send to your worker, team, or machine—leading to the imbalance of capacity and input that produces bottlenecks.)

#### How to Stick to Your Estimates

Even the best schedule is no guarantee of timely project completion. In this section, we'll explore Brooks's insights on the factors that delay projects and his strategies for keeping a project on track.

##### Why Projects Fall Behind

Before we can understand how to keep projects moving on schedule, we first need to understand why they fall behind in the first place. Brooks found that projects typically **fall behind schedule because of _accumulated small delays_ rather than unexpected crises or catastrophes**.**** In a major crisis, most employees will recognize the gravity of the situation and increase their efforts accordingly. However, smaller delays are often overlooked and allowed to accumulate unaddressed.

This problem is compounded because **lower managers often underreport small delays.** Brooks suggests that this doesn't necessarily mean you have deceptive lower managers. They may see themselves as taking responsibility to handle the problem themselves instead of bothering supervisors with minor details. Nonetheless, this results in higher managers not knowing when a project is starting to fall behind schedule.

> **The Three Stages of Potential Delays**
> 
> In his discussion of projects falling behind schedule, Brooks primarily focuses on delays in _perceiving information_ : You don't know that a project is falling behind, because you haven't noticed all the small delays adding up. However, In _Thinking in Systems_ , Donella H. Meadows explains this is **only one stage of the process where delays can slow down a project**.**** Managers also have to consider _delays in reacting to information_ , and _delays in the consequences of those reactions_.
> 
> To use Brooks's example, let’s say a manager finally takes stock of the team's progress and realizes they've fallen behind. Now they must decide when to react: Do they immediately try to address the problem, or do they sit on it and hope the team catches up? This is an opportunity to cause a _delay in reaction_.
> 
> Once the manager reacts by implementing a new efficiency solution, how will they know when it is working? The results may take time to come into effect. This is Meadows's third delay: a _delay in the consequences of the reaction_. She argues that these delays are especially challenging because they force a manager to make decisions with incomplete information.

##### How to Avoid Delays

Brooks offers two pieces of advice for cutting back on small delays:

**1\. Set measurable, binary benchmarks.** You can track progress much more accurately by setting measurable, binary benchmarks. A measurable benchmark is one whose progress you can easily track and quantify. A binary benchmark is a benchmark that has only two states: complete or incomplete. The opposite of a measurable, binary benchmark is one that is open to interpretation as to whether it has been reached. For example, if you're building a house and your benchmark is that "most of the roof" will be done by Tuesday, "most of the roof" could mean a lot of things. Conversely, the benchmark of, “nail in 250 shingles by 5 p.m.” isn’t open to interpretation—it’s either met or it's not.

> **The Difference Between Outcome Goals and Process Goals**
> 
> Brooks highlights the importance of using measurable and binary benchmarks to assess your progress toward a goal. However, he doesn't cover what _kind of goal_ best lends itself to success. Scheduling experts argue you can track progress even more clearly by distinguishing between outcome-oriented goals and process-oriented goals. Outcome goals are focused on _what_ you want to achieve, or the end result. Meanwhile, process goals are focused on _how_ you will achieve it—the individual steps along the way.
> 
> Scheduling experts advise that **process goals are often more achievable and realistic**. This is because you have more control over a _process_ than you do over its _outcome_. For example, if your goal is to fix all the errors in a software program by Thursday, this may be unreachable because _you don't know how many errors are left in a program._ On the other hand, if your goal is to fix five errors a day until they're all eliminated, this is within your control, and will therefore provide a clearer measurement of actual progress.

**2\. Track the completion of all these specific benchmarks.** The more aware you are of small delays, the more you can prevent them from accumulating unnoticed. Once you have measurable, binary goals, record when each is completed. Brooks had an entire team whose job was to record when each goal was met.

(Shortform note: Detailed progress tracking may feel overbearing or invasive to some of your employees. However, it doesn't have to be, so long as you focus on small achievements alongside the small delays. Some management experts argue that recognizing and celebrating small wins will even boost employee morale and productivity. Because larger achievements are rare, focusing on small achievements can sustain the everyday motivation employees need to keep your project on track.)

#### Brooks’s Law: Don’t Add More Employees to a Late Project

Brooks argues that once a project becomes late, **it's a mistake to add more employees in the hopes of speeding it up.** Many managers are tempted by this pitfall, hoping that extra labor will speed up the project. Brooks asserts this will only add further delays. In fact, he calls this principle "Brooks's Law": **_Adding more workers to a late project will make it even later._ **He provides two reasons why.

##### Reason #1: New Workers Add New Complexity and Opportunities for Poor Coordination

All of those new employees need to be onboarded and incorporated into the existing workflow, which will add time and effort. Furthermore, the additional employees will add more complexity. Recall that as you increase the number of employees working together,_the opportunities for miscommunication increase exponentially._ This complexity increases the likelihood of errors, meaning more time spent testing, debugging, and correcting.

(Shortform note: Brooks focuses on how new employees will require training and add complexity to a project. However, adding a significant number of new employees can also slow down a project because your team will have to take time building _relationships_. Management experts have found that teams do their best work when their members trust and rely on each other. These relationships take time to cultivate. Therefore, a team with a significant number of new workers needs time—and perhaps some intentional team-building—before it functions effectively.)

##### Reason #2: Programming Often Requires Sequential Steps

Sometimes, you can't move from **one stage of the project to another without completing an important step.** If you’re stuck on one step, you may be tempted to add more workers to the subsequent steps to speed up the process moving forward. This will simply reduce your efficiency because they won't have anything to do until that previous step is complete. For example, if you're building a house and waiting for the cement foundation to dry, you can't speed up the process by adding more roofers. They will all just stand around costing money without anything to contribute.

(Shortform note: Project management experts distinguish between sequential and parallel workflows. In a sequential workflow, each step is completed before moving on to the next. Whereas in a parallel workflow, certain steps are completed **simultaneously to cut down on work time**. For example, let's say you are making a stir fry. Working sequentially, you would chop every ingredient before you began cooking. In a parallel workflow, you would identify the ingredients that had the longest cooking times, chop those first, and then let them cook while you chopped the rest of the ingredients, saving you time. However, parallel workflows often require more planning and management, and only work on certain projects.)

> **How Ironclad Is Brooks's Law?**
> 
> Since the publication of _The Mythical Man-Month_ , several researchers have put Brooks's law to the test. Brooks himself reviews this research in one of the later editions of the book. While the rule holds up in general, researchers have found two mitigating circumstances.
> 
>   1. Adding more workers to a project doesn't necessarily make it later if they are added very early in the process. This will give them more time to onboard and acclimate to the project.
> 
>   2. Adding more workers to a late project doesn't make it as late if the workers are _team players_ : people who naturally accommodate others and find ways of contributing, but are very open to taking instruction and changing course as directed.
> 
> 

> 
> That said, Brooks stands by his law as a rule of thumb. He argues that many managers still make the mistake of thoughtlessly throwing extra staff at a late project to speed it up, and that his law cautions them against this tactic.

### Part 4: Managing Errors

No matter how carefully you plan your project, errors and problems inevitably arise. Regardless of the industry, large projects typically involve a lot of testing, repairing, and perfecting. This last section will explore Brooks's advice on planning for and managing errors to bring your project to completion.

#### Recommendation #1: Plan to Throw Out the First Draft

Brooks argues that you should **expect to discard your first attempt at your project and treat it as a learning opportunity.** He cautions against sinking time and effort into fixing your first draft at all. In his experience at IBM, there were so many errors in the first attempt, that it was more efficient to simply learn from the process, cut his losses, and begin fresh again. Therefore, Brooks advises you to treat your first draft of the _entire project_ as a trial run.

> **Reducing Complexity in the First Draft**
> 
> In later editions of the book, Brooks changed his mind about throwing out the first draft after discovering a new process that made this unnecessary. After leaving IBM, Brooks became a computer science professor, where he was influenced by many of the ideas of his close friend, programmer David Parnas. Parnas introduced Brooks to a new process in which one "grew" the program from the middle out.
> 
> The process required drawing a distinction between a program's _core_ functions and its _ancillary_ functions. Core functions are foundational to a program's operations, whereas ancillary functions are the added features built on that foundation. If you imagine your computer program as a tree, the core functions are like the roots and the trunk, whereas the ancillary functions are like the branches and leaves.
> 
> In Parnas's strategy, **the core functions would be programmed first and tested independently before moving on to the program's ancillary functions—like growing the trunk before the branches.** In Brooks's previous process, the first draft would be a complete tree: branches, leaves, and trunk. Parnas’s process reduced complexity by reducing the number of components that need to work together in the first draft. Once Brooks adopted this strategy, he no longer found it necessary to throw out the entire first draft.

#### Recommendation #2: Expect to Create Additional Errors

One of the most vexing parts of software development is that _repairing_ errors comes with the risk of _adding_ new errors, because fixing code requires changing it. Once you change something, you always run the risk that it won't coordinate as well with all the other components. Brooks offers two main takeaways.

**1\. You will reach a point where repairing and debugging provides diminishing returns.** There's no value in polishing a program to perfection forever because your project can never be perfect. Plan on cutting your losses eventually and deciding when the project is good enough.

**2\. Programs that are patched after they hit the market will slowly degrade.** As the programmers publish new _patches_ —repairs introduced after the software has already been published—they will continue introducing new errors. Brooks asserts that patched software naturally disintegrates because every patch runs the risk of making it worse. Therefore, he advises you to plan on eventually replacing your software instead of fixing __ it forever.

> **What Is The Law of Diminishing Returns?**
> 
> Managers in all disciplines must think about the law of diminishing returns in deciding on the _optimal_ time and effort to invest into repairing errors. Economists provide clarity about the law of diminishing returns: a microeconomic principle that states that there is an optimal threshold of investment, beyond which you start getting less and less out of your investment.
> 
> For example, let's say a farmer living in an arid climate installs a new irrigation system to water their crops. Because the plants had been living under such dry conditions before, this irrigation system leads to enormous yields the first year. So the next year, the farmer installs a second irrigation system hoping to repeat the results. Instead, the crop yield stays the same. Because their first irrigation system hit the _optimal threshold_ of water for their field, adding more water now results in _diminishing returns_.
> 
> Applying this logic to Brooks's theories of programming, we see that there is an optimal threshold of time and effort to invest in debugging. Continuing to repair errors will keep introducing _additional_ errors, and once the optimal threshold is passed, additional repair will no longer improve the product. Similarly, there is an optimal threshold for patching and updating software after it has reached the market. Beyond that threshold, your time and effort will be better spent simply designing the next version of the software.

#### Recommendation #3: Don’t Build Something You Can Buy

Brooks’s last piece of advice for overcoming the challenges of managing complex projects is simply not to do it at all. Because of the inherent challenges and complexity involved in certain projects, often you can save your company a lot of time by simply buying something off the shelf instead of producing it yourself. Brooks cautions you to consider what _actually_ needs to be made in-house, and where you can cut time, cost, and labor by making a simple purchase.

> **When Should You Outsource?**
> 
> Brooks advises you to avoid complicated projects when they are unnecessary. But how do you know when it’s time to find an outside contractor? Business experts offer four recommendations on when to outsource:
> 
> **1\. Your team is at maximum capacity.** If your employees already have too much on their plate, consider approaching them to see what tasks they’d like to delegate elsewhere.
> 
> **2\. Your company lacks certain skills or specializations.** It's a good idea to outsource when you don't have the staff to deal with a highly specialized problem or task.
> 
> **3\. There's no advantage to doing it in-house.** Consider what competitive advantage you gain by doing something in-house. If it's hard to come up with one, you might want to outsource.
> 
> **4\. Scaling up too fast.** If you're a small startup growing quickly and find that you can't keep up with demand, you may want to start delegating.

[[book_md/the-mythical-man-month/preview|preview]]

[[book_md/the-mythical-man-month/exercise-create-a-schedule-for-your-project|exercise-create-a-schedule-for-your-project]]

##### Welcome!

Let’s go on a quick tour of a Shortform book guide. 

Start

##### 1-Page Summary

Every guide starts with a 1-Page Summary. This is a 5-10 minute overview of the book’s key points. 

Next

##### Finished!

If you ever need to see this tour again, click here. 

Close

Guided Tour

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__




![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=a4f185bd-8db6-46a5-af2d-98a6fa0f0b95&sid=1711133063fa11eebdec89a8b8ae3bbc&vid=171147a063fa11eea7440fcfeb230d96&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20The%20Mythical%20Man-Month&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fthe-mythical-man-month%2F1-page-summary&r=&lt=351&evt=pageLoad&sv=1&rn=818344)
