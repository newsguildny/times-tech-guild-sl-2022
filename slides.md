## Unionizing NY Times Tech Workers

### with bubbles and red paint

<!-- .slide: data-background="#ff4040" -->

Notes:

- Intros
- We work at the New York Times, and last year we helped organize the largest
  union of tech workers in the country
- There's an old saying in organizing: "There are no shortcuts in organizing".
  It's totally true; we had literally thousands of one-on-one conversations over
  2 and a half years before we had enough support to go public
- _Buuuuut_, that doesn't mean that there aren't speed boosts!

---

This is the story of how we built solidarity and support for a union with our
coworkers, told through the technology we built along the way

---

## What we built

<!-- .slide: data-background="#ff4040" -->

- A bubble chart generator <!-- .element: class="fragment" -->
- A website <!-- .element: class="fragment" -->
- A Slack avatar generator <!-- .element: class="fragment" -->
- A live vote count tracker <!-- .element: class="fragment" -->

Notes:

- A bubble chart generator, which allowed us to pinpoint with surgical precision
  where what parts of the organization we had and hadn't spoken to
- A website that allowed us to communicate to the world and to our unit
- A Slack avatar generator that allowed to show support and solidarity in a
  remote-only workplace
- A live vote count tracker that allowed us to have what was possibly the first
  ever fully public union vote count, and build excitement and engagement within
  our unit

---

### I ❤️ my job. But...

Notes:

- You work at a company where things are not going quite how you'd like.
- Maybe there's something big going wrong: maybe you're working long hours, and
  you never get to spend time with your partner.
- Maybe you're being forced to return to the office, after multiple years of
  successful remote work.
- Maybe it's a pizza party where your raise should be.
- Maybe it's just a series of frustrating working conditions that are causing
  low retention at your job. Nothing huge on its own...but things add up over
  time.

- Here's the rub: you love your job. You're good at what you do and you care
  about your co-workers, so you can't just quit. You want to make the company a
  better place to work, for you, for everyone...but what are your other options?

---

### POV: You're called into a furtive conversation with a coworker.

Notes:

- "Hey!" your friend says. "Can we talk?"
- You get pulled into a conference room, a phone call, or a zoom meeting...and
  your friend starts describing the same things you've been noticing.
- There are a lot of decisions being made for y'all at work, decisions that
  impact your lives, that you have no input into.
- You either have to negotiate with your manager yourself to get something
  changed, just for you...like permission to wfh, or you just have to put up
  with these policies.
- It would be really cool if there was some way to work together with your
  coworkers, to collectively discuss what would be best for people, and then put
  those policies into place instead, right?
- Sweet! That's what a union is!

---

## Organizing

Data-driven decisions

<!-- .slide: data-background="#ff4040" -->

Notes:

- You know that you want to work together with your coworkers to make the
  company a better place to work.
- There are a few different ways to do that, legally speaking, but the most
  important thing is to get everyone on board, working together. You need to get
  the largest number of people possible collaborating on this, to build strong
  solidarity

---

### The Goal

Map out union support across the company

Notes:

- Your goal: to map out union support across your entire organization.

---

### How much does someone support the union?

1. All in! Let's organize! <!-- .element: class="fragment" -->
2. Yes! Keep me updated! <!-- .element: class="fragment" -->
3. I need to know more <!-- .element: class="fragment" -->
4. I don't think so... <!-- .element: class="fragment" -->
5. Thank you, but no <!-- .element: class="fragment" -->

---

### PS: Don't get caught!

Notes:

- it's not illegal
- you're in fact protected in doing this!
- but it's strategic to get all of your ducks in a row before management find
  sout

---

### Time to phone a friend!

And ask them to phone some friends too...

Notes:

- What would it look like if you talked to everyone you worked closely with, and
  could trust to keep a secret?

---

##

<!-- .slide: data-background-image="dist/images/org-chart-1.png", data-background-size="contain" -->

---

##

<!-- .slide: data-background-image="dist/images/org-chart-2.png", data-background-size="contain" -->

Notes:

- you know people on your sister team - they're great, you talk to them
  regularly
- but that next team over works on something completely different...it's a lot
  harder to be sure how they'll respond.
- The other fun thing is that if I work on the same team as Shane, and I reach
  out to everyone I work closely with...most of those people are going to
  overlap with the people Shane works closely with!
- So you can get stuck based on just mutual connections.

---

##

<!-- .slide: data-background-image="dist/images/org-chart-3.png", data-background-size="contain" -->

Notes:

- There are parts of the company that are too far away for you to have any
  insight into them.
- Even with a rippling outward effect, you're going to run into roadblocks where
  people don't have connections.
- There are parts of your group that may be deliberately silo'd off, for
  practical or political reasons, which makes cross-collaboration harder.
