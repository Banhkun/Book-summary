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

## Part 3: High-Frequency Trading Tactics

Lewis argues that the above six characteristics of an electronic-based stock market allowed high-frequency traders to exploit individual investors. In Part 3, we’ll explore two of the main ways they do this: _arbitrage_ and _front-running_. Within that discussion, we’ll describe six specific strategies that give HF traders an unfair advantage, allowing them to profit off the market in ways that are unavailable to regular investors.

### Arbitrage

Lewis explains that most HF firms make their money from different forms of _arbitrage_ , which is when traders buy and sell a stock at two different prices at two different exchanges. Traders who can effectively time their purchases and sales profit from the temporary differences in stock prices.

Lewis notes that stock values are constantly changing—prices shift multiple times in a second. Every time a stock is bought or sold, its value changes slightly. Usually its value doesn’t change very much—by fractions of a cent—but this small difference in price is enough for HF traders to take advantage of arbitrage.

To illustrate the concept, imagine you buy an old typewriter at a local antique store for $35. You then go to a different antique store, where they offer you $40 for your typewriter. You accept and pocket the $5. This is similar to how HF traders make money from arbitrage, but HF traders complete this process in milliseconds. For example, at NYSE, an HF trader buys 100 shares of stock priced at $200 and sells these stocks at Nasdaq for $200.10, thus profiting off the difference in price.

> **Arbitrage and Market Efficiency**
> 
> Lewis argues that the way that HF traders use arbitrage is bad for investors, but other experts point out that arbitrage itself is not inherently bad. In fact, it’s encouraged in the US. Experts believe that arbitrage contributes to market efficiency since it rebalances price discrepancies in stocks and minimizes the spread in stock prices.
> 
> This price rebalancing is known as the Law of One Price, which is an economic concept that states that the price of a stock will be the same price in a market free of transaction costs, legal restrictions, and currency exchange rates. The only way to achieve the Law of One Price is through arbitrage. By buying a stock at a low price and selling it at a higher price, market prices equalize.
> 
> The problem seems to stem from when certain parties can take advantage of arbitrage because of technological superiority, while other parties can’t. This leads to the imbalances Lewis discusses.

#### Tactic 1: Slow-Market Arbitrage (Also Called Latency Arbitrage)

Lewis explains that the most widespread tactic HFT uses is _slow-market arbitrage_ , or _latency arbitrage_. This is when HF traders use different latency speeds to capitalize on changes in stock prices. HF traders see changes in stock prices on one exchange and buy or sell those orders on other exchanges that haven’t caught up to the changes in stock prices. Slow-market arbitrage is why trading firms care so much about their latency speeds and why it matters to be a microsecond faster than their competitors.

(Shortform note: While Lewis discusses slow-market arbitrage within the US. stock markets, it can also be used in foreign markets. Stock prices on foreign exchanges are sometimes slower to adjust to exchange rates. Traders will purchase these stocks on foreign exchanges for lower prices (before it’s had time to update) and sell them at a higher price in the US market. According to a 2020 study, slow-market arbitrage costs regular investors about $5 billion dollars each year.)

Additionally, Lewis explains that the SIP (the program that determines the best market price for a stock) has a high latency, so it’s slower to obtain and then transmit market data. HFT firms developed their own faster versions of the SIP—which gathers and condenses stock prices from all the exchanges—giving them a slight sneak peek of what the market will do. Then the HF traders use this advance information to capitalize on the price difference.

Because HF traders have access to faster infrastructure than investors, they can see changes in the markets before anyone else. They can then use that advance knowledge to game the market—buying a stock at one price on one exchange and then reselling it for a higher price on another exchange where the price hasn’t updated to the lower price yet.

It’s the same idea as if you went into a popular clothing store chain and bought a shirt on sale. You leave that store with your new shirt and go to the same store in a different location. The second location hasn’t marked down its sale items yet, so you return the shirt for full price, pocketing the difference.

