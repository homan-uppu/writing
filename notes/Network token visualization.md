ways to do this:
- grid of personal tokens in the background with the Network token "on top" of them all with a very high "market cap".

this scene showcases the Network token: a token that is invested in every other token in the network. to represent this we will have a PersonalTokenPill that represents each personal token. this pill will use the ProfileSection component we already have (which can take a hex value as a color in place of the profile pic), along with a number to the right of the profileSection representing the valuation of the personal token. all of this is wrapped in a pill (a div with layer1 bg).

create 24 dummy personal tokens. 4 of them will be of the images we already have (amy, jane, maya, sam) - (reference from the dummyPersonalToken in models.ts), and the rest will be new personal tokens that you make up (along with unique hex values representing their profile pic).

the scene will be a grid of personal token pills moving horizontally (framer motion), with a single personal token pill called "Network Token" that is fixed in the center of the scene - on top of the other moving personal tokens.

the grid will be a column of 4 rows, each row containing 6 personal token pills.
let's zoom into the grid a bit so that at any given moment, there are some personal token pills cut off at the edges - to hint that there are more. and loop infinitely: i.e. make it look like there are infinite pills.

apply the right classNames, we'll style in the module.css file.