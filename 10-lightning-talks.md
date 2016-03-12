# Lightning Talks

*Friday, 11 March 2016, 4:45 p.m.*

Sometimes you don't need 45 minutes to explain a useful technique or interesting resource. Join your colleagues for a session of short (5-minute) talks about doing CAR, Web development or other related topics.


1. I Improved My Math Fluency, And So Can You — Ryann Grochowski Jones
2. Solve Every Statistics Problem with One Weird Trick — Jonathan Stray
3. Let lookup save you from the boring, repetitive work you've forgotten you're even doing — Chris Groskopf
4. Automation in the newsroom — Ariana Giorgi
5. Regular Regular Expression Exercises for Regular People — Dan Nguyen
6. Map tiles are dead; Long live (vector) tiles! — Ken Schwencke
7. How to read 52 books in 52 weeks — Nicole Zhu
8. What I learned working on Failure Factories — Adam Playford
9. Let's Talk About the Future of Interactive News Content — Gregor Aisch
10. Cats and Stats — Jennifer LaFleur

## I Improved My Math Fluency, And So Can You

*Ryann Grochowski Jones, Pro Publica*

I hated math because I wasn't good at it.

One of the reasons I became a journalist was so I would never have to do math again.

Math is like a foreign language -- I may be able to learn enough to be comfortable.

1. If books are your thing, read books. "Language comes naturally, math does not. …My brain is more comfortable thinking in words than in numbers."

2. Get out the pencil and paper. Figuring it out yourself helps. Not something you do on deadline.

3. Use recall. Do things over and over, then use your memory. Recall is like a workout for your mind.

4. Take a hike. Take a break and come back.

5. Chunk your learning.


## Solve Every Statistics Problem with One Weird Trick

*Jonathan Stray*

There's a better way with a newfangled device I like to call a computer.

Resample. Reduce.

Margin of error. If we could repeat the survey many times, we could just look at the distribution.

Resampling works even if your data isn't normal.

Significance testing.

Is one classroom better than another?

T-Test? No.

Things that dpeend on the class they're in, things that don't. Only use the second one. Permutation tests.

Insider trading.

Put your data in the grater.

Scramble trades through time, see who got really lucky.

Gravity waves.

Compare random data between detectors between instruments to find the probability of seeing a single that large by change.

Reduce your frustration, reuse your data.

## Let lookup save you from the boring, repetitive work you've forgotten you're even doing

*Chris Groskopf*

Wireservice is umbrella project for csvkit and agate. Agate is a data analysis library.

We're wasting so much time.

Not on Twitter or comments or flamewars. On mapping postal codes to state names. We're wasting 14.8 years.

The madness must stop.

Lookup!

Structured repo of lookup tables.

.csv has data, .yml file is metadate.

Agate-lookup.

States, ISO, NAICS, CPI.

~~VLOOKUP~~
~~LEFT JOIN~~
~~Bespoke Scripts~~
**lookup**

## Automation in the newsroom

*Ariana Giorgi*

Writing scripts or programs to streamline projects or increase productivity.

1. Finding stories
2. Collecting data
3. Writing short stories

* I will have to repeat this action in the future
* It's clear and straightforward what I'm looking for
* Doesn't involve much interpretation
* Info is consistently presented the same way.

### Finding stories

* Alerts
	* New documents
	* Updated data
	* Twitter feed
* Essential for focusing on breaking news
* ProPublica uses IFTTT for nonprofit explorer
	* Tracks updates for new documents, rss feed
	
### Collecting data

* Write parsers for data that's grabable

	```
	<p>Name</p>
	<p>John Smith</p>
	```
	
* Don't bother if it's not straightforward
* Anything interprative: Assigning yes/no or longer
* Machine learning: By the time you train it, you could've read it.*

### Writing short stories

* Not longwinded
* Focus on the facts
* Quakebot!
	* Collection was consistent
	* Eliminates time for reporter to gather info
	* Frees up reporter's time
	* Important info was already out the door.

## Regular Regular Expression Exercises for Regular People

*Dan Nguyen*

What can we find with regex? Patterns in text (so maybe stop turning text into data).

Love

Words that begin with a word

Words that begin with a letter

Every word over a length

Lines without a character.

Regex from command line with grep or ack or ag

Search all the files in all the folders

Use the Twitter API to move data from twitter to plain text -- but not to a spreadsheet yet.

Can find all the hashtags. Who do they mention. Who do they most frequently mention.

Match dates, use CSVkit.

Messy text, Hillary Clinton's email.

Search for confidential or secret.

FEC data too big for excel. 

## Map tiles are dead; Long live (vector) tiles!

*Ken Schwencke*

What's a map tile? Chunk of a map.

2010 census data, one dot per person, nationally.

Great, but one problem. Takes forever to render.

Vector tiles!

They're data, like little pieces of GeoJSON. Each square only contains the data in that area.

Vectors scale, you don't need one for every zoom level.

Make tiles: **Tippecanoe**

Serve up mbtiles file: **Tessara**

Can cache with varnish.

Every pool in LA County.

Every street sweeping sign in NYC, by day.

Vector files are rendered on the fly.

Mapbox -- metered
Mapzen -- free


## How to read 52 books in 52 weeks

*Nicole Zhu*

Why?

* Brain exercise
* See something through
* Be more interesting

When life hits you in the face:

Find a routine and make it stick.

* Carry a book around all the time.
* Don't finish books you don't like.
* Read multiple books at once.
* Keep it private.
* Read what interests you.

**Do whatever works for you.**

Tracking in a spreadsheet.

I wish I had more time to ________.

* Set quantifiable goals
* Make time for it
* Be accountable
* one day at a time
* no good time to start
* be kind to yourself

Go tackle something crazy.

## What I learned working on Failure Factories

*Adam Playford*

How I want to spend my time looking forward.

Great stories always trump great technology.

It was cool. Also totally useless.

Took way too long to decide to kill it. Seduced by technology.

Innovation & Risk.

Most ambitious web efforts should align with most ambitious journalism.

"True North"

You have to bring your compass with you.

Don't have philosophical thoughts halfway through.

Accept some inefficiencies, encouraging people to be generalists.s

Inefficiency (time)

Necessary (quality)

Next steps:

Putting graphics people into traditional reporting roles. Spend time on the technology for the story not technology for yourself.

## Let's Talk About the Future of Interactive News Content

*Gregor Aisch*

We call all kinds of things interactive. Everything is interactive?

Is it interactive when it takes a bunch of code to create?

Heart of interactivity is interaction. Human communication is an example.

Snowfall, slider, swiper = someone talking at you all the time. Grown up version of a picture book. All you do is turn the page.

Puzzles!

You have to write the words, trust that computer will understand, computer trusts you to write words.

Humans try to be smarter than the computer, we reply with humor.

Interactions are mostly about building relationships. If the interaction is fun, they might become friends.

Quartz mobile app, chats the news.

## Cats and Stats

*Jennifer LaFleur*

The data ladder: CATegorical, continuous

Dichotomous variables, on or off

Categorical: Color, Male/Female

Continuous: Age, height

Distribution: Normal, wide, skinny

Skew: Negative skew, positive skew

Paired tests, correlation

Regression: Dietary intake vs. ammonia excretion

Sampling, sampling error

Indexes

Tips: Study, do your homework, examine your work closely, talk to experts, get plenty of food and rest, repeat your work, remeber: You can do it.