## ICO Features to consider



### **1 - Multi-round AKA Multi-series**

“[If we want to strike](http://vitalik.ca/general/2017/06/09/sales.html) at the heart of this problem, how would we solve it? I would say the answer is simple: start moving to mechanisms other than single round sales”.

“Under no circumstances should the money raised be released all at once to the development team.

The token holders vote at the end of that year to choose whether the next N tokens should be released or given back to the token holders \(burning the tokens if gross incompetence is occurring\).

One can prevent massive buying of the tokens right before the vote by requiring token holders to stake N months before the voting period to be eligible to vote. This prevents whales and exchanges being able to shut down projects single-handedly without risk.”

[https://medium.com/@matthewdif/towards-responsible-token-sales-icos-291e69cc9ccf](https://medium.com/@matthewdif/towards-responsible-token-sales-icos-291e69cc9ccf)

[https://medium.com/mysterium-network/mysterium-network-presale-early-access-5x-reward-b292d423f96](https://medium.com/mysterium-network/mysterium-network-presale-early-access-5x-reward-b292d423f96)

#### **Code Examples**

“[The MilestoneVault](https://medium.freecodecamp.org/what-we-can-do-to-reassure-ico-investors-that-we-wont-vanish-with-their-money-ae9cfa3e162b) is a smart contract implementation of a vault that stores the crowdsale’s contributions and releases the funds as project milestones get completed.”

While the above partially solves the problem of having the founders run away with the funds it adds quite some complexity regarding governance. There’s the chance token holders that lost faith in the project or with ulterior motives freeze each attempt at releasing funds for the team. There’s requirement of using dispute resolution mechanism \(like what[Kleros](https://medium.com/kleros/kleros-a-tool-against-abuse-in-token-distribution-924217746c16)is building\).

#### **Example of Multi-Series ICO**

“[Then we compared](https://hackernoon.com/icos-dont-bite-off-more-than-you-can-chew-d658aae9579e) their actual results to a simulated alternative, where each project would seek funding through 4 token sale stages from ‘presale’, ‘Series A’, ‘Series B’ to ‘Series C’. The token crowdsale events are set in 6-month intervals, even though realistically the crowdsales could be spread to anything from 3–18 months. To simplify this vast analysis, we set each token sale event to distribute 10% of the total supply to participants of each token sale series, effectively leaving 60% of tokens for future distributions, project development team incentives, bounties etc.”

#### **Example**

* 10% of the total token supply is distributed during each token sale round

* Token sale rounds should secure a ‘sane’ amount of funding needed to develop the startup further. Typical investment rounds from the USA were used and the following averages were achieved:

◊ presale → average 1M USD / project

◊ Series A → average 5M USD / project

◊ Series B → average 19M USD / project

◊ Series C → average 35M USD / project

◊ Future series token sale targets have not been defined

* For simulation purposes, the token sale rounds are set 6 months apart but could be anything from 3–18 months, depending on a startup’s burn rate

* Presales attract investors willing to take higher risks to obtain possibly higher returns

* A discount on the market price needs to be given at each token sale round

### **2 - Forecasting**

See [Wings](/wings.ai) as an example of this approach:

In addition to governance layer, the WINGS platform also provides a decentralized forecasting mechanism, enabling the token holders to estimate the probability of a certain event in the project life-cycle, such as:

* Amounts raised during the project crowd-sale period

* Certain milestone fulfillment \(for example, the probability of the project delivering a working prototype\)

* The price of the project’s tokens at a certain point in the future.

After the crowd sale has completed, the WINGS token owners are rewarded according to their forecasts. The project is switched into live projects area, with the chosen governance model becoming active. The project creator and the token owners are now able to submit new proposals regarding the project, and decide on them via the forecasting.

Forecasting does not affect the project ICO parameters.

### **3 - Prohibited token transfers during or after the ICO**

“[I do NOT endorse locking](https://medium.com/@VitalikButerin/when-i-see-voting-games-i-usually-analyze-i-51-attacks-and-ii-bribe-attacks-looking-here-da7412a4a217) tokens to prevent trading. This is likely to just result in wrapper contracts, especially since we’ve seen a wrapper reverse dutch auction for Status already”.

**What happened?**

When the Status ICO was held and token transfers were prohibited, [some guy](https://etherscan.io/address/0x5adce2c8e78ca9102af302eab5937f7cefb0a266#code) issued a smart contract that did an IOU to the public at a higher price. Buyers could claim the purchase first and could withdraw their tokens later when transfers became enabled by Status. This can be viewed as an “ICO inside an ICO”.

In the same way, any developer that has “vested” or “locked” tokens can issue IOUs with a lower/higher price. See an example of a so-called “Token Release Schedule” - [https://blog.aion.network/publicsaleupdate-fa92cff05aed](https://blog.aion.network/publicsaleupdate-fa92cff05aed)

### **4 - Volume Discount \(AKA “buy at least $50000 of coins and get 20% more”\)**![](https://lh4.googleusercontent.com/Fst2mDK-7AQEqRQuEs6sEmJ1AvnpikMXm206CgNv_NXN-yRC8rzAcvetbvvwGovTF-TuJPtODLBU1NwDNXSqDVtTff6aGIhhisbLSSdNJLvcbjYQ8QXxRZGvjd9Qm0qqfJkQ5Aye)

There is an option to collectively pool the resources and to get a “Volume Discount”. Please see the description here -[https://hackernoon.com/hacking-a-popular-ico-practice-that-only-rewards-the-richer-7d10b2019f1e](https://hackernoon.com/hacking-a-popular-ico-practice-that-only-rewards-the-richer-7d10b2019f1e)

“One concern about this approach is that it creates a KYC/AML mess. Only one address would go through KYC and the participants of the pool wouldn't. The person deploying the contract would probably have to go through KYC and somehow be responsible for the KYC of the accounts joining the pool.”

### **5 - Roadmap dependent on token sale proceeds**

See [Tezos](http://tezos.com) as an example of this: ** **![](https://lh6.googleusercontent.com/Ny_Bto2_wnbSJSfvH68CqQKrOe39HvvleZb6olyC2U0olV3dAW_qp50IyH0iIv_cqaFbyj6TFhgDPZrywDDMgbUVKqiLyT-2Elget-vIwr2sUThZMsOkdp2fam5ma8NW9XO8h1eK)

### 6** - Reverse ICO **

[**https://blog.bigchaindb.com/tokenize-bits-and-atoms-6f2ed6800ba6**](https://blog.bigchaindb.com/tokenize-bits-and-atoms-6f2ed6800ba6)

[**https://medium.com/@harrymclaverty/reverse-icos-the-soundcloud-exit-strategy-almost-no-one-is-talking-about-651f4ef1f88e**](https://medium.com/@harrymclaverty/reverse-icos-the-soundcloud-exit-strategy-almost-no-one-is-talking-about-651f4ef1f88e)

“Companies undergo ‘Reverse IPOs’ as a simpler and quicker way of ‘going public’. A private company finds a typically underperforming public company and buys enough shares to control it. They then strip away everything but the organisational structure of the public company rendering it a shell, before completing a ‘share swap’ where shareholders in the private company swap their shares for shares in the shell company — rendering the private company public \(Example:[Burger King](http://www.reuters.com/article/us-burgerking-stock-idUSBRE85J0PW20120620%29)\).”

