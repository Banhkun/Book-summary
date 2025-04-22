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

## Using Descriptive Statistics to Describe Measures of Central Tendency

Now that we’ve established why learning statistics is important, we'll look at some basic statistics terms and concepts, starting with descriptive statistics. As their name suggests, descriptive statistics **take information in a data set and condense it into a meaningful figure** like an average or percentile.

When using descriptive statistics to summarize data, Wheelan explains that we always make trade-offs between complexity and utility.**Any time we take data from the real world and condense it into a single value, we gain insight into the data as a whole but lose some of the nuance and the ‘story’ behind that data**.

For example, say your local elementary school implemented a new reading program that improved overall student reading skills by 15%. Hooray! However, further analysis might show that those gains were concentrated in students from high-income families, and the reading skills of low-income students stayed roughly the same. In light of this more complete picture, it seems clear that the program needs to be modified.

As our reading program example shows, the descriptive statistics that we choose when summarizing data have a determining impact on the story the data tells. Above, the first story is that the school implemented a successful reading program. The second story is that the school implemented a reading program that only benefitted wealthy students, exacerbating existing gaps in reading skills. Therefore, Wheelan explains that **it's important that we're intentional and thoughtful about the descriptive statistics we choose to use.**

> **Equity in Data**
> 
> As artificial intelligence advances and data collection and interpretation become more computerized, holding onto the real-world nuance of data is increasingly important. Modern technology allows algorithms to analyze data and draw conclusions as reliably as human experts. For example, in 2016, an algorithm outperformed physicians in diagnosing skin cancers by analyzing over 100,000 photographs of moles and melanomas.
> 
> Diversity advocates stress the need to consider the story and nuance of the data used to build new tools and ensure that it represents all populations the algorithms are meant to serve. If the data we put into computer-based algorithms is biased, or misrepresents or under-represents certain populations, its results will be similarly flawed.
> 
> Using biased statistics to make medicine or social sciences decisions can exacerbate existing inequities because they will best serve the populations for which we've collected the most data (which often ends up being white populations). For medical conditions like diabetes, which are already more prevalent in minority populations, algorithms based on white patients are especially problematic because they will improve medical care for white patients while doing little for the populations they could benefit most.

Next, we'll look at some of the most basic descriptive statistics and discuss what they can and can't tell us about a dataset.

**Central Tendency: The “Middle” of a Data Set**

Some of the most basic descriptive statistics are measures of _central tendency_ , or what Wheelan refers to as the “middle” of a data set.

We talk about averages, one measure of central tendency, all the time. But as we'll see, **there are two main ways to communicate the midpoint of a data set: the mean (what we usually refer to as the average) and the median.** As statistics students, we should understand the difference between the two and when to use one over the other.

> **Another Measure of Central Tendency: The Mode**
> 
> There is a third measure of central tendency that Wheelan does not discuss: the mode. The mode is the value that occurs most frequently in a dataset.
> 
> For example, in the dataset 1,2,3**,4,4,4,4** ,5,5,6,6,7,8, the mode is four because it appears more times than any other number.
> 
> The mode is useful for identifying patterns in a dataset. For instance, say you’re interested in selling your home and look up what comparable homes in your neighborhood have sold for recently. You collect the following prices:
> 
> $180,000, $185,000, $190,000, $192,000, $195,000, **$200,0000, $200,000, $200,000** , $205,000, $208,000
> 
> You see that the most common sale price in your neighborhood is $200,000.
> 
> The mode is also useful for communicating trends in categorical data when there are no numerical values. For example, say you collected data on people’s favorite holiday, with the following results:
> 
> Christmas, Christmas, Christmas, Christmas, Christmas, Christmas, Christmas, Christmas, Christmas, Halloween, Halloween, Halloween, Thanksgiving, Thanksgiving, Easter, Easter.
> 
> You can’t calculate an average holiday, but you can see that Christmas is the most common choice.

#### The Mean (Average)

The average, or mean, of a data set is the sum of all of the values in the data set divided by the number of data points.

For example: If you wanted to know the average number of cookies you eat each time you open a package, you would keep track of the number of cookies you eat at each sitting and divide that number by the number of cookie-eating events.

**Number of Cookies Eaten per Sitting**  
---  
15  | 8  | 6  | 10  | 9   
  
The sum of the values in your data set: 15+8+6+10+9= 48

Divided by the number of data points (5): 48/5= 9.6

You average 9.6 cookies per sitting.

##### Limitations of Using the Mean

Wheelan cautions that the mean can be a misleading figure because it doesn't convey the influence of outliers in a data set. (An outlier is a data point that is numerically far from others in the same data set.) In other words, **a few “extreme” pieces of data can skew the mean in either direction, giving us a warped sense of the average.**

For example, a store manager may report that her average monthly sales of Easter egg chocolates totaled $300 over the last year. However, her monthly sales data shows that she sold $3,000-worth of chocolate eggs in April, while sales for the other 11 months totaled between zero and $25. In this data set, the month of April is an outlier, and the mean of $300 doesn't provide the truest picture of average chocolate egg sales for the store.

