*Initially published on Hackernoon: https://hackernoon.com/anti-growth-hacking-f2ffb2810203*

A “5” minute Youtube break turns into a 10, 15, 30 minute break.

I consume more than I intend to. Completely blocking sites, or regulating my use often doesn’t work, so instead I explored what sites do to hold attention, and tweaked them so that they are less distracting.
### Mis-Aligned Incentives

Most content platforms are incentivized to hold your attention for as long as possible because their **revenue** is tied directly or indirectly to the **time** you spend on them.

When what you want to do on a site doesn’t match what the site wants you to do, you’ll get situations like:

Here, Youtube suggests a video that’s irrelevant to what I’m watching. This suggestion is based on my viewing history, but doesn’t take into account whether I’m in the right context to want to see the suggestion. These suggestions are extra dangerous, because there is a part of me that really wants to click on it, since after all, it’s based on videos I’ve already watched.

As soon as you land on medium.com, you’re shown articles to read, even if your intent is to write.

Platform creators conveniently ignore your intent in order to nudge you to use the site in a way that benefits them.
### Attention Holding Tactics

I see 3 main types techniques that content platforms use to hold attention.
#### 1. User Interface Features

**Infinite scrolling of variable content:** Content is auto-loaded as you read, and you don’t know what’s about to be shown to you next. This mechanism triggers a dopamine response in your brain similar to pulling on a slot machine. It’s addicting. This infinite feed is found on most content platforms.

**Mobile:** Mobile’s viewing restrictions nudge you into spending more time within an app. Active context switching takes more effort (passively, notifications can intrude your immersion to take you to another app). To context switch without a notification trigger, requires, in the shortest case a double button press to go to your previously viewed app, and in the longest case, a button press, locating your next app on screen, and then click on it to open it. With all of the animations content loading, it’s still longer to switch apps on a phone vs. on a desktop browser, making you less likely to do so.
#### 2. Game-ification

We love to earn points. On some platforms, points act as reputation that’s useful in the context of the platform and beyond.

[StackOverflow](http://stackoverflow.com/?ref=hackernoon.com) users can leverage their reputation from the platform, in the real world since the skill to answer questions on StackOverflow often translates to programming knowledge / competence [1]. Host reputation on Airbnb affects how many guests you accommodate.

In others, points exist purely to drive engagement: Snapchat awards points when you send someone a snap.

#### 3. Suggestions You Want (NEED) to Click

The more you use a platform, the better it knows you and what suggestions you will click on.

These tactics aren’t always used to hold your attention. For example, the Uber app takes you to placing a ride (and hence leaving the app) quickly. It works for them because their revenue isn’t tied to how much time you spend in their app, but rather to how often and far you ride through their app. [2]

### Anti-Growth Hacking

I want to be able to choose whether to consume more information **before** seeing what it is, to turn content consumption into an active choice rather than a passive habit. This shift drains the power distractions hold…

I tweaked Youtube and Medium to ask before they show content:

[](https://hackernoon.imgix.net/hn-images/1*p25pzO-XZT2TpdR3HDKGvA.png "Download image")

Additional content and suggestions are shown only when you ask for it

[](https://hackernoon.imgix.net/hn-images/1*8SgQUzuX5-fVjXIWucogtQ.png "Download image")

The modified landing page for medium.com. This way, if you go to medium.com to write an article, you no longer have to see a feed of interesting articles to read before you get to the writing editor.

### Further Work and Exploration

- Study more sites and gather patterns to make this approach more robust. Website usage follows a power law such that tackling the top 10–20 content platforms should cover most content consumption.
- **Add more features**(e.g. make infinite feeds finite).
- **Anti-Growth engineer mobile:** Tackling mobile is important since most content is consumed on phones. Nature of mobile creates challenges to hack the user experience like you can on the web.
- **Re-think mobile design** to maximize utility and minimize distraction.

The internet is powerful. I’ve learned most of my skills by learning from the best, on the internet. At the same time, there are issues:

- **False information.**
- **Opinion bubbles**: It’s easy for me to fall into circles where my opinions of the world aren’t challenged, making my mental model of the world further from reality.
- **Noise:** Takes effort to feed my mind high value content.

With food, we’ve seen a massive increase in demand for healthier options. This came after decades of consuming addictive junk food that led to an obesity epidemic around the world.

**I believe that we consume too much bullshit content in a way that is unhealthy for our minds.** We’ll see increased demand for better content and tools to help us navigate content in a healthier way.

Let’s talk about what that healthy could look like.

### Notes

[1] Likely not the points themselves, but rather the quality of your answers on the platform. At the least it acts as a programming blog that also signals how useful people found your questions/answers.

[2] In fact, in Uber’s case, there might even exist a negative correlation b/w the amount of time I spend in their app with me paying for a ride. I predict that less clicks and time to placing a ride, the better for their conversion.

Thanks [Mitchell](http://mitchgordon.me/?ref=hackernoon.com), Nguyen for feedback on drafts.

I’m going to update the extension this weekend to support this version of Youtube. Older versions of Youtube, and all versions of Medium.com should work fine. Please reach out / comment below if you have any issues.