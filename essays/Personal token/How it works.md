### The Network

This system would be implemented as a network of personal tokens, along with the metadata required to keep track of who owns how much of what. From here on out I’ll refer to this system as the “Network”.

Both the individual raising capital, and the investor investing in others will need their own personal token in the Network to be able to transact in the Network.

### A personal token

A personal token is a fictional entity that represents:

- the owner of this personal token.
- wallet that stores $. (used to invest in other tokens, and where capital is deposited when a user raises money)
- which personal tokens own how much equity in this personal token (as number of shares out of total shares available).
- assets: the other personal tokens and companies (outside of the Network - i.e. in the "real world") that this personal token holds equity in.
- a history of all the transactions this personal token has been involved in.

<Card caption="A personal token with shareholders and a portfolio of other personal tokens and companies.">
  <PersonalTokenComp />
</Card>

There is no notion of a “user” in the Network. A user is simply represented by their personal token. It naturally follows that a user cannot own more than one personal token. A user holds equity in other personal tokens (by investing in them) **_through_** their personal token. For example, if Alice has 5% equity in Bob’s personal token, Bob’s personal token equity will be represented in the assets of Alice’s personal token.