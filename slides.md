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

### What if alignment came for free?

Notes:

- Before we dive in to the fun stuff, imagine for a moment, a world where you
  never had to hear the word "alignment" ever again
- Maybe you're a product manager, and you spent all of last week trying to
  figure out why your colleague seems to have a completely different definition
  of "scalability" than you do
- Or maybe you're a designer, and you can't figure out why that product manager
  keeps talking about "scalability" when you bring up how there are over a
  hundred slightly different blue buttons in your app
- One theme that we kept noticing is that collaboration just kept sort of...
  happening!
- Because we were all working toward a shared goal, there was never an
  "alignment" phase of the work; everyone improved on everyone else's ideas, and
  we were able to iterate super rapidly

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

<!-- .slide: data-auto-animate -->

---

### What does a public compaign website need?

- Personality <!-- .element: class="fragment" -->
- Information <!-- .element: class="fragment" -->
- Flexibility <!-- .element: class="fragment" -->

---

### Requirements

- Approachable for developers <!-- .element: class="fragment" -->
- Accessible to non-developers <!-- .element: class="fragment" -->
- Reliable and fast <!-- .element: class="fragment" -->

---

Approachable for developers

### Next.js

---

Accessible to non-developers

### Netlify CMS

---

Reliable and fast

### Next.js static export & Netlify CDN

---

### Lesson #1

People are busy

Notes:

Turns out, the hardest part of building a website for your union is the same as
the hardest part of buliding the rest of the union: organizing!

The first issue we had was actually getting enough people to dedicate enough
time to get something working.

Over the course of about 5 months, we worked in small spurts, usually one day at
a time

---

### Our first test

Testimonials

# B+

<!-- Gonna keep going here, just taking a break for now -->

---

## A Show of Solidarity <!-- .element: style="width: 400px; padding-left: 250px; color: #ff4040;" -->

<!-- .slide: data-background-color="#ff4040" data-background-image="dist/images/guild-frame-square-1.png", data-background-size="contain" -->

---

### The Big Question

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
