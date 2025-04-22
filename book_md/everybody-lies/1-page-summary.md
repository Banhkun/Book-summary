![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

Discover

Books

Articles

My library

Search

Discover

![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

# Everybody Lies

Back to Discover

[[book_md/everybody-lies/preview|preview]]

  * [[book_md/everybody-lies|everybody-lies]]
  * Full Book Guide

    * [[book_md/everybody-lies/exercise-think-like-a-data-scientist|exercise-think-like-a-data-scientist]]
  * [[book_md/everybody-lies/highlights|highlights]]
  * [[book_md/everybody-lies/community|community]]



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

_Everybody Lies_ , by Seth Stephens-Davidowitz,__ is about big data’s potential to revolutionize social science research. The book’s central premise is that **people reveal more about themselves when making web searches than they would ever reveal in public or a traditional survey**. Stephens-Davidowitz argues that by harnessing data from search results and similar sources, scientists have access to all new insights into issues like sexuality, racism, and health. He suggests that these insights can inform better social policies, improve institutions like education and health care, promote social equity, and bring hidden injustice to light.

Stephens-Davidowitz has a Ph.D. in economics and has worked as a data scientist at Google and as a contributor to _The_ _New York Times_. _Everybody Lies_ draws on his research using Google search results as well as data from PornHub, Wikipedia, and more. Though the book contains many surprising and interesting findings from this research, its real purpose is to explain the benefits—and drawbacks—of big data research. Stephens-Davidowitz says he hopes to inspire readers to enter the field of data science, much as Steven Levitt and Stephen J. Dubner’s _Freakonomics _inspired him to do the same.

This guide begins by explaining what big data is and why Stephens-Davidowitz is so excited about it. Then we look at the core of the book’s argument—a set of four benefits that big data offers researchers as well as a few potential drawbacks and dangers that Stephens-Davidowitz identifies. Along the way, we balance Stephens-Davidowitz’s optimistic views on data by pointing out some of the worrying uses of big data that have come to light since the book was published in 2017. Finally, we end with a bonus section that presents a few interesting highlights from Stephens-Davidowitz’s research that didn’t make it into the main body of the guide.

### Why Data?

Before we get into the specifics of how to use big data well, let’s look at the bigger picture of what big data is and why Stephens-Davidowitz says we should care about it. Though data science might seem arcane, Stephens-Davidowitz argues that it’s really an extension of our natural intuition and of the kinds of studies social scientists have always been interested in.

> **What Is “Big Data”?**
> 
> Stephens-Davidowitz explicitly refuses to define “big data,” arguing that the only way to do so is by assigning an arbitrary numerical cutoff—in other words, by deciding that if you have at least X data points, you have big data. While it’s fair to say that big data is a somewhat fluid concept, other data experts accept that there are some key characteristics that we can use to pin down “big data.” Chief among these characteristics are the “three Vs”:
> 
>   * **Volume:** The sheer amount of data. As you’d expect, big data implies very large data sets, typically measured in terabytes or petabytes. In refusing to define big data, Stephens-Davidowitz is mostly refusing to identify a specific volume at which data becomes big.
> 
>   * **Velocity:** With big data, new information comes in fast. If your data set consists of Twitter posts, for example, you’re taking in an average of 6,000 new tweets per second. Note that not all of the data Stephens-Davidowitz uses is high velocity. Google search results are; historical census databases aren’t. But as we’ll see later in this guide, big data techniques can yield new insights into older data that has accumulated gradually over time.
> 
>   * **Variety:** Big data comes in many forms (text, video, audio, and so on) and doesn’t fit neatly into a standardized database. Stephens-Davidowitz does talk about data variety, as we’ll see, though he doesn’t explicitly say that variety is one of the defining characteristics of big data.
> 
> 

> 
> Throughout this guide, we’ll point out places where the three Vs show up in Stephens-Davidowitz’s arguments.

#### Extending Our Intuition

Stephens-Davidowitz argues that when used well, data science is an extension of our natural intuition (though as we’ll see in a moment, it often defies our intuitive expectations and assumptions). He says that one of our basic activities as humans is spotting patterns and cause-effect relationships in order to make predictions. Good data science, he says, is just an expanded, more rigorous version of this activity. However, **data science has two advantages over our natural intuition: It can consider much bigger sample sizes, and it doesn’t get distracted by compelling stories.**

##### The Power of Bigger Samples

One of the problems with human intuition is that we can only base our judgments on our own knowledge and experience. For example, a teacher grading an essay might suspect that a student copied material from a source. That suspicion often depends on previous knowledge—for example, how similar the paper is to previous plagiarism cases the teacher has encountered and how different the questionable passages are from that student’s previous writing. Moreover, it’s hard to enforce plagiarism penalties based only on suspicion. But online plagiarism checkers—which compare the text in question to materials published on the web as well as to databases of other student papers—allow teachers to easily check questionable essays against millions of potential text matches.

(Shortform note: When it comes to human judgment, larger sample sizes (which often come with age and experience) can create overconfidence bias and prevent a person from recognizing deviations. For example, the longer a teacher teaches, the more likely she is to assume that she can recognize a cheater; this overconfidence can prevent the teacher from evaluating individual cases with thoughtful analysis.)

##### Defying Conventional Wisdom

According to Stephens-Davidowitz, another advantage data has over human intuition is that it isn’t beholden to conventional wisdom. Stephens-Davidowitz argues that humans are overly influenced by a good story, which leads us to make faulty predictions or explanations because they sound good or fit a preconceived notion. For example, sports commentators will often laud players for consistently getting clutch hits or hitting high-pressure shots—but data analysis suggests that clutch performance is mostly a statistical mirage rather than a repeatable skill.

(Shortform note: Our tendency to make predictions and conclusions based on stories rather than data is known as the narrative fallacy. In _Thinking, Fast and Slow_ , Daniel Kahneman explores the narrative fallacy and other related thinking errors at length. To overcome these inherent flaws in our thinking, Kahneman recommends learning to think statistically—and one way to do that is to augment our natural judgment with data science.)

> **Shortform Caveat: The Dangers of Cherry-Picking and Confirmation Bias**
> 
> It’s easy to think of data as being objective—after all, it’s a cliché that “numbers don’t lie.” But like any human endeavor, data science is liable to reflect the biases of the people who employ it. In particular, the kinds of studies Stephens-Davidowitz specializes in are particularly vulnerable to cherry-picking and confirmation bias (a tendency to notice only the information that supports our preexisting beliefs).
> 
> For example, Stephens-Davidowitz begins _Everybody Lies_ by comparing two maps of the United States: One shows the prevalence of Google searches for a racist epithet, and the other shows how much support Donald Trump received in the 2016 presidential primary. In general, the areas of the country that made racist searches line up with the areas that supported Trump. Stephens-Davidowitz concludes that Trump support was correlated with explicit racism.
> 
> However, as some readers have pointed out, if you compare these two maps to a map of electoral results from the 2016 general election, Hillary Clinton won some of the areas with heavy racist search activity, whereas Trump won a number of states with very few racist searches. This discrepancy suggests that the connection between racism and Trump support isn’t as clear as Stephens-Davidowitz suggests—a fact that might point to confirmation bias at work in Stephens-Davidowitz’s experimental design or in his interpretation of the data.
> 
> That’s not to discount big data’s _potential_ to make our judgments more objective. But for it to do so, we need to be aware of all of the ways we can bias the process:
> 
> **1) The research design itself can be biased.** In a paper called “A Hands-on Guide to Google Data,” Stephens-Davidowitz and co-author Hal Varian point out the danger of cherry-picking data by consciously or unconsciously using search terms that support the desired conclusion (though the authors cite Stephens-Davidowitz’s racism study as an example of how to _avoid_ this danger).
> 
> **2) The tools we use to help analyze the data can be biased.** In _Noise_ , Kahneman and his co-authors point out that computer algorithms can learn and perpetuate any biases present in the data they’re trained on.
> 
> **3) Our interpretations of the data can be biased.** In _Zero to One_ , PayPal co-founder and technology advocate Peter Thiel points out that computers are unlikely to ever completely replace humans, because in the end, humans are still the ones who have to draw conclusions from the data that computers collect and process.
> 
> In short, even the best data science needs to be constantly wary of the dangers of cherry-picking and similar biases. It’s worth keeping that consideration in mind as we continue to explore the benefits and drawbacks of big data.

