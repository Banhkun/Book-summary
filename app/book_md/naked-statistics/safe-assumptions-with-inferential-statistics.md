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

## “Safe Assumptions” With Inferential Statistics

We’ve examined how descriptive statistics help us summarize and describe data, characterize relationships, and make predictions. Next, we'll move on to _inferential statistics_ , which enable us to extrapolate beyond the data we collect and make inferences about how the world works.

Wheelan describes **inferential statistics as the combination of data and probability**. Just as probability is never a guarantee of an outcome,**there are no definitive answers in inferential statistics.** Rather, inferential statistics help us use what we _do_ know to make math-based best guesses about what we _want_ to know.

> **Inferential Statistics Don’t Provide a Mechanism**
> 
> As Wheelan explains, inferential statistics are very effective at illuminating and describing relationships, but they can’t actually prove anything by themselves because they are based exclusively on numerical data that can’t capture the complexity of the real world. In other words, inferential statistics give us a compelling reason to believe that two variables are related but don’t supply a mechanism for that relationship.
> 
> For example, say you’re researching the effectiveness of a stream clean-up program. Your regression analysis suggests a strong positive relationship between clean-up efforts and stream biodiversity, from which you infer (hence the terminology) that the program is working. However, you would still need to know _why_ and _how_ it is working. For example, perhaps your efforts to curb thermal pollution from a wastewater treatment plant upstream have led to a higher level of dissolved oxygen in the water, which has allowed more species to survive. Taken together, your understanding of the mechanism (heat from the wastewater treatment plant heats the water, and warm water holds less dissolved oxygen than cooler water) and your statistical analyses make a strong causal case for the clean-up program’s impact on water quality.

Next, we'll look at some of the most basic terms and concepts of inferential statistics.

### Hypothesis Testing

Inferential statistics test hypotheses, which are educated guesses about how the world works. Based on our statistical analyses, we can either accept these hypotheses as true or reject them as false with varying degrees of certainty.

There are common conventions around testing a hypothesis with inferential statistics. We'll give a general overview of some of these conventions and apply them to an example in the following sections.

> **A Good Hypothesis Takes Work**
> 
> The word hypothesis is often used colloquially to mean a guess. But this colloquial use can create misconceptions about what a scientific hypothesis is. A scientific hypothesis is based on background subject knowledge and research, a review of related studies, and a sound understanding of any statistics that will be performed during the study. Therefore, when researchers arrive at a quality scientific hypothesis, they have already put in a great deal of time and work.

#### The Null and Alternative Hypotheses

When we use inferential statistics to answer a question, we begin with a _null hypothesis_. **A null hypothesis assumes a relationship between two variables that we'll accept or reject.** Wheelan explains that the convention is to begin with a null hypothesis that we hope or expect to reject. For example, a vitamin company might hope to reject the null hypothesis that absorption of their new vitamin is no better than absorption of their previous formula.

Rejecting a null hypothesis in inferential statistics means “accepting” an _alternative hypothesis_. **The alternative hypothesis is the logical inverse of the null hypothesis.** If the vitamin company’s null hypothesis is that absorption of their new vitamin is no better than absorption of their previous formula, their alternative hypothesis is that absorption of their new vitamin _is_ better than absorption of their previous formula.

> **Why the Null Hypothesis?**
> 
> Establishing both null and alternative hypotheses might seem like a redundant step because they are inverses of one another, but the null hypothesis upholds a fundamental rule in science: You can only disprove hypotheses, never prove them. 
> 
> For example, say your hypothesis is that a certain species of bear only eats meat because that is all you have ever observed this type of bear eating. You can't possibly collect data on every individual bear of that species and everything they have ever eaten to prove your hypothesis. However, if you observe one of the bears eating berries, your hypothesis is quickly disproven.
> 
> While we can’t prove anything in science, we _can_ collect data to _support_ a hypothesis, which is the role of the alternative hypothesis. Therefore, the null hypothesis provides the opportunity to disprove an idea, and the alternative hypothesis provides the opportunity to use the results of our calculations to support an alternative idea.

#### Communicating Confidence in Statistics

