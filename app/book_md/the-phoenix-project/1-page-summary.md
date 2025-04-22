![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

Discover

Books

Articles

My library

Search

Discover

![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

# The Phoenix Project

Back to Discover

[[book_md/the-phoenix-project/preview|preview]]

  * [[book_md/the-phoenix-project|the-phoenix-project]]
  * Full Book Guide

    * [[book_md/the-phoenix-project/exercise-apply-the-pillars-of-production|exercise-apply-the-pillars-of-production]]
  * [[book_md/the-phoenix-project/highlights|highlights]]
  * [[book_md/the-phoenix-project/community|community]]



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

A business today lives or dies based on the strength of its IT department. Because information technology is so deeply integrated into everything a business does—from producing goods and services to interacting with customers, processing orders, and even paying its own employees—every company in the modern age has to be proficient in how to optimize IT services. Not doing so risks heavy consequences, up to and including the failure of the business.

_The Phoenix Project_ , published in 2013, presents a fictional case study of just such a scenario—an imaginary auto parts manufacturer that’s falling behind its competitors because it’s unable to align the work of IT services with the company’s larger goals. A new business initiative, dubbed “The Phoenix Project,” promises to bring the company into the 21st century by integrating online ordering, in-store sales, inventory management, and marketing campaigns. However, by botching the Phoenix rollout, the auto parts company almost implodes from a disastrous series of technical failures.

The authors of _The Phoenix Project_ are Gene Kim, founder of the digital security company Tripwire, Kevin Behr, who co-founded the IT Process Institute along with Kim, and George Spafford, Vice President Analyst for the business consulting firm Gartner. Together, they use their combined expertise in technology management and business practices to paint a picture of how a company that does everything wrong when it comes to IT can turn itself around, revamp its core practices, and get back in the competitive game.

In this guide, we’ll begin by summarizing the decline and phoenix-like resurrection of the fictional Parts Unlimited’s IT department. We’ll then dissect the story’s central message, first by explaining the authors’ diagnosis of what makes IT processes fall apart, then by describing the three fundamental pillars of IT management that Kim, Behr, and Spafford prescribe as a remedy—speeding up workflow, providing quick feedback, and encouraging a culture of perpetual improvement.

In addition, we’ll provide clarification on IT, business, and production concepts that the authors assume the reader’s already familiar with. We’ll discuss the practice of using fiction as a teaching tool for real-world situations and explore other authors’ ideas on management, leadership, workplace culture, and maximizing workplace productivity.

> **Fiction as a Teaching Tool**
> 
> In the last few decades, fictional scenarios like the one presented in _The Phoenix Project_ have become a popular tool for management writers. Fiction can illustrate otherwise dry business ideas in a way that emotionally connects with readers. Examples include _Who Moved My Cheese? _by Spencer Johnson and Patrick Lencioni’s _The Four Obsessions of an Extraordinary Executive_.
> 
> Some critics argue that the “business fable” genre often falls flat due to unsubtle, hamfisted storytelling and shallow characters who only exist to advance the authors’ arguments. However, some reviewers have praised _The Phoenix Project_ for realistically portraying the dysfunctional culture and personality conflicts that plague corporate environments and for making its concepts easily understandable so that they can be applied by the reader.

### The Saga of an IT Department

Our story focuses on the character Bill Palmer, a mid-level director at Parts Unlimited who’s promoted to vice president (VP) of IT Operations shortly before the grand rollout of the Phoenix Project, an online sales management tool that’s been years in the making. What he finds, though, is an IT department in utter disarray, stretched to its limit by constant demands and arbitrary deadlines it can’t possibly meet. Right out of the gate, Bill must cope with an emergency payroll issue, an ongoing conflict between IT Operations and the software development team, and a prospective board member who suspects that Bill’s IT department is going about its business all wrong.

On his first day as VP, Bill is thrust into trying to solve a payroll data problem that could result in many workers not receiving their paychecks. The difficulty resolving the issue is compounded by the lack of communication within the department. After sleepless nights and much departmental overtime, Bill determines that the root of the problem was a system change enacted by a vendor without the department’s knowledge. This clues him into what the authors say ought to be obvious in hindsight: **A process for tracking and approving system changes is essential to IT management.**

(Shortform note: As illustrated in the example above, change management and risk management go hand in hand, since a company’s information system must protect sensitive data regarding its business, its employees, and its customers. When implementing measures to approve and track changes, managers should express the importance of risk management to IT team members and the security risks that unauthorized changes might introduce, such as failing to properly encrypt passwords or enabling unauthorized access to the system.)

With the launch of the Phoenix Project on the horizon, Bill also has to mediate between his own department (Ops) and Application Development (Dev). Development accuses Ops of not prioritizing work such as Phoenix because Ops spends all of its time putting out fires like the payroll debacle. Operations fires back that Dev hasn’t left Ops enough time to properly test Phoenix before launch, nor has Dev provided the system specifications and operating instructions Ops will need to roll it out, meaning that Ops will still be fixing Phoenix problems even after the new system has already gone live. Much of that work will have to wait on Brent, the only software engineer who fully understands the company’s systems and can fix them.

(Shortform note: While Operations’ and Development’s roles can be inferred from context in the novel, they’re never explicitly spelled out. The Development group is responsible for generating new software, databases, and online interfaces, whereas IT Operations is responsible for maintaining the company’s existing hardware and software while installing and implementing new products created by Development. Even in companies where the two divisions are separate, there’s still significant overlap in their functions. IT Ops creates and maintains the systems within which Development designs new applications, and to do that effectively, Ops personnel must understand the tools and methods developers use.)

While trying to come to grips with the chaos in IT and the impending Phoenix launch, Bill meets Erik Reid, a management expert whom Parts Unlimited is courting to be a board member. Speaking on behalf of the authors, Erik understands Bill’s problems even better than he does, but Erik doesn’t spill his knowledge all at once. Instead, he gives Bill a few guiding pointers such as the need to understand **the different types of work, the danger of bottlenecks, and the three pillars of IT management** —fast workflow, quick feedback, and perpetual improvement (all of which we’ll expand on in this guide).

(Shortform note: Erik is a prime example of an author surrogate character—a figure who exists in a story to let the authors speak directly to the reader, usually for the purpose of expounding on the authors’ beliefs. Classic examples of author surrogates are John Galt, the character who interrupts Ayn Rand’s _Atlas Shrugged_ to instruct the reader on Rand’s philosophy of Objectivism, and Ishmael from Herman Melville’s _Moby-Dick_ , who repeatedly stops the story to discuss the minutiae of whaling. Galileo Galilei used the same literary technique to stage a fictional debate on the nature of the universe in his _Dialogue Concerning the Two Chief World Systems_.)

#### The Phoenix Disaster

In spite of Bill’s apprehensions, the Phoenix Project launch goes _even worse_ than anyone could have imagined. Thanks to the combination of a dysfunctional corporate culture, unrealistic expectations, and a lack of collaboration between Dev and Ops, the Phoenix release crashes not only the company’s online ordering system, but also the ability of their brick-and-mortar stores to make sales or process credit card transactions.__ The authors use the crisis to illustrate many points of failure—between management and IT, between Dev and Ops, and within IT Operations itself.

Even before the failures begin, Bill goes to the CEO begging for more resources, as well as permission to prioritize Phoenix above any other demands on IT. The CEO refuses to budge, demanding that IT make do with what it has and give equal weight to every request made by the organization. Meanwhile, Ops is unable to get Phoenix to work in a simulated test environment. Nevertheless, since the company’s marketing has already announced Phoenix’s release to the media, IT is forced to move ahead with implementation.

(Shortform note: In layman’s terms, a software development environment is made up of the computer hardware, operating systems, and other applications within which software is designed before implementation. Such environments are used to create software, test it, and model how it will be implemented into end-users’ devices. In _The Phoenix Project_ , issues arise because the development, testing, and production environments aren’t identical, leading to glitches in one environment that don’t appear in the others. Because no test environment can predict how software will behave on every device it’s installed on, many companies now employ beta testing and quick user feedback in order to test software once it’s been released.)

The Phoenix release almost destroys the company, making it hemorrhage money and customers as sales become nearly impossible to complete and users’ credit card data become unsecure. The CEO lays all the blame on IT and even threatens to outsource the whole department if Bill can’t find a way to meet the company’s bloated expectations. The authors show how this is a point of common ground between Dev and Ops because **Operations and their counterparts in Development are frequently asked to perform miracles with little or nothing to go on.** Bill despairs about finding any solution, and he considers leaving the company altogether.

(Shortform note: The authors imply that outsourcing IT services would be a disaster for their fictional company, arguing that in-house IT is inherently superior. Outsourcing IT does have disadvantages such as taking a company’s internal systems controls out of its hands and into those of a consultant, thereby limiting that company’s flexibility to adapt quickly to changes in its market. However, outsourcing IT also has advantages: Contracting an outside company to provide IT support can reduce operational costs, provide access to a broad range of skilled professionals, and help keep a company up-to-date with industry standards.)

#### The Turnaround

Bringing the company back from the brink is a larger job than merely IT’s. With some nudging from potential future board member Erik, the CEO admits his own culpability while Bill begins to envision new ways to correct IT’s problems and prevent them in the future. These include the short-term solution of stopping all work on everything except Phoenix while restructuring for the long term to produce faster, smaller product releases that allow for quicker testing and releases.

Bill suggests stopping any work unrelated to Phoenix. This includes not accepting any new projects into the IT workstream until enough of the work in progress is completed and his team can assess IT’s technical debt—the amount of future work that’s accrued by taking shortcuts and quick fixes in the past. It also gives them time to better manage Brent, the one engineer whose skills are so essential that he acts as a bottleneck to all of IT’s work.

(Shortform note: The authors don’t define _technical debt_ , which is a general industry term for software issues that designers put off solving in favor of short-term workarounds. Technical debt can take the form of software bugs, wasted resources, and misleading documentation. Incurring technical debt allows developers to move ahead on projects that are at least partially working, under the assumption that they or someone else will make time in the future to resolve the problem’s underlying issues. Left unchecked, technical debt leads to faulty applications, longer development time, and disgruntled customers whose software doesn’t work as promised.)

The freeze on new tasks gives IT enough space to correct some of Phoenix’s problems while also giving Bill room to explore how IT’s work impacts the company as a whole. According to the authors, that impact is huge. IT’s functions support every single business goal of a modern corporation in one way or another. From his research into the company’s needs, Bill realizes that the Phoenix Project—one giant platform, years in the making, designed to do everything, everywhere, all at once—was ill-conceived from the start. **What’s been needed all along are smaller applications that are faster to design, test, and roll out,** and that can therefore be more responsive to customers’ needs in real time.

(Shortform note: Though the authors tout the advantages of designing and implementing smaller software packages, there are trade-offs involved in turning away from larger applications. Small applications may lack the rich functionality of larger ones and they may not be as _scalable_ —meaning that they won’t respond as well as large programs to changes in the volume of usage of the amount of data being processed.)

##### The Unicorn Project

While Bill keeps some of his team on the job to stop Phoenix from sinking the company’s boat, he devotes the rest of IT’s resources to a new initiative called “Project Unicorn,” which merges Dev and Ops in a collaborative cycle that automates their redundancies and allows them to design, test, and implement software solutions at a rapid pace. Using the Unicorn structure, Dev and Ops are able to bypass Phoenix entirely and deliver on its promised functions by creating smaller, more versatile applications.

(Shortform note: Gene Kim wrote _The Unicorn Project_ as a standalone companion to _The Phoenix Project_ , one that retells the story from the point of view of a software developer. Whereas _The Phoenix Project_ places its emphasis on IT management, _The Unicorn Project_ highlights fundamental principles of software design—namely that code should be simple, use readily available resources, and be focused on serving the needs of the customer. Kim also stresses that a good work environment for software designers should let them find joy in creativity, encourage continual self-improvement, and allow designers to safely report their mistakes and seek help when needed.)

After the success of the Unicorn Project, Bill builds on IT’s work by launching a program to continually test their systems for weakness and introduce improvements, both to the software they create and to the process by which IT functions. As a result of Bill’s success in IT, the CEO places him on a fast track to become Parts Unlimited’s next Chief Operating Officer (COO). The authors predict that in the future, most corporate COOs will have backgrounds in IT because IT is now so heavily integrated into every business function a company performs.

(Shortform note: While it’s too soon to tell if the authors’ predictions are correct, it’s true that many COOs rise to their position because of their strategic skills and creative problem-solving abilities. A COO needs to understand both the technical and business aspects of how a company functions to help all the divisions within a business work in conjunction and not against each other’s interests. The COO is often the CEO’s second-in-command and has usually worked in multiple positions at several different companies before rising to that level.)

### Work and What Stops It

Throughout their narrative, Kim, Behr, and Spafford illustrate the common workflow challenges that plague IT departments. At the root of these issues, when they occur, is a failure to recognize, prepare for, and manage the two greatest disruptors of productivity—unexpected work and bottlenecks.

In the story, Erik challenges Bill to identify and understand the four types of work IT performs. The first of these are business projects initiated by the company or one of its divisions, such as sales, marketing, or human resources. The novel’s titular Phoenix Project is a business initiative on the largest scale. The second type of work constitutes internal IT projects, such as upgrading servers or migrating data. The third class of IT work is made up of changes, often minuscule, to databases, app configurations, and lines of code. The authors suggest that such changes are a major source of work and potential problems that, if unmanaged, contribute to the fourth type of work IT does—unexpected work that grinds the system to a halt.

> **Sources of Work in IT**
> 
> The way the authors differentiate between “business projects” generated by the company at large and “internal projects” generated by IT might at first glance seem to imply that IT is inherently separate from the rest of the organization, an attitude that the authors discourage later in the book. A potentially more useful distinction is that business projects advance the company’s business goals directly, while internal projects serve those same goals indirectly __(for example, by improving overall efficiency). To make sure projects stay on track and maintain buy-in from the people involved, it’s important that any project be clearly aligned with the company’s goals—whether that project is internal to IT or in support of another division.
> 
> From a layman’s perspective, the type of IT changes the authors describe can often seem perplexing—such as when a program you’re using or your operating system mysteriously updates itself with no discernible change in performance. Nevertheless, these seemingly constant updates are vital to keep up with advances in technology, fix software bugs, close security vulnerabilities, and stay in compliance with ever-changing legal regulations. From a business perspective, these changes also arise as a result of user feedback and market research to determine how to better match a company’s products with customer demand.

Unexpected work is almost always an emergency, or at least is made to seem that way, and it gets in the way of doing anything else. Unexpected work includes fixing a nonstop flood of technical problems, many of which aren’t prioritized by importance, but rather by how vocal the person complaining about the issue is. What’s worse, **unexpected work creates even more work** by taking time away from the system testing and preventive maintenance that would stop such problems from arising in the first place. To correct unexpected problems quickly, the solutions implemented are often untested patches and workarounds that build up technical debt in the system, laying the groundwork for more unexpected problems.

(Shortform note: In the authors’ fictitious company, as well as in many real-world organizations, people have learned that the quickest way to get IT’s attention is to treat every problem like an emergency. However, this makes prioritizing difficult. One solution may be to implement a priority matrix, as described by Steven Covey in _First Things First_. While those tasks that are truly urgent will require immediate attention, Covey argues that the most important work is that which will have a significant impact but hasn’t yet risen to the level of an emergency. Making this category of work a priority will ideally prevent problems from becoming emergencies at all.)

#### The Bottleneck

The authors say that the other work stoppage in any system is the _bottleneck_ (which the authors refer to as the _constraint_), defined as **the one link in the chain that limits the speed of the entire production process.** In the fictional example, the bottleneck is Brent, the lone engineer whose unique and exhaustive knowledge of Parts Unlimited’s computer systems makes him the indispensable go-to guy for every task IT tries to perform. As a result, IT can’t do anything without involving Brent in some way, and so no work gets done any faster than Brent is able to get to it. Because Brent is so overburdened, he doesn’t have time to document his work, which means his knowledge isn’t shared and IT becomes even more reliant on him as a crutch.

(Shortform note: One danger of the particular type of bottleneck Brent represents is that employees overloaded with so many tasks risk burning out from the combination of high demands, insufficient resources, and little or no recovery time between switching from one emergency to another. Though _The Phoenix Project_ doesn’t address this directly, 75% of workers experience burnout at some point. Preventing workplace burnout requires listening to employees’ needs, curbing excessive overtime, and building a workplace culture based on clearly defined roles and expectations.)

Brent is merely one example of the kind of bottlenecks that can constrict a system. The authors list other types of bottlenecks based on those described in _The Goal: A Process of Ongoing Improvement_ by Eliyahu M. Goldratt. These include the creation of test environments for software, installing large amounts of new code, and getting approval for changes from committees. Whatever your system’s bottleneck is, the authors are clear that **you can’t push work through your department any faster than your bottleneck will allow.** Any attempt to do so will result in a traffic jam of work piling up at one station while the rest of the production line sits idle.

(Shortform note: Though the authors derive most of their ideas about managing bottlenecks directly from _The Goal_ , Goldratt makes some recommendations that aren’t echoed in _The Phoenix Project_. One is to decrease workstations’ idle time, which Kim, Behr, and Spafford caution against, as we’ll see in the following section. Another is to outsource the bottleneck’s functions, which _The Phoenix Project_ ’s authors also don’t recommend. In _The Goal_ , Goldratt doesn’t discuss pesky human factors such as personality clashes, bureaucratic hold-ups, and company values that also contribute to the problem of bottlenecks and trying to unstop them.)

### The Pillars of Production

None of the problems of IT are insurmountable, but Kim, Behr, and Spafford argue that addressing them requires completely rethinking how IT work is done. In their fictional case study, they demonstrate how work management principles developed on factory production lines can be applied in an IT environment, where the production of software, databases, and networks can be likened to manufacturing physical products. The three foundational pillars of production can be summed up as 1) fast workflow, 2) quick feedback, and 3) continual improvement.