#### Data Gives the Social Sciences More Rigor

In addition to improving on our natural intuition, **data studies can make the social sciences more rigorous**. Stephens-Davidowitz notes that traditionally, there’s a divide between hard sciences (such as physics and chemistry) and soft sciences (such as psychology and sociology). That divide boils down to differences in method and types of evidence, with critics accusing the social sciences of advancing theories that can’t be falsified.

Stephens-Davidowitz gives the example of Freud’s theories of sexuality, which Freud based on his own observations and interpretations rather than on experimental evidence. Stephens-Davidowitz shows how Google and Pornhub search data let us test these previously untestable ideas (he finds no evidence for Freud’s claim that phallic symbols in dreams reveal latent desires; on the other hand, he finds a surprising number of searches for parent-child incest videos, suggesting some truth to Freud’s Oedipal theory).

> **Big Data and the Replication Crisis**
> 
> It’s worth wondering about the role of data-driven research in light of science’s (including psychology’s) ongoing replication crisis—in which an alarming number of experimental findings can’t be reproduced in follow-up experiments.
> 
> On one hand, some of the explanations for the replication problem have to do with experimental sample sizes. In some cases, unreliable studies might use undersized samples, which increases the chances of finding false positives. Similarly, some scientists have been accused of consciously or unconsciously manipulating their data, for example, by ending an experiment as soon as they find a statistically significant result—a practice that likewise increases the chances of faulty findings.
> 
> On the surface, data science seems to offer an antidote to these problems. Big data, by definition, operates with very large sample sizes, which decreases the chance of stumbling across small-scale fluke results or cherry-picking data.
> 
> On the other hand, data-based studies can introduce their own problems. For example, data researchers often start with the data and then formulate hypotheses to explain the patterns they find—a reversal of the traditional scientific method. This approach introduces the risk of mistaking large-scale random variation for meaningful patterns (a problem Stephens-Davidowitz calls the “curse of dimensionality” and which we discuss later in this guide).
> 
> Finally, as suggested above, data research is susceptible to some of the same problems that plague traditional methods and lead to cherry-picking and confirmation bias—problems such as arbitrary definitions, flexible hypotheses, and liberal thresholds for experimental success. In traditional science and data science alike, there’s always the chance of researchers designing studies and interpreting results in ways that support their pet ideas (or their field’s established theory).
> 
> None of this is to dismiss data science—or traditional science, for that matter. But it’s not a given that data studies will _necessarily_ equate to more (real or perceived) rigor for social sciences, especially when scientific rigor is, itself, under fire at present.

