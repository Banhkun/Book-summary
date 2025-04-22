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

## Using Descriptive Statistics to Summarize Data Distribution

As we've seen, measures of central tendency don’t give us the “full story” of a dataset. **We can get a clearer picture of that story by combining central tendency with a description of the data’s distribution.**

### The Normal Distribution

The _normal distribution_ is a foundational concept in statistics. A normal distribution refers to a dataset that forms a perfectly symmetrical bell curve around the mean when graphed as a frequency distribution (a visual representation of data where the height of the bars represents the number of times a specific outcome occurs).

![image1.png](https://media.shortform.com/images/nakedstatistics-normaldistribution2.png)

(Note that the mean and the median will be the same in a perfectly symmetrical distribution.)

When a dataset looks the same on either side of the mean, we say it's symmetrical. Symmetrical distributions feel intuitively familiar because, as Wheelan explains, they happen in real life all the time. For example, most babies start to crawl somewhere between six and 12 months, with an average of around nine months. Some will crawl earlier than six months, and some will crawl after 12 months, but the peak of our frequency distribution will be at nine, and the frequency of crawlers will taper off symmetrically in either direction.

**Normal distributions are particularly useful because they allow us to know what percent of our data lies within a certain distance (measured in standard deviations) of the mean without doing any calculations.**

#### Shortform Commentary: Skewness

When data isn’t normally distributed, we often say that it's “skewed to the left” or “skewed to the right.” Wheelan introduces this concept but doesn’t provide a full explanation of what being skewed left or right means. Since this terminology is common in statistics, and the concept can be tricky, we'll cover it here.

Data that are skewed to the right have a longer “tail” to the right of the peak of the curve. In other words, there are a few values in the dataset that are much larger than the others. These larger values make the mean larger than the median. This is also called a positive skew because it skews the mean in the positive direction. An example of positive skew could be a few outstanding students inflating the class average on a difficult test.

![image2.png](https://media.shortform.com/images/nakedstatistics-positiveskew2.png)

Data that is skewed to the left has a longer “tail” to the left of the peak of the bell curve. In other words, there are a few values in the dataset that are much smaller than the others. These smaller values make the mean smaller than the median. This is also called a negative skew because it skews the mean in the negative direction. An example of negative skew could be a few students who skipped class, bringing down the class average of an easy test.

![image3.png](https://media.shortform.com/images/nakedstatistics-negativeskew2.png)

#### Standard Deviation

**We can describe how “spread out” a dataset is around its mean by using a descriptive statistic called the “standard deviation.”** Once we know the standard deviation, we can make statements like “Value X is one standard deviation above the mean” or “Value Y is two standard deviations below the mean.”

Wheelan explains that**the standard deviation will be relatively small when data clusters tightly around the mean and relatively large when the data is spread out.**

In the image below, Dataset One has a smaller standard deviation than Dataset Two.

![image4.png](https://media.shortform.com/images/nakedstatistics-standarddeviations2.png)

We can often intuit which of two datasets is likely to have a larger standard deviation than the other. For example, say we have two hypothetical datasets: Dataset One is a collection of the average typing speed, in words per minute, of 100 professional typists. Dataset Two is a collection of the average typing speed, in words per minute, of 100 randomly selected people at the local library.

We can reasonably guess that Dataset One will have a smaller standard deviation than Dataset Two because we know that professional typists all type fast. Therefore, most of the values in Dataset One likely cluster around a similar fast typing average (the mean). In contrast, we're likely to find a mix of slow and fast typists at the local library, meaning the values in Dataset Two will be more spread out.

> **Z-Scores**
> 
> Wheelan doesn’t discuss an additional statistic often reported alongside the standard deviation: the z-score. The z-score pinpoints precisely how far a particular data point is from the mean in a normal distribution. It’s measured in standard deviations. A z-score of zero means that a particular data point is the same as the mean. A z-score of -1.5 means the data point is 1.5 standard deviations smaller than the mean. A z-score of 2.6 means that a data point is 2.6 standard deviations larger than the mean.
> 
> The z-score is useful when we're interested in how a particular piece of data compares to the dataset as a whole. For example, say you catch a fish that looks particularly large. You look up the mean size and standard deviation for that fish species and calculate a z-score of 2.5 for the fish you caught, meaning your fish was 2.5 standard deviations above the average-sized fish of that species.

#### Normal Distribution Proportions

As mentioned above, normal distributions are particularly useful because we automatically know (without doing any calculations) what percent of the data lies within one, two, three, (and beyond) standard deviations of the mean. In a normal distribution, shown below, the bulk of the data (68.2%) falls within one standard deviation above and below the mean, 95.4% of the data points fall within two standard deviations above and below the mean, and 99.7% fall within three standard deviations. Each dataset has its own standard deviation, but these percentages remain the same whether the standard deviation value for a given dataset is one, 50, or 500.

(Note: In a normal distribution, 34.1% of the data falls within one standard deviation above the mean, and 34.1% falls within one standard deviation below the mean, for a total of 68.2%.)

![image5.png](https://media.shortform.com/images/nakedstatistics-stddevpercents2.png)

Wheelan explains that, **in general, when a value lies within one standard deviation of the mean (in either direction), we say that it's relatively similar to the average**. Once a data point is more than two standard deviations from the mean, we can see that it's larger or smaller than roughly 95% of the other values in the dataset, making it relatively dissimilar to the mean.

We'll highlight these concepts with an example of how standard deviations and the normal distribution can help us orient ourselves in a dataset:

Say you start working toward a karate black belt. One year into your training, you earn the yellow belt: the first belt of the process. You proudly ask the sensei how long it takes the average person to reach this milestone. He tells you that the timing is normally distributed and that it takes people an average of three months with a standard deviation of three months. You humbly realize that you are three standard deviations above the mean at twelve months of training, meaning that 99.7% of the other students at the gym earned their yellow belts faster than you.

Now, say that, undaunted by your relatively slow progress toward your yellow belt, you stick with your training. Eleven years later, you earn your black belt. When you ask your sensei how long it takes the average student at the gym to reach this level, he tells you that the average time is ten years, with a standard deviation of six years. You feel proud! You have met your goal, and your timeframe falls well within one standard deviation of the mean, meaning that your time was pretty average.

This example highlights how **the size of the standard deviation adds context to a dataset.** Since most people earned their yellow belt within a relatively narrow timeframe (smaller standard deviation), we might infer that the skills necessary to reach that level are reasonably straightforward. In contrast, the timeframe to earn a blackbelt was widely distributed (larger standard deviation), suggesting that the achievement requires enough skill and dedication to separate students by several years.

> **Theory-Driven and Data-Driven Models**
> 
> The normal distribution is a theoretical model for how data tends to arrange itself in the real world. While many natural phenomena take on a close-to-normal distribution, virtually nothing that we can collect data on will be perfectly symmetrical. Therefore, researchers and statisticians use the normal distribution, knowing it’s an effective yet imperfect tool because it relies, in part, on theory.
> 
> The ability to analyze data with technology has the potential to change our relationship with the normal distribution. Modern researchers can let computers generate their own models that perfectly fit the dataset they’re analyzing. These are called data-driven models since they rely solely on data rather than data and theory.
> 
> There are advantages to both data-driven and theory-driven models. Data-driven models are more precise when making predictions because the equations they generate are based entirely on the dataset of interest and not a theoretical curve. However, data-driven models are susceptible to being statistically accurate but not representative of the real world if the data used to generate the predictive equations are biased.
> 
> Theory-driven models are useful because they help ground our understanding of the underlying phenomena behind the data. An algorithm generated by a computer can seem abstract, whereas equations and conclusions drawn from a normal curve, for instance, can be easier to conceptualize. For example, as we see in this guide, the normal distribution is central to learning statistical concepts. As noted above, the normal curve is also particularly useful because of the predictable standard deviations in a normally distributed dataset.
> 
> Data-driven and theory-driven models can coexist and inform each other. For example, data-driven models can become theory-driven models over time, and a data-driven model can be used to _predict_ , while a theory-driven model can be used to _explain_ the same phenomenon.

### Using Correlation to Quantify Relationships

We’ve reviewed how the mean, median, and standard deviation summarize and describe a dataset. According to Wheelan, another goal of descriptive statistics is to summarize the relationship _between_ two datasets.

**We can quantify the strength and direction of the relationship between two variables with a figure called the _correlation coefficient_.** The correlation coefficient uses the standard deviation and mean of two datasets to calculate how well a change in one dataset tracks a change in the other (for example, how well a change in the amount of floral perfume someone wears predicts a change in the number of mosquito bites they get).

Correlation coefficients are values between negative one and one. A correlation coefficient of one signifies a “perfect” correlation between two variables, meaning that a change in one “perfectly” corresponds with a change in the other. A correlation coefficient of zero indicates that the variables have no meaningful connection to each other—a change in one doesn’t predict a change in the other at all.

The sign of the correlation coefficient communicates the direction of the variables’ relationship. Our variables “move” up or down _together in a positive correlation_. When one goes up, so does the other. For example, you might notice a positive correlation between the amount of floral perfume you wear (a known mosquito attractant) and the number of mosquito bites you get—the more perfume you wear, the more bites you get.

Our variables “move” in opposite directions in a negative correlation. When one goes up, the other goes down. For example, you might notice a negative correlation between the amount of bug spray you put on and the number of mosquito bites you get—the more bug spray you wear, the _fewer_ bites you get.

> **Caution in Interpreting Correlation**
> 
> It’s tempting to extrapolate beyond a correlation coefficient and make conclusions that correlation can’t support. Perhaps the most well-known correlation fallacy is equating correlation and causation. We’ll cover Wheelan’s discussion of this common mistake next. But there is another correlation interpretation error that is easy to make and not covered in the book: using group-level data to make conclusions about individuals.
> 
> When we hear that two variables are correlated, it’s natural to think about how we can apply that information to our own lives. For example, hearing that there’s a positive correlation between the amount of chocolate people in a certain country eat and how many Nobel Prize winners come from that country might make you think that eating chocolate makes you smarter. _The New England Journal of Medicine made just such a suggestion in 2012_ when they used per capita chocolate consumption data and Nobel laureates’ country of origin to report that eating chocolate might improve our cognitive function.
> 
> The article in the _New England Journal of Medicine_ drew criticism from the scientific community because it used population-level data to make an assumption about individuals that correlation can’t support. Critics point out that since the study uses population-level data, it’s possible that the Nobel Prize winners themselves didn’t actually eat any chocolate at all! The journal’s prominence makes this oversight especially problematic because of the potential for spreading misinformation and also highlights how easy these errors are to make.

#### Correlation Is _Not_ Causation

Just because two variables are correlated doesn't mean one is _causing_ the other. **Correlation quantifies a relationship between two variables, but it doesn't explain that relationship.** Wheelan notes that this is a crucial distinction to keep in mind, as equating correlation and causation can lead to misinformed decisions.

For example, data might show a positive correlation between owning an expensive car and dying in a plane crash. But if you avoid buying an expensive car because you're worried that it might somehow _cause_ you to die in a plane crash, you misunderstand the concept of correlation.

There are plenty of reasons why the same people who can afford to purchase an expensive car might be more likely to die in a plane crash—namely because they’re more likely to be on a plane in the first place. Wealthy people may choose to fly rather than drive long distances, take more vacations, or even own and travel on a plane of their own. Therefore, while there may be a relationship between being in a plane crash and owning an expensive car, the relationship is one of correlation, not causation.

As we see in the example above,**we need to think logically and critically when interpreting statistics.**

> **Inferring Causation From Correlation**
> 
> It can be easy to equate correlation with causation even when we know better. Wheelan explains that when the correlation between two variables is particularly strong, or when changes in variables track each other tightly, it can be difficult not to infer a causal relationship.
> 
> Tyler Vigen uses comedy to highlight this natural yet problematic tendency in his book _Spurious Correlations_ and on his website. By sifting through mountains of data, Vigen generates graphs that show uncannily tight correlations between unrelated variables. For example, he highlights a nearly 99% correlation between how much margarine the average American eats and how many couples get divorced in Maine. Additionally, his research shows a nearly 99% correlation between the amount of money arcades make every year and the number of people who earn a doctorate degree in computer science that same year.
> 
> Vigen’s work has been highlighted by the _Harvard Business Review_ and received positive reviews from the _Boston Globe_ and _Washington Post_ , among others, in part because these ridiculous examples highlight the fact that equating causation with correlation is incorrect, no matter how close the relationship.

[[book_md/naked-statistics/using-descriptive-statistics-to-describe-measures-of-central-tendency|using-descriptive-statistics-to-describe-measures-of-central-tendency]]

[[book_md/naked-statistics/exercise-spot-misleading-statistics|exercise-spot-misleading-statistics]]

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=b547ea88-bef0-49da-8673-e649e7b15404&sid=f30c5e70639211ee87d33f0876d93783&vid=f30c9700639211eeb3a75d830392c94f&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fnaked-statistics%2Fusing-descriptive-statistics-to-summarize-data-distribution&r=&lt=418&evt=pageLoad&sv=1&rn=690947)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



