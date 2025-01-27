I believe personal tokens will soon become a foundational piece of our society: future generations will raise money by selling a portion of their personal tokens in order to finance their learning, instead of paying for education.

AI will make all of our work more complex & creative, leading to a power law distribution of outcomes: few will be responsible for the majority of economic value created in the world. In addition, as AI becomes more powerful, quality education actually becomes *more* expensive, not less as many seem to believe.

As a result, paying to learn doesn't make sense because most people won't earn back their investment on a reasonable timeline, if ever. Raising money from investors by selling equity in personal tokens will be how most people will finance their learning. Basic income too will be provided as an investment.

My previous essay ["VC will be the best way to finance learning"](/vc-learning) explores why in greater detail. This essay is an exploration of how this personal token could look like, and how to actually bring it to life. This is a *very* early draft, and most of the thinking below may end up being entirely wrong. 

I'd appreciate your feedback.

### A personal token

A personal token is a fictional entity that represents an individual's equity in companies and other personal tokens.

(Image of Bob with his token floating above - BobToken)

People can invest in someone by purchasing a portion of their personal token, entitling them to a proportional share of that person's future economic gains from their equity in companies, and other personal tokens.

Similar to a [C Corp](https://en.wikipedia.org/wiki/C_corporation), a personal token would be divided into a certain number of "shares". Authorized shares are the number of units a personal token is divided into. Issued shares are the shares that are issued to people.

(Alice's "portfolio of investments).

Whenever Bob sells his equity in another company or personal token, those who own BobToken would get their proportional share.

(animation of $ flowing from the sale to both Bob and Alice according to their respective ownership percentages).

A unit of BobToken would be valued according to what the market believes is Bob's potential to create value over the long-term. Similar to a company, the value of a personal token is grounded in anticipation of actual economic value creation, not just popularity / clout.

**How is a personal token different than just a company that you create to represent your investments in other companies - sort of like a VC firm? Why is a new financial instrument necessary?**

To be clear, the starting point for a personal token may very well look like just another company with a few modifications. But, there are a few crucial differences between a personal token and a company such that it makes sense to treat them differently.

A personal token is inseparable from the individual. Unlike a company who's owners can change entirely, an individual can't give away personal token such that they no longer have it. In another sense, a personal token is like an abstraction "above" all the companies that a person will have equity in.

A personal token also represents a different sort of behavior: investing in people *before* they may have something specific that they are going to create. Companies are generally formed when there is a specific product or service that the founders want to create, rather than something more open ended.

Even if the underlying implementation is a "company", from a use-case, behavioral, social context, a personal token is a new financial primitive.

And since a personal token isn't the same as a company, certain features of companies won't translate to personal tokens. For example:
- It probably doesn't make sense to give investors "voting rights" or to have some kind of "board of directors" that oversees the activities that the individual does. This curbs freedom that is bad for both the individual and the investors.
- Might make sense to "cap" returns. E.g. when an investor makes 1000x their investment from a personal token, their equity in it is transferred back to its owner. 
- Might need to limit how much of a personal token an individual can sell. e.g. if 99% of my future outcomes go to my investors, my life feels screwed.

### Priorities
#### 1. Trust
Investors must be able to trust that their equity in personal tokens will be honored.

They should have confidence that they will receive payouts. They should have confidence in the system to prevent fraud, and have some recourse in the case of fraud (i.e. an individual raises money and runs with it, or doesn't accurately disclose their earnings from equity sales).

Trust is the foundation of this system. Without trust, capital won't flow into the network of personal tokens because people won't be sure of the returns even if they invested in the right tokens. People don't play when they think the game might be rigged.

#### 2. Ease
Creating a personal token should be fast, simple, and affordable. Eventually, everyone will just have one by default similar to IDs, etc.

#### 3. Efficiency
Payouts as close to instant as possible.

### How

- an overview of the system design
	- blockchain network with sufficient decentralization to enable a thriving ecosystem of apps and services based on personal tokens.
		- allows creating 3rd party services that can interface directly with the end-user.
			- what are some good 3rd party services?
	- verifiable "proof of judgement".
	- sufficient centralization required to curb fraud (elaborate).
	- blockchain & reality of the messy world kept in sync.
	- real-world identity - ensure that a person can only create one personal token, and can't just create more.
	- sufficient centralization.
	- transparent.

From a legal standpoint, a personal token is undeniably a security. Trying to present it otherwise in order to skirt laws is a shortsighted, unambitious approach. This system will need to be compliant with regulations in order for it to last.

Still, we'll need to be quite creative because existing legal structures ("company", "LLC", etc.) weren't designed for personal tokens. And, in the long-run, we'll have to play a major role in helping shape regulations and legal primitives that make implementing personal tokens smoother.

I don't have a legal background, so much of my exploration has been via chatting with Claude. An interesting suggestion from Claude that's prob worth a deeper dive:

```
Let me help explain how we could structure this platform while navigating the regulatory requirements. I'll break this down into steps and explain both what needs to happen and why.

First, let's understand what's happening from a regulatory perspective: When someone creates a personal equity token and sells portions of it to investors in exchange for money and with the expectation of future returns, they're creating a security. This is true regardless of whether it's on a blockchain or not - the underlying economic reality is what matters.

Now, let's look at how we could structure this:

Instead of individual LLCs, we could have your platform company create a master LLC with what's called a "series LLC" structure. Think of this like an apartment building where each apartment is legally separate from the others. Each personal token would be a separate series under this master LLC.

Here's how it would work step by step:

When a user creates their personal token:

1. They provide identity verification (crucial for regulatory compliance)
2. They sign a standardized contract that:
    - Assigns their rights to future earnings to their specific series under the master LLC
    - Defines what earnings are included (equity sales, etc.)
    - Sets up their obligations to report earnings
    - Establishes how proceeds will be distributed

When they want to fundraise:

1. Your platform (the master LLC) files a Form D for their specific series
2. The fundraising link is technically an invitation to invest in that series
3. When investors "apply," they go through accreditation verification
4. The smart contract that records ownership percentages is connected to the legal rights established in the series LLC

The advantage of this structure is that:

1. Individual users don't need their own LLCs
2. One master Form D filing can cover multiple series
3. The blockchain records serve as a transparent ledger of ownership
4. The legal structure provides enforceability

However, this approach means your platform company takes on significant responsibilities:

1. You'll need to register as an investment adviser or broker-dealer
2. You'll need robust systems for tracking and distributing proceeds
3. You'll need strong compliance procedures
4. You'll need to manage tax reporting for all the series

The key to making this work is ensuring that the legal agreements and blockchain implementation work together seamlessly. For example, when the smart contract records that someone owns 10% of a personal token, that needs to correspond to actual legal rights to 10% of the designated earnings under the series LLC structure.

This is similar to how some real estate investment platforms operate - they use a series LLC structure to separate different properties while maintaining a unified platform for investors.
```


#### Combating fraud

While having a 


### History

- on the natural arc of societal evolution: trade -> money -> company -> personal tokens (an abstraction that sits "above" companies and other assets).

There's also prior experiments towards personal tokens that didn't scale:
- [RAC token](https://rac.fm/rac-token) by [RAC](https://x.com/rac).
- $ALEX by [Alex Masmej](https://x.com/alexmasmej).
	- https://medium.com/@AlexMasmej/taking-risks-during-chaos-initial-alex-offering-339883bb7f6d
	- https://decrypt.co/25980/alex-mamsej-fractional-shares-ethereum
	- https://www.reddit.com/r/ethereum/comments/g4tllj/the_man_who_sold_fractional_shares_in_himself/
	- https://a16zcrypto.com/posts/article/creator-tokens-and-community-tokens/ (an essay he wrote).
- [friend.tech](https://friend.tech).
	- https://www.perplexity.ai/search/what-is-friend-tech-how-was-it-FzM2eUiySBG.XUvFH9rBpg

These experiments show why trust and grounding tokens in actual economic value are so important to attract, and importantly sustain, capital coming into the network.

### Future
- All of our assets will increasingly recorded on chain. 
- AI will help identify fraud at scale. The better AI becomes, the more decentralized this network can become. The network requires some degree of centralization **to function well and prevent fraud**.

### Open questions

### Help

- How you can help and why you might want to.
-

### Notes