### How to Use Data Well

Despite all of these potential advantages, Stephens-Davidowitz acknowledges that it’s easy to use big data ineffectively—for example, by obsessing over the sheer size of your dataset without thinking about what that data can actually do for you. To get the most out of big data, Stephens-Davidowitz says you should focus on its **four main benefits: new types of information, unprecedented honesty, high resolution, and easy cause-effect analysis**. In this section, we’ll explore each of these benefits in turn.

#### Benefit #1: New Types of Information

Stephens-Davidowitz says that one of the benefits of big data is that it opens our eyes to new types of information that weren’t previously available or that we might not previously have been able to study. (Shortform note: This benefit essentially expounds on big data’s _variety_ —one of the three Vs mentioned earlier.)

##### Words, Words, Words

There’s nothing new about using words as data. As Stephens-Davidowitz points out, linguists, social scientists, historians, and others have studied words and word usage for a long time. But **big data dramatically enhances the type and volume of words researchers can study**. (Shortform note: It’s this enhanced _volume_ —another of the three Vs—that makes familiar data like text into big data. Thanks to the sheer volume of text databases and the ease of searching and comparing texts, it’s easier than ever before to study how words are used and combined across many different contexts.)

Stephens-Davidowitz himself bases most of his insights and arguments on search terms used in Google and other search engines. Search engines—and the databases of information they compile as users use them—are a relatively recent invention and represent a new source (or _variety_) of data for researchers and analysts.

> **A Brief History of Web Search**
> 
> Just how new is search data? The first search engine, Archie, was launched in 1990 as a relatively simple tool for searching public file servers (prior to Archie, the internet was indexed by hand). Throughout the 1990s, a number of new search engines emerged that allowed users to search the whole web like we’re used to today. In 1998, Google introduced better search methods and other improvements and quickly became the predominant search engine worldwide—today, over 90% of web searches are run through Google.
> 
> It’s unclear whether earlier search engines compiled search data the way Google does—and early on, even Google didn’t publish their search data regularly. But in any case, it’s hard to imagine Stephens-Davidowitz’s research prior to Google. Even if earlier search engines had collected search data, that data would be spread across a handful of companies instead of centralized in one place. Likewise, none of those prior search engines had anywhere near the user base Google has today—and it’s the sheer amount and currency (_volume_ and _velocity_) of information that makes Google’s data useful for the kinds of studies in _Everybody Lies_.

Stephens-Davidowitz points out that computers also make it easy to analyze large volumes of text and/or speech that would be difficult or impossible to deal with manually. For example, he cites a study of word frequency in Facebook status updates and shows how word usage breaks down among gender and age lines—for example, perhaps unsurprisingly, he demonstrates that college-age people post about “studying” during the “semester” whereas 20-somethings drink “beer” when they aren’t “at_work.” Similarly, he explains that researchers can use sentiment analysis to determine the overall emotional tone of a body of text.

(Shortform note: While Stephens-Davidowitz is excited about how academic researchers can use text analysis—for example, he cites studies that use sentiment analysis to map narrative trajectories in works of fiction—most of the practical application of these techniques seems to take place in the business world. For example, businesses use text analysis and sentiment analysis to gauge customer interest and reactions, detect problems early, and improve customer service.)

##### Unconventional Data Sources

Though Stephens-Davidowitz specializes in using search records, text databases, and other similar types of data, he points out that there are new data sources that researchers have only recently started to tap. These data sources show that big data isn’t just about bigger databases of traditional information—it’s also about how **new technologies let us turn more things into data** by making them easy to measure, collect, compile, and analyze.

For example, Stephens-Davidowitz suggests that **bodies can be data**. He describes how consultant Jeff Seder helps buyers choose winning racehorses (Seder and his colleagues once advised a client to re-buy the horse he had just put up for auction—that horse was American Pharaoh, who went on to win the Triple Crown). Seder’s secret is that instead of looking at traditional horse judging factors like pedigree, he found anatomical factors (like left ventricle size) that correlate to race success.

(Shortform note: Body-based data is now far more prevalent than in Stephens-Davidowitz’s 2017 account. Whereas Seder’s work required him to custom build a portable ultrasound machine to examine horses, wearable fitness trackers and smart exercise equipment now allow many users to turn their bodies into data on a daily basis. Privacy experts have raised concerns over this trend, pointing out that these kinds of fitness products can record your biometric data, location, behavior patterns, and even your face and voice. In one notable case, maps based on Fitbit data revealed the location and layout of US military bases around the world and even showed the identities and workout routes of individual soldiers.)