> **Removing Outliers From a Dataset**
> 
> Research suggests that researchers in the biomedical field often remove outliers that skew their datasets. While this practice may be common, it may also be problematic because it can increase researchers’ chances of a false positive finding. In other words, removing outliers can make statistical results look more significant than they really are. Therefore, studies may be published with “statistically significant” findings that would not be significant were the whole dataset included.

**The Median**

The median is another way to measure central tendency and is not influenced by outliers. The median takes an ordered data set (where the values are organized into ascending order) and divides it in half. **The median is the middle value of a data set**(or the average of the two middle values if the data set has an even number of data points).

Back to our chocolate eggs example, our ordered data set might look like this:

**$ Earned From Chocolate Easter Egg Sales**  
---  
0  | 0  | 0  | 1  | 1  | **4** | **10** | 15  | 16  | 20  | 25  | 3000   
  
To calculate the median, we take the average of four and 10, which is seven. So the median chocolate egg sales figure is $7, which is a very different figure from the mean of $300, even though both are measures of central tendency.

> **Choosing Between the Mean and Median**
> 
> Because the mean and median can tell different stories about a dataset, there is a convention in statistics for when to use one over the other: When a dataset is evenly distributed, the convention is to use the mean. When a dataset is not evenly distributed, or extreme outliers will skew the mean, the convention is to use the median. However, the mean is the only measure of central tendency used in mathematical statistics calculations and is used more often than the median.
> 
> Another way to add context in reporting central tendency is to provide the mean or median _and_ a sense of the spread of the data, such as the range (highest and lowest values) or standard deviation (which we'll discuss next). For instance, in our chocolate egg example, if the manager reported a sales mean of $7/month and a range of zero to $3,000, readers would quickly see that sales aren’t evenly distributed.

#### Communicating Central Tendency

Since the mean and median can communicate different messages about the “middle” of a dataset, it's important to keep the difference between them in mind when communicating and interpreting statistics. Wheelan explains that**it’s common for people to share the mean instead of the median, or vice versa, to suit their goals**.

For example, say the beach authorities at a fictional beach were collecting data on the number of jellyfish stings swimmers suffered each week throughout the summer. The data might look something like this:

**Jellyfish Stings/Week/500 swimmers**  
---  
June  | July  | August  | Sept   
0  | 0  | 0  | 0  | 0  | **0** | **0** | 1  | 3  | 50  | 150  | 300   
  
(Shortform note: In this example, the dataset is naturally ordered, so we don't need to order it to determine the median.)

The mean number of jellyfish stings is 42. The median number of stings is zero. Beach authorities could either say:

A) “Visit our beach! The mean number of weekly stings per 500 swimmers throughout the summer is only 42!”

or

B) “Visit our beach! The median number of weekly stings throughout the summer is zero!”

Neither of these statements is incorrect, but they convey a different message to prospective swimmers. The beach authorities are sure to advertise option B over option A because option B makes the beach look more attractive.

This example highlights two of Wheelan’s cautions about descriptive statistics.

First, **neither the mean nor the median tells prospective visitors the “story” behind the dataset** , which suggests a “jellyfish season” at the beach that might be worth planning a visit around. But again, when we condense the real world into a statistic, this nuance is lost.

Second, this example showcases how **statistics make it possible to mislead people without actually lying**. Many readers would likely read option B and interpret it as reassurance that they can visit the beach at any time and are highly unlikely to get stung by a jellyfish. As we can see, in mid-September, this is simply not true.

> **The Utility of Central Tendency**
> 
> Measures of central tendency are foundational to how we think about and communicate data. But as Wheelan cautions and our jellyfish example highlights, if they aren’t used with care, they can be unhelpful or even dangerous.
> 
> A TED Talk entitled “The Myth of Average” highlights how the misapplication of central tendency affected the United States Air Force in the 1950s. Despite having well-trained pilots and the most advanced airplanes to date, the Air Force was dissatisfied with pilots’ performance. Research on the dimensions of thousands of pilots revealed that the cockpits designed for the “average-sized” pilot didn’t fit _any_ pilot well, and the ill-fitting cockpits prevented the pilots from flying their best. In response, the Air Force shifted its design focus from making cockpits that fit the average person to making cockpits that could accommodate the extremes of human dimensions. This shift improved the performance of existing pilots and allowed the Air Force to recruit the most diverse pool of fighter pilots in the world.
> 
> The lesson in this example is that a tool designed for the average user isn’t likely to be ideal for anyone. In many cases, such as a pair of scissors, we can easily accept this compromise. However, when it comes to life-altering scenarios such as flying a plane, we may want to rethink designs based on an average.

[[book_md/naked-statistics/why-learn-statistics|why-learn-statistics]]

[[book_md/naked-statistics/using-descriptive-statistics-to-summarize-data-distribution|using-descriptive-statistics-to-summarize-data-distribution]]

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=c77e4ccf-70d9-4a40-ba9f-9fccc1e519d6&sid=f30c5e70639211ee87d33f0876d93783&vid=f30c9700639211eeb3a75d830392c94f&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fnaked-statistics%2Fusing-descriptive-statistics-to-describe-measures-of-central-tendency&r=&lt=332&evt=pageLoad&sv=1&rn=232345)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