- The first step is collecting all of the information about who works where.
- Nowadays, we have a handy online directory. There're some pretty strict
  policies about "appropriate use of work resources", and like I mentioned
  earlier...we didn't want to spill the beans by scraping the site...IT WAS
  FRUSTRATING!
- It was a slow process to pull in names of all of our coworkers regularly,
  tracking new hires and departures to keep our lists up to date.
- We did sort of a quilting bee situation, where people joined up in a zoom call
  and tried to make light work of it!
- We had it easy...in less digital times, I've heard of folks working retail,
  having to grab printouts of shift schedules from out of trash bins to collect
  this information!

---

### Why is the org chart so important?

Notes:

- And this is so, so important: in the Amazon warehouse in Bessemer, one of the
  big issues the workers faced was that they had no idea how many people would
  be grouped into their prospective union. They showed up for a card count, a
  union verification step where you need to have proven support of more than 30%
  of the group in order to prompt an election, expecting the total group size to
  be roughly 1500 workers.
- Amazon responded that there were actually 5800 workers.
  - "fifty-eight hundred"
- This large difference in total workers quadrupled the number of supporting
  card signers needed to trigger the election process to begin!

---

### The humble spreadsheet

<!-- .slide: data-background-image="dist/images/dataviz-spreadsheet.png", data-background-opacity="0.4" -->

Notes:

- This is where all organizers start - you have to dump your data somewhere.
- However, we had 600+ people we were keping track of, and this got unteneble
  fast.
- We needed to track a bunch of fields for each chart, and however many filters
  and conditional formatting in the world couldn't distill it down to something
  usable at a glance

---

## d3

Tried and True Data Viz

<!-- .slide: data-background-image="dist/images/dataviz-d3-simple.png", data-background-opacity="0.4" -->

Notes:

- This wasn't the best, but it was functional! And better yet, I didn't have to
  code any visualization.
- I wrote some quick python processor to crunch our spreadsheet into usable
  format and generated files with hierarchies and colors specified.
- I stole code for this super simple force-repelling graph from the internet,
  and just...let it do its thing.
- Colors are hopefully sort of obvious, if not color-blind friendly:
  - the greener, the more pro-union
  - the redder, the more anti-union
  - greys are both 3s AND unassessed, and you can maybe start to predict from
    there some of the issues we saw almost immediately
- But! We were able to see the patterns, including which parts of the
  organization we didn't have data on or didn't have support in yet. This was
  invaluable in helping us decide who to talk to going forward.

---

## More d3

Overloaded and Confusing

<!-- .slide: data-background-image="dist/images/dataviz-d3-overloaded.png" data-background-opacity="0.4" -->

Notes:

- The thing is, our spreadsheet was getting more and more complicated. It wasn't
  just "What number?" but now we wanted to track things like "who signed a
  card?" and "Who participated in our latest action?"
- So, uh, I added more colors.
- This was really bad. Super bad. No one could read it.
- Worse, you can't easily print from d3
  - so either folks had to run this on their own computers
    - not an option for our non-engineering bretheren
    - really annoying for engineers who don't use python or javascript, tbh
  - OR they had to look at my terrible screenshots, way zoomed in so you could
    read the names...and therefore you couldn't pan around to see the whole
    image.
- Like I said, VERY BAD!

---

## The Bubble Chart

Shay reorganizes the chart

<!-- .slide: data-background="#ff4040" -->

---

##

<!-- .slide: data-background-image="dist/images/dataviz-bubble-v1.png" data-background-size="contain"-->

Notes:

- All credit to our coworker Shay Culpepper - I asked if she could figure out
  how to export the image, and she revolutionized how we displayed the data in
  the process!
- She realized that we don't need any information about the managers, and
  removed all of their nodes.
- As a result, all of the branches that took up so much space were removed too,
  making it far more readable
- Instead, each nested bubble represented a layer of management
- Her tool also allowed us to easily change color based on different parameters.
  Instead of just 1-5 assessments, we colud now look at "who doesn't have an
  organizing contact?" and "how long ago were they last contacted about the
  union"?

---

##

<!-- .slide: data-background-image="dist/images/dataviz-bubble-site.png"  -->

Notes:

- (we can cut this slide if we want!)
- Shay actually spent time making a shiny interface for this as part of a
  master's thesis and now there's a slick online interface for uploading CSVs
  and stylizing a whole bunch of facets in the display!
- But that came much later, so let's get back to the timeline at hand!
- maybe put this somewhere? At the end? After this? TKTK -
  data-for-power.shay.dev/
- TIMING - 11:30 - bubble chart
- TKTK - why are these notes weird?

---

## Going Public

Building nytimesguild.org

<!-- .slide: data-background="#ff4040", data-background-size="50p"-->

---

### What is going public?

- First impression on the world outside your unit
  <!-- .element: class="fragment" -->
- First chance for management to publicly respond
  <!-- .element: class="fragment" -->