Stephens-Davidowitz also argues that **images can be data.** For example, he describes how a company called Premise uses smartphone photos of things like gas station lines or grocery store produce to make economic predictions that are better and timelier than any traditional measures. What both images and biometric data have in common is that they’re easier to collect, compile, and study than ever before. Premise’s work is possible only thanks to smartphones, which guarantee that many people have high-quality cameras on their person at all times and which make it easy to share photographic data to a main hub from anywhere in the world.

(Shortform note: Whereas Premise contributors collect image data deliberately, other sources of image data are less obvious—and potentially more problematic. For example, Amazon’s smart doorbell Ring has come under fire for sharing video information with law enforcement without warrants. Similarly, a British judge recently ruled that a Ring doorbell violated a neighbor’s privacy due in part to its ability to record private conversations up to 68 feet away.)

#### Benefit #2: Honest Information

In addition to expanding the types and amounts of data we collect, Stephens-Davidowitz says that big data offers more honest information than we’ve ever had before. He points out that **people tend to lie in traditional surveys**. For example, people are unlikely to be totally honest about their sexual habits when talking to another person—even if that person is a stranger administering an anonymous survey.

Respondents will probably be more honest in an online survey than an in-person survey—but that still doesn’t solve the problem of self-deception. Stephens-Davidowitz argues that we’re often poor judges of our own thoughts and behaviors because we don’t want to acknowledge the less savory aspects of ourselves.

##### Google Confessions

**Google searches and other internet activity** , on the other hand,**reveal truths that might never come out in traditional data-gathering methods** like surveys. For example, Stephens-Davidowitz shows that in states whose laws oppose gay marriage, the percentage of self-reported gay men is much lower than the estimated average across the whole population. But, he says, if you look at searches on Google and on porn sites, the percentage of male users looking for gay porn (or asking how to tell if they’re gay) is much closer to that average. Also, the percentage of gay men as defined by search results is roughly stable from state to state.

This suggests that search data is a more accurate—and honest—measure of gay male sexuality than traditional surveys. Similarly, Stephens-Davidowitz says that search results reveal truths about all kinds of topics that we have an incentive to lie about or hide in real life, such as:

**1) Sexuality:** Stephens-Davidowitz says that, in addition to the data on gay men, search results cut against common stereotypes about sexuality. For example, women are just as likely to ask Google why their husbands or boyfriends don’t want sex as men are to ask the same about their wives and girlfriends.

**2) Prejudice:** Stephens-Davidowitz argues that the prevalence of searches for racist terms and phrases reveals that there is a lot more explicit prejudice (as opposed to unconscious bias or systemic inequity) than traditional surveys suggest.

**3) Child Abuse:** During the 2007-08 financial crisis, experts predicted a rise in child abuse and neglect only to be surprised by a downturn in cases. Stephens-Davidowitz shows that searches like “my mom beat me” went up in heavily affected areas—suggesting that abuse and neglect increased, but that cases went unreported or uninvestigated because of lessened resources.

**4) Abortion:** Stephens-Davidowitz explains that searches about self-induced abortion are more common in states with restrictive abortion laws.

> **Why Do People Confess to Google?**
> 
> One of the interesting things about Stephens-Davidowitz’s research is that many Google searches take the form of declarative statements rather than questions or strings of keywords. For example, Stephens-Davidowitz cites queries like, “I regret having children”—statements that seem more like diary entries than search terms. Stephens-Davidowitz acknowledges this oddity, but because he’s more interested in the topics of searches than their syntax, he doesn’t spend much time exploring _why_ so many people “talk” to Google this way.
> 
> One possible explanation has to do with how people construct their identities. In a paper examining the causes of dishonest self-reporting on surveys, Philip S. Brenner and John DeLamater propose that people might answer surveys in ways that reflect who they want to be __ rather than their actual actions. In other words, if honesty is important to you and you consider yourself to be an honest person, you might, if surveyed, misreport how much you lie—not because you’re embarrassed to admit to your occasional dishonesty, but because you subconsciously see the survey as a chance to reconfirm your “honest person” identity by reporting honest behavior.
> 
> Brenner and DeLamater’s hypothesis adds an interesting nuance to the idea that users see Google as a safe space. Just as certain questions—like, “Why won’t my partner have sex with me?”—might be hard to ask in public because they’re embarrassing, certain opinions might be hard to acknowledge if they cut against the ways we define ourselves. For example, if you regret having children, that regret might very well threaten your identity as a parent. In other words, just as Google offers a private way to look for information or advice you wouldn’t want to ask other people for, it also seems to offer a place to express thoughts that you might not even want to admit to yourself.

##### Reasons for Hope

Stephens-Davidowitz argues that although a lot of this data seems depressing, it also offers causes for hope. He gives three reasons:

