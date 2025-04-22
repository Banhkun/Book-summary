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

## Finding Answers With Regression Analysis

All of the statistics and data collection scenarios we've covered so far have been relatively straightforward because they’re primarily concerned with just one variable. However, Wheelan argues that many socially important research questions are “messy,” with intertwining variables spanning prohibitively long periods.

For example, say you wanted to know whether exposure to a particular chemical (we’ll call it chemical X) is associated with an increased risk of developing cancer. You can't hope to design a research study to test this question because exposing a group of people to a chemical you suspect causes cancer would be ethically problematic. Additionally, there are myriad other variables in addition to chemical exposure that affect people’s risk of developing cancer: smoking, genetics, diet, exercise, and so on. Finally, the risk of developing cancer is often measured throughout a lifetime. Researchers, understandably, want answers within their lifetimes.

In “messy” research scenarios, an inferential statistical tool called _regression analysis_ can help us infer relationships between variables that we wouldn’t otherwise be able to study. **Regression analysis quantifies the direction, magnitude, and significance of an independent variable’s relationship to a dependent variable.**

> **Longitudinal Studies**
> 
> As Wheelan explains, we can’t answer many of society’s largest and most pressing questions with a single experiment. For example, why have autism rates skyrocketed in recent years? How does the food we eat impact our chance of getting Alzheimer’s or other diseases? What effect will a given economic downturn have on the retirement outlook of the current workforce? All of these questions encompass an untold number of variables and may take decades to answer. One way researchers attempt to answer these types of questions is with longitudinal studies.
> 
> Longitudinal studies follow the same individuals, often repeatedly measuring the same variables over the course of years or decades. Often, they simply involve observations and no intervention. Longitudinal studies can embrace the complexity of individual lives because they don’t attempt to standardize people’s experiences. Rather, focusing on a single variable (or group of variables) can provide strong evidence for the effect of a particular experience, treatment, or exposure across various circumstances over time.
> 
> While longitudinal studies require a great deal of commitment, their insights are invaluable to researchers in medical and social sciences. For example, another longitudinal study called the Baltimore Longitudinal Study of Aging began in 1958 and has informed how the medical field understands the aging process. Additionally, according to UNICEF, longitudinal studies are particularly valuable for understanding how life experiences affect childhood development.

### Regression Analysis Basics

**Regression analysis illuminates the relationship between an independent variable and a dependent variable**. According to Wheelan, we can think of the independent variable as the “event” we're interested in and the dependent variable as the associated outcome. In the chemical exposure and cancer example, your independent variable is chemical exposure, and your dependent variable is cancer rates.

