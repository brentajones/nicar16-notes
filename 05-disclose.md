# When and How Data Journalists Disclose Their Methods

*Thursday, 10 March 2016, 4:45 p.m.*

[slides](assets/05-disclose.md)

While a data journalist's toolkit is becoming more and more complex, the responsibility to disclose and explain our methods remains a bit murky. How do we explain to a lay audience our usage of models or machine learning techniques? What if there is an error in a library we used to perform our analysis? What do readers need to understand about our techniques to properly interpret the results of our analysis? Should we publish source/raw data? These are a few of the questions we will raise and attempt to answer — with your help. Audience participation will be an important part of this session. Let's figure out some transparency best practices for data journalists.

* Chris Groskopf, Quartz
* Ryann Jones, ProPublica
* Stuart Thompson, WSJ
* Aaron Williams, Washington Post

## Examples

*Stuart Thompson*

ProPublica releases whitepapers, and "more friendly" methodology pages.

> We used acceped statistical methods…

**Should we all do this with complex analysis?**

and

**Do we have time?**

Buzzfeed released data and analysis to GitHub. Linked specific passages to GitHub analyses. Makes it reproduceable.

**Does this help most readers understand the data?**

**What is the goal?**

### Examples of when we do this…sort of

FiveThirtyEight links a bunch of footnotes. Says "The 2006 calculations are a bit more complicated." Also "I used a form of machine learning called a random-forest model to generate these predictions."

Bloomberg explained it a more complex way. "Tweet at me with corrections or pedantry."

**What parts should we explain?**

**Are readers equipped to understand it?**

**Do they care?**

### When we don't do it

**Most of the time?**

NYT analyzed air bags, may have done some analysis, but didn't explain it.

**Is there any harm in not doing it?**

**Do readers have different expectations for transparency by organization?**

## Who is the audience for transparency?

*Ryann Jones*

Two audiences, readers and critics.

Good to have something written down to point readers to. Whitepapers come in handy for critics; investigative journalism invites critics, will try to poke holes in your methodology. Shows you've done your due diligence.

*Stuart Thompson*

Spectrum of people, thing that unites them is context. When we quote people we give their title and occupation to provide context and let readers weight their opinion.

It's not always about 100% transparency, but it is about 100% trust.

*Aaron Williams*

Also helpful for reporter or team. When you've been working on the story for a while, it's helpful to be able to explain what you just did.

"It gives me a peace of mind."

## What motivates ProPublica to spend so much time doing this, and why is it valuable for large and small projects?

*Ryann Jones*

Was in response to interest from readers. Also using data store as a revenue source (cleaned data or calculated fields). Invites curiosity from readers and researchers. "Everybody wins."

## Balance between time invested in documenting process and other

*Aaron Williams*

Reinforces your own analysis, reminds how you came to those conclusions. Becomes a tool for other reporters in the newsroom. Document as much as you can, really for yourself — it's easy to forget.

## Are reporters encouraged or required to publish data/methods?

*Stuart Thompson*

Encouraged, not required. Like going to the gym — you know you should. No established path to vet code. IP concerns, messy code. You don't always code something in a way that's releasable.

Methodology sections seem to be the least lively — can we make them better? E.g. Instead of a blog post, a series of graphics.

## What's the minimum? What's our obligation?

*Stuart Thompson*

Providing context for understanding results. Mentioning the name of the model may not be enough. But it can be simple. E.g. after switch to a logarithmic scale: "This makes numbers comparable."

When you're creating new data, you should explain how.

*Ryann Jones*

Before methodology is published, ProPublica sends it out to other researchers. They don't call it "peer review". Sort of an informal peer review. If they hadn't sent it out to doctors, the story would be poorer for it. Can't usually send code to review, but methodology can be helpful.

## How do data projects change the way we do corrections? How can we be transparent about tools we use?

*Aaron Williams*

Aren't necessarily a bad thing. We have a responsiblity to do it. No one forces you to use the tools, you chose it.

*Stuart Thompson*

Size of correction should match the size of the error. What do readers really need to know to understand what went wrong and how you fixed it?

If we're not transparent about things, straight up data manipulation or lying will be very hard to catch (maybe harder than plagiarism or fabrication).

## One tip

*Stuart Thompson*

Build methodology as you do it. Data diaries. Starting at the beginning makes it doable.

*Ryann Jones*

Make sure someone else looks at your work, hopefully inside your organization. We won't release without extensive bullet-proofing and fact-checking.

*Aaron Williams*

If you're releasing code, release it, then follow the steps again or get someone else to follow it. If you're going to do it, do it right.

## Q&A

Q: Is it important to the community for open-source, reproduceability, etc.

A: *Aaron Williams*: Competition with other newsrooms can make opening data murky. Can usually at least explain how we did it. Not having a methodology is not a good strategy. Methodologies encourage learning.

*Chris Groskopf*: Other benefits to reproduciblity: You can redo it yourself, later. Pitch that, keep the philosophical stuff to yourself.

Q: Times when divulging your methodology turned out not good?

A: *Stuart Thompson*: "Not good" probably usually just means a correction, which is still good. Competitors might pick up on the story.

Q: Hard sell to reproduce something rather than work on something new. Newer is better. How can we encourage "peer review" from other journalists?

A: *Stuart Thompson*: Core challenge for transparency, openness and open-sourcing. Need strong leaders who believe in it. Can have success iterating on old things.

*Chris Groskopf*: A story that's published with a really good explanation can often be localized. A form of peer review. Can't happen if we don't publish methodologies. Also publishing methodology implies a level of confidence.

Q: Types of projects you won't take on because they're too academic?

A: *Ryann Jones*: Special section of data store specifically for academics. Desire for the data from academic world is there, and we have desire to work with academics. 

Q: Analysis becomes a kind of source. Our explanation for that source is relegated to a nerdbox; we'd never do that with a "regular" source. Why are the stats things not treated with that same sort of attribution?

A: *Chris Groskopf*: I draw the line at generating primary source measurements. If we transform data, that's defensible. If someone here invented a sensor, it would need more backing.

*Stuart Thompson*: When we cite human sources, we don't go into a lot of depth about the person to give them that context (usually), and people aren't advocating that. Can be situations where methodology is crucial to understanding the findings.

Q: Investigative journalism comes from "healthy paranoia". Maybe we ought to think about protecting the work of all of us from a rogue actor. Explicit thinking about what our standards should be. Sometimes pays to think about the worst possibility that could happen.

A: *Chris Groskopf*: We've reached a critical mass in this industry where we needs best practices. As more and more people start documenting, it will be easier to point out when there are failures that standards weren't followed.

*Stuart Thompson*: Are we ready to do that? It may take something bad to happen before everyone wakes up.

Q: Where does reporting methodology/data endanger sources or communities? Confirmation of sources, watermarked data leading back to source, etc.

A: *Ryann Jones*: Sometimes we're forced to not release the data, or sign something saying "We're the only ones allowed to look at this data." Be open about why you can't share data. Can still probably disclose methods without identifying numbers.

*Aaron Williams*: Fight the urge to just find data and publish it right away. It is important to think about repercussions. Created a separate set of data to publish.