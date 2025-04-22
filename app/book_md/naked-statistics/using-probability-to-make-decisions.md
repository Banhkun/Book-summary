![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

Discover

Books

Articles

My library

Search

Discover

![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

# Naked Statistics

Back to Discover

[[book_md/naked-statistics/preview|preview]]

  * [[book_md/naked-statistics|naked-statistics]]
  * Full Book Guide

    * [[book_md/naked-statistics/shortform-introduction|shortform-introduction]]
    * [[book_md/naked-statistics/why-learn-statistics|why-learn-statistics]]
    * [[book_md/naked-statistics/using-descriptive-statistics-to-describe-measures-of-central-tendency|using-descriptive-statistics-to-describe-measures-of-central-tendency]]
    * [[book_md/naked-statistics/using-descriptive-statistics-to-summarize-data-distribution|using-descriptive-statistics-to-summarize-data-distribution]]
    * [[book_md/naked-statistics/exercise-spot-misleading-statistics|exercise-spot-misleading-statistics]]
    * [[book_md/naked-statistics/using-probability-to-make-decisions|using-probability-to-make-decisions]]
    * [[book_md/naked-statistics/safe-assumptions-with-inferential-statistics|safe-assumptions-with-inferential-statistics]]
    * [[book_md/naked-statistics/finding-answers-with-regression-analysis|finding-answers-with-regression-analysis]]
    * [[book_md/naked-statistics/exercise-design-a-study|exercise-design-a-study]]
    * [[book_md/naked-statistics/quality-data|quality-data]]
    * [[book_md/naked-statistics/reducing-bias-in-data|reducing-bias-in-data]]
    * [[book_md/naked-statistics/exercise-examine-your-sources-of-bias|exercise-examine-your-sources-of-bias]]
  * [[book_md/naked-statistics/highlights|highlights]]
  * [[book_md/naked-statistics/community|community]]



Adding to Favorites 

Removing from Favorites 

## Using Probability to Make Decisions

Probability is another way to use descriptive statistics to make informed decisions.****

Probability is a mathematical ratio that communicates the likelihood of a particular event over all other possible outcomes.**Probability allows us to manage uncertainty by measuring risks and putting possible outcomes in perspective.** Wheelan explains that understanding probability can be especially relevant to our daily lives because we make decisions based on our _perception_ of probability all the time.

However, **our perception of likely outcomes is often mathematically irrational**. For example, the probability of getting in a car accident while driving to a beach is far higher than the probability of being attacked by a shark there, but we often—irrationally—fear the shark risk more.

We'll discuss some of the basic concepts and applications of probability next.

> **Probability Isn’t Intuitive**
> 
> There are several reasons for our mathematically irrational perception of probability, including:
> 
>   * **Confirmation Bias** : This is when we focus on what we expect and ignore the rest. Using our shark attack example above, we might justify our fear of swimming at the beach with a statement like, “Well, that one guy was bitten by a shark at Cape Cod last year!” ignoring the tens of thousands of swimmers who weren’t attacked.
> 
>   * **Anecdotal Logic** : Improbable events are statistically bound to happen, and people notice and talk about them when they do. These stories of improbable occurrences stick in our minds and shape our perception of what is likely. For example, say you have a friend diagnosed with an exceedingly rare cancer. Even though your friend’s diagnosis is an anomaly, the rare form of cancer suddenly feels more prevalent.
> 
>   * **Short-Term Thinking** : Humans are evolutionally hardwired to think in the short- and middle-term, which can make us feel like we're witnessing statistically improbable events when we're not (for example, witnessing a 100-year flood) and make us unable to process long-term data (for example, focusing on the cold snap over the last several days and ignoring climate change).
> 
> 

> 
> Our brains’ tendency to misunderstand probability makes it a useful subject to study if we want to use statistics to make more informed decisions.

### Basic Probability

We can determine how mathematically likely an outcome is by setting up a fraction with the outcome we're interested in on top and all _possible_ outcomes on the bottom. For example, in a bag of 32 chess pieces, 16 will be pawns. The probability of pulling a pawn out of the bag will be 16/32, which reduces to 1/2, or 50%.

**The probability of _multiple_ independent events happening is the _product_ of their probabilities.** For example, in a bag of 32 chess pieces, the probability of picking a pawn out of the bag twice in a row (provided you put the first pawn back in the bag) is 16/32 x 16/32. When reduced to 1/2 x 1/2, the product is 1/4, or 25%. The probability of this happening three times in a row is 1/2 x 1/2 x 1/2, which equals 1/8 or 12.5%, and so on.

Sometimes, we're interested in the likelihood of one of two mutually exclusive outcomes. In that case, **option A _or_ option B's likelihood is the _sum_ of their probabilities**. For example, the likelihood of picking a pawn _or_ a bishop out of the bag of chess pieces is 16/32 (probability of a pawn) + 4/32 (probability of a bishop). We can reduce this to 4/8 + 1/8, which is 5/8 or 62.5%.

Other times, we're interested in the likelihood of one of two non-mutually exclusive outcomes. In that case,**the probability of A or B happening is the sum of their individual probabilities minus the probability of both events happening.** For example, the probability of picking a pawn _or_ a piece (any piece) from the white set of chess pieces is 16/32 (chance of a pawn) + 16/32 (chance of a white piece) - 8/32 (the number of white pawns, which are already included in the calculation through the first fraction). When we reduce this to 2/4 + 2/4 - 1/4 it equals 3/4 or 75%.

> **Thinking in Percents**
> 
> As we've outlined above, the probability of any event is a mathematical ratio; a percent.
> 
> However, most people’s thinking is naturally binary; relegated to the categories of “yes,” “no,” and sometimes “maybe.” In their book _Superforecasting_ , authors Philip Tetlock and Dan Gardner outline the characteristics of “superforecasters,” people who have a talent for accurately predicting future events. The authors argue that superforecasters are better at making predictions than the average person because they think in percentages.
> 
> As _Superforecasting_ explains, binary thought processes were likely helpful for our species’ evolution. If you’re staring into the face of a lion, you don’t want to spend time calculating the percent chance that the lion will attack. Luckily, we face fewer life-and-death decisions in modern life than our ancestors, and the ability to think about the future with more mathematical nuance is often helpful. Investment decisions, for instance, require more nuanced thinking than an immediate “yes” or “no.” Superforecasters naturally think of decisions as having a range of possibilities, each with their own likelihood, and are instinctively able to make astute decisions.

### Using Probability to Make Financial Decisions

People often use probability to assess risk when making financial decisions. Wheelan explains that **a statistic called the “expected value” can help us determine whether we want to take a financial risk** when we know the probability of each possible outcome and its respective payoff.**** To calculate the expected value of a financial investment (risk), we multiply the financial payoff for each possible outcome by its probability and then add them all together.

For example, say you were interested in building a tiny house on your property to rent to tourists. It will cost $50,000 to build the house. Based on location and current market demand, you estimate a 25% chance that the house won't be rented at all during the first two years, a 50% chance that it will be rented “part-time” and earn $1,500/month, and a 25% chance that it will be in high demand and rented “full time,” earning $3,000/month. To calculate the expected value of the investment during your first two years, you would multiply $0 by 25%, $36,000 (for two years of part-time rentals) by 50%, and $72,000 (for two years of full-time rentals) by 25%, and add them together for an expected value of $36,000.

Wheelan explains that we can represent the calculations for the expected payoff visually in a decision tree. For your tiny house, your decision tree would look like this:

![image6.png](https://media.shortform.com/images/nakedstatistics-decisiontree2.png)

Again, probability dictates that your investment is _likely_ worth $36,000 in the first two years. But**l** ooking at your decision tree, you can also see that it's reasonably likely that you'll make no money at all and also reasonably likely that you'll only make $18,000.

The decision tree highlights an important lesson in probability: **Probability is a tool, not a guarantee**. Unless the probability of an event is zero or 100%, we should always be prepared for an unlikely outcome. Wheelan reminds us that **statistically improbable things happen all the time** (someone’s “illogical” ticket purchase will win them the lottery!).

Since no outcome is guaranteed, Wheelan explains that **we all use probability differently depending on our goals, motivation, risk tolerance, and so on**. For example, Wheelan points out that the expected value becomes a more and more useful statistic as the number of financial risks one takes increases. Real-estate developers, for instance, can use this tool to make sure that their multiple investments are likely to make money as a whole. Even if one property loses money or underperforms in a given year, as long as the expected value of their portfolio is profitable overall, they are likely to make money.

> **Decision Trees for Purchasing Stock**
> 
> As Wheelan explains, probability is an effective tool for managing risk. Unfortunately, many of us underutilize probability when investing in the stock market. Research shows that we tend to overestimate the probability of rare events and our ability to foresee them. For example, people will often invest in a single stock that they think will be the next Apple instead of spreading their investment across a diverse portfolio. This desire to “hit the jackpot” instead of earn a more modest yet statistically likely return on their investment leads people to under-diversify their stock to the detriment of their wallets. Data suggests that these errors in judgment cost the average investor $2,500 per year.
> 
> Using a tool to assess the probable outcomes of our financial investments, such as the decision tree described in this section, is likely a good idea before investing in the stock market. With a decision tree, our “gut feeling” about a stock can be tempered by math, and we may make smarter investments.

### Predictive Analytics and Using Probability to Discriminate

As we've seen, with enough data, probability allows us to make reasonably good predictions about future outcomes. This exercise is called predictive analytics. But Wheelan reminds us that just because we _can_ make predictions with predictive analytics doesn't necessarily mean that we _should_.

Wheelan explains that **the application of probability in modern society is a contentious topic**. For example, Wheelan notes that data may allow us to identify patterns that make someone _statistically_ more likely to be a terrorist than someone else. Some argue that we should use every tool at our disposal to prevent a potential attack from happening, despite negative outcomes for those wrongly accused. In contrast, this “statistical discrimination” is ethically unacceptable for others.

As the above example highlights,**the “math part” of probability may be relatively straightforward; but it's up to _people_ to determine how to apply that math in the real world.**

> **Systematic Statistical Discrimination**
> 
> The statistical discrimination that Wheelan discusses is purposeful. Agencies that use statistics to profile people, like potential terrorists, have the explicit purpose of using data to single people out. However, modern statistical discrimination is often more insidious. Life-altering decisions are often made with computer algorithms that rely on “big data” and statistics. For example, computers “decide” whether some students are admitted to a certain college, whether people are offered a loan, or whether someone gets an interview for a job. If biased data goes into computer-based algorithms, the computer’s “decisions” will also be biased.
> 
> For example, the use of SAT scores as a deciding factor for college admission and financial aid awards has been highlighted as a barrier to upward mobility for Black and Hispanic or Latino students, as they have historically scored lower on the test than white and Asian students. Therefore, an algorithm using SAT scores to set admission thresholds would be biased against admitting Black and Hispanic or Latino students. In fact, this may be one of the reasons that students from these populations are underrepresented in selective schools.
> 
> Wheelan highlights the problematic relationship between income and the SAT by noting that wealthy parents can send their children to SAT prep classes to improve their scores. Since wealth is unevenly distributed and often concentrated in white populations, the fact that spending ability can impact SAT performance only further exacerbates gaps in scores between white students and Black and Hispanic or Latino students.

[[book_md/naked-statistics/exercise-spot-misleading-statistics|exercise-spot-misleading-statistics]]

[[book_md/naked-statistics/safe-assumptions-with-inferential-statistics|safe-assumptions-with-inferential-statistics]]

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=360ed84e-8271-4361-b1f1-489643fc87d4&sid=f30c5e70639211ee87d33f0876d93783&vid=f30c9700639211eeb3a75d830392c94f&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fnaked-statistics%2Fusing-probability-to-make-decisions&r=&lt=548&evt=pageLoad&sv=1&rn=239059)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



