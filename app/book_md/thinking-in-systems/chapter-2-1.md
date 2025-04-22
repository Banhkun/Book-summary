![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

Discover

Books

Articles

My library

Search

Discover

![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

# Thinking in Systems

Back to Discover

[[book_md/thinking-in-systems/preview|preview]]

  * [[book_md/thinking-in-systems|thinking-in-systems]]
  * Full Book Guide

    * [[book_md/thinking-in-systems/introduction|introduction]]
    * [[book_md/thinking-in-systems/part-1|part-1]]
    * [[book_md/thinking-in-systems/exercise-define-a-system|exercise-define-a-system]]
    * [[book_md/thinking-in-systems/chapter-1-2|chapter-1-2]]
    * [[book_md/thinking-in-systems/exercise-feedback-loops|exercise-feedback-loops]]
    * [[book_md/thinking-in-systems/chapter-2-1|chapter-2-1]]
    * [[book_md/thinking-in-systems/chapter-2-2|chapter-2-2]]
    * [[book_md/thinking-in-systems/part-2|part-2]]
    * [[book_md/thinking-in-systems/exercise-improve-your-system|exercise-improve-your-system]]
    * [[book_md/thinking-in-systems/chapter-4|chapter-4]]
    * [[book_md/thinking-in-systems/chapter-5|chapter-5]]
    * [[book_md/thinking-in-systems/part-3|part-3]]
    * [[book_md/thinking-in-systems/chapter-7|chapter-7]]
  * [[book_md/thinking-in-systems/highlights|highlights]]
  * [[book_md/thinking-in-systems/community|community]]



Adding to Favorites 

Removing from Favorites 

## Chapter 2-1: Building More Complicated Systems

In reality, systems are much more complex than the simple examples we’ve covered so far.

  * A single stock may not just have an inflow and outflow, but really have multiple flows in and out, as well as multiple balancing and reinforcing loops working in opposite directions.
  * A single flow may affect dozens of stocks.
  * Feedback loops affect each other, reinforcing each other or balancing each other.



For example, the world population has an inflow representing birth rate, but birth rate is influenced by a vast number of inputs, such as the overall economy, healthcare, and politics, which are themselves complex systems.

In this chapter, we’ll take what we’ve learned and build up to more complicated systems, which are simplistic models of real-world systems. The author calls this collection of systems a “zoo,” which is an appropriate metaphor. Like in a zoo, these animals are removed from their natural complex ecosystem and put in an artificially simplistic environment for observation. But they give a hint of patterns in the real world and yield surprisingly insightful lessons.

### One Stock + Two Balancing Loops

First, we’ll look at a system with one stock and two balancing loops that compete against each other. We know that a balancing loop tries to bring a stock back to a setpoint. What happens when two balancing loops have different setpoints but act on the same stock?

The concrete example we’ll use is a thermostat that heats a room that is surrounded by a cold environment.

  * The stock is the temperature of the room.
  * One balancing loop is the cold outside environment, which constantly absorbs heat from the room that leaks through the walls and windows. This loop tries to bring the room’s temperature down to the cold outside temperature.
  * The other balancing loop is the thermostat and the furnace, which tries to bring the room’s temperature up to the thermostat temperature.



The stock and flow diagram looks like this:

![thinking-in-systems-thermostat.png](https://media.shortform.com/images/thinking-in-systems-thermostat.png)

So how does the system behave? It depends on which balancing loop is stronger:

  * If the room insulation is airtight and the furnace is strong, the heating loop is much stronger. The temperature will be consistently maintained near the thermostat setting (say, 68°F).
  * If the room is very leaky (say, a window is broken) and the furnace is weak, the cooling loop is much stronger. The temperature will hover closely to the outside temperature (say, 30°F).



Where exactly the room stabilizes its temperature depends on the relative strength of the balancing loops. The stronger loop will drive the stock closer toward its setpoint. **The general takeaway: in a system with multiple competing loops, the loop that dominates the system determines the system’s behavior.**

One implication of two competing loops is that the stock levels off at a point near to the stronger loop’s setpoint, but not exactly at it. If a thermostat is set to 68°F, the room temperature will level off slightly below 68°F, because heat continues to leak from the stock even as the furnace generates heat. (For this reason, people often set the thermostat to a bit above the temperature they want, or thermostats temporarily overshoot to bring the temperature above the setpoint.)

The strength of the loops may also vary over time. For example, the outside temperature drops during night and rises during day. Thus, the cooling loop is stronger at night and weaker during the day. If the heating loop stayed at the same strength throughout the day, then you’d find the room temperature would drop more at night than during the day. By understanding the strengths of the loops and how they fluctuate over time, you can predict the room temperature.

A thermostat is fairly unimportant in the grand scheme of things, but think about how this system applies to your paying off credit card debt. To pay off the debt, you need to pay not just the current bill but also cover the interest generated while you’re paying—otherwise, you will never quite pay off your bill. This applies equally to the national debt.

### One Stock + Two Balancing Loops, With Delay

We’ll now take the system we just discussed—one stock with two balancing loops—and introduce delays. Delays are common in the real world. It takes time to transmit information, to process the information, to act on the information, and to get the result of your actions. All of these delays disrupt how the system behaves.

For this example, imagine the manager of a car dealership who has to stock her car lot for sale:

  * The stock is the inventory of cars on the lot.
  * One balancing loop is the outflow of cars as customers buy them. 
  * The other balancing loop is the inflow of cars from the manufacturer. In response to too low of a stock, the manager orders cars from the factory.



The manager wants to keep the inventory at a set number of cars to cover ten days’ worth of sales. In an ideal world, every time a customer drives a car off the lot, a new one instantaneously appears to replace it. The car stock is kept at exactly the same number.

Of course, reality doesn’t work this way. In practice, there are several key delays that hamper the response time:

  * A perception delay: instead of deciding based on each day’s data, the manager averages out the inventory changes over the past three days. This prevents the manager from overreacting to short-term fluctuations, but it introduces a delay in case of a major sudden change.
  * A response delay: instead of ordering all the cars she needs at once, the manager meters out the order over three days. This again avoids over-corrections.
  * A delivery delay: it takes a week for the factory to get the order and deliver the cars. 



At an equilibrium, these delays aren’t a big deal. The manager can figure out the typical rate of car sales and adjust for all the delays. The car lot stays at a steady number.

But let’s look at a new situation—say there’s a sudden, permanent increase in daily car sales of 15%. In the long run, since the manager wants to stock 10 days’ worth of cars in the lot, she needs to increase her inventory. Again, in an ideal world, the cars would just appear instantaneously on the lot without any delay, and she’d be set.

But the real world has delays. What’s the effect of all of these delays? Surprisingly, **the delays cause oscillations** :

![thinking-in-systems-oscillations.png](https://media.shortform.com/images/thinking-in-systems-oscillations.png)

Why does this happen? In essence, the delays cause decision making that falls out of sync with what the car lot really needs:

  * While the sales increase, the manager is averaging sales to make sure the sales boost is real. When she’s sure it’s real, she increases her orders to the factory.
  * However, there’s a delay of a week for the cars to arrive. During this time, the inventory keeps shrinking. The car lot is now well under its ideal car count and still dropping. The manager panics and increases the orders of cars.
  * At long last, the cars from her first orders arrive. They gradually replenish the inventory and for a moment the car lot is at the ideal inventory size.
  * But the largest orders the manager recently placed in a panic are still coming. The manager can’t cancel the orders.
  * As the cars pile up, the manager wonders how she’s going to get rid of all the cars. She freezes her orders to the factory.
  * As the car deliveries stop, the sales keep happening, and the inventory gets drawn down again. The whole cycle repeats.



As an analogy, if you’ve taken a shower where it takes a long time for turning the knob to do anything, you’ve experienced the wild, unpleasant oscillations in water temperature. You don’t get quick feedback on your actions—if the water’s too cold, you turn the knob all the way hot; then it gets scalding, and you quickly clamp it down; then the water gets too cold, and so on.

#### Fixing Oscillations

Oscillations can cause more problems.

How do you fix this? One intuitive reaction is to see the delays as bad. Surely, shortening the reaction time should solve the problem! The car manager decides to shorten her perception delay, reacting to two days’ data instead of three, and shortening her response delay, ordering the entire shortfall in one go, rather than spacing it out.

This actually makes things worse. The oscillations increase dramatically:

![thinking-in-systems-oscillations-worse.png](https://media.shortform.com/images/thinking-in-systems-oscillations-worse.png)

(Shortform note: this graph is an approximation to illustrate the point. System analysts build quantitative models to produce more accurate charts.)

In essence, **shorter delays cause larger overreactions** —at the car lot’s lowest points, the manager places large orders multiple times in succession. This causes a huge buildup of cars, which takes a long time to draw down. The cycle repeats.

**Counter-intuitively, the better reaction to oscillations is actually to slow reaction time.** Oscillations are a sign of overreacting. The manager should under-react—if she increased her delays from 3 days to 6 days, the oscillations would dampen quite a lot:

#### The Importance of Delays

As you’ve seen, delays affect systems a lot, in somewhat unpredictable ways. That’s why systems thinkers are obsessed with identifying delays and studying their impact.

This example just represents a single simple car lot. Imagine things like this happening throughout the broader economy, in hundreds of thousands of places, all interconnected. All the car lots around the world are connected to the manufacturer, which is connected to the parts makers, who are connected to suppliers of steel, rubber, electronics. Every single member here has its own idiosyncratic delays and oscillations—imagine the coordination it takes to produce new cars and ship them nationwide!

### One Stock + One Reinforcing Loop, One Balancing Loop

Next, we’ll look at a system with one stock and two loops that compete against each other—one reinforcing, and one balancing.

The concrete example we’ll use is the world population.

  * The population is the stock.
  * The reinforcing loop is birth rate—the more people there are, the more who reproduce. By itself, this leads to natural exponential growth.
  * The balancing loop is deaths—the more people there are, the more who die. (Shortform note: In essence, the setpoint of this balancing loop is 0, and the further away from 0 the stock is, the more people who will die.)



The stock and flow diagram looks like this:

![thinking-in-systems-population.png](https://media.shortform.com/images/thinking-in-systems-population.png)

As with the previous system, the relative strength of the two competing loops determines how the stock changes over time.

  * If the birth rate is higher than the death rate, the population will grow exponentially. This is where the world overall currently is.
  * If the death rate becomes larger than the birth rate, the population would shrink. (This can happen if the birth rate plummets, or the death rate skyrockets, or both.)
  * If they are equal, the population will stay the same.



Different circumstances can drive the relative strength of the birth or death loop:

  * Data suggests that as countries get wealthier, birth rates fall. Therefore, poorer countries with high current birth rates may not retain high birth rates as their economies develop.
  * A lethal, contagious disease could drastically increase the death rate. For instance, during the HIV/AIDS epidemic, projections of populations in areas with high HIV prevalence had to account for higher mortality.
  * Birth rate could also fall due to social factors, such as lower interest in raising children or fertility issues.



#### The System of the Economy

The economy works similarly to the world population, in that it fits the same system model of a stock, one reinforcing loop, and one balancing loop:

  * The stock is capital. These are assets that do useful work, such as factories, machines, and labor.
  * The reinforcing loop is reinvestment. The excess output that is produced can be reinvested into producing more capital stock, which in turn increases output.
  * The balancing loop is depreciation, or the decrease in the usefulness of the capital stock. This includes machines breaking down and labor skills becoming obsolete.



As with the world population, the strength of the two loops determines the behavior of the system. If reinvestment is stronger than depreciation, the capital stock will rise. Otherwise, the capital stock will fall, and the economy will decline.

And, again, changing the circumstances can change the strengths of the loops. New technology that reduces the breakdown of industrial machines decreases depreciation. Inversely, political actions that reduce reinvestment can weaken an economy.

You can see how two systems that look very superficially different actually behave similarly. This is the type of insight that systems thinking yields.

And of course, the population and economy are inextricably intertwined. People contribute labor to the economy and they consume within it; likewise, the economy affects the population’s birth rates and death rates. Systems can get complicated very quickly.

[[book_md/thinking-in-systems/exercise-feedback-loops|exercise-feedback-loops]]

[[book_md/thinking-in-systems/chapter-2-2|chapter-2-2]]

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=9fdff355-f2b8-4272-b1e4-f9c615dbf3cf&sid=48a964a0642711eeb2d9b36fc717f5e2&vid=48a9a1e0642711eebeaf23361361f0d4&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fthinking-in-systems%2Fchapter-2-1&r=&lt=990&evt=pageLoad&sv=1&rn=74318)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



