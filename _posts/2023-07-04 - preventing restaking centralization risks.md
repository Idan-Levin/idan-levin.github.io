---
layout: post
category: blog_posts
---


### preventing centralization risks from restaking 

In the latest <a href='https://www.youtube.com/watch?v=aP9f_1v9Ulc'>Bankless</a> episode about restaking, Justin Drake highlighted a key risk that restaking protocols pose to Ethereum's decentralization.

I want to explain this risk and offer an economic solution that I believe can solve it, and by this to prevent centralization risks from restaking protocols in the future. Let's start by explaining the risk itself first - stake centralization due to the existence of restaking services. We need to go back to Proposer-Builder-Separation (PBS) to understand this better:

One of the great successes of PBS was that it leveled the playing field for validators. With PBS, every validator that tapped into the PBS relay got to enjoy the same yield for staking (and offer it to its delegating stakers). The idea here is that there isn't any economic advantage for any validator from building more profitable blocks than others. Hence users are indifferent in delegating their stake between the different validators because all the returns are the same.

Post PBS, there isn't a return-to-scale advantage to any validator. Return to scale for some validators enables them to have better returns, and consequentially to become very dominant by attracting more stake than other validators (=centralization risk). So the key principle to eliminating centralization risks is not allowing any validator to have an economic advantage over other validators (especially advantages that compounds with size).

### why restaking gets us back to stake centralization?


Now let's move to restaking, and why it changes this dynamic:

Eigen Layer and similar restaking services allow an infinite number of new permissionless services to be built on top of Ethereum, using the same stake. This creates an infinite space for inventing new permissionless services built on top of Ethereum. But this also creates a new type of centralization risk that PBS was aimed at solving - Restaking protocols will allow validators to tap into new staking services in addition to just validating Ethereum consensus.

Eventually, these validators can offer better returns to their delegators by not just offering plain Ethereum staking yields. Now we can get some additional yield on top of Ethereum staking yield! yay!

After restaking, validators that tap into restaking services can offer higher APY to their delegators! How much higher? Well, it depends on how many staking services they eventually tap into (you can theoretically tap into how many you would like). How will validators determine which restaking services they should tap into and offer to their stake delegators? Analyzing a specific service built on restaking might not be such an easy job as one might think. Understanding the risks from new consensus protocols, oracles, or other permissionless services built using restaking protocols, is not an easy job!

As a validator, you need to have a very deep understanding of the service you tap into and offer to your stake delegators, in order to truly understand the risks and potential rewards.

Stake delegators, and subsequently capital inflows, will likely avoid validators who mindlessly tap into restaking services without fully understanding the associated risks. They will most likely prefer to delegate their stake to sophisticated validators with reputations that can underwrite restaking services successfully.

This presents a significant challenge - sophisticated validators with more resources and deeper pockets can better understand the risks and rewards of specific restaking services. Over time, this advantage can accumulate and result in a better reputation for the validator that has more resources. This returns us to the starting point - some validators will have a return to scale, which will allow them to attract more capital. This leads to centralization risks, the very issue PBS was designed to solve!

The end game here is that a few validators that can underwrite restaking services better (and communicate it outwards) will gain most of the stake and reputation. an we get out of this centralization pitfall in an elegant way and still enjoy restaking innovation?

Yes!

The solution, in short, is standardizing a restaking aggregation service that all validators can tap into, a 'one size fits all' approach. This is akin to an Exchange-Traded Fund (ETF) in traditional finance.

Before we get into the solution, there are some simple assumptions we need to make first -

1. There will be many restaking services, probably hundreds of them eventually.
2. They will have a different risk-reward ratio.
3. Pareto rule will apply to their success, meaning few services (could be tens) will probably become very dominant, so if you will rank services by their dominance you will get a pareto distribution.
4. Now let's introduce a classical finance theory called 'portfolio theory', coined by Harry Markowitz (who won the Nobel prize for this).

Portfolio theory explains how to allocate an investment portfolio in an optimal way. We can think of each restaking service as a specific asset and the combination of different restaking services as a portfolio.

What if we could select an optimal mix of restaking services?

That will be great because instead of having lots of discretion for each validator in picking the different services to tap into and offer to restakers, they can just pick the optimal portfolio. And then it doesn't matter which validator you delegate your stake to because they offer the same optimal portfolio. The optimal portfolio is great and advances decentralization, because there is no discretion in picking staking services! Now every validator that wants to offer restaking, can offer the vanilla product (which is the optimal portfolio of restaking services), and assuming this will be the market-preferable option, we are again, evening the playing field for validators!

This also solves the problem of individual restakers that hold LSTs and want to restake by themselves. In their case the issue is that stake will accumulate to specific services, which might get too much of Ethereum stake used by them. Instead of having to underwrite a specific service, the restaker can just choose the optimal portfolio and enjoy diversification of restaking. This will ensure that the stake flowing to some services will not make them 'too big to fail' (because they accumulated too much stake).

You may ask, why should this work? Why would restakers prefer an 'optimal portfolio'?

We have a lot of evidence from traditional markets that ETFs are a great efficient solution for long-term investment (a big portion of public funds are held in these portfolios). There are some good reasons for that:

1. Optimal portfolios are diversified, and diversification, when done in a good way, eliminates risk.
2. Users don't have the capacity to actually choose across tens/hundreds of different restaking services.
3. Buy-and-hold (restake-and-hold in our case) is a great strategy for passive investors.
4. We can safely assume that having a market-agreed-upon efficient portfolio of restaking services can become very popular by restakers.

There are obviously some open questions:

- How do we agree on such an optimal portfolio and what are the criteria for getting in as a restaking service?
- Will this standard create overdominance of a specific set of services?
- Can we get a market consensus on this?
- Should we create multiple optimal portfolios catering to different risk levels (high risk, medium risk, or low risk)?

### Summary:

- Create an optimal portfolio of restaking services.
- If the market accepts this as a standard, most users participating in restaking will likely choose the vanilla product used by others.
- Most validators offering the optimal


![1](/restaking1.png){:.ioda}

![2](/restaking2.png){:.ioda}


