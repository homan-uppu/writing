Each person who joins the network has a personal token.

Their personal token represents their equity in two kinds of assets:
1. Equity in other personal tokens (in this network => verifiable on chain).
2. Equity in companies (source of truth is outside of the network => verified through an [oracle](https://en.wikipedia.org/wiki/Blockchain_oracle)).

A user (Alice) can raise money from investors in the network by selling equity in her personal token. This represents Alice giving up equity in her future outcomes in exchange for valuable capital today that would help Alice generate future outcomes.

Over time Alice will earn equity in the companies she creates, or works at, and will also earn equity in others' personal tokens within the network that she invested in.

When Alice sells her equity in someone else's personal token, or in a company, a portion of the capital she gains through by selling equity goes to those who hold equity in Alice's personal token - proportional to how much equity they hold.

*(TODO: understand why we don't have to take into account how much the user bought the shares in the first place, and why we can just distribute from the entire sale amount? something feels wrong here. read: capital gains).*

Implementing capital distribution within the network (when equity in another personal token is sold) is straightforward: through a smart contract. When Alice successfully sells her equity in a personal token, some of it is automatically siphoned off by the smart contract to the wallets of those who hold equity in Alice's personal token - proportional to how much equity they hold.

Implementing capital distribution when Alice sells equity in a company is more challenging. When equity in a company is cashed out, Alice technically "owes" those who hold equity in her personal token their share of the capital Alice gained from selling equity in a company.

Alice will need to report this somehow, and be able to transfer value within the network to those who hold equity in Alice's personal token. This point at which the network interfaces with the real world poses the greatest risk for the network's success because it's where bad actors have the opportunity to cheat others.

Let's say Dan is a bad actor: he wants to raise money on this network without any intention to actually create value in the world (or hide it) and just run away with the money he raises from investors. Dan would then be incentivized to hide his successes in the real world from the network so that he doesn't have to pay investors their share of the value he's created in the world.

The success of this personal token network depends on how well it can dis-incentivize bad actors like Dan.

Some ideas on how this can be done:
1. Once it's clear someone is a fraud, block them from participating in the network in the future: meaning they cannot invest in others' personal tokens. Over time this will be the most powerful lever to minimize fraud because the economic potential of investing in people will be enormous.
2. Track their successes in the real world and identify discrepancies (e.g. they may say they joined a startup on LinkedIn, but haven't reported that they've gained equity in a company to their investors).
3. Ensure all investments comply with regulations around securities so that in the case of fraud users have access to the courts to sue fraudsters. As the network becomes more powerful, it will rely less on the public courts, and more on incentives that will keep people in line (i.e. people will not be want to lose out on the opportunity to profit from personal tokens).

In order to implement these ideas, each user must be associated with their real-world identity (e.g. government issued ID / something like [WorldID](https://world.org/world-id)). Users can't just create new personal tokens and disassociate with their past.

I currently can't see a way in which the network can be completely decentralized because if it were, how would fraud be identified, and how would bad actors be kicked out of the network? Actions like these can't just be put to a vote. There needs to be some central authority with the power to make these calls in order to protect the integrity of the network.

Complete decentralization creates great opportunity for fraud. ([NFT rug pulls](https://www.perplexity.ai/search/what-is-an-nft-rug-pull-and-wh-l2MUzbggRFGpyJ83Mf1A7w)).

Privacy can be supported via zero knowledge proofs so that a person can keep information about their investments private.

Governance of the centralized authority will need to be well designed. Over time, the central authority should lose power (proportional to how good AI becomes). Its decision making should be transparent. And there should probably be a way for the network to overrule certain decisions.

## meta
In addition to building and operating the network, the organization behind the network will be also responsible for:
- shaping regulations around personal tokens.
- shaping culture by making the world more ambitious.

