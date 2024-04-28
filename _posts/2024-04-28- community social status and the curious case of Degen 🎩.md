---
layout: post
category: blog_posts

---

In 2019, Eugen Wei published an incredible blog post titled '<a href="https://www.eugenewei.com/blog/2019/2/19/status-as-a-service">Status-as-a-Service</a>'. He analyzed how social media platforms act as status-generating services, where users perform activities to gain social capital, similar to a video game where status is the score.

He theorized that social platforms operate by offering users status in exchange for engaging content, which in turn helps these platforms grow. His description encapsulates really well the essence of the social media game and provides a great mental model to think about the future of social networks and status-creation over the internet. 

## Algorithm as a Status Controller

We can view status as the currency of these social networks. On platforms like Twitter, likes, retweets, and follows are considered the ingredients of social status. Users create engaging tweets about news, culture, or entertainment and populate the town square of Twitter. In return, they gain followers which is akin to status.

Platforms control the distribution of status by managing the feed algorithm. They determine what content is seen and by whom. By designing these algorithms, platforms can influence which actions are rewarded with visibility. In response, users adjust their strategies to the algorithm to gain more status. The algorithm is the 'invisible hand' that exists in social media, dictating the fate of how social status is created or destroyed. Shadow banning, the practice of hiding a user's visibility from other users' feeds, is the secret weapon of social networks, allowing the platform to completely erase a user's social status.

![Degen Image 1](/degen1.png)

## Social Status in Web3

Web3 social networks innovate on the idea of status generation and control. Farcaster would probably be the best place to analyze and estimate today how web3 social networks will impact the distribution of online — or onchain — status in the future.

Farcaster is a relatively new, decentralized web3 social network that has shown solid growth in 2024. It grew from 2,000 active users at the beginning of the year to over 80,000 DAUs as of today, thanks to the introduction of <a href="https://docs.farcaster.xyz/learn/what-is-farcaster/frames">Frames</a> and <a href="https://docs.farcaster.xyz/learn/what-is-farcaster/channels">channels</a>, which were highly successful features that enabled developers to build ‘mini-apps’ on top.

The social graph and social activity in Farcaster are recorded on the protocol, a peer-to-peer network which holds the replicated state of the network. However, users usually interact with the protocol through the Warpcast client, which looks and feels much like the Twitter app but with additional features.

The team that created the Farcaster protocol also maintains Warpcast, where most of the activity occurs. **This means that the population of the social graph on Farcaster, the protocol, happens mostly with the intent of the Warpcast client, which controls the algorithm.** This is similar to web2, where the team controlling the client also controls the algorithm and status creation.

## The Curious Case of Degen

Degen began as a community coin for the Degen channel on Warpcast in January 2024. The community held a contest to choose a logo and branding, and the purple top hat was selected 🎩. The Degen token grew organically within Warpcast, with its first utility being a tipping system.

This system was straightforward—users could reply to casts with 'X $Degen' to indicate the tip they wanted to give. The offchain tipping system scanned Farcaster, summed up all the Degen tips, and airdropped them into the respective user's wallet (this type of experiment was also made in 2020 with the <a href="https://www.reddit.com/r/CryptoCurrency/wiki/moons_wiki/">$MOON coin</a> on r/CryptoCurrency under a community points product rolled out by Reddit. This product was <a href="https://www.reddit.com/r/CryptoCurrency/comments/17a33ql/serious_sunsetting_community_points_beta_and/">sunset</a> on Oct-23).

This was only possible because of the open nature of Farcaster; the network is always readable, and unlike other social networks that tightly control their APIs, an external system can always read the state of the network. This was also facilitated by every address in Farcaster being linked to a wallet address, making it easy to airdrop tokens to it.

The early Degen team made two brilliant decisions:

1. Users could tip without any wallet transaction, just by replying in casts (very low friction).
2. The Degen distributions were created out of thin air; every day users received an allowance, so it didn’t feel like spending something, but rather like contributing to someone.

These two brilliant decisions created something entirely new, which is the subject I want to get to—a new social status distribution system.

## Degen as a Status Distribution Mechanism

One side effect of the Degen tipping system was that it created an alternate universe to distribute status on the Warpcast client, independent of the Warpcast feed algorithm. Tipping was permissionless, and suddenly there was another status creation game outside the control of Warpcast. Users that seek to play in the status generation game could now play two types of games - the traditional game, which is getting likes and follows on Warpcast, and the Degen game, which was writing content that the Degen community would reward with tips.

The status creation is so significant that after a user receives the Degen token (an ERC20), they completely control it and can port its status anywhere outside of the Farcaster ecosystem. Meaning, Degen social status is portable, unlike legacy status created in the web2 systems.

**This created an external system that rewards users with social status for good content, which is outside the control of the core social media algorithm.** This is only technically feasible because Farcaster is open, which explains why we don’t really see these activities outside of web3.

![Degen Image 2](/degen2.png)

*A unique Degen Actions button was added to see how much Degen an address holds ('Bag Bias') and what its allowance status is ('$DEGEN stats). This allows to add social status to each account not only in traditional terms, but also with the new layer of Degen social status. You can now know the Degen social status of each account.*

So if I had to describe Degen from this standpoint, I would probably say:

**"Degen is an autonomous social status network, governed by the Degen community, that creates portable social network status."**

![Degen Image 3](/degen3.png)


When I sent this post for review, I got some feedback that there is another angle to the Degen tipping game which is - Degen is more about paying for good content and less about social status. But because of the close relationship between writing good content and earning social status in the platform (in the form of followers, shares, and likes), I think it makes sense to think of Degen distribution as both a form of money and status, and you can almost use both of these interchangeably.

### Buying vs. earning

However, there is one caveat to Degen status creation: you can buy Degen. Since the token is completely tradable, you can't really view Degen holdings as pure status because some might have been acquired organically and some might have been bought on the markets. It has yet to be known and explored how the tradability of Degen will impact its status formation, but there is a wide design space to explore which includes different tipping systems and their status creation capabilities (I list a few in the next section, such as soul bound tipping).

### Exploring New Ideas

We can play with the mechanism behind Degen to create a wide design space of external status creation systems. Here are some rough ideas that might be explored:

1. **Other content-enhancing coins –** Can we create an AI coin that gets tipped for excellent AI technical content? Or content about food for the foodies? How granular can we take the idea of content enhancement? Will we have tiny micro status communities in the future for every niche vertical?
2. **Farcaster clients based on the Degen reputation system** – create another client that prioritizes Degen holdings when deciding which content to show in the feed. This will be a Degen-first client, where the Degen community can have full control over curation. Should bought Degen receive the same weight as earned Degen?
3. **Soul bound tipping (non-transferableEx tipping)** – tip with coins in a non-transferable way, which could create a long-term social status for the address but also is less speculative and harder to bootstrap.

### Conclusion

It appears that Degen, although it started as a fun experiment, is a pioneering project in the creation and distribution of social status over the internet.

With the lightweight tipping system it created, it promotes independence from monolithic platforms and enhances user freedom. Once Farcaster has enabled open state to be read, it created room for creating new types of social status systems on top.

There is much more experimentation that should take place in the future around external status creation, and this is just the beginning. If you’re working on something like this, make sure you ping me :)

Long live the Degens 🎩