Because the authors’ point-of-view character is a vice president of IT operations, one might assume that their advice is intended for readers in corporate management positions. However, understanding the principles that follow will be essential for everyone in the production process, since implementing the authors’ recommendations will require buy-in from many people in a company and certainly everyone in IT.

(Shortform note: The authors’ core concepts (which we’ll discuss in the sections that follow) evolved from principles of ITIL, Lean, and Agile production methods, which are mentioned in _The Phoenix Project_ but not explained in depth. ITIL (Information Technology Infrastructure Library) is a set of best practices for delivering IT services that were introduced in the 1980s and have continued to develop over time. Lean production is a manufacturing process first developed at Toyota that minimizes waste within a production system. Agile project management is a system that takes Lean principles and applies them to software development.)

#### Pillar 1: Fast Workflow

The first keystone, “fast workflow,” may sound like a _goal_ and not a place to start. However, the authors lay out a series of procedures that can establish a faster flow of work through IT from the outset. These include creating a visual tracking method to monitor and schedule work through IT, reducing the paths by which work enters the pipeline, breaking projects down into smaller, independently manageable components, and opening up your bottleneck so that work flows through it as quickly as possible.

To begin with, **managing workflow is impossible without a way to monitor its progress.** The authors repeatedly recommend using a _kanban board_ (a visual tool that shows the status of tasks as they pass through IT) both for tracking work and for scheduling tasks as they come in. A visual tracking tool lets you document how much time a task takes at each station, and therefore it indicates how much work you can afford to take on. If certain tasks are regularly repeated, then documentation will allow you to plan for exactly how much time they will take. It will also make you aware of how many time-consuming handoffs occur as a task is passed from one station to the next and whether you can reduce those handoffs in order to speed up workflow even more.