(Wheelan notes that no matter how close the relationship between independent and dependent variables is,**** regression analysis can only illuminate relationships. **It can't determine causation.** Therefore, we use terminology like “association” between an independent and dependent variable rather than saying that the independent variable _“causes”_ a change in the dependent variable.)

As with other inferential statistics, regression analysis begins with a null hypothesis that you’ll either accept or reject at a specified confidence level. The null hypothesis in this example is that “Exposure to chemical X is not associated with an increased risk of cancer.” Say you set your confidence at .05, meaning you want to be at least 95% sure when accepting or rejecting the null hypothesis. Next, you collect data from a large, random sample of people who were exposed to the chemical and compare their cancer rates to the cancer rates of the general population.

To learn about the process and statistics involved, we'll carry this example through each step of regression analysis.

> **Confounding Variables**
> 
> There is a third category of variable, confounding variables, that researchers would often prefer not to have in their experiments. Confounding variables obscure or confound (hence the terminology) the relationship between the independent and dependent variables and, therefore, the validity of regression analyses. Since confounding variables can impact the dependent variable, the independent variable, and the relationship between the independent and dependent variables, it can be difficult to distinguish exactly which relationship the regression analysis is analyzing.
> 
> For example, say you were interested in studying the relationship between excessive sugar consumption and subsequent meltdowns in children. A confounding variable might be the fact that oversized sweet treats are often a part of special occasions, which also naturally drain children’s energy and can lead to post-fun meltdowns. Therefore, without further analysis, you can’t be sure whether the sugar or the excitement precipitated the meltdown.

#### The Regression Coefficient and Line of Best Fit

As Wheelan explains, when we plot our independent and dependent variables in a scatter plot, we can often infer their relationship at a glance. (Note: The independent variable is plotted on the horizontal axis, and the dependent variable is plotted on the vertical axis.) Below is a scatter plot for a hypothetical dataset comparing cancer rates and exposure to chemical X. Without doing any statistics, we can see that as chemical exposure increases, cancer rates also increase.

![image9.png](https://media.shortform.com/images/nakedstatistics-regressionscatter2.png)

Regression analysis _quantifies_ this relationship by **finding a line of best fit for a scatter plot of our data.**

![image10.png](https://media.shortform.com/images/nakedstatistics-lineofbestfit2.png)

The line of best fit doesn't actually go through many (if not most) of our data points, but instead is a line that minimizes the total distance between itself and all of the data points, hence the term “best fit."

The slope of the line of best fit is represented by the _regression coefficient_. **The regression coefficient** tells us the direction of the relationship (positive or negative), and by how much a change in the independent variable predicts a change in the dependent variable.

For example, say your regression coefficient for cancer rates and chemical exposure was +2. The positive sign tells you that an increase in exposure is associated with an increase in cancer, and the number two tells you that for every unit that chemical exposure increases, the risk of cancer increases by two units.

**Once we know the regression equation, we can use it to calculate specific values.** For example, you could calculate the cancer risk at one, five, or 10 “units” of chemical exposure.

> **Regression Analysis for Smoking and Lung Cancer**
> 
> The above example linking cancer risk and chemical X is of course hypothetical. However, researchers have enough data on smoking and cancer rates to make the sort of predictions outlined above. For example, a study in the National Library of Medicine used regression analysis to calculate that for every additional 1% that American adults smoke (collectively), lung cancer rates rise by 164 cases per 1,000 citizens.
> 
> It’s important to remember that the regression equation represents a line of “best” fit, meaning that it’s set up to minimize the distance between the line and all collective data points. Therefore, when using a regression equation to measure an outcome like lung cancer, we can’t expect the regression equation to give us a perfect prediction for _our individual_ risk. Our personal risk of developing cancer could be higher or lower than a regression equation predicts, sometimes by a great deal.
> 
> For example, plenty of heavy smokers never get lung cancer, and plenty of non-smokers do. Just as descriptive statistics can’t encompass the nuance of the original dataset, a regression equation based on population-level data can’t encompass the complexity of an individual (although we will discuss how to get closer predictions with multivariate regression analysis below).

#### The R2 Statistic

Regression analysis goes a step further than quantifying the association between independent and dependent variables. Thanks to a statistic called the R2 statistic, regression analysis can tell us **_how much_ of the change in our dependent variable is explained by changes in our independent variable.** In our chemical exposure example, for instance, R2 can tell you how much of a person’s overall cancer risk is determined by their exposure to chemical X, and how much is due to other factors such as smoking, diet, exercise, genetics, and so on.

R2 is reported as a value between zero and one and interpreted as a percent. A value of zero means that our regression equation can't predict our dependent variable at all, and a value of 1 means that it can predict 100% of the variation in our dependent variable.

In the cancer risk example, if your R2 for chemical exposure was .08, then 8% of a person’s overall cancer risk would be explained by their exposure to the chemical, and 92% would be due to other factors.

> **R 2 is Only for Linear Relationships in Linear Regression**
> 
> The R2 statistic is easy to misunderstand and, therefore, easy to use improperly. Often people interpret R2  as encompassing _any_ relationship between the two variables being studied. However, R2  in linear regression only deals with linear relationships. it's possible for two variables to be related, just not in a linear way.
> 
> (Note: There are R2 values for non-linear relationships, but they are outside the scope of Wheelan’s text, which only covers linear regression.)
> 
> For example, if you were collecting data on algal blooms (which often occur when excessive nutrients make their way into waterways and algae populations explode), you might plot nutrient levels on your x axis and algae growth on your y axis. During an algal bloom, algae growth will likely follow a non-linear exponential curve. Therefore, your R2 might be zero even though there is a strong relationship between the two variables.

### Multivariate Regression Analysis

As we've discussed, what makes regression analysis so useful to researchers is that it allows them to isolate variables of interest. **However, regression analysis is not limited to analyzing the effect of one independent variable on a dependent variable.** In fact, we can include as many relevant independent variables as we’d like in our regression equation. Including multiple independent variables in a regression equation is called _multivariate regression analysis_.

Continuing our chemical exposure and cancer example, say that after running the regression analysis discussed above, you wanted to switch your focus to quantifying the overall risk of getting cancer from _any_ source over a lifetime. In addition to exposure to chemical X, you could include other independent variables that have been associated with cancer in your regression equation: sunburns, smoking, diet, exercise, genetics, and so on.

With each independent variable added to the regression equation, researchers hope to bring their R2 statistic closer to one. In other words,**the more independent variables associated with a dependent variable that we can capture in our regression equation, the more accurate the equation will be.** An equation that encompassed every relevant independent variable would be able to perfectly predict the value of the dependent variable. With our cancer example, for instance, if every possible independent variable associated with cancer were represented in the equation, we could use it to calculate an individual's exact risk of getting cancer in their lifetime.

> **Multivariate Regression Analysis for Birth Weight**
> 
> Multivariate regression analyses are particularly useful in the medical field. Because they include more independent variables, they can provide a more individualized sense of a patient’s overall health or risk for a certain condition.
> 
> However, as Wheelan notes, multivariate regression analyses used in medicine shouldn’t attempt to include every possible independent variable because doing so can confound the results. For example, if several variables are thrown into an equation, there is a high chance that at least one “unimportant” variable will appear significant simply by chance, and its inclusion will skew the output of the equation. Therefore, the independent variables that are selected for a regression equation should have a large impact on the dependent variable. These variables can be selected via a partnership between physicians, researchers, and statisticians.
> 
> For example, data from over 350,000 births were used to analyze the relationship between maternal smoking and maternal age on infant birth weight. (We can infer that the researchers expected both age and smoking status to have a large effect on birth weight.) Results showed that smoking had an impact on infants’ birth weight and that the effect of smoking on birth weight increased with increasing maternal age. For 16- to 17-year-old mothers who smoke, the risk of having a low birth weight baby was 1.43 times greater than for non-smokers. In contrast, infants born to 40-year-old mothers who smoke were 2.63 times more likely to have a low birth weight than babies born to non-smoking mothers of the same age.

### Regression Analysis Pitfalls

Since we use regression analysis to study some of society’s most pressing problems, Wheelan explains that using regression appropriately can be a matter of life and death. Therefore, Wheelan emphasizes that _human_ logic and reasoning are essential components of regression analysis.

Wheelan gives the following reminders for obtaining and interpreting reliable regression analysis results.

Reminder 1:**Even when our regression analysis shows that our independent variable is a strong predictor of our dependent variable, we still can't report that one has _caused_ the other**. For example, there may be a highly significant regression coefficient and large R2**** for the relationship between white-tailed deer populations and rates of Lyme disease. But this doesn't mean that the deer are _causing_ the Lyme disease (as we know, the ticks that feed on the deer are).

> **The Power of Hindsight**
> 
> Sometimes it takes the power of hindsight to realize that an independent variable isn’t actually causing a change in a dependent variable. For example, a company called Sensa Products made $364 million between 2008 and 2012 by selling weight loss powder that users sprinkled on their food. The powder was meant to enhance the smell and taste of food, with the idea that users would feel satisfied with less food, and thus lose weight with little effort. The Federal Trade Commission called Sensa’s marketing misleading and scientifically unfounded and fined the company $26.5 million dollars in 2014.
> 
> As Sensa Products earned millions of dollars before being outed by the FTC, surely a percentage of users lost weight using the product. For those users, there _was_ a correlation between using Sensa and losing weight. Finding out that Sensa’s claims weren’t scientifically valid doesn’t invalidate people’s actual weight loss, and the correlation remains. In hindsight, however, those who lost weight on the product might be able to identify other variables that led to their weight loss. For example, perhaps using Sensa inspired them to simultaneously adopt other healthy habits like more exercise or decreased sugar intake.

Reminder 2: We should**be careful not to invert our independent and dependent variables**. For example, if you wanted to study the link between money and happiness, you would have to be very thoughtful about which variable you selected as the independent variable. If money is your independent variable, you would be studying whether rich people tend to be happier than less-rich people. In contrast, if you select happiness as your independent variable, you would be studying whether happy people tend to be richer than less-happy people. While the two questions may sound similar, these are quite different studies from a research perspective.

> **Using Statistics to Assess Whether Money Can Buy Happiness**
> 
> A 2010 study from Princeton University used two statistical methods Wheelan covers in _Naked Statistics_ to study the question of whether money can buy happiness. First, the study used polling to gather data from 450,000 responses to a Gallup survey about day-to-day emotions and overall life evaluation (how people rate their life in the “big picture”). Next, researchers used multivariate regression analysis to analyze whether a high income is correlated with increased emotional wellbeing and better life evaluation.
> 
> The results of the study suggest that money can buy happiness to a point. Income was positively correlated with life evaluation in general (people had a more favorable opinion of their lives overall if they made more money) and positively correlated with emotional well-being up to an income of $75,000. Beyond $75,000, income no longer predicted emotional well-being.
> 
> In this case, income was the independent variable and emotional well-being and life evaluation were dependent variables (each dependent variable was analyzed separately). If the researchers were to invert the variables and use emotional well-being and life evaluation as independent variables, and money as the dependent variable, their study would be answering a different question.
> 
> For example, instead of suggesting that money makes people happy, inverted variables might suggest that high life evaluation or emotional well-being somehow leads people to make more money; perhaps they are more effective at work, more ambitious, more likely to be promoted, and so on. While the data may be the same, the implications of the research are different. In this case, additional studies might focus on how to leverage the traits of “happy” people to be more successful at work.

Reminder 3:**Our results will be misleading if they omit a critical independent variable.** For instance, say we published a hypothetical paper highlighting a large and significant regression coefficient for the amount of time people spent at the beach and rates of skin cancer. Our results imply that just being at the beach might somehow give a person cancer when in reality it would be the sunburns in unprotected beachgoers that lead to cancer.

> **The Placebo Effect**
> 
> Recent insight into the effectiveness of placebo treatments has shown that the power of placebos may highlight missing independent variables in medical research. Since a placebo is generally thought of as “no treatment,” we might logically expect patients receiving a placebo “treatment” to experience no medical benefits in a clinical trial. However, in one study, participants who took a placebo pill experienced 50% as much migraine relief as participants taking the actual drug.
> 
> The results of the above study aren’t an anomaly. Research has shown that placebos help ease symptoms from pain to anxiety, even when people know that the “drug” that they’re taking is a placebo. Research on why placebos ease symptoms is ongoing, but possible explanations include increased body awareness, the release of dopamine and endorphins when taking a placebo, as well as the healing act of engaging in a self-care ritual (simply taking a pill, even a sugar pill).
> 
> From a research and statistics perspective, the knowledge that placebos can actually act as treatments suggests that there may be several independent variables at work in “control” groups that are unaccounted for.

Reminder 4: **We shouldn’t extrapolate our regression analysis results to a population for whom our study was never intended**. For instance, say we ran a regression analysis that showed a large and significant negative relationship between the number of miles that healthy 1- to 5-year-old dogs walked each day and behavioral problems. We shouldn’t use these results to make a blanket statement that _all_ dogs will behave better when they are walked as far as possible, as this would likely be bad advice for many senior dogs and dogs with certain health conditions.

> **Grapefruit Juice and Medication**
> 
> Reminding ourselves to interpret the results of regression analysis as they were intended is a good way to prevent alarmist reactions to research findings. For example, research shows that grapefruit juice can have health benefits for some and be a health hazard for others, as it contains a chemical that binds to digestive enzymes in our gut and prevents intestinal absorption of certain medications. When these medications can’t be absorbed in our gut, they instead travel to our bloodstream, which can lead to dangerous side effects. A sudden blood increase of calcium channel blockers used to treat high blood pressure, for instance, can lead to a dangerously slow pulse or low blood pressure.
> 
> However, it would be incorrect to infer that _all_ people should abstain from grapefruit juice for fear of its “dangerous effects.” This caution only applies to populations taking specific prescriptions. For other people, grapefruit juice contains valuable vitamin C, potassium, and fiber.

[[book_md/naked-statistics/safe-assumptions-with-inferential-statistics|safe-assumptions-with-inferential-statistics]]

[[book_md/naked-statistics/exercise-design-a-study|exercise-design-a-study]]

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=5e4c1bba-54ac-4848-88d6-d50651b248e9&sid=f30c5e70639211ee87d33f0876d93783&vid=f30c9700639211eeb3a75d830392c94f&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fnaked-statistics%2Ffinding-answers-with-regression-analysis&r=&lt=289&evt=pageLoad&sv=1&rn=88380)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



