---
layout: post
title: The Lead Developer Conference
tags: [experience-report]
published: false
---
## The Lead Developer what now?
The Lead Developer conference, or at least the one I went to, was held on the 23rd and 24th of June 2016, in the Queen Elizabeth II Centre in London, during the _Brexit_ vote.

It's a conference mainly about "that other part" of a job as programmer, namely working with people.

I can **highly** recommend this conference to anyone. It's not just for developers; scrum masters, managers, and other roles can all benefit from the abundance of information shared at this conference.

All the slides can be found on the [conferences website](http://2016.theleaddeveloper.com/blog/2016-06-23-slides-from-the-lead-developer-2016), but I link to the specific slides (and my notes) in the short bits I write about the talks below.

## A word of thanks
Thank you to my faithful travel companions and Cegeka colleagues [Jan Sabbe](http://twitter.com/@jansabbe) and [Bart De Neuter](https://be.linkedin.com/in/bart-de-neuter-8058689).

Thanks also go out to my employer, [Cegeka](http://www.cegeka.com), who paid for travel, accomodation and the entrance fee.

Thanks to the organizers, [White October Events](http://www.whiteoctoberevents.co.uk), who did an _amazing_ job at making everyone feel at home and for being super friendly people in general.

And thanks to [Meri Williams](http://twitter.com/@Geek_Manager), with her witty announcements, for being the perfect host and inspiring example to us all.

## Scribblings of a madman
Based on my [notes](http://github.com/sch3lp/LeadDevNotes), I'm sharing the most important things I learned in every talk I watched. So, you can decide if it's interesting or not.

_Placeholder TOC_

## Day 1
### Patrick Kua - What I wish I knew as a first time tech lead
Using his mesmerizing art in his slide-deck, Patrick Kua ([@patkua](http://twitter.com/@patkua)) gave everybody some pointers on the path to a _wise lead developer_.

He mentioned some recognisable things such as: _trust your team_, _delegate to it_, _provide guidance_, _don’t write code all the time_, _don’t make all the technical decisions_.

But the coolest thing I learned was that there are certain skills of yourself (as a leader) that can be represented by archetypes or personas.
Patrick identified the Coach, Shepherd, Shaman, and Champion. 

_The Coach_ (e.g. in a soccer team) personifies the part of you that tries to keep the team together and motivated.

_The Shepherd_ is the part of you that guides individuals back to the team, or guides the team to a shared goal.

_The Shaman_ is your story telling skill. I thought it was so cool that this is important enough to validate turning into a persona. I never thought of it that way but it sure is refreshing. 

And finally _The Champion_, is that part of you that can _Lead by example_ your team to a higher level.

We all carry all of these personas with us, it's certain situations that will call these out at times.

Patrick closed off by saying that our role as Lead gives us greater impact. And instead of becoming the [_10x Dev_](http://www.construx.com/10x_Software_Development/Productivity_Variations_Among_Software_Developers_and_Teams__The_Origin_of_10x/), we can grow the individuals in our team so that the team becomes the _10x Dev_.

This keynote really set the tone for the talks that we'd see over the course of the next 2 days in London.

[Slides](http://www.slideshare.net/thekua/what-i-wish-i-knew-as-a-first-time-tech-lead) / [Notes](https://github.com/Sch3lp/LeadDevNotes/blob/master/leaddev.md)

### Heidi Waterhouse - The 7 righteous fights
The 7 righteous fights... you should be fighting.

Heidi's ([@wiredferret](http://twitter.com/@wiredferret)) talk was mainly about making sure your application adheres to _Localization_, _Security_, _Extensibility_, _Documentation_, _Affordance_, _Acceptance_ and _Accessibility_. If you don’t take these into account, you’ll build up _compound technical debt_.

I learned that _Affordance_ is about nudging your users so they use your application correctly.

About _Security_ she had a lovely quote: ​_Internet is not a series of tube connected to hackers wearing hoodies_​. That got a good laugh.

About technical debt in general she said if it’s already in a release, you’ll get more resistance of fixing it. She made the fitting analogy by saying that trying to fix stuff in a codebase after it's release is ​_like trying to pound chocolate chips into an already baked cookie_​.

[Slides](https://docs.google.com/presentation/d/1-IXKHM__IeS9h4OhGODzXIrqVZGD6dzZk1SN3v_rBeo/edit#slide=id.p) / [Notes](https://github.com/Sch3lp/LeadDevNotes/blob/master/leaddev2.md)

### Mike Gehard - Moving from Monolith to Microservices
Mike ([@mikegehard](http://twitter.com/@mikegehard)) went so fast through his presentation that it's gonna take me at least a second viewing to really understand all the things he was trying to say.

The way Mike approached moving from a Monolith to Microservices is by starting from a monolith and then move towards Microservices, instead of trying to guess which microservice to distill from your application and do _trial and error_ from that position.

Why Monolith first? Because it’s safer to learn about your domain and it'll cost less to change _Bounded Contexts_.

Basically what he was saying was _Use the benefits that immersive design provides_.

1. Write API level tests
2. Arrange/Organize your application so you can **see** your domain (and _Bounded Contexts_)
3. Break out components
4. Promote one of your components to a microservice (here you'll also build the minimum required infrastructure and test it out)
5. Continue promoting microservices

As you might notice from the lingo, Mike is a big fan of Eric Evans' Domain Driven Design (he even made the same jokes that go along with it). He also didn't fail to mention Simon Brown's component structuring.
This made me feel right at home. :)

[Slides](https://github.com/mikegehard/journeyFromMonolithToMicroservicesSlides/tree/leadDev) / [Notes](https://github.com/Sch3lp/LeadDevNotes/blob/master/leaddev3.md)