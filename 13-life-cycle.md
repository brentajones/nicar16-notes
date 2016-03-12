# The life cycle of a news app

*Saturday, 12 March 2016, 11:30 a.m.*

A news app needs planning, care and feeding. If you design an app that needs to be updated, you can’t always count on government agencies maintaining the same format. This panel will give you some tips for designing apps in a way that will keep them alive: How to care for them and how to make those difficult end-of-life decisions.

* Scott Kline, ProPublica
* Jacqui Maher, BBC
* Jolie McCullough, Texas Tribune
* Jennifer LaFleur, Reveal/CIR

## Anitpatterns

*Scott Kline*

"Abandon in place"

1792, Freeman's Journal.

1998, San Jose Mercury News — Animal transactions. Now redirects to homepage.

1998, AJC — Nursing home guide. Now 404s.

2002, The Nation — Death Row calendar. 404s.

2005, Chicago Crime. Redirects.

2005, Washington Post — Congress votes database. Abandoned in place. "This page has been archived."

2009, NYT — Toxic Waters Project. Still there.

## Texas Tribune News Apps Updating Challenges

*Jolie McCullough*

### Government Salaries Explorer

Very time consuming, but still important. It's documented, anyone on the team learns.

Comes in all different data sets, they've developed a method to not update by hand.

### Prisons database

Data all comes from the same place. Still needs processing.

### Newer updates (how they're starting to think)

#### Faces of death row

Updated whenever death row changes

Google Spreadsheet-based

#### Public School explorer

Didn't really think about how to update it for the future, so it was recently re-built and documented.

Upload CSV files from education department.

### Apps with a set lifespan

#### Texas Legislative Guide

Per legislative session, not ongoing.

You have to set limits. How much of the long tail are you going to try to catch.

#### Disappearing Rio Grande

Followed a photographer along the river. Django App. Reporter and photographer updated it daily. Then converted to static HTML after project ended.


## Cycle of a news app

*Jacqui Maher*

"What is a 'News App', exactly?"

Articles start in CMSes.

What's the scenario?

"Just because you have a CMS doesn't mean you'll be able to edit everything on your website." — Mike Rastiello

"Interactive" "News Apps"

Like what?

* Repeated coverage of regular events — Olympics, sports, Elections
* Reacting to breaking news events — death of bin Laden, Haiti Earthquake

Most require a flipside — user-facing + a way to publish (maybe an admin?)

Literally hundreds of admins.

Searching for news apps on news sites is hard.

Extensive article posted through CMS? Could have been a news app.

Guantanamo Docket.

What if we treated our full story of the Islamic State as a news app, with updated info instead of having multiple disparate versions of stories?

"About the data" section

Times missed the Flint water story. If they'd kept the toxic water story up to date and devoted resources to it they might have caught it.

## Questions

Q: Are expectations for interactives or apps different from articles? E.g. removing names from stories later.

A: *Jolie McCullough*: Definitely. They update the database once a month with information from the corrections department. Also includes the date it was last updated.

*Scott Kline*: Doctor databases. They're concerned with phone number and address. Changes have to be remembered somewhere. They have a config file. Also make it clear who to contact in case of errors.

Q: Databases with criminal info, once you decide to stop updating, how do you deal with updates? Do you take databases down?

A: *Scott Kline*: Databases of nurses being disciplined. It's old now. "The facts are still the facts. Design plays a huge role." Make it less sensationalistic. Make sure the date is prominent.

Q: What are some design considerations for archiving an app that wasn't designed for it? Pagination, forms, etc.

A: *Jacqui Maher*: Case by case basis. Replicate functionality using simpler tools. Figure out what's still relevant.

*Scott Kline*: It's a rabbit hole. It's not just search — external APIs for example. "You shouldn't decide when you're making a piece of journalism to let the technology tell you what to do." Preparing for baking is not such a hardship that you must limit your creativity.

Q: Suggestions for knowing when your old apps are broken? Audits? Ability for self-monitoring apps?

A: *Jacqui Maher*: You can put in some monitoring, dashboard. Airbrake.

Q: Communicating updates to readers?

A: *Jolie McCullough*: Social media, posts on CMS. Prominent updated timestamp.

Q: How do you structure projects from inception?

A: *Scott Klein*: Bailout project started as spreadsheet on reporter's computer. Reporter got invested in story, keeps updating it. Make good tools for reporters so they can keep it up.

*Jolie McCullough*: Same with death row app. Personal investment.