(Shortform note: The kanban __ boards the authors mention are a production tool first developed by Toyota to visually track issues on their car production lines. They have since become a standard tool for tracking work through any kind of production process, and while kanban boards can be digital, the simplest ones—as depicted in _The Phoenix Project_ —are just whiteboards with vertical columns depicting each stage in the production process and sticky notes representing each project moving through the system. In _Personal Kanban_ , Jim Benson and Tonianne DeMaria Barry describe how kanban __ boards can be used by individuals to manage tasks in their daily work and personal lives.)

As you monitor your department’s workflow, you’ll also become aware of all the different avenues by which work—often _unexpected_ work—enters and confounds the flow of operations. People in many organizations have grown used to calling IT staff directly to fix what they perceive as “urgent” computer problems, interrupting and backlogging whatever projects your staff was meant to be working on. **Identifying where and how unexpected work interrupts production is the first step in limiting the amount of work in progress.** The authors stress that doing so is vitally important to speeding up IT production.

(Shortform note: Unexpected interruptions are doubly deadly to IT workflow. Not only do they back up the whole production process, as the authors describe, but they also hinder individual workers’ ability to focus on _any_ given task. In _Eat That Frog!_ , Brian Tracy details the cost of multitasking—or “task shifting,” as he more accurately describes it. After being interrupted, it takes 17 minutes to completely refocus and continue with your work. Multiply that by the number of IT personnel who are interrupted by one crisis after another, and it’s clear how badly unexpected disruptions can impact overall efficiency.)