Since there are no definitive answers in inferential statistics, we can never accept or reject a null hypothesis with complete certainty. Instead, **we accept or reject a null hypothesis with a specified degree of confidence, known as the _confidence level_**.

The person running the statistical test sets the confidence level. Wheelan explains that commonly used confidence levels are .05, .01, and .1, but researchers can set their confidence level wherever they choose.

**Confidence levels represent the uncertainty that remains when we reject the null hypothesis.** So at a .05 confidence level, we can be 95% confident in rejecting the null hypothesis (.05 as a percent is 5%, and 100-5 gives us 95%). At a .01 confidence level, we can be 99% confident in rejecting the null hypothesis.

In statistics, when we reject a null hypothesis, we accept the alternative hypothesis as (probably) true. For example, if the vitamin company rejects their null hypothesis at a .05 confidence level, it means they are 95% certain that the alternative hypothesis—that their new formula has better absorption than their previous formula—is true.

> **Criticism of the Null Hypothesis Approach**
> 
> The null hypothesis system provides a systematic and standardized approach to assessing data with statistics. However, it's also criticized for allowing “sloppy” scientific research to pass as acceptable. We’ll highlight two of these critiques.
> 
> The convention of accepting or rejecting a null hypothesis as the final step in data analysis is a suboptimal way to further scientific knowledge. First, when the null hypothesis is accepted, data from these “negative findings” are often not published or shared with the scientific community or public. This leads to an underrepresentation of negative results in the scientific literature and an overrepresentation of positive results. (Wheelan highlights this issue, and we’ll discuss it further in the last section of this guide.)
> 
> For example, 10 studies could show no link between eating a certain food and getting arthritis. But if one study did show a statistically significant relationship between the two, it would be published and shape public perception. The still-valuable data from the nine negative findings would likely be forgotten.
> 
> The fact that statistical analyses are reported with a certain confidence level is another reason to include data from negative findings in the scientific literature. Even the highest confidence levels leave room for Type ll errors (discussed below), meaning statistically significant findings are reported as not significant. This means there is likely a great deal of important and statistically significant research that goes unread by the scientific community.
> 
> Second, when the goal of data analysis is to reject the null hypothesis, too little emphasis is placed on the alternative hypothesis. Since the convention when rejecting the null hypothesis is to accept the alternative hypothesis, the alternative hypothesis should also be well-researched and thought out. However, it's often simply presented as the opposite of the null hypothesis.
> 
> For example, if you rejected my null hypothesis that there is no relationship between eating a certain food and arthritis, and accepted the alternative hypothesis that there _is_ a relationship between eating a certain food and arthritis, that might be the end of the analysis in your publication. However, this leaves your readers with no context for _what_ the relationship between food and arthritis is. Therefore, an alternative hypothesis based solely on the rejection of the null hypothesis can lead to nebulous conclusions that are less informative than ideas making their way into scientific publications “should” be.

##### Type l and Type ll Errors

Wheelan explains that another way to think about confidence levels is as the “burden of proof” that you’re putting on your statistical analyses. While a high burden of proof might seem intuitively desirable, there are trade-offs to consider when selecting confidence levels for statistical analyses. To understand these trade-offs, we need to understand Type I and Type II errors.

**Type I errors are _false positives_ , which means we reject a null hypothesis that is actually true **(and accept an alternative hypothesis that is actually false). For example, if the absorption of our vitamin company’s new formula wasn’t any better than the previous formula, but their study led them to conclude that it was, they would be making a Type l error.

**Type lI errors are _false negatives_ , which means we accept a null hypothesis that is actually false **(and reject an alternative hypothesis that is actually true). For example, if the absorption of our vitamin company’s new formula _was_ better than the previous formula, but their study led them to conclude that it wasn’t, they would be making a Type ll error.

Setting your burden of proof (confidence level) high, say, .001, makes it statistically more difficult to reject the null hypothesis because, at that level, you have to be 99.9% certain the alternative hypothesis is true before you can reject the null. This makes you more likely to make a Type ll error by accepting the null hypothesis as true when it's not.