> **SIP Timestamps Indicate a Lack of Latency Arbitrage**
> 
> While Lewis believes latency arbitrage is a problem for investors, other experts disagree. In 2015, the SEC changed the SIP data to show the time by the microsecond, as well as showing when exchanges transmit data to their feeds. By comparing these two timestamps, traders can identify the latency of trades.
> 
> According to a study analyzing nine months of trading data, traders who used the SIP data actually _earned_ three cents per 100 shares rather than losing money as Lewis claims. The study also found that around 97% of trades happen when data from both timestamps match, indicating that most trades don’t suffer from a lag in latency.

#### Tactic 2: Dark-Pool Arbitrage

Lewis names another HFT tactic: dark-pool arbitrage, which is similar to slow-market arbitrage. **Dark-pool arbitrage is when HF traders make money buying and selling stocks using the price differences between dark pools and other exchanges**. Dark-pool arbitrage generates more than a billion dollars a year.

As discussed in Part 2, banks aren’t required to immediately publish what goes on in their dark pool, or private stock exchange, thus allowing investors to trade more discreetly. But because they don’t immediately publish this information, there is a time lag between dark pools and public stock exchanges. Lewis explains that this time lag means dark pools are slow to reprice stocks when their values change on public stock exchanges, thus allowing HF traders to commit dark-pool arbitrage.

For example, say Jordan has an order to buy Tesla stock waiting in a dark pool. Then Tesla stocks decrease in value on the public markets from $300.00 to $299.99. A dark pool is slow to reprice Tesla’s stock from $300 to $299.99 on their exchange. An HF trader buys Tesla stocks on the public exchanges for $299.99 and sells them to Jordan at $300 before the dark pool reprices the stock to $299.99. Thus, Jordan loses money to the HF trader.

> **European Regulations Discourage Dark-Pool Arbitrage**
> 
> In response to concerns about dark-pool arbitrage and misuse, US regulators are still exploring the possibility of dark-pool regulation, but European regulators responded more quickly by introducing MiFID II in 2018, which encouraged more transparency and expanded on existing stock regulations from 2007. Under MiFID II, only 8% of a stock’s average trading volume within a year can be completed in dark pools. The regulation also set minimum limits for the size of trades to exclude HF traders, who generally buy and sell small-sized orders, and encourage investors to use dark pools as originally intended: to allow investors to make large trades without impacting market prices. Experts note that these regulations have made dark-pool arbitrage less of a concern in their markets, which could provide a framework for US regulators.

#### Tactic 3: Rebate Arbitrage

HF traders found ways to exploit different exchange rules, including the changes in the rebate system. As discussed earlier, different exchanges have different rebate rules—sometimes an exchange rewards takers with a rebate and charges makers a fee, while other exchanges do the opposite. To make money off of these new rebate rules, HF traders use rebate arbitrage, which is **when HF traders capitalize on differences in rebate rates at different exchanges.** HF traders profit from the rebates, not from the stock itself. This tactic doesn’t add or take away stock from the overall market supply—instead, the stock just moves from exchange to exchange.

In rebate arbitrage, HF traders buy a stock for which they receive a rebate. Then they immediately sell the stock for the same price on an exchange where they’ll also receive a rebate for selling that stock or on an exchange where the fee to trade is less than the rebate they’ve already received. Thus the money from buying and selling the stock cancels out, but the HF trader pockets the rebates. Lewis explains that the rebates are cents or fractions of a cent per stock, but HF traders buy and sell large quantities of stocks in a short amount of time, meaning these tiny rebates add up and result in large profits.

For example, BATS might offer a $0.03 rebate for each share bought, and NYSE might offer a $0.05 rebate for each share sold. An HF trader could buy a $50 stock from BATS and receive the $0.03 rebate. Then it could immediately sell that $50 stock at NYSE and receive the $0.05 rebate. The HF trader made $0.08 for moving the stock around, but it didn’t actually help the market. If the HF trader bought and sold 100,000 shares of this stock, they’d make $8,000 from the rebates.

