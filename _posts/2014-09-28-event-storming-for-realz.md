---
layout: post
title: Event Storming for realz
tags: [event-storming, experience-report]
published: false
---

After last times [Event Storming exercise](/2014-07-12-event-storming-exercise) I was anxious to do it again. 
And as luck would have it, an opportunity arose soon after.

Friend and colleague Tom Toutenel asked me if I could facilitate an event storming session for one of our newly won clients. I was, of course, happy to oblige.

## Context

Tom explained that his team wanted to pick the brains of our client so they would get a shared understanding of what they need to build. Preferably in a "Storymap". And if possible, define a first "Story" to start their sprint in the week after the storming session.

Another noteworthy fact: a considerable amount of effort by the client had been put into making a thorough analysis of what needed to be done. Eventhough this effort is worthwile, this prompted me to make sure that the group wouldn't limit themselves too much by the obtained knowledge.

## Preparation is half the battle

As you might imagine, I wanted to prepare properly since I'm dealing with an actual client. Neither a pet project, nor another exercise. So I revisited my previous blog post, more specifically all Alberto's answers. And I checked the notes I had written down the first time I tried event storming again.

### Pointers I wrote down

I've been using a mini todo-board in my "journal" with mini post-its and the tasks I made for myself were the following:

* Have Stickies, Sheets and Sharpies for every participant
* Prepare room (I had no paper roll, so I sticked 15 sheets of flipchart paper in "landscape mode" to the wall with painters tape)
* Introduce yourself
* Check their expectations
* Give context: EventStorming = What?, Tackle specific problem
* Put up Events; past tense, start in the middle, extend space if necessary
* Is Domain Expert interested in Event x? (To solve issues with granularity)
* Put up Commands + external systems (note to self: look for hotspots)
* Event to Event is ok: "Person had a birthday --> Person reached pensionable age"
* Take note of gestures ("moving", "pointing", "cutting")
* Make UI cards with screens if helpful
* Ubiquitous Language!

## Silence before the storm

As I was preparing the room with flipchart sheets and "superstickies" that would serve as the colorcoding legend I got a little nervous. I got a little mental checklist loop going to gain some confidence.

* Are they stuck in the same discussion?
* How are we doing on time?
* Is everyone still interested?

## Introducing: the participants

In the blue corner we present to you our client, a big contender in belgians electricity market, bringing in a total of 3 persons. *I picked different names, to preserve their anonymity.*

````
Lommy, the functional analyst.
Leonard, the architect.
Lionel, the project lead, aka the product owner.
````

And in the red corner, hailing from camp Cegeka. *I make these up, these are their actual names. A trio of Toms. A TomTrio. A Tromio?*

````
Tom T., the team lead.
Tom C., the scrum master/customer proxy.
Tom B., the developer.
````

All these people are going to work together in the hours ahead, to create a shared understanding of what problem they want to solve together.

## No hiccups

After explaining who I was, and what my role was going to be in the next hour(s), I explained Event/Model Storming in short and what the rules of the game were. Everyone then proceeded to post Events on the sheets of paper. No buts, no arguments, everyone was in the same boat and understood the value of having a shared understanding.

There were only a few instances in which Events were not in past tense, and those were quickly fixed once I pointed it out.

Lommy, *the functional analyst*, went back-and-forth between stickies and his laptop. This told me that he was posting events that were a little bit biased. Most of the time though, other participants had already posted similar events. Which confirmed understanding of both participants and informed me that this bias was negligible. He IS the *Domain Expert* after all.

## Ubiquitous Language

Especially after they started posting External Systems it appeared that there were some issues in the word choice. It appeared that naming External Systems and their actors went particularly well and was clear to everybody. However, once events came in to the problem domain, wording started to get a little fuzzy. Lommy, Leonard and Lionel were all using different words to describe the same events. Which caused a lot of confusion for our Tom Trio.

This is where I noticed immediate benefit of Event Storming: stuff like this usually appears when you get to that bit of the solution.

## Hotspots

## Facilitating "aha-moments"

## Conclusion

## Doing it better next time