In contrast, setting your confidence level lower, say, .1, reduces the burden of proof necessary to reject the null hypothesis because you only need to be 90% certain the alternative hypothesis is true before you can reject the null. This makes you more likely to make a Type l error by rejecting a null hypothesis that is actually true (and accepting an alternative hypothesis that is actually false).

> **Reasons for Type l and Type ll Errors**
> 
> A small sample size can be the cause of some Type ll errors. For example, say you were studying whether malaria is more common in mosquitoes in one region than another, but you only collect 20 mosquitoes from each location. It’s possible that you’d miss a statistically significant difference between the larger mosquito populations because you simply didn’t survey enough mosquitoes. Therefore, large sample sizes can help reduce Type ll errors.
> 
> A significant relationship other than the one you’re studying can also be the cause of some Type l errors. For example, say you’re studying the effects of a healthy lunch initiative on school children’s attention levels in class. Your statistics show a significant relationship between increased attention levels and participation in the healthy lunch program. However, this increased attention may actually be caused (at least in part) by the new outdoor exercise program the school implemented at the same time, and students are focusing better in class after coming in from an outdoor walk. Therefore, careful consideration of possible confounding factors can help reduce some Type l errors.

Since **you can never fully eliminate the possibility of making Type l and Type ll errors** , the circumstances around your research and statistical analysis will determine which one you are more willing to accept.

For example, as a medical researcher working on a new vaccine, you might have a very low tolerance for rejecting a true null hypothesis (Type l error). Since people’s health is at stake, you want to be very sure that your vaccine works. Therefore, you might opt for a high confidence level, say, .001, meaning that you are 99.9% confident when you reject the null hypothesis that your vaccine is not effective against a certain malady. In this case, by opting for such a high level of confidence, you increase your chances of making a Type ll error and concluding that your vaccine is not effective when, in fact, it is.

In contrast, you might be more inclined to accept a Type l error as a social sciences researcher looking to implement a recreational therapy program at a local senior center. You might even set your confidence level at .25, meaning that you would be 75% confident in rejecting the null hypothesis that your recreation program does not produce clinically significant results. In this case, your rationale might be that even if the results of the program are not clinically measurable, the community as a whole will still enjoy it, and there is little risk of doing harm.

> **Remembering Type l and Type ll Errors**
> 
> The concept of Type l and Type ll errors can be tricky to grasp and retain. An article from the National Library of Medicine suggests using the story of the Boy Who Cried Wolf as a memory tool. The first time the boy cries “wolf” in the story, the citizens all come running. This is a Type l error because there is no wolf even though they think there is. We can remember that it’s a Type l error because it happens first in the story. Later, there really is a wolf when the boy cries “wolf,” but no one comes since they don’t believe him. This is a Type ll error, which we can remember because it happens second in the story.

##### Statistical Significance

The results of statistical analyses are often reported as being “statistically significant” or “not statistically significant.” **When results are statistically significant, it means that you can be reasonably certain that your observed results are due to the variable you are measuring and not to random chance.**

Statistical significance is often reported with a statistic called the p-value. The p-value pinpoints how likely your results are given a true null hypothesis. In other words, it tells you the likelihood of getting your results if the variable you’re measuring really has no effect and chance alone influenced the data.

**A small p-value adds confidence to rejecting the null hypothesis.** When the p-value is less than your established confidence level, you can report your results as _statistically significant_.

For example, say our vitamin company chooses a .05 confidence level for their statistical analysis, meaning that they want to be 95% confident when they reject the null hypothesis and move forward with the new formula. Their statistical analysis shows a p-value of .01. This means that there is a 1% chance that their results are due to random chance, and the null hypothesis is true (in other words, there is a 99% chance that these results are _not_ just due to chance). Since this p-value falls within their 95% confidence level for rejecting the null hypothesis, they report their results as “statistically significant.”

