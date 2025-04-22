![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

Discover

Books

Articles

My library

Search

Discover

![Shortform App](/img/logo.36a2399e.svg)![Shortform App](/img/logo-dark.70c1b072.svg)

# Flash Boys

Back to Discover

[[book_md/flash-boys/preview|preview]]

  * [[book_md/flash-boys|flash-boys]]
  * Full Book Guide

    * [[book_md/flash-boys/shortform-introduction|shortform-introduction]]
    * [[book_md/flash-boys/part-1|part-1]]
    * [[book_md/flash-boys/part-2|part-2]]
    * [[book_md/flash-boys/part-3|part-3]]
    * [[book_md/flash-boys/exercise-reflect-on-high-frequency-trading-tactics|exercise-reflect-on-high-frequency-trading-tactics]]
    * [[book_md/flash-boys/part-4|part-4]]
    * [[book_md/flash-boys/part-5|part-5]]
    * [[book_md/flash-boys/exercise-reflect-on-high-frequency-trading-solutions|exercise-reflect-on-high-frequency-trading-solutions]]
  * [[book_md/flash-boys/highlights|highlights]]
  * [[book_md/flash-boys/community|community]]



Adding to Favorites 

Removing from Favorites 

## Part 5: Katsuyama’s Solutions to High-Frequency Trading

After discovering these HFT tactics and Wall Street’s greedy response to it, Katsuyama and his team decided to fight HFT rather than mimic its tactics to make money. In this section, we’ll discuss his team’s first attempt at fighting HFT: a trading program called Thor. Then we’ll explore their second attempt: a new stock exchange. We’ll also discuss the six features the team implemented to make trading fair against HF traders’ six tactics.

### Thor

As their first step to addressing HFT techniques, Katsuyama’s team developed a trading software called Thor. Lewis explains that Thor slowed down a broker’s order so that it arrived at all exchanges simultaneously. While it may seem counterintuitive to go slower, this tactic actually helped Katsuyama’s team successfully fill their orders and saved them money. Slowing the orders down prevented an HF trader from front-running it to another exchange and changing the price of the stock.

For example, without Thor, a broker’s order arrived at BATS in three milliseconds and NYSE in six milliseconds. In the three milliseconds before his order got to NYSE, an HF trader saw his order at BATS, thus revealing that there was a known buyer for a certain stock. The HF trader raced to NYSE, bought that stock, and sold the stock to the broker at a higher price.

But Thor slowed down the speed of the broker’s BATS time, meaning his orders arrived at both BATS and NYSE in six milliseconds. The HF trader then wouldn’t have a time advantage, removing the opportunity to front-run the trader’s order.

> **The Tactical Approach of Removing Momentum (Speed)**
> 
> As a first attempt to fight HFT, Thor took a counterintuitive approach by _slowing down_ their latency rather than increasing their speed to match or beat HFT. This tactic inverts a strategy that Sun Tzo outlines in _The Art of War_ , which states that momentum is the life force of any conflict. When momentum is on your side, you have the advantage. You can create this advantage by manipulating your enemy into action.
> 
> But by recognizing that they could never match or beat HFT’s momentum (speed), Katsuyama’s team _avoided conflict_ (in this case, HFT’s ability to front-run) by reducing their own momentum (slowing down some of their stock orders), thus manipulating their enemy (HFT) into _inaction_ (not frontrunning their orders) rather than action.

### IEX: A Fair Stock Exchange

Next, Katsuyama and his team quit their jobs at RBC to create their own stock exchange. They called it the Investors Exchange, or IEX. The purpose of IEX was to make investing fair by preventing the predatory behavior of HF traders.

**Lewis believes that they succeeded—IEX ranked number one on a list evaluating exchanges on how well they adhere to trading regulations.** IEX also had larger trade orders than other exchanges, as well as more random trades. So if a stock changed price in another market, IEX was less likely to execute trades because of it.

When creating IEX, Katsuyama and his team knew they couldn’t ban HFT on their exchange. But they could take preventative measures against the tactics HF traders used to exploit investors. Lewis discusses the team’s five solutions addressing each of the HFT tactics.

> **IEX vs. Regulation**
> 
> While Lewis praises IEX for fighting HFT, some critics note that in doing so, he perpetuates the idea that stock exchanges will correct themselves without regulation. Critics believe that regulating bodies like the SEC—not exchanges or traders—should be responsible for keeping up with changes in stock trading—especially for something as influential as HFT—and taking actions to protect investors. Experts have suggested a small tax on every trade, called the Tobin Tax, that would have little effect on regular investors but deter HF traders by reducing the margins they make on their frequent trades.
> 
> However, Lewis and critics seem to agree on the fact that while the SEC _should_ regulate HFT more, they’re _not_ —and if they are, they’re acting too slowly. In 2021—seven years after the book’s publication—the SEC began considering new mandates for HFT firms that would require them to report all of their trades and to be subject to periodic exams. Lewis praises the IEX team for their actions _in spite of_ the SEC’s failure to do so.

#### Solution 1: Counteract Speed Advantages

As discussed earlier, HF traders have speed advantages that result in slow-market arbitrage (when HF traders watch for stock price changes and then buy a stock at one exchange at a lower price, then sell it at another exchange before the second exchange has updated its prices).

To address this problem, IEX increased the amount of time it would take for any investor—including HF traders—to access the exchange’s market, which erased any speed advantages for HF traders. To do this, they moved their "point of presence,” or a point where traders connect to an exchange, 10 miles away from their matching engine in New Jersey and coiled the cable between the two locations to lengthen the time it took to get a signal from one to the other.

In doing so, IEX created a 350-microsecond delay that slowed down HF traders accessing their exchange and therefore allowed IEX to interact with other exchanges at the same time as HF traders, instead of behind them.

> **Is IEX Being Unfair to HF Traders?**
> 
> While Lewis claims IEX’s tactics (the point of presence and 350-microsecond delay) make trading fairer for regular investors, some experts object to IEX slowing down traders’ orders. They believe that IEX is effectively using latency arbitrage against HF traders since the exchange is using old prices on other exchanges before traders on those exchanges can update their own prices, thus making trading with IEX unfair for HF traders. They believe these tactics only benefit big investors and portfolio managers.
> 
> However, this argument seems to acknowledge that using “old” prices to perform latency arbitrage is unfair—it’s just a question of whether humans or technology are on the receiving end of it.

#### Solution 2: Investors Can Request Banks Send Orders To IEX

Because IEX couldn’t control what happened in banks’ dark pools, they couldn’t directly address dark pool arbitrage. But Lewis notes that the team found a way to indirectly address the issue: They encouraged investors to request that their orders be sent to IEX.

As we discussed earlier, the banks weren’t sending customers’ orders on to other exchanges where the order could be fulfilled, thus allowing an HF trader—who had paid the bank for access to the dark pool—to commit dark pool arbitrage (profiting off small differences in price between dark pools and other exchanges).

Lewis explains that IEX wanted to prevent the banks from allowing customers’ orders to sit unfulfilled in the dark pool. IEX thus encouraged investors to request that their orders be sent to IEX.

(Shortform note: While Lewis claims HFT exploits investors, some experts believe that HFT only really affects wealthy investors, such as the ones managing hedge funds, who charge their retail investors more than what they lost to HFT. Critics accused Lewis of creating victims to make his story more interesting.)

However, many banks initially resisted these requests, as they didn't want to send IEX the business nor did they want to decrease trading volumes in their own dark pools, as high volumes improved their statistics.

To solve this problem, Katsuyama met with a group of influential investors and explained to them exactly how banks had been exploiting them so that they would put pressure on their banks to send orders to IEX. He also met with Goldman Sachs executives and showed them that they would never be able to compete with HFT firms and their advanced algorithms. As a result, Goldman Sachs managers began directing their orders to IEX.

Because of his efforts to educate investors and banks about the advantages of using his (fairer) exchange, IEX soon gained a reputation as an exchange that could solve the problems that HFT had created and make trading more equitable again.

(Shortform note: While encouraging investors to ask their bank to send their orders to IEX was a solution, it didn’t completely fix IEX’s problem since it put the responsibility on the investor to make sure their bank cooperated and sent an investor’s order to IEX. To address this problem, in 2016, the SEC approved IEX’s application to become an official exchange, thus requiring brokers to send their orders to IEX when it offers stocks at the best price. In doing so, it’s not up to the investor to make sure their order goes to IEX.)

#### Solution 3: Eliminate Rebates

As their next solution, IEX eliminated rebates. Instead, IEX _charged the people involved in both sides of the trade_ $0.009 per share. This approach differed from the previous model, which charged one side of the trade and paid the other a rebate.

Lewis explains that without rebates, HF traders couldn’t commit rebate arbitrage or rebate baiting by moving stocks between exchanges to profit off of rebates. In addition, regular brokers didn’t have the incentive of a rebate to send orders to IEX first, which allowed HF traders to front-run her order. By charging both the maker and the taker a fee, traders didn’t have an ulterior motive—the appeal of a rebate—to trade at IEX.

Lewis believes that as a result, traders and investors who truly wanted to buy or sell stocks—and not just receive rebates—were encouraged to trade at IEX. If someone truly wanted to buy or sell a certain stock, they’d be more likely to pay the small fee to do so.

> **Reevaluating Rebate Effectiveness**
> 
> Following IEX’s decision to remove rebates from its trading process, the SEC reexamined whether or not rebates are an effective quality of the exchange. Although the SEC still allows rebates, it has admitted that rebates may create conflicts of interest when brokers choose where to send their orders. The SEC has considered testing how markets would function without rebates. NYSE and Nasdaq sued to stop this experiment before it went into effect.
> 
> However, the SEC identified advantages to the current rebate model, stating that rebates might make it easier for brokers to identify fair stock prices, while also encouraging trading on exchanges. It also noted that taking away rebates could make stock prices worse for investors. While IEX hasn’t faced any of these issues, their analysis may hold true if all exchanges eliminated rebates.

#### Solution 4: Three Order Types

To reduce information baiting, Katsuyama and his team limited the number of order types to three, as opposed to the 150 offered by other exchanges at the time. Lewis argues that fewer order types made trading more straightforward, encouraging investors who actually wanted to buy and sell stocks, instead of just use order types to glean information, to trade with IEX. By limiting the number of order types, IEX prevented HF traders from baiting information out of investors: HF traders had fewer ways of determining what stocks an investor wanted or how much an investor was willing to pay.

(Shortform note: While Lewis notes that IEX has three order types, the exchange has increased the number since the publication of the book. IEX now has three classes of order types—ones for standard and retail investing, as well as what IEX calls their Signal Series order types, which are supposed to offer “enhanced price protection.”)

#### Solution 5: Publish Trading Rules

To counteract the secrecy of dark pools, IEX decided to publish their trading rules that they use for their matching engine. Lewis explains that they also showed what order types they allowed on IEX, as well as whether or not any other investors were given special access to their exchange. They hoped being transparent would build investor trust and encourage other exchanges to do the same.

(Shortform note: Lewis believes IEX fostered trust with investors through being honest and transparent about what was happening in their trades, which is a strategy other experts recommend. In _Algorithms to Live By_ , Brian Christian and Tom Griffiths note that one simple way to improve the equilibrium of a competitive game, such as stock trading, is to change the rules to make honesty and transparency the optimal strategy. The authors argue that when you design a game in which players are incentivized not to hide their intentions, it eases the burden on everyone. Players no longer have to stress about predicting what others are going to do, or what others think they’re going to do.)

[[book_md/flash-boys/part-4|part-4]]

[[book_md/flash-boys/exercise-reflect-on-high-frequency-trading-solutions|exercise-reflect-on-high-frequency-trading-solutions]]

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=208bbbb1-aa23-4464-a99c-147279fb58cd&sid=49fff5b0636c11eeb9c611038afc8668&vid=4a005010636c11ee80c703d4c4a7acd5&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fflash-boys%2Fpart-5&r=&lt=475&evt=pageLoad&sv=1&rn=647142)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



