# Which chart should I use, and why? Information design for the human brain!

*Friday, 11 March 2016, 10:15 a.m.*

We'll explore how research into the ways people estimate numbers will change how you think about choosing charts to tell your stories. (And, no, it doesn't mean everything is a bar chart.) We'll also talk about using color and animation in ways that the human brain understands - intuitively.

* Peter Aldhouse, BuzzFeed News
* Alexandra Kanik, Mediashift

## Visualization = encoding data by visual cues

*Peter Aldhouse*

[presentation link](http://paldhous.github.io/NICAR/2016/infodesign.html)

* Length
* Slope
* Color hue
* Volume
* Angle
* Length (aligned)
* Area
* Color intensity

### Brains don't treat these equally

From most accurate to least (to encode numbers):

* Length (aligned)
* Length
* Slope/Angle
* Area/Color Intensity
* Volume
* Color Hue

**Doesn't mean everything's a bar chart**

### Comparisons: Change over time

* Column chart - length encodes differences
* Line chart - slope encodes rates change over time
* Dot and line chart - combines slope and position
* Dot-column chart - basically the same as column

### Case study: Immunization in California kindergartens

#### Aggregated
Length on aligned scale
Slope, y-axis doesn't start at zero.
Dots and line, start axis at zero.

#### Several counties
Bars are hard to read.

Dot and line is better. But too busy. Too many lines, too few colors.

Solution: Color intensity. We've lost a bit of ability to compare, but gained ability to see the whole overview. It's a compromise.

#### Every school

Position on aligned scale and area. Accepting the idea that people won't be able to see individual school data, but get a bigger picture.

### The Color Wheel

Using color: Fit it to the data

* Qualitative
* Sequential
* Diverging

Use Colorbrewer, helps avoid excluding colorblind folks.

## The Importance of Color

*Alexandra Kanik*

[presentation link](assets/07-information-design-ak.pdf)

Storm Surge map using rainbow color scale, you don't know it's water unless you know it's water (aka the color scheme doesn't help you understand).

Blue with color intensity instead supports the conceptual material.

"Don't make people's brains work harder than they have to."

Political map using common colors for parties makes your brain work less hard than using ad hoc colors.

### The Stroop Effect

Brain reads words quicker than the color the word is printed in.

## Spatial vs. Sequential

NYT Olympics Finishes in chart and sound

Spatial: Dots on a line
Sequential: Sounds played one after the other

Animated GIFs are sequences

## Q&A

Q: Kindergarters w/o immunizations, better to do percentage w/o or w?

A: Two reasons: Smaller numbers are easier to see the difference, also what we care about is the number who *didn't* get the vaccine. Sketch, experiment, try it a lot of different ways.

Q: How do we process whitespace around graphics?

A: Consider data ink/pixels (Tufte). Annotation is also important — sparse but informative. Lack of whitespace can contribute to confusion and anxiety.

Q: Horizontal bars vs. Vertical bars

A: General rule of thumb: If you're comparing few things, columns might be best. Time is usually from left to right. If you have a lot of things to compare and it's not time, horizontal bars can be more compact.

Q: How to sort data sets? How does that change interpretation?

A: Clarity is key. Goes back to the question "what do you want to show?" Alphabetical makes things easy to find. There's usually not a single answer.

Instead of thinking "I've got this data, what's the chart?" think "I've got this data, what's the story?"

Overall message: Make it easy for people. If you've worked with data for a while, your visual literacy is probably above average.

Q: Using blue for water, would you consider changing red to signal danger?

A: Goes back to purpose. If you were trying to create a warning, that might make sense.

Q: Advice for journalists who are not coders to do visualizations.

A: [Datawrapper](https://datawrapper.de/). [Tableau](http://www.tableau.com/) is good for exploratory, has sensible defaults. [Plot.ly](https://plot.ly/) is easy to use. [Google Charts](https://developers.google.com/chart/) can be ok.