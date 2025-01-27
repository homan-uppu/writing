
## III. System

### Priorities

We will optimize for economic growth: to maximize the market capitalization of the Network.

Why? Optimizing for economic growth requires the Network to prioritize the most ambitious individuals. And these are the best kind of individuals to build for because they care about their reputations and are less likely to engage in fraudulent behavior (which will be one of our major challenges).

This is also less of a choice than it seems. In the early days of personal tokens (perhaps the first few decades), I predict we will see competition between different Networks with different design decisions leading to different trade-offs. Yet, network effects are incredibly strong: everyone will want to participate in the Network with the greatest market capitalization because that is where they will have access to the most capital. We will see a winner-takes-all dynamic. In a world in which people can freely choose which Networks to join, people will flock to the Network that is best capitalized that they believe will continue to be in the long-run. The other Networks will fade away.

### Admission
How selective should admission into the Network be?

### Tackling fraud

By fraud, I mean any kind of manipulation / deception with the intention to profit.

**Investor confidence is critical for the Network to survive**. If investors feel that there's too much fraud on the network, or feel like they don't have a good recourse if they’re scammed, they won’t invest.

Fraud could be:

- **Identity fraud**: A user who has already created a personal token and raised money in the past creates another personal token on the Network in order to raise more money while hiding their history. This is something that a user who has already raised capital and has consistently failed to create any value would want to do to cover up their poor track record.
- [Rug pulls](https://www.coinbase.com/learn/tips-and-tutorials/what-is-a-rug-pull-and-how-to-avoid-it): a user raising capital by fabricating a pitch without actually having the intention to create long-term value. They raise money and aren’t seen again.
- **Avoiding capital gains distribution**: A user, after raising capital (and therefore has investors who own some equity in their personal token), intentionally fails to report selling company equity (outside of the Network) in order to avoid having to pay their investors their proportional share of the capital gained from the equity sale.

In order to make sure that a user can only have one personal token and can't hide their track record from investors, the Network will need to verify the human behind the user: via government ID verification, or perhaps by taking advantage of something like [WorldID](https://world.org/world-id).

In order to prevent rug pulls, it would help to have the backing of courts. This requires treating personal tokens as securities and complying with the regulations around securities. In cases of fraud, investors (or the Network’s legal counsel) can then file lawsuits under federal securities laws ([particularly Rule 10b-5](https://www.investopedia.com/terms/r/rule10b5.asp)) for material misrepresentations or omissions made during fundraising. In the early stages, to minimize legal complexity, restricting the Network to only users in the US makes the most sense because of its ambitious talent pool and quality of investors.

To prevent avoiding capital gains distribution, the Network could require users who have shareholders in their personal tokens to submit their tax returns annually (which would reflect any capital gains).

Yet, prevention is far more valuable than cure. Having a strong community of high quality, ambitious users who genuinely want to do great work is critically important. Ambitious individuals operate on long time horizons and wouldn’t want to damage their reputation for some measly short-term gains. Therefore, the Network will need to be able to penalize bad actors \*\*\*\*such that they can’t participate in the Network.

Investors who believe they’ve been scammed can flag it and the fundraise will be investigated by the fraud authority: a team that works for the Network that is responsible for identifying fraud and taking measures to penalize bad actors.

Assessing whether fraud actually took place can be difficult. In order to have sufficient information to assess claims, it would help to encourage personal token owners and their shareholders to communicate within the Network itself, so that in the case that someone claims fraud, the Network’s fraud authority can inspect the communication between the parties, do research in the real world to validate claims, and come to a decision on whether it believes fraud took place and to what degree.

When this authority decides someone is a bad actor, they can freeze the bad actor’s personal token on Network, and the bad actor would be barred from participating in the future.

Blocked users should have a way to challenge decisions. When this happens, the evidence and argument produced by the fraud authority would be shared to a sufficient number of Network users who could vote on whether fraud actually took place (and thereby whether the user can be let back in or not).

Centralization (with a decentralized means to correct mistakes) is required in the early days in order to swiftly block bad actors so that they don’t do more damage to the Network. As artificial intelligence becomes more powerful, this function can be more decentralized: i.e. instead of giving a small group of people power, Network users instead vote on the prompts & examples taught to the AI to determine what is fraud on the network and what isn’t. Therefore, **I predict degree of decentralization to be proportional to the degree of intelligence of AI.**

We could also introduce a voting system to determine who is a part of this fraud authority. This will be important because there can (and will likely be) bad actors in the fraud team as well.

### Synchronization

The source of truth for equity in companies lies outside of the network:

<SyncScene />


### Sufficient decentralization

There are 3 types of functions in the Network:

1. **Tied to the network**. There are no 3rd party implementations available. Designed and implemented by the core team with feedback from the users in the Network, and possibly with Network participation in shaping features (for example, through voting). To fundamentally change these functions, you would need to start a new Network.
2. **Tied to the client.** Any user can create their own implementations for these functions and expose them to other users through an open marketplace. These 3rd party implementations are built on permission-less decentralized primitives: i.e. no centralized authority can censor, block, and 3rd party developers need no one’s permission to build and distribute their versions of these functions.
3. **Peer to peer:** these functions are between individual users of the Network without interference from any central authority.

#### 🌐 Tied to network:

- **Admission**: verifying and accepting people into the Network
- **Fraud prevention**: assessing fraud complaints and penalizing bad actors

#### 📱 Tied to client:

- **Discovery feeds**: ways in which users of the Network can discover each other. For example: through a feed of active fundraising rounds

#### 👥 Peer to peer:

- **Raise capital**
- **Invest**
- **Sell on chain equity**
### Network token

The Network Token is similar to other personal tokens except that:

1. It is not tied to any individual user, but rather to the Network itself.
2. Its shares can be traded freely without requiring anyone's approval.

Whenever equity in a personal token is sold on the network through a fundraising event, a small equity stake (0.1%) in each personal token is automatically granted to the Network Token as a "transaction fee". The more fundraising rounds for a personal token, the greater the Network token's equity in that personal token.

Therefore, the Network token's portfolio represents the Network itself.

The Network Token is divided into 10 million shares that can be freely traded, allowing anyone to invest in the overall growth and success of the Network.

As with with personal tokens, whenever a user sells their equity in any personal token, say Amy sells her equity in Jane's personal token, a percentage of the capital gains falls into the wallet of the Network token proportional to how much equity the Network token holds in Amy's personal token.

<NetworkTokenScene />

The wallet associated with the Network token is considered the treasury. To balance operational needs with shareholder returns, when new revenue enters the treasury, 30% is immediately distributed to Network Token shareholders, while 70% is retained in the treasury to be used for legal compliance, development of new features, security, and anything that's is required to preserve the integrity of the Network.


### Promoting competition

I predict in the first few decades of this system, multiple Networks will co-exist - each with different design decisions. Eventually, the Network that best optimizes for total market capitalization, will be the single winning Network that will win over the rest (extreme power law distribution).

### Governance

- Core team
- Legal counsel - talk about how we will need to help create the legal framework to enable personal tokens => meet the legal system where it is + help define the future.