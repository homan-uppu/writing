a component to render a personal token.

props:
- profilePicSrc
- name
- valuation: string
- bio: string
- linkInBio
- shareholders: ShareHolder[]
- portfolio: LineItemProps
- shareholders: LineItemProps

whole container is a flex column with 48px padding.
within container:
- Bio
- Shareholders
- Portfolio

sections.

the Bio containers:
- LineItem representing the owner of this personal token.
- Bio
- linkInBio (blue and opens in new page).

Shareholders are just LineItems that only have equity, no value, and type is only of personal tokens.

within the portfolio, there are both types of LineItems: companies and other personal tokens, separate the two, give each their own headers, and a divider between the personal tokens and the companies in the portfolio.

There are 2 section headers in this component: "Shareholders", and "Portfolio". Make the SectionHeader a separate component that can be exported. it is a geistMono font, text-transform uppercase, and secondary font color.

don't style anything in this file, just use the styles. approach and we'll style in the module.css file.