> **P-value Misconceptions**
> 
> As Wheelan explains, the p-value is a tool for determining whether the values in our dataset are “significant” from a statistical perspective. Since the p-value can be a tricky value to grasp, people have several common misconceptions about it. We’ll highlight two of them.
> 
> First, people mistakenly believe the p-value communicates how strong an effect one variable has on another. For example, if your data showed a statistically significant relationship between eating spinach and being able to lift heavier weights an hour later, and your p-value was .001, you might infer that spinach has a large impact on strength. However, a small p-value only means a small likelihood that your results were due to random chance. The reality might be that participants were able to lift just an extra two ounces after eating spinach.
> 
> The second common misconception is that a small p-value means that you are likely to get the same result if you run the experiment again. In our above example, for instance, since your p-value of .001 indicates a .1% chance that your results were due to random chance, you might infer that you don’t need to do the experiment again because your results are pretty conclusive. However, the p-value is specific to the dataset being analyzed and can vary widely even between different samples testing the same variable. This is especially true with smaller sample sizes.

### Using Inferential Statistics

Now that we’ve covered the basic concepts of hypothesis testing, we’ll look at common applications of inferential statistics.

As Wheelan explains, inferential statistics are a powerful research tool due to a statistics tenet called the central limit theorem. The central limit theorem states that**the mean of a representative sample will be close to the mean of the larger population**. Therefore, we can confidently make inferences about a population from a sample or about a sample from a population, and we can compare samples to each other. We'll explore each of these general applications of inferential statistics with an example.

> **Representative vs. Random Sampling**
> 
> Wheelan explains that a representative sample is a group of individuals taken from a larger population that reflects the composition of the population as a whole. In a representative sample, every member of the population should have an equal chance of being selected into the sample. Therefore, a representative sample _should_ be as diverse as the underlying population.
> 
> Wheelan’s examples assume that representative samples are also _random_ samples. He does not explicitly cover the idea that random and representative samples are technically two different sampling techniques. Random samples are, as they sound, randomly selected. Therefore, random chances make it possible for a sample to be random but not representative of the true diversity of the underlying population.
> 
> For example, say you’re handing out random handfuls of small chocolates from a big bowl on Halloween. You have an equal number of peanut butter, white chocolate, and peppermint chocolates in the bowl. You’d expect each handful to have about ⅓ of each. However, while unlikely, it’s possible to get a handful that has no peanut butter chocolates at all. While the chocolates were selected randomly, the sample that particular kid receives doesn’t reflect the composition of the bowl.
> 
> Representative samples, on the other hand, have the explicit goal of representing a population’s underlying diversity. Samples that are both randomly selected _and_ truly represent the diversity of the underlying population are random representative samples.
> 
> One technique for obtaining a random representative sample is called stratified random sampling. In a stratified random sample, a population is broken down into subgroups based on common characteristics. Then individuals are selected randomly from the subgroups to make up the sample. The number of individuals selected from each subgroup is in proportion to the size of that subgroup in the larger population.
> 
> Clearly, obtaining a stratified random sample takes a lot of work. As we'll discuss later in this guide, this is why Wheelan notes that obtaining reliable data is often the most difficult part of statistics.

#### Making Inferences About a Population From a Sample

We can use samples to glean reliable information about an entire population if we know the population’s mean and standard deviation for the variable we're interested in. Since collecting data on an entire population is often neither feasible nor possible, the central limit theorem allows us to ask research questions that would otherwise be unanswerable.

(Note: Wheelan explains that 30 is the minimum sample size for reliable statistics, although there are mathematical fixes for smaller sample sizes.)

For example, many people believe that participating in gymnastics at a young age stunts girls’ growth. You can’t possibly collect data on _every_ female gymnast to answer this question. Still, with the central limit theorem and inferential statistics, you can use a sample of gymnasts to test the null hypothesis that: “There is no difference in height as an adult between female gymnasts and non-gymnasts.”

> **Explicit Sampling Methods**
> 
> Including how samples are collected in a study is an important feature of ensuring replicability, a feature of high-quality research. If a study is replicable, other researchers can verify results, and trust in the study increases. In contrast, no one can verify the results when a study isn't replicable, and the study becomes less trustworthy. Replication is why scientific papers include a materials and methods section.
> 
> For example, as an ornithologist reading a study about local bird populations, you might raise an eyebrow if the study reports a much higher population density for a particular species than you’d estimate for your region. Without an explicit description of sampling techniques, you’d have no idea how the researchers arrived at those numbers. Did they count the number of nests in a given quadrant? Did they sit in one spot for a given amount of time and count birds? Did they play bird sounds and tally responses? Without context for their sampling methods, the researchers’ results might become meaningless to your critical eye.