Another key component of speeding up workflow is to reduce the size of the projects you take on. Huge projects meant to accomplish multiple business goals at once, such as the authors’ disastrous Phoenix Project, are so unwieldy that identifying design problems and errors is that much more time-consuming and difficult. **Dividing large projects into small, discrete units can let each part move through design, testing, error-fixing, and rollout in a timely manner,** sometimes on the order of days or weeks instead of months or years. If there’s any fundamental flaw in one of the smaller components of a project, it can be caught and corrected that much sooner, before it can have a devastating impact on the whole.

> **Individual Focus Applied to a Team**
> 
> The authors’ suggestion to break large projects into small, discrete units is a common piece of advice that productivity experts usually prescribe to individual workers. For example, in _Eat That Frog!_ , Tracy lists breaking tasks into actionable steps as both a cornerstone for making large goals achievable and an effective way to avoid distraction. In the context of _The Phoenix Project_ , that distraction takes the form of nonstop demands on IT’s time.
> 
> At Google, software designer Jake Knapp devised a method for addressing that form of distraction by taking personal productivity tools and applying them to achieving team goals. In _Sprint_ , he and co-authors John Zeratsky and Braden Kowitz describe a process for gathering a team and shutting out distractions such as email and meetings for a specific amount of time—such as a week—in order to complete the design of a tightly focused product with an incredibly rapid turnaround.

