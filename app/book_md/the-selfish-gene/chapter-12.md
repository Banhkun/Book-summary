![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

Discover

Books

Articles

My library

Search

Discover

![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

# The Selfish Gene

Back to Discover

[[book_md/the-selfish-gene/preview|preview]]

  * [[book_md/the-selfish-gene|the-selfish-gene]]
  * Full Book Guide

    * [[book_md/the-selfish-gene/chapters-1-2|chapters-1-2]]
    * [[book_md/the-selfish-gene/chapter-3|chapter-3]]
    * [[book_md/the-selfish-gene/chapter-4|chapter-4]]
    * [[book_md/the-selfish-gene/chapter-5|chapter-5]]
    * [[book_md/the-selfish-gene/chapter-6|chapter-6]]
    * [[book_md/the-selfish-gene/chapter-7|chapter-7]]
    * [[book_md/the-selfish-gene/chapters-8-9|chapters-8-9]]
    * [[book_md/the-selfish-gene/chapter-10-11|chapter-10-11]]
    * [[book_md/the-selfish-gene/exercise-think-about-the-impact-of-memes|exercise-think-about-the-impact-of-memes]]
    * [[book_md/the-selfish-gene/chapter-12|chapter-12]]
    * [[book_md/the-selfish-gene/chapter-13|chapter-13]]
    * [[book_md/the-selfish-gene/exercise-identify-extended-phenotypes|exercise-identify-extended-phenotypes]]
  * [[book_md/the-selfish-gene/highlights|highlights]]
  * [[book_md/the-selfish-gene/community|community]]



Adding to Favorites 

Removing from Favorites 

## Chapter 12: The Prisoner’s Dilemma

This chapter is about another way to use game theory to explain behaviors, especially at the population level. By using game theory, scientists can determine effective behavioral strategies. They can also find—or at least approximate—an ESS for a population made up of such behaviors.

**The Prisoner’s Dilemma is a logistical riddle closely tied to game theory.** In the Prisoner’s Dilemma there are two players, each with two options: Cooperate and Betray. Neither player knows which option the other has chosen, and they are not allowed to influence the other’s choice in any way.

If both players choose Cooperate, they each get a significant payout—but a smaller one than in the next situation. If one player Cooperates and the other Betrays, the betrayer gets a large payout while the cooperative player suffers a large penalty. If both players Betray, they each suffer a small penalty. Cooperation and betrayal are altruistic and selfish actions, respectively. Therefore, everything we know about the Dilemma could be compared to nature.

**In any single instance of the game, the logical choice is to simply pick Betray.** If your opponent chose Cooperate, you’ll get a larger payout than if you’d also chosen Cooperate. If your opponent chose Betray, you’ll suffer a smaller penalty than if you’d chosen Cooperate.

**However, the strategy becomes much more complex if you play over and over again.** Now one Always-Betray strategy can get stuck in a penalizing loop with another one, while more cooperative strategies have the chance to reap mutual benefits. Of course, an Always-Cooperate strategy will still lose every time to an Always-Betray strategy.

### Which Strategies Are the Most Effective?

Professor Robert Axelrod once invited programmers to create programs that use Prisoner’s Dilemma strategies, which he then entered into a virtual “tournament.” In this tournament, each program played 200 rounds of Prisoner’s Dilemma with each of the others, including a copy of itself. Whichever program had the highest total score at the end was the winner.

There were a number of complex strategies submitted for this tournament, some of which were quite cutthroat. However, the surprising winner of the tournament was a simple program called Tit for Tat. This program always played Cooperate on the first round, then for each round after that it simply copied what its opponent had done last. This made it so cooperative strategies were rewarded, while aggressive strategies were punished. Afterward, Axelrod calculated that a so-called “Tit for Two Tats” program would have done even better; such a program wouldn’t Betray until having been betrayed twice in a row itself, and would therefore have avoided some penalizing loops that Tit for Tat got caught in.

Out of 15 programs submitted, eight of them were programmed to never Betray first, and those eight “nice” programs had the highest scores. The aggressive strategies all scored significantly lower than their cooperative counterparts. The weakest of the top eight was an “unforgiving” program, which played Cooperate until the first time it was betrayed, and then played Betray every round after. This meant that it couldn’t break out of penalizing loops the way the other cooperative programs could.

Professor Axelrod held a second tournament after announcing the results of the first. Many programmers submitted “nice” programs for this second contest, reasoning that cooperation must be a winning strategy since it had done so well the last time. One entrant was the theorized Tit for Two Tats that would have won the previous tournament. Others tried submitting more aggressive, cutthroat strategies, hoping to take advantage of the cooperative field.

Once again, Tit for Tat had the highest score, beating even the Tit for Two Tats program that would have won the first tournament. The fact that Tit for Two Tats did not do as well in this tournament as it would have in the last one demonstrates an important point: **The best strategy depends on what others around you are doing.** Similarly, while Tit for Tat does well against a wide range of opponents in a diverse field, it would not succeed if the field were _too_ aggressive, because its first Cooperate play would put it at an immediate disadvantage.

Axelrod held a third tournament using the same programs from the second. However, this time he tried to mimic biology by paying winners not in points, but in “offspring” who would go on to the next round. After around 1,000 “generations,” the proportions of offspring stopped shifting in any meaningful way. That is to say, the field had reached its Evolutionarily Stable Strategy.

Axelrod ran this simulation six times. Tit for Tat was the most successful in five of them, with similar cooperative-but-retaliatory programs also doing quite well. Aggressive programs tended to do well at first, but decline and die out as they drove their “prey” to “extinction.”

**However, Tit for Tat alone—or any program that never Betrays first—can’t be considered a true ESS.** Such a population could be infiltrated by a mutant program that _never_ picks Betray. As long as there are no aggressive programs in the field, that new program can spread. That would leave the entire population vulnerable if an aggressive program were later introduced. Axelrod coined the term “Collectively Stable Strategy” to describe this situation (remember that an ESS _cannot_ be invaded by another strategy).

### Finding Stability

We could consider Axelrod’s system to have two stable points. One is the Tit for Tat dominance (or similar cooperative-but-retaliatory strategies) we saw. The other is Always-Betray dominance—in a field dominated by Always-Betray programs, no other program could do better because no strategy can beat Always-Betray in a head-to-head match.

**Which stable point the system goes to depends on which programs are present at the start, and what—in a computer simulation—could be called chance.** However, if we shift to thinking about nature, we can come up with better explanations than pure luck.

In nature, most animals tend to cluster together with others of their kind—not only because of the advantages of doing so, but also because most organisms don’t stray very far from where they were born. This is called _viscosity_.

Tit for Tat does best when surrounded by similar strategies. On the other hand, Always-Betray does particularly badly when surrounded by other aggressive strategies, as they get locked into penalizing loops. Therefore, a cluster of Tit for Tat will prosper, while a cluster of Always-Betray will suffer.

**While it will be difficult for another strategy to invade a population of Always-Betray individuals, it’s almost inevitable that it will happen eventually.** A population of creatures with the Always-Betray strategy will continually weaken itself, while a population of more cooperative individuals will prosper and spread. Sooner or later the balance will tip back toward the cooperative population.

**Therefore, while Always-Betray is technically an Evolutionarily Stable Strategy (in the sense that no other program could do better in a population of Always-Betray), and Tit for Tat is technically not an ESS (because it could be invaded by a mutant program and eventually overthrown), it could be said that Tit for Tat has a long-term stability that Always-Betray lacks.**

Aggressive strategies have a quality that Tit for Tat lacks, which may explain this difference. This quality could be called envy, or perhaps competitiveness. The key difference is that Tit for Tat is not concerned with “beating” its opponent—in fact, it can’t possibly get a higher score than its opponent, since it will never Betray unless it’s betrayed first. Tit for Tat’s only concern is for scoring points, not for scoring _more_ than anyone else.

Aggressive strategies, on the other hand, seek to “win” their matches by beating down their opponents. This is why, when a field is dominated by aggressive programs, they inevitably suffer for it. The mistake aggressive strategies make is treating Prisoner’s Dilemma like a _zero sum game_ : a game in which one player’s win must be another player’s loss, such as chess. However, in Prisoner’s Dilemma—and, arguably, in nature—both players can do quite well if they’re not concerned about “winning.” This is the very nature of reciprocal altruism.

[[book_md/the-selfish-gene/exercise-think-about-the-impact-of-memes|exercise-think-about-the-impact-of-memes]]

[[book_md/the-selfish-gene/chapter-13|chapter-13]]

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__




![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=f324c9ba-76c1-4f69-bbb4-992d347f8451&sid=1711133063fa11eebdec89a8b8ae3bbc&vid=171147a063fa11eea7440fcfeb230d96&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20The%20Selfish%20Gene&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fthe-selfish-gene%2Fchapter-12&r=&lt=417&evt=pageLoad&sv=1&rn=162673)
