---
layout: post
category: blog_posts

---

The 2023 price rally in Solana has ignited a fiery 'geeky' discussion on X between developer communities regarding different blockchain architectures.
It is quite common to watch tribes of developers and investors in crypto land fighting over what is the best/right tech, and "modular vs. monolithic" is the current hot discussion.

So, it is worthwhile explaining what modular and monolithic are, and why it matters:

Modern blockchains store shared state and execute code, and the big question is how to do this efficiently - meaning how can you scale the execution of code and storage of shared state, without incurring big costs that are not affordable by users (and under the obvious constraints of public blockchains like decentralization, safety and liveness).

Ethereum has become really expensive over the last few years (in rush time transferring ETH might cost as high as a few tens of dollars), and competing blockchains like Solana are offering fast and cheap transfers that cost a few cents. To solve that, Ethereum aimed for a modular roadmap that will ease costs and increase throughput with low costs as well.

Modular blockchains remind me of the same trend that we've seen with cloud computing - the cloud allowed computers to decompose into their different components. Over the cloud, you can consume compute, memory, and storage separately - each priced separately, and can be scaled horizontally or vertically independently. This allows for catering to varying needs, costs, and technical requirements.

The same trend is happening with blockchains like Ethereum today. You can think of Ethereum as composed of different 'layers' - consensus/settlement, data availability, and execution. Consensus is the part that makes the network agree on a specific state, data availability provides the needed historical data to verify the network's integrity, and execution is a runtime environment for executing codes (i.e., smart contracts).

Until 2020, usually, all these components lived together, <a href='https://ethereum-magicians.org/t/a-rollup-centric-ethereum-roadmap/4698'>but as of the end of 2020, Ethereum has adopted a 'rollups-centric roadmap'</a>, which is about turning itself into a settlement layer, while outsourcing execution and data availability to different layers.

Since then, there has been a Cambrian explosion of innovation across the different layers, such as rollups, which have raised billions of dollars in aggregate from the best investors in the world.

But not everyone agrees on this approach. Blockchains like Solana approached the scalability and technical difficulties of blockchains with another approach - more engineering! Solana has innovated on many of the different components of a blockchain, around networking (faster P2P data propagation), consensus (parallel agreeing on a shared state using sophisticated consensus algorithms), and execution (parallel execution of code). You can find many new engineering gadgets in Solana that try to solve the scalability and cost tradeoffs better. But all of these components are cramped together in the same client (the software that nodes run), hence a monolith. 

The objectors to the monolithic Solana approach claim that this comes with a huge cost for running nodes on the network and contradicts the decentralized nature of blockchains, making the network less stable and more centralized.

Personally, I'm in the modular camp. why?
### Modular > monolithic

1. **Open-source culture** - This allows for constant innovation across the stack and helps avoid protocol ossification. Anyone can add any teak to the EVM when it is an L2, or even use another VM (Eclipse is building a Solana based VM on Ethereum). Ethereum recently launched an RIP (Rollup Improvement Proposal) for the coordination of different imporvements between rollups and Ethereum. 
2. **Anti-fragility** - The failure of a single component doesn't bring everything down with it. So if tomorrow morning one of the rollup bridges gets hacked (i.e. a failure of an execution enviorment), the industry gets to survive. 
3. **Better pricing of network resources** - Modular pricing for compute, data availability, and settlement. 
4. **Better competition** ("tech discovery") - Competition among different components helps the market discover the best technologies. 
5. **Allows for more nuanced usage/edge cases** - Different users have varying specifications; modular design caters to all of them. There are many cases of specialized VMs such as Canto, that are experimenting with new types of incentives and value accrual from different VM pricing models. 
6. **Specialization** - Each component in the stack can focus on what it does best. For example parallel execution, which Ethereum doesn't need to prioritize, can be optimized at the rollup level.  
7. **Decentralization/scalability spectrum choice** - Allows users to choose their preferred position on this spectrum. Ethereum the monolith is expensive and decentralized, volition is more centralized with data but cheaper, validium is a middleground. 


Monolithic architecture has some very obvious advantages - everything is composable and much easier to coordinate changes. However, I believe that open source collaboration will eventually compound to an extent that is unbeatable by other chains. The best historical example of this is Linux, with a great description of the open source model in the book 'The Cathedral and the Bazaar'. Or, as they say - if you want to go fast, go alone; if you want to go far, go together.


