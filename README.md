# Bounties for ETHSanFrancisco
Hey Hackers, unsure of what to work on for ETHSanFrancsico? Consider taking a look at what you can build with Kyber! One thing that we'd like to promote is the spirit of collaboration, and leveraging our protocol for use in other projects. For example, [InstaDapp](https://ethindia.conteract.io/) was put together in ETHIndia, where they won $3k in DAI.

### 1. Collateral liqudation on-chain
Lending platforms such as ETHLend, Dharma and Bloqboard allow for ERC20 tokens to be put as collateral. In the event of a loan default, 
the lender keeps the collateral. Currently, he would have to actively liqudate it to the token of his choice. With Kyber, this liqudation can be done seamlessly.

### 2. Off-chain virtual orderbook relayer
One strong advantage of Kyber is that liquidity is already on-chain (tokens and prices are already on the smart contract). Anyone can query the Kyber contract for the expect buy and sell rate, such as 1 or 2 ETH equivalent amount of a token. Thus, one can then reconstruct an orderbook with orders extracted from Kyber’s liquidity pool. Let's denote orders extracted from Kyber as on-chain orders.

It would be cool to build a relay can combine both 0x's and Kyber's model: there are always on-chain orders relayed from Kyber and users can also create new off-chain orders should they wish to sell/buy at a different price. What's really interesting is how the settlement occurs between a new on-chain order with an existing off-chain order, since it may require interactions between both Kyber and 0x smart contracts.

### 3. Integration into MakerDAO's CDP
The creation and closing of a CDP can only be done with ETH and DAI respectively. Futhermore, the process is rather tedious and complicated, where one has to understand the mechanism well. Consider simplifying the process to make it user-friendly and easy to create a CDP to obtain DAI, and closing one with ERC20 tokens.

### 4. Arbitrage Bots
Need Spyros' input to proceed.

### Open Category
These are just some of the ideas we propose, but you may have better ones! Dig into our tech, utilize it in a cool way and show us!

---
## Prizes
We will choose 1 winner for each category to receive $2000 USD in KNC tokens!
The open category has separate conditions which can be seen [here](), with a bigger prize pool of $3000 USD worth of KNC tokens!

## Criteria (Placeholder)
1. Quality of execution - ideas are nice, but the more important thing is to have a working PoC for your project. We recommend to stay realistic and lean with the execution.
2. DAO Architecture - We will pay attention to the way you structure your DAO/ Dapp. We recommend following the architecture detailed here. Using reputation based voting is mostly better than a token based voting. We encourage the use of the Holographic Consensus protocol to enhance the decision-making capacity of an organization (where fits).

## Team
We will have a booth set up during the event, so just drop by to meet us! 
@Loiluu, @Anyhowclick, @ayobuenavista, @bby7777 and @denizined will be around during the event to assist with any questions you may have!
Additionally, you may join our [developer group on Telegram!](https://t.me/kyberdeveloper)

## Getting Started
Our [developer portal](https://developer.kyber.network/) is the place to go!
In particular, do check out our [DApp Integration Guide!](https://developer.kyber.network/docs/DappsGuide/)