#### Making Inferences About a Sample From a Population

Since we know that samples look like their underlying population, we can also use the central limit theorem to make inferences about the composition of a sample taken from a given population. For example, say the organizers of a fun-run want to know how long they should give participants to finish their two-mile course. They can’t know the exact pace of each participant who will show up at the race, but they can use average running paces from the general population to assume that the majority of participants will finish the course between the 20- and 30-minute mark.

> **Marketing and Data**
> 
> A common example of population-level data being used to make inferences about samples of people is targeted marketing. This trend also broadly applies to women and marketing. Data shows that female consumers make up to 80% of all purchasing decisions and that women make the plurality of couples’ decisions. Therefore, a great deal of current marketing targets women rather than men, with the logic being that ads reaching a sample of female shoppers will yield higher returns than ads reaching a sample of male shoppers.

#### Making Inferences to Connect Samples

Since samples look like their population, we would expect two samples taken from the same population to look like each other. When they don’t, the two samples have significant underlying differences in terms of the variable we're studying.

For example, a researcher’s null hypothesis might be: “There is no difference in lung cancer rates between asbestos factory workers and the general population.” The researcher could collect data on 100 asbestos workers and 100 people from the general population and compare cancer rates. If the rates of lung cancer were significantly different between the two samples, it would be a powerful indicator that the two samples came from “different populations” with respect to the variable we're studying (in other words, as far as lung cancer rates are concerned, asbestos workers are in a different population than the public).

> **Using Samples to Generate Categories**
> 
> Wheelan explains that statistics can help researchers group people into different “populations” pertaining to a specific research question. While these groupings may be statistically sound and collectively beneficial, like all statistics, they can lack the nuance necessary to understand individuals. For example, a highly publicized and controversial way that biomedical samples are used to categorize people is using the average testosterone levels of men and women to disqualify some female athletes from athletic competition.
> 
> Testosterone is widely considered to be a performance-boosting hormone, and as such, having “extra” testosterone as an athlete is considered cheating. Therefore, women whose testosterone levels are well above the female mean are considered to be in a different population than other female athletes and can be barred from competition.
> 
> Many people argue that barring women from competition on the basis of testosterone is a form of legal discrimination. While a female with high levels of testosterone might be a statistical rarity, Wheelan reminds us that statistically improbable events happen all the time. With roughly 7.75 billion people in the world, there will be many women whose levels of testosterone naturally fall well outside the average female range. Many argue that since anomalously tall individuals are not barred from playing basketball, and people with anomalously long torsos are not barred from competitive swimming, the rationale behind this decision is debatable.

#### Standard Error

We noted above that according to the central limit theorem, the means of large representative samples will be “close” to the mean of the underlying population. More specifically, the central limit theorem states that **sample means form a normal distribution around the population mean.** In other words, if we took enough samples, the means of those samples would form a perfectly symmetrical bell curve around the true mean of the population.

For instance, let's say you took a random sample of 100 people, measured their heights, and got a mean height of 5 feet 7 inches. Then you repeated the experiment with a different group of 100 people and got a mean height of 5 feet 8 inches. If you repeated the experiment 50 times with 50 different samples, then plotted those 50 sample means on a graph, they would form a normal bell curve centering on the true average height for the entire population.

Since data is distributed predictably around the mean in a normal distribution, we use the same principles we covered in our discussion of standard deviation to describe _how close_ a particular sample mean is to the population mean. However, when we're discussing the distribution of sample means around a population mean, we use a statistic called _standard error_ rather than the standard deviation. **The standard error is the standard deviation of sample means around a population mean.**

As a reminder, in a normal distribution, 68.2% of data points will fall within one standard deviation of the mean, 95.4% of data points fall within two standard deviations of the mean, and 99.7% of data points fall within three standard deviations of the mean. Therefore, for a group of sample means around a population mean, 68.2% of sample means will fall within one standard error of the population mean and so on.

