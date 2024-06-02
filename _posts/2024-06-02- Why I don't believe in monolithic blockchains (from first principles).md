---
layout: post
category: blog_posts

---

Why I don't believe in monolithic blockchains?

Explaining from first principles:


1. Blockchains are computers.

2. Computer history has shown us that when you build more bandwidth, storage, and compute capacity, developers build more demanding apps and use these excess resources.

3. That is why, no matter how many transactions/gas you can process per second, if you're a successful blockchain, it will never be enough.

4. This will result in one of two scenarios: fees go up, or you need to increase hardware/networking requirements for nodes (which leads to centralization).

5. You can't solve this with gadgets like differential pricing for high-demand pieces of state. You just isolate the problem from interfering with other things (high-demand apps will still be expensive). It's still an issue.

6. All roads lead to execution sharding. Call it whatever you want (shards/rollups/subchains).

7. Once you go to sharding the execution and decoupling execution and consensus, what do you need for a base settlement layer?

8. But even before that, what don't you (really) need? - parallel execution, fancy networking gadgets, or some crazy VM.

9. What do you actually need? Heavy economic security, verifiability of every piece of the stack, heavy research on potential black swans and security risks, support for validation of shards/rollups state transitions, support for escape hatches to prevent censorship in rollups, and a code language that is battle-tested and free of bugs.

10. These things have massive network effects, and I don't think any other chain other than Ethereum is close to achieving these things. Does this make me a maxi? No. I thought about these things from the ground up, and if any other chain aims toward these futures, I'll be there to support it.

11. And lastly, where can I be wrong and where do other smart people disagree with me?

I think the nature of the disagreement lies in the core assumption of what a blockchain is. If you see it as a Nasdaq substitute or some purely financial system, then your mental model is: if I can get a blockchain to x TPS, I'm done. This point of view assumes there is a saturation point for demand, like Visa or Google queries, and once you reach it, demand will reach an equilibrium. I think this perspective comes from too much skeuomorphism around thinking of blockchains in the context of finance. But anyway, this is the core disagreement between monolithic and modular blockchains. If blockchains are computers, I think that monolithic blockchains will lose the battle of scaling. If blockchains are Visa substitutes, monolithic blockchains will win over the complex and fragmented modular blockchains.

Whatever the case, long live blockchains.
