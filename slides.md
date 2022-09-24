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
- Maybe it's a series of frustrating working conditions that are causing low
  retention at your job. Nothing huge on its own...but things add up over time.

- Here's the rub: you love your job. You're good at what you do and you care
  about your co-workers, so you can't just quit. You want to make the company a
  better place to work, for everyone...but what are your other options?

---

### POV: You're called into a furtive conversation with a coworker.

Notes:

- "Hey!" your friend says. "Can we talk?"
- You get pulled into a conference room, a phone call, or a zoom meeting...and
  your friend starts describing the same things you've been noticing.
- {{tiny tiny description of a union, no details}}

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
  policies about appropriate use of work resources, and like I mentioned
  earlier...we didn't want to spill the beans by scraping the site
- It was a slow process to pull in names of all of our coworkers regularly,
  tracking new hires and departures to keep our lists up to date.
- We did sort of a quilting bee situation, where people joined up in a zoom call
  and tried to make light work of it!
- We had it easy...in less digital times, I've heard of folks grabbing printouts
  of schedules from out of trash bins to collect this information!

---

### Why is the roll call so important?

Notes:

- And this is so, so important: in the Amazon warehouse in Bessemer, one of the
  big issues the workers faced was that they had no idea how many people would
  be grouped into their prospective union. They showed up for a card count, a
  union verification step where you need to have proven support of more than 30%
  of the group in order to prompt an election, expecting the total group size to
  be roughly 1500 workers.
- Amazon responded that there were actually 5800 workers.
- This large difference in total workers quadrupled the number of supporting
  card signers needed to trigger the election process to begin!

---

### The humble spreadsheet

<!-- .slide: data-background-image="dist/images/dataviz-spreadsheet.png" data-background-opacity="0.4" -->

Notes:

- This is where all organizers start - you have to dump your data somewhere.
- However, we had 600+ people we were keping track of, and this got unteneble
  fast.
- We needed to track a bunch of fields for each chart, and however many filters
  and conditional formatting in the world couldn't distill it down to something
  usable at a glance

---

## Tried and True Data Viz: d3

Notes:

- this is why it was bad tktk

---

## The Bubble Chart

Notes:

- All credit to our coworker Shay Culpepper

---

## Going Public

Building nytimesguild.org

<!-- .slide: data-background="#ff4040" -->

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

<!-- Add a photo of someone's Slack with all of the Guild avatars -->

---

## Vote count!

Notes:

- At the start of 2022 we had a vote with the National Labor Relations Board, to
  determine whether our group wanted to form a union.
- The build up made heavy use of the bubble chart, but once the ballots had been
  mailed back, there was very little to do, except for sit around anxiously.

---

### Coding up an Elections Tracker

Building excitement to build community

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

### TKTK title?

TK image of the slack "I can do this in an hour"

Notes:

-