![image7.png](https://media.shortform.com/images/nakedstatistics-standarderror2.png)

Using our height example, say the mean population height is 5’8”, and we calculate a standard error of 1 inch for our sample means. A sample with a mean height of 5’10” would be two standard errors taller (on average) than the population mean height. Another way to say this is that this sample mean is larger than 95.4% of all other sample means.

> **The Benefits of a Large Sample**
> 
> Wheelan explains that the standard error is calculated by dividing the standard deviation of the sample by the square root of the sample size (number of data points). Because the size of the sample is in the denominator in the standard error equation, Wheelan notes that large sample sizes reduce the standard error. However, because the equation uses the square root of the sample size, a large increase in sample size corresponds to a much smaller decrease in standard error.
> 
> In our height example above, for instance, we had a sample height of 5 feet 7 inches and a standard error of one inch from a sample of 100 people. Provided the standard deviation of the sample remains consistent, if we wanted to decrease our standard error to half an inch, we would have to sample 400 people. If we wanted to reduce our standard error to a tenth of an inch, we would have to sample 10,000 people. As we can see, the larger the sample, the more precisely we can pinpoint how close our samples are to the true population mean.

### Polling With the Central Limit Theorem

Another powerful use of inferential statistics involves polling. Since polling involves making inferences about a population from a sample, **the central limit theorem allows us to use polls to predict public opinion**. In polls, our “sample mean” is the percent of survey respondents who indicate that they'll vote a certain way, and our “population mean” is the actual percent of people who will vote that same way on election day.

For example, say you conduct a survey to see whether voters will approve a ballot measure to build a local dog park. Your sample is the people who respond to your survey. Your “sample mean” is the number of respondents who indicate that they'll vote “yes” on election day. Your population mean is the number of residents who will _actually_ vote “yes” on election day.

The standard error and normal distribution allow us to gauge how confident we can be in our polling results. The standard error of a poll is also a percent. **We can use the standard error to establish a range around our polling results within which we expect the true election results to fall** , and our normal distribution to express how confident we are in that range. We'll illustrate this with our dog park example.

![image8.png](https://media.shortform.com/images/nakedstatistics-standarderror2.png)

Say that 55% of your dog park survey respondents indicate that they'll vote “yes,” and say that you calculate the standard error of your survey to be 4%. The range of “yes” responses within one standard error of your poll is 51% to 59%. Using the normal distribution, you know that 68.2% of the time your polling results will be within one standard error of the true election results. Since 51% is over half the votes, you can be 68.2% confident that the dog park will pass with between 51% and 59% of the votes.

(Note: If a range of two standard errors from our poll results was still above 50% we would be able to use the normal distribution to say that we were 95.4% confident the measure would pass, and if a range of three standard errors from our poll results were still above 50%, we would be able to say that we're 99.7% confident that the dog park will pass.)

> **Polling and the US Census**
> 
> The US census is an example of how the central limit theorem allows pollsters and researchers to make back and forth inferences between a sample and a population. The census provides the most accurate data possible about the US population. Using this population-level data, pollsters and researchers can compare the results of their samples to the overall population and calibrate their sampling results with known population values. For example, if your research showed much smaller families in your sampling area than indicated by the census, you might adjust the family size of your sampling results to fit the census count better.
> 
> Calibrating polling results with census data is common practice because it’s assumed that polls will be inaccurate to varying degrees. Using census data to more accurately weight certain demographics can help pollsters get closer to the “right answer” (the population mean). In other words, census data helps pollsters organize their data into a more representative sample. Working in the opposite direction, sample data from the American Community Survey sent to portions of the US population each year helps update population-level census data between census counts.

[[book_md/naked-statistics/using-probability-to-make-decisions|using-probability-to-make-decisions]]

[[book_md/naked-statistics/finding-answers-with-regression-analysis|finding-answers-with-regression-analysis]]

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=9dd021df-c339-402c-a62b-5e62a0e87601&sid=f30c5e70639211ee87d33f0876d93783&vid=f30c9700639211eeb3a75d830392c94f&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fnaked-statistics%2Fsafe-assumptions-with-inferential-statistics&r=&lt=469&evt=pageLoad&sv=1&rn=86580)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