##### Open Your Bottleneck

The authors insist that to truly speed up workflow through IT, you should make the most efficient use of your bottleneck. By visually monitoring the work through IT, you’ll quickly identify where the bottleneck is—most likely one overburdened workstation. Though it may be counterintuitive, **workstations need idle time in order for work not to pile up.** The authors provide a simple formula to determine how much time a task will spend in the queue at any given station (the wait time) depending on how much time that station spends idle:

Wait time = Percent of time busy / Percent of time idle

According to this formula, wait times at a station that’s 80% busy and 20% idle will be four times longer than at a station that’s 50% busy and 50% idle.

(Shortform note: The authors’ suggestion that workstations and employees should have a certain amount of idle time goes against the grain of using efficiency as a way to cram in even more work. In addition to the authors’ mathematical reasoning, some studies have shown that downtime on the job is vital to mental health and productivity. Some research has revealed that the brain requires regular rest periods throughout the day to maintain its full cognitive function. Nevertheless, we must note that in order to be productive, downtime should be planned and not the result of unforeseen equipment breakdowns or poor communication.)

Once you’ve identified your bottleneck, you can arrange your workflow so that you don’t send work to the bottleneck faster than it can handle. Tracking work will also let you know if any of the bottleneck’s work can be automated. If the reason for the bottleneck is unshared skills or knowledge, as in the fictional example of Brent the software engineer, you should **document everything the bottleneck does so that knowledge and skills can be shared among your team,** eventually leading to sharing of the workload. Once one bottleneck has been opened up, you may find another in your production line. If so, apply the same steps as before.