**First, he says that** **big data suggests that you’re not alone**. Internet searches show that in pretty much any case, a lot more people than you think share the kinds of concerns, troubles, and interests that you might never admit to in public.

**Second, he argues that big data can point out suffering that we wouldn’t otherwise notice** , as with the child abuse data mentioned above.

**Finally, he says,** **big data provides feedback we can use to solve problems**. He explains that during an Obama speech decrying Islamophobia, Islamophobic searches actually increased—except after a line about Muslim athletes and soldiers, which seemed to prompt curious rather than hateful searches. Stephens-Davidowitz says that Obama’s speechwriters appeared to capitalize on this data by tailoring a future speech to focus on concrete examples of Muslim Americans rather than abstract calls for tolerance.

> **…And Reasons for Concern**
> 
> While Stephens-Davidowitz focuses on the potential benefits of the uncomfortable truths people reveal online, it’s also worth pointing out how some of these truths can be exploited for more cynical purposes. For one thing, even as big data suggests the sheer diversity of opinions, preferences, habits, and interests, it offers up that diversity as a boon to advertisers: Google Trends—the same resource behind much of Stephens-Davidowitz’s research—positions itself in part as a marketing tool that promises to help businesses craft better campaigns by revealing the topics their prospective customers search for.
> 
> Unfortunately, the targeted ad techniques that have grown out of big data can easily be used to create racially discriminatory ad campaigns—for example, by illegally excluding racial and ethnic minorities from housing ads. In extreme cases, some journalists have shown how easy it is to create ads specifically intended for “Jew haters” on Facebook while others have demonstrated how Google’s ad platform actually helps advertisers target racist search terms by offering related searches such as “black people ruin neighborhoods.” It’s important to note that Facebook and Google disable these sorts of abuses when they come to light, but recent studies suggest that the larger problem still exists.

#### Benefit #3: High Resolution

Stephens-Davidowitz argues that one of the powers of big data is that **it allows you to zoom in on specific subsets of data, which in turn allows new insights** and new types of studies. (Shortform note: This benefit derives from another of the three Vs— _volume_.)

##### High Definition Information

Big data allows us to zoom in because, by providing so many data points, **it gives our information better resolution in the same way that a high-definition display improves resolution by including more pixels**.

For instance, Stephens-Davidowitz describes using Wikipedia’s database to figure out what geographical factors give you the best chance of succeeding in life. He used the database to figure out the birth county of every American notable enough to warrant a Wikipedia entry, then he cross-referenced that information with census and other data to find that the most important factors for success are proximity to a big city, proximity to a major university, and proximity to an immigrant population. His point is that a study like this is only possible because he had enough information to zoom in on individual counties and compare them across numerous factors.

(Shortform note: A study like this points to another power of big data that Stephens-Davidowitz doesn’t explicitly discuss: the ease of cross-referencing different types of information. Much of Stephens-Davidowitz’s work involves combining and comparing data from different sources to draw out new insights—even from “old” information like census data.)

##### The Power of Doppelgangers

Another big data technique Stephens-Davidowitz identifies is what he calls the **_doppelganger_ method—a technique where researchers make predictions about one person by studying another person who’s statistically similar to the first person**.

He explains that this method was first developed by statistician and political forecaster Nate Silver, who used it to predict baseball players’ future performances. Silver realized that instead of trying to map a player’s performance onto a generic career trajectory curve, it would be better to find the past players who were statistically most similar to the player in question. These similar players are what Stephens-Davidowitz calls doppelgangers, and finding them lets you use them as a reference for your predictions. For example, if you’re trying to decide whether to keep or trade your star hitter as he nears 30 years old, you can look at his doppelgangers to see whether they kept performing or declined in their 30s.

Stephens-Davidowitz suggests that the doppelganger method could be used to improve other fields such as medicine. He argues that if we gathered and compiled enough medical data, we could find doppelgangers for each patient, and doctors could use these doppelgangers to inform their medical decisions. For example, by comparing a patient to other similar patients, a computer could flag the early symptoms of disease before they’re obvious to the doctor. He argues that a doppelganger system would also let patients find others similar to themselves in order to find out what treatments helped their doppelgangers.

(Shortform note: In _Thank You for Being Late_ , Thomas Friedman mentions that IBM found a similar use for Watson—their computer system most famous for beating Ken Jennings and Brad Rutter at _Jeopardy!_. They trained Watson to identify early-stage melanomas by looking at pictures of questionable skin lesions and comparing them to a database of cancerous and noncancerous lesions. The goal, according to an IBM researcher, is for computers to reduce the size of the haystack doctors have to sift through to find the needle of early cancer—Friedman further argues that by shifting the diagnostic burden onto Watson, doctors can focus on exercising the judgment and empathy that only humans provide. The technique has since been expanded by other researchers to use AI to evaluate large expanses of patients’ skin for suspicious marks.)

**Similar to zooming in, finding doppelgangers requires a high volume of information** —you need enough people in your database to have a high likelihood of finding matches, and you need enough different data points on those people to be able to compare them meaningfully. Stephens-Davidowitz points out that the doppelganger technique—like many statistical and data science developments—started in baseball because baseball has far more comprehensive data (in terms of breadth, depth, and historical longevity) than most fields.

