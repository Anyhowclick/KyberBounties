# Bounties for ETHSanFrancisco
After witnessing the cool projects built at ETHBerlin, we cannot wait to see what ETHSanFrancisco can offer! There is a strong spirit of collaboration at these events, and we hope to further promote this ideal through the bounties we are offering. To get an idea of the kind of collaboration going on, take a look at [InstaDapp](https://ethindia.conteract.io/), a project put together in ETHIndia, where they won MakerDAO's first prize bounty of $3k in DAI.

Our proposed bounties have a core idea of leveraging our protocol for use in other projects.

### 1. Collateral liqudation on-chain
Lending platforms such as ETHLend, Dharma and Bloqboard allow for ERC20 tokens to be put as collateral. In the event of a loan default, 
the lender keeps the collateral. Currently, he would have to actively liqudate it to the token of his choice. With Kyber, this liqudation can be done seamlessly.

### 2. Off-chain virtual orderbook relayer
One strong advantage of Kyber is that liquidity is already on-chain (tokens and prices are already on the smart contract). Anyone can query the Kyber contract for the expect buy and sell rate, such as 1 or 2 ETH equivalent amount of a token. One can then reconstruct an orderbook with orders extracted from Kyber’s liquidity pool. For greater accuracy, consider querying rates from individual reserve contracts instead of Kyber's contract. In any case, let us denote orders extracted from Kyber as on-chain orders.

It would be cool to build a relay can combine both 0x's and Kyber's model: there are always on-chain orders relayed from Kyber and users can also create new off-chain orders should they wish to sell/buy at a different price. What's really interesting is how the settlement occurs between a new on-chain order with an existing off-chain order, since it may require interactions between both Kyber and 0x smart contracts.

### 3. Integration with MakerDAO's Collateralized Debt Position (CDP)
The creation and closing of a CDP can only be done with ETH and DAI respectively. Futhermore, the process is rather tedious and complicated, where one has to understand the mechanism well. Consider simplifying the process to make it user-friendly and easy to create a CDP to obtain DAI.

1. Allow a creation of a CDP with ERC20 tokens. Use Kyber's protocol to exchange the ERC20 token for ETH, and then ETH to PETH from Maker.
2. For the closing of a CDP with ERC20 tokens, exchange the tokens to DAI.

### 4. Ensuring on-chain price equilibrium
Prices on and off chain are not always the same across different price discovery venues. Make a dapp that takes advantage of market ineficiencies between Kyber and another venue and (instead of a regular crypto investor) buy low and sell high! Take the bounty, keep the profit! 

Ethereum allows for a contract to execute a trade only if some conditions exist. So if there is a common ERC20 token between Kyber and another on-chain price discovery venue, and it happens that the buy price on the other is smaller than the sell price on Kyber or vice versa, the contract can execute the trade for an instant and risk-free profit. While such DApps are already existing (take a look at past trades on Kyber!), BUIDL something like this earns you a bounty, instant and measurable and consistent profit from the trade proceedings and whilst ensuring price equilibrium across the market. Triple Win!

### Open Category
These are just some of the ideas we propose, but you may have better ones! Dig into our tech, utilize it in a cool way and show us!

---
## Prizes
We will choose 1 winner for each category to receive $2000 USD in KNC tokens!<br>
The open category has a bigger prize pool of $3000 USD worth of KNC tokens!

## Criteria
### Normal Category
#### 1. User Experience (X%)
Intuitive, easy to use, understand and interact with. 

#### 2. Technical Difficulty (Y%)
Going above and beyond what we specified. Good code quality, bug free, documentation.

#### 3. Usability (95-X-Y%)
Other projects are able to build on top of your application, or incorporate it into their own.

#### 4. X Factor (5%)

### Open Category
#### 1. Idea (X%)
The importance of Kyber's protocol in the application, & originality of the idea.

#### 2. User Experience (Y%)
Intuitive, easy to use, understand and interact with. 

#### 3. Technical Difficulty (Z%)
Going above and beyond what we specified. Good code quality, bug free, documentation.

#### 4. Usability (95-X-Y-Z%)
Other projects are able to build on top of your application, or incorporate it into their own.

#### 5. X Factor (5%)


## Team
We will have a booth set up during the event, so just drop by to meet us! 
@Loiluu, @Anyhowclick, @ayobuenavista, @bby7777 and @denizined will be around during the event to assist with any questions you may have!
Additionally, you may join our [developer group on Telegram!](https://t.me/kyberdeveloper)

## Getting Started
Our [developer portal](https://developer.kyber.network/) is the place to go!
In particular, do check out our [DApp Integration Guide!](https://developer.kyber.network/docs/DappsGuide/)
