![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

Discover

Books

Articles

My library

Search

Discover

![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

# The Goal: A Process of Ongoing Improvement

Back to Discover

[[book_md/the-goal-a-process-of-ongoing-improvement/preview|preview]]

  * [[book_md/the-goal-a-process-of-ongoing-improvement|the-goal-a-process-of-ongoing-improvement]]
  * Full Book Guide

    * [[book_md/the-goal-a-process-of-ongoing-improvement/shortform-introduction|shortform-introduction]]
    * [[book_md/the-goal-a-process-of-ongoing-improvement/part-1|part-1]]
    * [[book_md/the-goal-a-process-of-ongoing-improvement/exercise-define-your-goal|exercise-define-your-goal]]
    * [[book_md/the-goal-a-process-of-ongoing-improvement/part-2|part-2]]
    * [[book_md/the-goal-a-process-of-ongoing-improvement/part-3|part-3]]
    * [[book_md/the-goal-a-process-of-ongoing-improvement/exercise-identify-your-bottleneck|exercise-identify-your-bottleneck]]
    * [[book_md/the-goal-a-process-of-ongoing-improvement/part-4|part-4]]
    * [[book_md/the-goal-a-process-of-ongoing-improvement/exercise-improve-your-bottleneck|exercise-improve-your-bottleneck]]
    * [[book_md/the-goal-a-process-of-ongoing-improvement/part-5|part-5]]
    * [[book_md/the-goal-a-process-of-ongoing-improvement/part-6|part-6]]
    * [[book_md/the-goal-a-process-of-ongoing-improvement/part-7|part-7]]
  * [[book_md/the-goal-a-process-of-ongoing-improvement/highlights|highlights]]
  * [[book_md/the-goal-a-process-of-ongoing-improvement/community|community]]



Adding to Favorites 

Removing from Favorites 

## Part 5: Structuring Around the Bottleneck

Once you identify the bottleneck and improve its capacity, you may find other problems arising that decrease throughput. In the narrative, the team goes through multiple iterations of solving problems, yielding the below principles.

### Keep Non-bottlenecks Synchronized with the Bottleneck

In the story, the team identifies a robot as the bottleneck. They devise a system whereby all parts destined for the bottleneck are always worked on at highest priority at non-bottleneck steps. This increases throughput temporarily, until they discover that at final assembly, suddenly there are shortages in non-bottleneck parts while there is massive inventory upstream of the bottleneck. How could this be?

They discover that they were **running non-bottlenecks at full-speed** and cranking out bottleneck parts **far in excess of what the bottleneck could process**. In turn, the non-bottlenecks had insufficient capacity to produce their non-bottleneck parts.

To avoid this, **you must synchronize the non-bottlenecks with the bottleneck** , to prevent massive deviations. Goldratt proposed the **Drum-Buffer-Rope** method, as follows:

#### Drum

**The bottleneck dictates the pace of production of non-bottlenecks.**

Analogy: the slow boy scout beats a drum, and others take steps with the drum beat. **If the boy scout beats more slowly, everyone else steps more slowly.**

Similarly, a machine may regularly report its production rate, and the non-bottlenecks adjust their own rates up and down accordingly.

Release starting materials to the non-bottlenecks strictly at the drumbeat rate.

  * The lead time can be calculated so the starting resources pass through upstream steps and arrive just in time at the bottleneck.
  * Similarly, all independent non-bottleneck routes can be timed so that all parts meet at assembly simultaneously.



#### Buffer

**The bottleneck should have surplus inventory upstream so it doesn’t idle.**

Analogy: non-bottleneck boys can scout ahead, clear brush so the bottleneck boy can keep walking at normal pace without having to stop.

This buffer allows for “good enough” scheduling rather than needing to be perfectly accurate.

Goldratt suggests choosing a time buffer equal to half the current lead time, then decreasing or increasing as deadlines or hit or missed.

#### Rope

**When non-bottlenecks exceed a certain surplus level, they idle.**

Analogy: tie a rope between the boy in the front and the bottleneck boy, and limit the maximum distance between the two.

Similarly, prevent work-in-process inventory from exceeding a threshold level.

  * Henry Ford purposely limited space for inventory to detect bottlenecks.
  * In Toyota manufacturing, inventory is limited to containers containing a number of units, marked by a card. When this container is withdrawn for further processing, the card is returned to the upstream work center - only then can the center produce.
  * In Kanban software engineering, no work can be added to a pipeline until the existing work has been moved to the next pipeline.



In addition, production requires prioritization - complicated chains require more parts to be worked on in the correct order to avoid queue times. As a simple heuristic, prioritize batches by **time elapsed since its release** \- the longer parts have been waiting, the higher the priority they get worked on.

### The Four Components of Processing Time

Each piece of material spends time from when it enters a plant to when it leaves:

  * Setup time: the resource prepares itself to work on the part
  * Queue time: the part waits for a resource while the resource is busy
  * Process time: the part is being modified to become more valuable
  * Wait time: the part waits for another part to be assembled together



All types of time add cost to the system and lower throughput.

**For parts going through bottlenecks, queue time is dominant. For non-bottlenecks, wait time is dominant.**

### Cutting Batch Sizes

Traditionally, larger batch sizes are seen as more efficient per part. However, this decreases agility and increases inventory.

Imagine cutting batch sizes in half, and the benefits that result:

  * You’ll halve the work-in-process inventory, which will ease cashflow.
  * You reduce queue and wait times for parts.
  * You reduce lead time from order to delivery.
  * One drawback: this will require more frequent deliveries from suppliers.



But wait - won’t cutting batch sizes increase setup time at non-bottlenecks? This isn’t really an issue. Remember, **an hour saved at a non-bottleneck is a mirage.** Reducing an hour at a non-bottleneck doesn’t increase throughput, because the bottleneck determines throughput.

(For what it’s worth, cutting batch sizes also decreases idle time, since non-bottlenecks are kept busier rather than waiting for the big batch upstream.)

### Appearance of New “Bottlenecks”

When you increase capacity at the bottleneck, you may start seeing shortages in non-bottleneck parts that hold up other parts of the chain.

While by reflex you might think this is a new genuine bottleneck, be wary - often production has so much extra capacity that it takes a _huge_ increase in throughput before this really happens.

For example, in the plot of the _The Goal_ , a non-bottleneck is producing two parts - part Y that goes through a non-bottleneck chain, and part X that goes through a bottleneck. If you focus the non-bottleneck entirely on part X, then you create a scarcity of the non-bottleneck parts Y - which creates an artificial bottleneck.

Instead, ideally you synchronize all parts that run through all chains so that the right number of parts reach the last step at the same time to meet market demand (with some buffer).

Similarly, **taking on more orders may reduce spare capacity on non-bottlenecks, depleting inventory in front of the bottleneck and starving it of work**.

### Virtuous and Vicious Cycles

As the protagonist of the narrative finds, productive practices can lead to virtuous cycles and increased competitiveness.

By adopting lean manufacturing principles like bottleneck alleviation, small batches, and Drum-Buffer-Rope systems, a **cascading series of benefits** happens:

  * You improve throughput, lower inventory costs, and limit traffic jams.
  * This decreases turnaround times.
  * This in turn reduces cost per product (by spreading fixed costs over more products).
  * Which allows lower prices and increases sales.
  * You can also respond faster to the market.



In contrast, Goldratt points out how **poor practices can lead to aggravating policies** that cause further problems. Focusing on cost-accounting and local efficiencies:

  * Causes full activation of resources to prevent idling.
  * This increases inventory and causes longer queues for parts.
  * This causes a greater backlog and missed deadlines.
  * This in turn prompts earlier release of starting material (a natural reaction), which increases work-in-progress inventory and aggravates the situation.
  * Also, this prompts people to ask for more capacity and increase batch sizes (for the sake of efficiency), which further increases inventory, causes traffic jams requiring more management attention.
  * All of these symptoms decrease sales.



[[book_md/the-goal-a-process-of-ongoing-improvement/exercise-improve-your-bottleneck|exercise-improve-your-bottleneck]]

[[book_md/the-goal-a-process-of-ongoing-improvement/part-6|part-6]]

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=eb604154-7f23-41ff-bfbd-bbdfdf79a08d&sid=1711133063fa11eebdec89a8b8ae3bbc&vid=171147a063fa11eea7440fcfeb230d96&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fthe-goal-a-process-of-ongoing-improvement%2Fpart-5&r=&lt=327&evt=pageLoad&sv=1&rn=653693)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