(Shortform note: Coincidentally, baseball also offers another example of the type of _new_ data we saw earlier. Baseball analytics traditionally relied on players’ statistics (batting average, home runs, and so on) for insights. But recently, ballparks installed video-based tracking systems like PITCHf/x to record information like pitch velocity and spin rate, batted ball speed and trajectory, players’ running speed and ground covered, and so on. These new data types have opened up a whole new realm of performance analysis, showing that even in one of the most data-heavy industries imaginable, there are brand new types of data yet to be unearthed and studied.)

#### Benefit #4: Easy Cause-Effect Studies

The final benefit Stephens-Davidowitz says big data has is that **it makes it easy to perform causal research**. Scientific studies typically try to find cause-effect relationships by performing experiments that determine what impact a given variable has in a specific situation. In the social sciences, this research traditionally involves recruiting volunteers, dividing them into two or more groups, exposing some of the groups to the variable, and comparing those experimental groups to the control group.

Stephens-Davidowitz points out that this traditional experimental process requires a lot of funding, time, and other resources—and these factors limit the number of experiments researchers can do as well as the scope of those experiments. He says that big data research eliminates these problems, thereby vastly expanding the research we can do.

##### A/B Testing

**One way big data makes causal research easier is by enabling simple A/B testing.** Stephens-Davidowitz explains that an A/B test entails randomly selecting groups of users and showing each group a different version of a product or feature. For example, if a business is developing a new webpage, they might code their site so that half of their visitors see a red background and half see a blue background. They could then track each group to see how long people stayed on the page, how many links they clicked on, and whether they bought anything. By comparing the red group to the blue group, the company could determine which background color is more effective.

(Shortform note: Stephens-Davidowitz frames A/B testing as a way for data science to expand social science research, but the scientific benefits are not so clear cut. For one thing, most of the real-world applications of A/B testing seem to be limited to the corporate and political worlds—which might explain why Stephens-Davidowitz’s examples are limited to experiments with marketing and interface design. Moreover, when sites like Facebook have used A/B techniques to explore sociological questions, critics have questioned the ethics of manipulating users’ emotions or influencing their voting behavior in the name of research.)

##### Natural Experiments

**Big data also makes causal research easier by allowing researchers to study pre-existing data** (rather than running experiments to generate new data). Stephens-Davidowitz calls these kinds of studies _natural experiments_ —a technique common in fields like economics and epidemiology where controlled experiments would be impossible or unethical. A natural experiment entails studying the results of natural processes such as disease outbreaks or market changes as though they were the results of randomized controlled experiments.

For example, Stephens-Davidowitz cites studies that examined whether attending an elite high school or college results in better outcomes than attending an ostensibly lesser school. It wouldn’t be ethical to ask schools to alter their admissions for the sake of an experiment, so the researchers instead turned to pre-existing data. To account for the fact that elite schools attract elite applicants, researchers studied two groups—students who just made it in and those who just missed the admissions cutoff or who were admitted but went to school elsewhere. The studies examined future salaries as a measure of success, and found similar results from both groups, suggesting that the schools themselves have little impact on their students’ future success.

As with zooming in and doppelganger studies, this kind of research is only possible thanks to big data’s high volume. Researchers needed to know a lot about the students in question: their application qualifications like test scores, their backgrounds, which colleges they applied to, which colleges they attended, and their career earnings.

(Shortform note: Researchers conducting natural experiments need to be especially careful to avoid some of the pitfalls mentioned earlier—namely, cherry-picking data to suit a hypothesis or, conversely, shaping a hypothesis to fit the data. _Antifragile_ author Nassim Nicholas Taleb also warns about the danger of data scientists mistaking coincidental correlations for cause-effect relationships. Taleb argues that an easy way to confirm a causal relationship is by observing whether the proposed cause always comes before the proposed effect—something that’s harder to do when studying data after the fact rather than observing events as they happen.)

### Data’s Drawbacks and Dangers

Even though Stephens-Davidowitz is openly enthusiastic about data studies, he’s aware that **data has drawbacks and limitations and can lead to great harm if used unethically.** In this section, we’ll look at some of the drawbacks and dangers Stephens-Davidowitz identifies and explore some cases where these dangers have come to pass since the book’s publication.

#### Drawbacks: When Data Gets in the Way

Stephens-Davidowitz warns that good data science isn’t just a matter of amassing a giant data set. When working with data, he says it’s important to keep data’s shortcomings in mind and not lose sight of the bigger picture.

##### Drawback #1: False Correlations

Stephens-Davidowitz says that when a dataset is too detailed, it can lead to predictive errors. The problem, he says, is the **_curse of dimensionality_ —a phenomenon whereby the more details a dataset contains, the more likely it is to suggest false positives when you look for predictive correlations.**

