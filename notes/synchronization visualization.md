the purpose of this scene is to show that the company portfolio assets for a personal token are off chain.

we'll do this by showing two containers adjacent to each other:
- "On chain" container
	- label "On chain" (use the SectionHeader comp from PersonalToken).
	- render the portfolio as it's rendered in PersonalToken (use a state for the token - and initialize to the dummyPersonalToken).
	- in the portfolio, draw a solid border around the Personal token assets, and a dashed line around the company assets.
	- Give this container: styles.onChainContainer
- "Off chain" container:
	- label "Off chain".
	- leave the top part blank (that is the same height as the personal token assets)
	- draw the same company assets, with a solid border this time around - that is aligned vertically with the same company assets in the On chain container.
- place a line at the right center of the companies container in the On Chain container, to the left center of the companies container in the Off chain contianer.