> **Car Rebates as a Potential Framework for Stock Rebates**
> 
> While Lewis criticizes rebate arbitrage, other experts aren’t concerned by this tactic, saying HFT _should_ be rewarded for providing market liquidity, or the ease of buying or selling stock. This divide in opinion may explain why US regulators haven’t yet decided whether or not to keep rebates.
> 
> Other industries can provide guidance on how to address rebate arbitrage. For instance, car dealerships sometimes offer rebates to consumers, which are usually applied to the down payment of the vehicle. These rebates come from the car manufacturer, and the dealership is required by law to use the rebate—if they withhold any portion of the rebate, they risk legal action. This framework could possibly be used for stock trading in that the rebate can be applied to the stock price, offering a better deal upon purchase, rather than as a kind of additional payment. The car industry also indicates that legal regulation might not discourage market activity.

### Front-Running

Lewis also describes front-running, **when traders use advance knowledge of an impending trade to capitalize on that trade.** The main goal of front-running is to gather information—about stocks, the market, and investors—that other traders don’t know and then to use that information to make smarter trading decisions.

Traders who know a stock is about to be bought or sold can buy or sell that stock for themselves and can buy or sell that stock for a better price. For example, if you know that another trader is about to buy a large quantity of Apple stock, you’ll know that the value of Apple stock is about to increase in price. The demand has increased, meaning the price will probably increase as well. You use this knowledge to buy Apple stock before the other trader, while the stock is at a lower price. Then, when the price rises, you can sell it for a profit.

Lewis contends that HF traders use versions of front-running to gather information about regular investors and other traders. Then they use this information to make educated decisions about profitable stock orders. We’ll discuss three versions of HFT front-running: rebate baiting, electronic front-running, and information baiting.

> **Gray Areas of Front-Running**
> 
> While Lewis describes front-running as using insider knowledge to make unfairly advantageous trades, the issue isn’t as black and white as he makes it seem. There are types of front-running that aren’t illegal, such as index front-running.
> 
> Index front-running happens when companies are added or removed from an index fund, such as the S&P 500, which manages large collections of stocks. When this information is announced, traders can buy or sell stocks of that company that will be beneficial to them. It’s not illegal to do this since the information is available to anyone looking for it.
> 
> This is why some critics don’t agree that HF traders are front-running simply because they receive public information faster than other traders. However, reports revealed that HF traders bought direct access to market data, giving them advance knowledge over other traders, which could be considered a form of front-running.

#### Tactic 4: Rebate Baiting

Lewis discusses another tactic the new rebate rules allowed for was _rebate baiting_ , which is when an HF trader monitors an exchange where human brokers are more likely to send their orders first because they’ll get a rebate. The HF traders use this information to front-run the order to other exchanges that haven’t received it.

(Shortform note: Because rebates may create a conflict of interest for brokers when sending out customer orders, regulators are reevaluating rebate effectiveness. Under Europe’s MiFID II, most forms of rebates are banned to increase transparency about what investors pay for when working with brokers. This regulation could inspire US regulators to also eliminate rebates, as the absence of incentives may not negatively affect markets and could reduce the chance of rebate baiting.)

#### Tactic 5: Electronic Front-Running

Lewis notes that while the new trading regulation (Reg NMS) was intended to protect investors by offering the best stock prices, it allowed HF traders to use the rules against investors through electronic front-running, which is when an HF trader spots a broker trying to trade at one exchange and—using this information—races to another exchange to beat him to that particular stock. Then the HF trader buys or sells it to the broker—who isn’t as fast as the HF trader—for a profit.

Lewis notes that Reg NMS mandates that traders buy stocks at the best (lowest) market price. But the regulation doesn’t guarantee that the exchange with the lowest stock price will have the exact number of shares an investor wants. Thus, a broker might have to go to multiple exchanges to fulfill an investor’s entire order. When he does this, his order tips off HF traders of his intentions to buy or sell a certain stock. The HF traders can then race to other exchanges to buy the stock he wants, only to sell it to him at a higher price.