(Shortform note: What the authors describe is a formalized process to convert individual knowledge into institutional knowledge. However, individual knowledge includes more than practices and procedures that can be written down. Individuals have skills and intuitions that can only be acquired and passed on through training and experience. Documentation is certainly vital, but to truly build institutional knowledge, a business must make its knowledge easily accessible to employees while encouraging seasoned workers to mentor new team members, even as early as the onboarding process.)

#### Pillar 2: Quick Feedback

In order for a streamlined, faster workflow to be beneficial, your system must generate and implement corrective feedback all along the production chain. Feedback cycles, like your projects themselves, should be small and efficient so that problems can be identified quickly, connecting both Development and Operations, and resolved in a way that generates new information.

The authors note that systems such as large software packages and sprawling computer networks are far too complex for any one person to fully understand. Therefore, work on those systems must be designed in such a way that errors can be detected and corrected quickly. Small project sizes let you catch and fix problems before they become disasters, but to enable this, **your production process must generate feedback at every step in which work is performed.** One example of a way to create this kind of feedback is to institute checklists for every task being done, especially at any point in the process where work is passed from one station to another.

(Shortform note: In _The Design of Everyday Things_ , Don Norman describes the “small product” feedback loops recommended in _The Phoenix Project_ as a cycle of iteration that’s intended to generate errors as fast as possible so that they can be quickly corrected. Norman favors this approach for small projects only, arguing that for large projects, implementing constant testing and feedback is cost-prohibitive. Kim, Behr, and Spafford don’t dispute this point, and it may be part of the reason why adherents to their design philosophy argue against large, resource-intensive projects altogether.)