- First real test of the strength of your organizing
  <!-- .element: class="fragment" -->

Notes:

- Unionizing is a political action. Some of the leverage that unions have comes
  from support from outside the company. A campaign has a lot more power if, for
  example, reader of the New York Times are supportive of the position of the
  unit
- Management can't really directly address the campaign until there's a public
  campaign to address. Once we went public, we knew that management would likely
  almost immediately begin a counter campaign
- You might have a lot of folks (in our case, a lot a lot) willing to say they
  support unionizing behind closed doors, but there's no way to learn how well
  that will translate to public support until you go public

---

### What does a public compaign website need?

- Personality <!-- .element: class="fragment" -->
- Information <!-- .element: class="fragment" -->
- Flexibility <!-- .element: class="fragment" -->

Notes:

- So one of the tools we decided to develop to help us go public was a website
- The first two jobs are jobs that every website has:
  - Make it clear the tone ond personality of the website owners
  - Provide information in a structured and accessible way
- We also needed to be able to change the content somewhat rapidly. Things
  evolve quickly when a campaign is launched, and we need to be able to keep
  everyone up to date!

---

### Requirements

- Approachable for developers <!-- .element: class="fragment" -->
- Accessible to non-developers <!-- .element: class="fragment" -->
- Reliable and fast for readers <!-- .element: class="fragment" -->

Notes:

- We based our technology choices on requirements that we derived from the goals
  above
- People are busy, and union work is essentially a second, unpaid job. We can't
  rely on availability of long-term contributors; it has to be easy to onboard
  new developers and for folks to make changes when no developers are available
- And websites are no good for anyone if they're not accessible to as many
  people in your audience as possible!

---

Approachable for developers

### Next.js

Notes:

- Our frontend developers almost exclusively develop with React, and a bunch of
  our systems use Next.js
- Next.js is also pretty "batteries-included" for a React framework. It doesn't
  have a huge learning curve.

---

Accessible to non-developers

### Netlify CMS

Notes:

- This had a nice balance of being very easy to set up on the development side,
  supporting static site builds, and being very accessible for non-developers
  that wanted to work on the site content
- We could rapidly prototype and build custom components for the CMS that
  supported even fairly complex UIs, like an FAQ accordion with nested markdown
  contents, with some regex and a React component.

---

Reliable and fast

### Next.js static export & Netlify CDN

Notes:

- Next.js has a static export feature that builds out a fully static version of
  the site, removing the need for a backend application server.
- Netlify CMS has built-in support for Netlify's Identity service for user
  authorization and authentication, so Netlify CDN was a natural choice for
  static file hosting
- The result was a fairly low-weight, fast website, easily accessible anywhere
  in the world

---

### Our first test

Testimonials

Notes:

- One of the first use cases for the website was to add a huge list of
  testimonials from everyone in the organizing committee on why we were
  supportive of a union

---

# B+

<!-- .slide: data-background-image="dist/images/testimonials.png" data-background-size="contain" data-background-opacity="0.4" -->

Notes:

- This went alright! An engineer other than myself was able to contribute pretty
  significant amounts of code, and it was super easy to import all of the
  testimonials that we got as markdown files
- I still had to be really heavily involved in the development though.
- We encountered a previously unforeseen issue: Building this highlighted
  testimonials widget was a fun new challenge in JAMstack land

---

### A Mulligan

Frequently Asked Questions

# A-

Notes:

- Way better. First pass was implemented entirely by another engineer, and
  adding full markdown supported added with myself and yet a third engineer in a
  pairing session
- The actual contents of the FAQs were edited by several people across the unit

---

### The Big One

Copy-editing

# A+

Notes:

- Another member who hadn't been involved with the website at all before this
  point was able to copy-edit the entire website from the CMS! No one needed to
  make any code changes at all.
- This is what we'd been after from the start

---

<!-- .slide: data-background-image="dist/images/website.png" -->

---

## Public Support <!-- .element: style="width: 600px; margin: auto; color: #ff4040;" -->

<!-- .slide: data-background-color="#ff4040" data-background-image="dist/images/guild-frame-square-1.png", data-background-size="contain" -->

---

### The First Request

Voluntary Recognition

Note:

- The first thing that happens when a unit goes public is that we ask management
  to voluntarily recognize us.
- Throughout the campaign, we'd been gathering hundreds of signed cards from
  coworkers that were supportive of the union
- It's in everyone's best interest for management to just say yes, but they'll
  only do it if it feels like a vote would be redundant anyway

---

### It's not enough to have the numbers

We also have _look_ like we have the numbers!

Notes:

- We needed a way to make it obvious to management how much support we had,
  which was a lot
- Buuuuut no one was in the office!

---

### Attempt #1

Google Slides, and a lot of documentation

Notes:

- Like any good, scrappy product, the first step was to actually figure out what
  we wanted to build
- Started with a mock from a designer in Google Slides. Each slide was a
  template, and you could add a photo and then export the slide as a new picture
- Then, everyone could have a nice Guild frame around their Slack avatars!
- Slack avatars are super visible when everyone's remote
- Even for very technical users, this was too many steps to follow

---

### Attempt #2

Olov has an idea

Notes:

- An engineer, more or less on a whim, decided to make a super rough tool to
  make the process easier
- The idea isn't new; people used to make these all the time in early social
  media days
- Cut out as much complexity as possible: no server, no database, all static
  files, free hosting (surge.sh)

---

### Swarm

Fun ideas have their own gravity

Notes:

- Another engineer (Romina), and another designer (Riley) were excited enough
  about the idea to hop in and help out
- Designer had the idea to support preview, and show all of the frames at once,
  try out new photos from the same page
- Romina implemented the new design

---

<!-- .slide: data-background-image="dist/images/slack-avatars.png", data-background-size="contain" -->

---

## Vote count!

Notes:

- At the start of 2022 we had a vote with the National Labor Relations Board, to
  determine whether our group wanted to form a union.
- The build up made heavy use of the bubble chart, but once the ballots had been
  mailed back, there was very little to do, except for sit around anxiously.

---

### The Elections Tracker

Building excitement to build community

<!-- .slide: data-background="#ff4040" -->

Notes:

- PSYCH!
- No NYT election would be complete without an elections tracker!
- Don't worry...we didn't implement a needle.
- Building this tracker was fast and fun, but this was also working towards our
  goal of building community
- this isn't just community for our tech unit, but building excitement amongst
  our soon to be fellow NewsGuild members, the labor community, and the tech
  community as a whole!
- We couldn't let people into the Zoom call, where the Board agent read
  envelopes one at a time, but we _could_ put up a live feed of the votes as
  they came in

---

##

<!-- .slide: data-background-image="dist/images/shane-bravado-1.png", data-background-size="contain" -->

Notes:

- Roughly two weeks before the vote count, I woke up one day and said WE NEED A
  VOTE TRACKER
- I'm a backend dev, and I don't know how to put the pieces together to do this!
  Thankfully I work with amazing folks, who were equally excited about the idea

---

### That turned out to be true

Notes:

- We had the website itself set up already, so we were just putting up an
  additional page.
- As you can see, Shane jumped in to save me, and we recruited a handful of
  people to get the other details worked out:
  - Jeff - another engineer
  - Riley - the designer from all of the above projects
- It was literally an hour to hook up the main components, then a bit more time
  to prettify it

---

### Firestore

Notes:

- TKTK technical details

---

### The Day of the Vote Count

Notes:

- The NLRB agent had a stack of hundreds on envelopes and read them out, one by
  one, holding them up to the camera to show them off
  - YES, YES, NO...
- the vote count process is a bit complicated, because both we and mgmt have the
  option to contest ballots...but at the end of the day we needed 50%+1 yes
  votes out of the total submitted ballots

---

##

<!-- .slide: data-background-image="dist/images/vote-ct-tally.png"-->

Notes:

- You heard it here first! We manually incremented the vote counts as they were
  read off.
- We didn't have time to write a wrapper to increment and decrement the votes,
  so it was harder than it should have been!
- I manually typed in new values every time we heard a result, and the tracker
  updated in real time
- opt - I did make a typo once that said that we won by like three times as many
  votes as we have members, so, uh...whoops.

---

##

<!-- .slide: data-background-video="dist/images/confetti.mp4" data-background-size="contain" data-background-video-loop="true" -->

Notes:

- wub

- opt - Did I cry when we won? Yes I cried, everyone was crying. Did that make
  it super hard to keep typing numbers into the small box? YES, VERY MUCH SO.
- But the confetti was worth it, even if we had just seen it fifteen minutes
  before when I made that typo!
- Our coworker Joe put that together, and you can still activate it on that page
  of our site if you go click on the little tada emoji!
- And of course, having a union was also worth it! We immediately started to
  switch gears and begin the more difficult work of building up our union's
  democratic structures and gearing up for our first contract campaign!

---

## There are No Shortcuts in Organizing

<!-- .slide: data-background="#ff4040" -->

Notes:

- Our organizing efforts were built on many dozens of people having a total of
  many thousands of one on one conversations with our coworkers. There's no real
  way to build connections, to build solidarity, to build community without
  getting to know each other.
- You need to know what people want to improve. And you need to know why, what
  it is about each issue that makes it so important to them.
- There was no bit of technology that we built or used during those years, or
  today when we've had a biiiiiit more time to think things through, that could
  have replaced these conversations.
- Like organizers have been saying for decades, there are no shortcuts in
  organizing...you have to have the conversations, and you have to build the
  relationships.

---

## Questions?
