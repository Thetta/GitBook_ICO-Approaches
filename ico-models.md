## **ICO Models**

Some/many properties of these approaches can be combined together.

### **1 - Reverse Dutch Auction model \(Gnosis, RaidenNetwork, OraclesNetwork, etc\)**

[**https://medium.com/@nickikwhite\_5051/token-sale-models-part-ii-price-schedules-b36716a1a9de**](https://medium.com/@nickikwhite_5051/token-sale-models-part-ii-price-schedules-b36716a1a9de)

[**http://vitalik.ca/general/2017/06/09/sales.html**](http://vitalik.ca/general/2017/06/09/sales.html)

**Properties:**

1. Capped \(either in token amount or in raised ETH\)

2. Unlimited in time

“In this scheme, investors are incentivized to buy later on in the sale, as the price of the token falls, so that they can get a better deal. Ideally, this means that investors can enter into the sale at a point in which they think the valuation is fair.

A Dutch auction starts with a very high price and cap which continuously declines with every block over time, based on a predefined formula. During the auction, participants can send in ETH to bid at a point in time where they find the price reasonable. The auction ends once the price multiplied with the number of offered tokens equals the total ETH amount sent to the auction.

All participants receive their tokens at thesame final price.”

There are two possible outcomes for the Investor:

1. The sale closes before the valuation drops to below V. Then you are happy because you stayed out of what you thought is a bad deal.

2. The sale closes after the valuation drops to below V. Then you sent your transaction, and you are happy because you got into what you thought is a good deal.

#### **Example - Gnosis**

![](https://lh5.googleusercontent.com/rWIEIr5VBV-Hh__2QplM0BP9n7hBbXGinDYdltqJ2TNoIu_XzxlEvn1KqRO60D_ZwBEz7-Ra6jPFErJhh-dLPsAduz7u4XtuDg-JWdLgGM4JFdJsfhVIOGvamUja1cH_SA)

#### **Example - Raiden Network**

[**https://medium.com/@raiden\_network/the-raiden-token-auction-explained-1cc0c7946b26**](https://medium.com/@raiden_network/the-raiden-token-auction-explained-1cc0c7946b26)**    
**![](https://lh5.googleusercontent.com/Wf_ZvwO_l8qQ69dGIvxzbvUm_PY0QM3AHf29jQV4zoWl2cs8_95bL0ImtPyBdtHjfZSRBKiFxKTcGoYzQ9QKU7qrN5_1jGjpqwng6Ch_XQUm8AxfrO5TVpXzpBv9nZQwuQ)  
**Example - Oracles Network**![](https://lh3.googleusercontent.com/rLzw4S6hFlduK5re3h1rQwGsN5cvVfkdh0OaSTH_hsiaOQPlklqajqeqwZAspdU7pT2y6gmsiLY2Wc9NnxtVaWAZm_i6W8b9pzf6AGIayt1J1w8ElRdSr7_-3Yw3aKI9aA)

### **2 - Interactive Coin Offering model \(Truebit\)**

[**https://people.cs.uchicago.edu/~teutsch/papers/ico.pdf**](https://people.cs.uchicago.edu/~teutsch/papers/ico.pdf)

[**https://medium.com/truebit/interactive-coin-offering-a-protocol-explained-267065ef3819**](https://medium.com/truebit/interactive-coin-offering-a-protocol-explained-267065ef3819)

[**https://medium.com/modular-network/building-the-interactive-token-sale-1545514bf108**](https://medium.com/modular-network/building-the-interactive-token-sale-1545514bf108)

“It’s an ICO purchase protocol, in which each individual contributor will choose an amount of tokens they’d like to purchase and a “Personal Cap”.

Personal Cap is the specified LIMIT of the total amount of ETH raised in the sale for a participant. If the total amount of ETH raised in the sale is more than the personal cap, the contributor will be removed from the sale or poked out”.

### **3 - Variable Token Vesting model \(Filecoin\)**

[**https://coinlist.co/assets/index/filecoin\_index/Filecoin-Sale-Economics-e3f703f8cd5f644aecd7ae3860ce932064ce014dd60de115d67ff1e9047ffa8e.pdf**](https://coinlist.co/assets/index/filecoin_index/Filecoin-Sale-Economics-e3f703f8cd5f644aecd7ae3860ce932064ce014dd60de115d67ff1e9047ffa8e.pdf)

[**https://blog.aion.network/publicsaleupdate-fa92cff05aed**](https://blog.aion.network/publicsaleupdate-fa92cff05aed)

“Investors in the Filecoin ICO were presented with several options of discounts and lock-up times. They could choose a 6 month lock-up for 0% discount, 1 year lock-up for 7.5% discount, 2 year lock-up for 15% discount and a 3 year lock-up for 20% discount. Although I’ve been using the term “lock-up,” in the case of Filecoin’s ICO, the correct nomenclature would be “vesting.” In order to avoid a flood of new tokens in the market that would arrive all at once when the lock-up period ends, Filecoin chose to vest its tokens to investors at a constant rate over time, issuing a fraction of them every time a new block was added to the blockchain. This ensures a slow trickle of tokens coming online which should help keep the token price, and the overall network, stable.”![](https://lh5.googleusercontent.com/zEcV5YsuBETUYHH8lPB_yOJBnyazu-pZxK3tvhhJPPoroXdfHXHtzEcEmFYELbwmar3COLNFuDSn-ZnWFYOyrhbrpriIJj7zmHMAhQEDJ09uQsflaotoBtYRYJOx12kqDg)

### **4 - Simple “old school” capped ICO with Discounted Refunds model \(Angel-tokens\)**

[**https://github.com/ChainCloud/angel-contracts**](https://github.com/ChainCloud/angel-contracts)

[**https://bitcointalk.org/index.php?topic=2385917.0;all**](https://bitcointalk.org/index.php?topic=2385917.0;all)  
**  
**“You can invest in the Angel Token ICO knowing that there is an immutable Ethereum Smart Contract protecting the bulk of your Ethereum investment.

During the first 5 months you can be involved in the community and talk to the Founders, and see the initial investments and trades being made with the Ethereum raised, as well as benefit from any potential price increases of Angel Token as it gets listed on the exchanges.

If, for any reason during the first 5 months, you wish to no longer be involved, then as an ICO investor you can return your tokens. You will receive back up to 80% of the invested Ether amount, \(80% during the first 100 days and 40% during the next 50 days\).“

### **5 - Proportional Token Allocation aka Proportional Refund model \(still in development\)**

[**https://github.com/ethereum/EIPs/issues/642**](https://github.com/ethereum/EIPs/issues/642)

[**https://medium.com/@nickikwhite\_5051/token-sale-models-part-iii-proportional-refund-1243cbd43286**](https://medium.com/@nickikwhite_5051/token-sale-models-part-iii-proportional-refund-1243cbd43286)

“In a proportional refund, the total number of tokens being sold is given up front as well as the total amount of money being raised. This sets a “cap” in a sense, but the difference is that the total amount of money that can be pledged to the ICO is allowed to exceed this cap. The token sale goes on taking in as much money as investors are willing to commit, very much like an uncapped sale, until the sale ends. At the end of the sale, the sold tokens are distributed according to the proportion of money invested by each participant and all excess contributions are refunded. So as an example, if 2 investors placed 300 ETH and 100 ETH in my token sale that was capped at 100 ETH, 75% of the tokens for sale would go to the first investor and 25% would go to the second. Then, 225 ETH would be refunded to the first investor and 75 ETH would be refunded to the second investor.

The nice part of this design is that you get the benefits of both a capped and uncapped sale. As in an uncapped sale, anyone can contribute to the sale and get a piece of the pie. And like in a capped sale, investors know the price at which they are buying the tokens, even if they may not know how many tokens they will end up getting. This sounds good on the surface, but it still doesn’t resolve the issue of being excluded from the sale by big players. Certainly you will always be able to contribute to the sale and get at least a small fraction of the tokens sold, but if a few whales put up 95% of the total ETH in the sale, then only 5% will go to the smaller players. And there’s nothing stopping a whale from majorly over allocating to the sale just to push other players out.”

### **6 - Continuous Token aka Safe Token aka NoICO model \(Bitcoin, etc\)**

[**https://medium.com/@simondlr/continuous-token-curated-registries-the-infinity-of-lists-69024c9eb70d**](https://medium.com/@simondlr/continuous-token-curated-registries-the-infinity-of-lists-69024c9eb70d)

“With continuous token models, tokens are minted as needed, and used within the protocol or application when required. There is no “ICO”, “Token Generation Event” or “Token Launch”. The network/dapp forms around the need of the token and dissolves naturally if it is not useful anymore.”

[**https://media.consensys.net/exploring-continuous-token-models-towards-a-million-networks-of-value-fff153175776**](https://media.consensys.net/exploring-continuous-token-models-towards-a-million-networks-of-value-fff153175776)

“The idea is that instead of pre-selling tokens during a launch phase, the tokens are minted as needed through various means. The tokens are then dispensed for services rendered in the network.”

### **7 - Inflation Funding model \(still in development\)**

[**https://medium.com/@petkanics/inflation-and-participation-in-stake-based-token-protocols-1593688612bf  
**](https://medium.com/@petkanics/inflation-and-participation-in-stake-based-token-protocols-1593688612bf)[**https://forum.livepeer.org/t/an-overview-of-bonding/97**](https://forum.livepeer.org/t/an-overview-of-bonding/97)

This is a variation of the “Continuous Token” model mentioned above.

“An algorithmically adjusting token issuance model for stake based protocols, where high quality participation is vital to the quality and security of the network. The case for such a model in this type of network is as follows:

1. Participants contribute value to the network.

2. Greater participation rate yields greater security.

3. Incentives must exist for participation.

4. Targeting a participation rate, rather than a token issuance rate, aligns better with ensuring a high quality network.

5. Participation targets may be easier to move via decentralized governance than token issuance rates.

The result of working through these assumptions is that a protocol can set a participation target, say 50% of all tokens staked and participating, and that inflation rate can adjust automatically to incentivize this target. If less than the target % of token are bonded, then the inflation rate can creep up and the protocol will issue more tokens each round. If the participation rate is above the target, the inflation rate can reduce itself and fewer tokens will be issued each round”.

[**https://medium.com/@FEhrsam/funding-the-evolution-of-blockchains-87d160988481**](https://medium.com/@FEhrsam/funding-the-evolution-of-blockchains-87d160988481)

“Inflation funding is where things get interesting. It allows economic rewards that are otherwise unthinkable. Remember, if Ether holders believed an upgrade \(ex: sharding\) would make the price go up by &gt;10%, they’d be happy to pay close to 10% of their tokens for it. That means Ethereum could crowdfund a $3bn feature bounty by inflating the number of ETH by 10% and pay the newly created tokens to the creator\(s\) of the upgrade. This is somewhat analogous to taxes:everyone in the community chips in to fund common infrastructure \(ex: roads\) which no one would build alone.

A protocol which provides strong incentives for people to improve it is likely to evolve faster than one that does not. So blockchains which fund innovation through token inflation would seem to have a superior evolutionary algorithm. And over the long run, rate of change is often more important than starting point”.

### **8 - Curated Lists model \(1Hive, etc\)**

[**https://medium.com/@simondlr/tokens-2-0-curved-token-bonding-in-curation-markets-1764a2e0bee5**](https://medium.com/@simondlr/tokens-2-0-curved-token-bonding-in-curation-markets-1764a2e0bee5)

[**https://medium.com/@simondlr/introducing-curation-markets-trade-popularity-of-memes-information-with-code-70bf6fed9881**](https://medium.com/@simondlr/introducing-curation-markets-trade-popularity-of-memes-information-with-code-70bf6fed9881)

[**https://medium.com/@lkngtn/district0x-feedback-2-building-a-strong-network-effect-d629da10d5f6**](https://medium.com/@lkngtn/district0x-feedback-2-building-a-strong-network-effect-d629da10d5f6)

Great overview of Curation Markets is available here:

[**https://docs.google.com/document/d/1VNkBjjGhcZUV9CyC0ccWYbqeOoVKT2maqX0rK3yXB20/edit?usp=sharing**](https://docs.google.com/document/d/1VNkBjjGhcZUV9CyC0ccWYbqeOoVKT2maqX0rK3yXB20/edit?usp=sharing)

\(optional\) There is no requirement for a token launch. The token can be minted at any time just like in the "Continuous Token model" above.

“Curation Markets allows open source projects to earn from the work they collectively create. Curation is important in order to make decisions together. Any open source project can have an associated curation market attached it, helping it to make sure what pull requests should be merged and what features to consider.

A curation market is a smart contract on Ethereum that is deployed for a specific shared goal or topic that allows the minting of tokens set by a hard-coded algorithm. The cost \(in ETH\) to mint a token increases as the supply increases \(as more tokens are minted\). The cost decreases as the supply decreases \(tokens are withdrawn \(“burned”\) from supply\).

**Example:**

* **@1 000 supply, a token will cost: 0.01500809654 USD**
* **@5 000 000 supply, a token will cost: 41.31333111 USD**
* **@10 000 000 supply, a token will cost: 53242.33775 USD** 

The minted tokens are bonded to specific curators chosen by the token holders per sub-topic. Using their proportional standing in the curation community \(per topic\), these curators then back certain information \(equivalent to an “upvote”\). They can also revoke their backing.

Depending on the design: the ETH that is used to mint the tokens are either kept in a communal deposit, or split towards a trusted beneficiary. These design considerations are dependent on what the shared goal is.

A user can opt to voluntarily leave without selling on the secondary market. When leaving, a user can take a portion of the communal pool with them as reward. This reduces the supply and the subsequent cost to enter is also thus decreased”.

### **9 - DAICO aka Tapped ICO model \(by Vitalik Buterin\)**

[**https://ethresear.ch/t/explanation-of-daicos/465**](https://ethresear.ch/t/explanation-of-daicos/465)

“After the contribution period, the contract has one major state variable: tap \(units: wei / sec\), initialized to zero. The tap determines the amount per second that the development team can take out of the contract.

There is also a mechanism by which the token holders can vote on resolutions. There are two types of resolutions:

* Raising the tap

* Permanently self-destructing the contract \(or, more precisely, putting the contract into withdraw mode where all remaining ETH can be proportionately withdrawn by the token holders\)

Either resolution can pass by some kind of majority vote with a quorum \(eg. yes - no - absent / 6 &gt; 0\). Note that lowering the tap by vote is not possible; the owner can voluntarily lower the tap, but they cannot unilaterally raise it.

The intention is that the voters start off by giving the development team a reasonable and not-too-high monthly budget, and raise it over time as the team demonstrates its ability to competently execute with its existing budget. If the voters are very unhappy with the development team’s progress, they can always vote to shut the DAICO down entirely and get their money back”.

### **10 - Initial Bounty Offering \(U.cash\)**

[**https://cointelegraph.com/explained/how-initial-bounty-offering-can-help-the-unbanked-explained**](https://cointelegraph.com/explained/how-initial-bounty-offering-can-help-the-unbanked-explained)

“An Initial Bounty Offering differs from the well-known Initial Coin Offering in that users can acquire tokens by completing bounties.”



  
  


  
  


**    
**