Feedback cycles can’t be confined to Operations—they must include Development as well. Developers must know if their code is effective or problematic as quickly as possible, not months down the line after they’ve moved on to other projects. The authors say that **feedback from Ops must be incorporated into the very beginning of the Development process,** in effect merging the two departments into one cohesive DevOps gestalt. Ideally, the feedback and response time between designing and installing new systems needs to be fast enough to keep up with customer demand, whether those “customers” are clients of your company or other departments inside your organization.

(Shortform note: To shape the beginning of the development process, feedback loops must transmit information all the way back from the _end_ of the process. In _User Friendly_ , Cliff Kuang and Robert Fabricant explain that designers must understand the end-user by observing and empathizing with customers’ experience—what they enjoy about using the company’s software, and what frustrates them about it. An effective information loop provides feedback in the user’s direction as well. For example, an effective online store design will unambiguously let customers know if they’ve successfully completed a purchase—and if not, then _why_.)

The moment your feedback measures detect a problem, it should be fixed immediately, not patched with a workaround and put off until later. The authors insist that **problems should be tackled by the people closest to them as part of their regular responsibilities.** More than that, those people should bring in as much help as they can get from their department to resolve the issue. This way, the issue becomes a learning opportunity that generates new knowledge for the organization. By documenting the whole solution process, that knowledge becomes embedded in IT's procedures and toolkit for future problems.

(Shortform note: There’s a lot more to documenting institutional knowledge than simply writing down the steps people take to solve problems, though that’s certainly a place to start, as it is in the authors’ scenario. In order to be useful, that documentation has to be easily accessible to any employees who need it. In practical terms, it can take many forms, such as flowcharts, training manuals, and internal databases, all of which take time and effort to design, organize, and curate. None of this can be done haphazardly, but must be part of a company’s overall knowledge management strategy.)

#### Pillar 3: Constant Improvement

The last and perhaps most important component to harnessing IT’s—or any system’s—full productivity is to **create a culture of continual improvement through practice, repetition, experimentation, and _useful_ failure. **Using the story of their fictional company’s ill-conceived “Phoenix Project,” the authors provide a negative example of a company with a toxic workplace culture and a blueprint for a better way to encourage growth, development, and innovation that benefits your business as a whole.

The defining characteristic of a toxic workplace is that employees’ behavior is guided by a constant fear of failure. In such a culture, administrators address mistakes and malfunctions by assigning blame and taking punitive action. As a result, people are discouraged from identifying errors and problems in a system. Feedback is silenced, because who will provide it when the default cultural response is to kill the messenger? Toxic work cultures stifle any improvement, and without constant improvement, a system will stagnate and problems will fester until they become catastrophic.