Stephens-Davidowitz gives the example of flipping coins to try to predict the stock market. Say you flip a coin every day, record whether it was heads or tails, and then record whether the stock market went up or down that day. Stephens-Davidowitz says that if you perform this test using 1,000 coins for two years, it’s likely that by pure chance, at least one coin’s results will appear to correlate with market performance. Obviously this correlation is false. But Stephens-Davidowitz says this problem happens any time you test a lot of variables against a small number of outcomes—such as when trying to predict the stock market or link gene variations to disease likelihood.

(Shortform note: In addition to the risk of drawing conclusions based on random noise as Stephens-Davidowitz describes, the curse of dimensionality can make it hard to draw any meaningful conclusions at all. That happens when you classify data into so many parameters that all data points appear equidistant from each other and there are fewer “clusters” of data to draw your attention—in other words, you can no longer see useful similarities between items.)

##### Drawback #2: Data for Data’s Sake

Stephens-Davidowitz points out that it’s easy to fall in love with data for its own sake. When that happens, **we’re likely to lose sight of what the data was supposed to be doing for us in the first place**. He gives the example of standardized testing in education, which aims to make teaching and learning measurable by generating data on student outcomes. But in many cases, schools end up focusing on improving their test scores (which are tied to schools’ reputation and funding) by any means necessary—means that include limiting the curriculum in order to focus on test prep and, in extreme cases, cheating on the tests.

Stephens-Davidowitz says that studies suggest the best way to use data to measure teacher quality is to combine test scores with other factors like student evaluations and classroom observation. He says that many fields are finding that **this combination of big data and traditional, small-scale information works better than focusing on big data alone**.

> **Big Data vs. Small Data**
> 
> Similarly, in _Small Data_ , author and branding consultant Martin Lindstrom argues that big data on its own is misleading and that it should be coupled with what he calls “small data”—in-person observation of people’s desires and motivations.
> 
> Lindstrom gives the example of LEGO, which tried to address struggling sales by turning to big data research. That research convinced the company that millennials would be easily bored by toy building blocks, so the company simplified its sets in an attempt to offer instant gratification. This approach failed. But when market research _interviews_ with actual children revealed that kids like mastering hobbies, LEGO found more success than ever before by making _more_ complicated sets—an approach that directly contradicted what big data had told them.
> 
> Lindstrom’s definition of “small data” is not the only one. Other researchers use the term to describe small-scale measurements of specific attributes—such as wind direction sensors on wind turbines or smart bottle labels that track a medicine’s remaining shelf life. This kind of small data can work on its own (for example, by telling the turbine to adjust its blades to maximize electricity output) or integrate with big data techniques (for example, to track when, where, and why medicines expire on shelves).

#### Dangers: Exploitation and Privacy Invasion

Stephens-Davidowitz warns that big data can easily lend itself to exploitative practices by businesses and by governments.

##### Businesses Exploit Customers

While A/B testing can help businesses optimize their products and services by identifying the most effective design choices, **it can also help them make their offerings more addictive**. He points out that from a business perspective, a site like Facebook is ultimately designed to get you to spend more time on Facebook. The more addictive they make the site and its services, the better, and A/B testing helps them find the best ways to keep users hooked.

Similarly, Stephens-Davidowitz argues that **businesses can use the doppelganger method to extract the maximum profit from their customers**. He gives the example of casinos, which can use data about customers like you to predict your pain point—the point at which you lose enough money that you won’t come back to the casino for a while, if at all. Once they know your pain point, they can let you lose money until you’re approaching that point, then intervene to offer you a free dinner or other perks. They come across as generous when in reality they’re manipulating you by stopping you from gambling now so that you’ll come back sooner.

(Shortform note: Some critics warn that data-based business practices might have even farther-ranging consequences than these. For example, in _21 Lessons for the 21st Century_ , Yuval Noah Harari argues that the increasing prevalence of computer algorithms threatens to erode our free will. He suggests that the more we learn to trust computer-generated suggestions, the less we trust our own decision-making capabilities—taken to an extreme, he argues that this trend could lead to humans entrusting their entire lives to computers and their data-driven recommendations.)

##### Minority Report

Finally, **Stephens-Davidowitz warns of the temptation to use data to make inappropriate predictions about individuals**. He points to studies of loan applications that identify which words are most correlated with future defaults and which are most associated with paying back the loan. He points out that it would be unfair for a lender to use this information to deny a loan in any one particular case, based only on the words an applicant used. That’s because data can only identify statistical likelihoods, which tell us, for example, that _many_ people who “swear to God I’ll pay back this loan” default; this insight says nothing about _any specific_ loan applicant’s likelihood of default (whether they “swear to God” or not).

(Shortform note: And yet, as Harari points out, many banks and other institutions already use algorithms for just such purposes—a practice that potentially leads to new forms of discrimination. Similarly, some fitness trackers offer discounts on insurance premiums for meeting certain fitness goals—what they don’t tell you is that there’s nothing stopping insurance companies from raising your rates based on the data they collect.)

Likewise, Stephens-Davidowitz says, it may be possible to correlate, for instance, a rise in searches for racist terminology in a specific neighborhood with the likelihood of racially motivated violence in that neighborhood. He argues that it may even be prudent to use this information to allocate police resources. But **he rejects the idea of acting against individuals** —just because somebody’s Google search suggests an _interest_ in committing a hate crime doesn’t mean that person will _actually commit_ any crime.