For example, an investor wants to buy 200 shares of Company X. At NYSE, there are 50 shares available at a price of $50.00. At BATS, there are 100 shares available at $50.02. At Nasdaq, there are 200 shares available at $50.01. Normally, a broker would buy the 200 shares (on behalf of the investor) from Nasdaq, since she is guaranteed to get the number of shares she wants at a decent price. But because of Reg NMS, the broker is required to purchase the 50 shares for $50.00 from NYSE, since this is the lowest market price. Seeing this purchase, an HF trader now knows that Company X’s shares are in demand. It uses this information to race to BATS and Nasdaq and buy those shares. Then when the broker’s order for the remaining 150 shares gets to Nasdaq or BATS, the HF trader sells the broker the shares at $50.03. Because of the HF trader’s electronic front-running, the broker pays more than if she’d bought the 200 shares from Nasdaq in the first place.

> **Could Replacing Reg NMS Solve Electronic Front-Running?**
> 
> Other experts agree with Lewis’s argument that traders have found ways to exploit well-intentioned regulation, such as Reg NMS, providing HFT with avenues to front-run investors. Some experts even recommend replacing Reg NMS with entirely new—albeit more relaxed—regulation. One suggestion is to outline several factors—not just price—that a broker must consider when executing customer trade orders, such as:
> 
>   * The price of the stock
> 
>   * How secure the market is at the time of purchase
> 
>   * The size of the transaction
> 
>   * The type of transaction
> 
>   * The number of markets researched
> 
>   * How easily the transaction can be fulfilled
> 
> 

> 
> Experts argue that by considering more factors of a trade, investors would get a more satisfactory deal, as their trade would be customized to them and their preferences instead of just price. However, as with Reg NMS, this well-intentioned regulation may lay the groundwork for other kinds of investor exploitation as traders find new ways to scheme the markets.

#### Tactic 6: Order-Type Baiting

Lewis explains that another front-running strategy is order-type baiting, or when an HFT examines different order types—and the parameters that accompany them—to figure out the intentions of an investor. So, for example, an HF trader’s order type might alert an HF trader that an investor withdraw an order if another broker doesn’t act on it. If a broker does act on the order, HFT uses this information to front-run their order to other exchanges, forcing the investor to pay a higher price.

Because of order-type baiting, HFT accounted for 99% of all orders made, but only half of all completed trades. Lewis believes that most of the orders HF traders made were used to get as much information about investors (and their intentions to buy or sell) as possible, thus hurting ordinary investors.

> **Order-Type Baiting as Game Theory**
> 
> Another way to think of HFT and order-type baiting is through the lens of game theory. In _The Undercover Economist_ , Tim Hartford explains that game theory is a discipline adjacent to economics and mathematics, where a “game” is defined as an activity in which predicting another’s actions affects your own actions. Many everyday situations, like driving, are games. When you’re behind the wheel, you drive based on the rules of the road but also based on what behavior other cars on the road are exhibiting. If a car is driving erratically, or too quickly, you’ll likely switch into a more defensive driving mode. If a car in front of you is driving too slowly, you’ll attempt to pass. By analyzing and predicting the actions of investors through order-type baiting, HF traders—algorithmic, rational decision-makers—use this data to maximize their payoffs.

[[book_md/flash-boys/part-2|part-2]]

[[book_md/flash-boys/exercise-reflect-on-high-frequency-trading-tactics|exercise-reflect-on-high-frequency-trading-tactics]]

![](https://bat.bing.com/action/0?ti=56018282&Ver=2&mid=f7aeb3d9-d9ff-4aeb-b1f2-5635023f937f&sid=49fff5b0636c11eeb9c611038afc8668&vid=4a005010636c11ee80c703d4c4a7acd5&vids=0&msclkid=N&pi=0&lg=en-US&sw=800&sh=600&sc=24&nwd=1&tl=Shortform%20%7C%20Book&p=https%3A%2F%2Fwww.shortform.com%2Fapp%2Fbook%2Fflash-boys%2Fpart-3&r=&lt=483&evt=pageLoad&sv=1&rn=985626)

__

  *   * Allow anyone to **view** this annotation
  * Allow anyone to **edit** this annotation



* * *

Save Cancel

__