On the other hand, **a productive company culture will encourage people to report problems at once.** The authors show that if employees can trust that they won’t be reprimanded—and may in fact be _rewarded_ —for identifying and helping solve issues detrimental to the company, then those employees will feel an ownership stake in seeking out ways to improve the whole system. If they’re encouraged to take risks in the process by trying solutions that may or may not work without fear of reprisal from on high, then your company will foster a culture of innovation in which even failed attempts at improvement are seen as a way to generate knowledge that can be shared across the organization.

> **The Value of Making Mistakes**
> 
> A corporate culture in which mistakes and failures are rewarded as long as they move the company forward may not be as unlikely as it sounds. In _Reinventing Organizations_ , Frederic Laloux says that such companies already exist and that they represent the next stage of organizational evolution. These companies run on the basic assumptions that workers can be trusted to make good decisions and that when employees feel they have an ownership stake in the company’s success, they’ll hold themselves accountable for their mistakes without any threat of administrative punishment. Meanwhile, that same culture of trust gives workers the freedom to unlock their full creative potential.
> 
> As a counterexample to the toxic workplace depicted in _The Phoenix Project_ , consider that of Pixar, as presented by its co-founder Ed Catmull in _Creativity, Inc._ According to Catmull, embracing failure as positive is an essential ingredient to Pixar’s innovation and success in the animated film industry. The key is to normalize failure by removing its associated stigma of fear. That way, when mistakes are made, people come together as a group to address them with creative solutions, rather than retreating into personal silos to avoid receiving blame. To destigmatize the inevitable mistakes that arise from experimentation, managers must cultivate trust by taking risks themselves and admitting their own errors.

Finally, the authors state that businesses should formalize their systems of continual improvement. IT staff can hone new solutions and practices while refining them through repetition and practice. Teams within DevOps can root out flaws in their products by pushing their products’ limits, forcing errors to emerge before they crop up on their own. One way to accomplish this is to **deliberately introduce faults and design flaws into the production line** so that staff can practice identifying errors, providing feedback, and coming up with resolutions. Not only can you identify systemic deficiencies in this way, but you’ll also promote a culture in which experimentation, risk-taking, and learning become an institutional way of life.

(Shortform note: The idea of deliberately making mistakes to test a system predates _The Phoenix Project_ or even the modern IT department. Inventors, advertisers, and even telephone companies have introduced deliberate errors into their practices to test their guiding assumptions. In order to make productive mistakes, it’s important to know what a system’s underlying assumptions are. Mistakes should be designed to confirm or dispute those beliefs, especially when those assumptions are the basis of regular, automatic decisions.)

> **DevOps, Past and Present**
> 
> The ideas behind DevOps—the merger of software development and IT operations into one department—began to cohere about five years before being illustrated in The Phoenix Project. The term “DevOps” was coined in 2009 by Patrick Debois of the photography website Flickr. As a management and design philosophy, DevOps gained traction in the business world over the following decade, allowing products to get to market more quickly while fostering ingenuity and creative experimentation, especially in the software industry.
> 
> Currently, DevOps principles are fueling a trend toward applications based on microservice architectures in which individual functions and processes are handled by small, modular units of software. There has also been a shift toward cloud-based computing that lets developers build software without spending their own time and resources building the hardware to support it. Finally, DevOps practitioners are using artificial intelligence and machine learning tools to enhance system operations, speed up software deployments, and enable faster testing and analysis of new products.

[[book_md/the-phoenix-project/preview|preview]]

[[book_md/the-phoenix-project/exercise-apply-the-pillars-of-production|exercise-apply-the-pillars-of-production]]

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

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=9489e2f4-5ff1-4517-b3c2-40f33d56b954&sid=1711133063fa11eebdec89a8b8ae3bbc&vid=171147a063fa11eea7440fcfeb230d96&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fthe-phoenix-project%2F1-page-summary&r=&lt=283&evt=pageLoad&sv=1&rn=327817)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