Stephens-Davidowitz acknowledges that these lines can be fuzzy: If police know that someone has been Googling where to buy guns and ammunition, how to modify those guns to make them fully automatic, and for information on a nearby school, should they intervene directly against that person? Should they inform the school? The answers aren’t clear.

> **How Governments Already Exploit Big Data**
> 
> Just as banks and insurance companies already use data to inform their decisions, governments and law enforcement already use data to surveil citizens and, in some cases, act against them. In _Permanent Record_ , Edward Snowden details how he discovered a secret US government program for collecting data on individuals without warrants. Though this program’s public exposure was met with outrage and legal challenges, government surveillance and data collection has only expanded since Snowden blew the whistle in 2013. For example:
> 
> 1) Data-mining company Palantir has come under criticism from human rights advocates and its own employees for maintaining a lucrative contract with the US’s Immigration and Customs Enforcement agency—which has used Palantir’s technology to detain and deport immigrants.
> 
> 2) During the COVID-19 pandemic, the US and UK governments partnered with Palantir to track patients and map outbreaks.
> 
> 3) With the overturning of Roe v. Wade, privacy advocates worried about the potential for the government to scrutinize pregnant women’s online activity and even track their locations in order to intervene against those who might seek abortions.
> 
> These real-life applications of big data bring to mind Harari’s concerns about who owns and has access to personal data. In _21 Lessons for the 21st Century_ , Harari argues that data in government hands poses the threat of authoritarian measures bordering on national mind control.

#### Bonus: _Everybody Lies_ ’s Insights and Curiosities

_Everybody Lies_ is full of strange, interesting, and disturbing insights into human nature. Throughout this guide, we’ve focused on the logical core of Stephens-Davidowitz’s arguments about big data—which means ignoring most of the juicy tidbits in order to focus on his fundamental claims. Given how important (and fun) those tidbits are to the book as a whole, we’d be remiss not to include a few of the more interesting details that didn’t make it into the main body of the guide. For instance:

1) Conventional wisdom holds that most professional basketball players come from poor inner-city backgrounds—but in fact, for black players in particular, **being born in a wealthy county doubles the chances of reaching the NBA**. Stephens-Davidowitz explains that a wealthier background means better nutrition (which translates to height) and better interpersonal skills (which help players navigate the pressures and politics of professional sports).

2) According to textual analysis, American newspapers on average are more liberal than conservative—not because the papers themselves have a political agenda, but because they shape their content to appeal to the political biases of their audiences.

3) Women are twice as likely as men to search for porn that features violence against women.

4) Violent movies reduce the rate of violent crimes.

5) Super Bowl ads are so effective that companies are actually underpaying for them. The ad’s impact is strongest in the markets whose teams play in the game.

> **A Final Shortform Note: The Humanity of Data Analytics**
> 
> It’s also worth ending on facts like these because, while they might seem trivial, they remind us of the human interest at the core of _Everybody Lies_. As Stephens-Davidowitz points out, data isn’t valuable in and of itself—its value lies in its potential to advance human ends (for good or ill, as we’ve discussed throughout this guide). Ultimately, it’s not about any specific technique or technology or even about big data per se; it’s about how new information—and new ways of _working with_ information—can help us better understand ourselves and improve our lives. We can infer that Stephens-Davidowitz includes these fascinating insights, in part, to connect data with our humanity, and it previews where data has gone since.
> 
> If we review the trends in data science since _Everybody Lies_ ’s 2017 publication, we see an increasing emphasis on combining data with human insight. In recent years, data scientists, technology professionals, and companies have emphasized more flexible and versatile data applications and better integration with human users. For example:
> 
> 1) The fields of AI and machine learning have moved away from ever-larger data sets in favor of techniques like transfer learning, in which machines are programmed to learn new but related tasks based on things they already know. This approach allows researchers to use AI to study problems for which large data sets might not be available or practical.
> 
> 2) Similarly, developers have found that AI works best when it’s trained not just by large datasets, but also by human expertise. This approach not only improves the AI, but it also leads to a helpful division of labor as computers tackle routine tasks and humans only step in to solve more difficult problems.
> 
> 3) Many companies have started pursuing data democratization—a practice of empowering everyone in the organization (not just specialized analysts) to understand, access, and work with data.
> 
> As technology continues to evolve, the specifics will keep changing; as we can see, data research already looks different from what we find in _Everybody Lies_. But as society becomes increasingly driven by data, it only becomes more important to consider the underlying human potential (for good and for harm) that Stephens-Davidowitz describes.

[[book_md/everybody-lies/preview|preview]]

[[book_md/everybody-lies/exercise-think-like-a-data-scientist|exercise-think-like-a-data-scientist]]

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

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=866a3966-311c-47b0-84cf-2fc442c705b9&sid=49fff5b0636c11eeb9c611038afc8668&vid=4a005010636c11ee80c703d4c4a7acd5&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Feverybody-lies%2F1-page-summary&r=&lt=336&evt=pageLoad&sv=1&rn=264544)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



