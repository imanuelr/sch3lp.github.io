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

### Lorna Mitchell - Wonderful world of webhooks
Lorna ([@lornajane](http://twitter.com/@lornajane)) gave a lightning talk about why WebHooks are cool.

I remember that Webhooks are less chatty, and that its content is usually large (coars-grained) because you want to push the information that's useful to 80% of the use cases to stay as least chatty as possible.

[Slides](https://speakerdeck.com/lornajane/the-wonderful-world-of-webhooks) / [Notes](https://github.com/Sch3lp/LeadDevNotes/blob/master/leaddev4.md)

### Dan North - How to make a sandwich
Dan ([@tastapod](http://twitter.com/@tastapod)) North, the man, the Legend, gave a really great talk about _Feedback_.

He first talked about Feedback in the context of Systems Theory, which he does a way better job at explaining than I ever will so watch the video when it's released.

The most important thing I picked up about this part is that there are different motivations why one would offer feedback. And that when you notice you would be offering feedback to control the one you're giving feedback to, you should just walk away.

In the next part we learned about how to deliver feedback using SBI, _Situation Behavior Impact_.

And different ways of structuring feedback, e.g. the infamous _Sandwich_ model.

To receive feedback there is only one rule: _Always say Thank You_. Even if the feedback you got made you angry. Because it shows your appreciative of getting feedback. Try to map that feedback you got to SBI yourself (how was the other person thinking about giving you feedback).

Great talk to start off the lunch. :)

[Slides](https://speakerdeck.com/tastapod/how-to-make-a-sandwich) / [Notes](https://github.com/Sch3lp/LeadDevNotes/blob/master/leaddev5.md)

### Duretti Hirpa - How to get engineering team to eat their vegetables
To stay in the food analogies after a very nice lunch, Duretti's ([@Duretti](http://twitter.com/@duretti)) talk about how teams operate had some really great one liners.

My favorite ones being _(Acceptance of) vulnerability leads to a learning culture_, _Coordination **IS** competitive advantage_, _Productivity is a measure of comfort_.

She noticed what qualities a good team shows:
* A good team wants _you_ to win
* Has a sense of togetherness
* Has a place for vulnerability.
* Is psychologically safe
* Has empathy

Nice talk with a whole lot of truth bombs. Worth watching when the video's get released.

[Slides](https://speakerdeck.com/duretti/how-to-get-engineering-teams-to-eat-their-vegetables) / [Notes](https://github.com/Sch3lp/LeadDevNotes/blob/master/leaddev6.md)

### Katie Fenn - Writing Modular Stylesheets with CSS Modules
Katie Fenn ([@katie_fenn](http://twitter.com/@katie_fenn)) took the stage and talked about how CSS Modularization is sensical because along with making components in JavaScript, you also want the same for your CSS.

`CSS Modules` is the way to achieve this fairly easily. I think it makes the most sense when you work with `JSX` components like you do when you use `ReactJS`.

Other than the various JS loaders, you can also use it with both Sass and Less.

[Slides](https://slidr.io/katiefenn/writing-modular-stylesheets-with-css-modules-the-lead-developer-2016#1) | [Notes](https://github.com/Sch3lp/LeadDevNotes/blob/master/leaddev7.md)

### Yasmina Banaszczuk - I know just the right person
After that short technical talk, in came Yasmina ([@lasersushi](http://twitter.com/@lasersushi)), ready to blow us all away with refreshing german directness and delicate, yet powerful tone of voice. 

Her talk was all about how our (personal) networks can influence hiring and retention in the tech industry.

After laying out studies and papers about how we really hire "People like ourselves", we delved deeper into the motivation behind it.

She gave a hilarious example of how the name _Kevin_ has (had?) a bad connotation in Germany, which even lead to a word called [Kevinismus](http://blogs.discovermagazine.com/discoblog/2012/02/01/does-a-lame-name-make-you-more-likely-to-be-a-smoker-with-low-self-esteem/#.V2v5Q-Z97AU), and the entire floor laughing out loud when she visibly felt embarassed about all the _Kevin_'s in the audience, and the continued, emboldened laughter after she exclaimed _There's actual research in that!_.

At the end of her talk we got a nice summary:

Check your processes, your networks and yourself.

Are they varied, do they have same educational background, do they spend their nights gaming, or do they speak or dress the same way?

Then your network might be too homogeneous.

This might turn your networks into gate**keepers** instead of welcoming, open gates.

A very refreshing and interesting talk, with a very smart and very fun to listen to speaker. Definitely watch her talk when it gets released. 

If you're interested in more of her research, definitely check out [her website](http://frau-dingens.de/). She's currently working on a series of articles on [_The Habitus of Tech_](http://frau-dingens.de/the-habitus-of-tech/).

Slides | [Notes](https://github.com/Sch3lp/LeadDevNotes/blob/master/leaddev8.md)

### Joel Chippindale - Telling stories through your commits
One of Joel Chippindale ([@joelchippindale](http://twitter.com/@joelchippindale)) was preaching to the choir (at least on my part) about how _The key challenge as lead dev is managing complexity_ and how _Naming, code design, refactoring and automated tests are all about **communicating** the intent of our software_.

He then went on to say that VCS (like Git, Mercurial, SVN, ...) is underused in this regard.

To have _every line of code always documented_, he presented us with the 3 principles he adheres to.

1. Make atomic commits; What's the smallest useful change u can make to ur codebase?

2. Write good commit messages (on [his website](http://blog.mocoso.co.uk/talks/2015/01/12/telling-stories-through-your-commits/) he links to [Chris Beams' _How to write a good commit message_](http://chris.beams.io/posts/git-commit/))

3. Revise your development history before sharing. With `git rebase`.

The biggest motivator to a team on using these principles is that all of them have the benefit of making commits simpler, and also easier to think about.

Absolutely loved this talk. It amazed me how much information he was able to cram in a relatively short talk.

Check out [his website dedicated](http://blog.mocoso.co.uk/talks/2015/01/12/telling-stories-through-your-commits/) to this concept.

[Slides](https://speakerdeck.com/mocoso/telling-stories-through-your-commits-lead-developer-conference-2016) | [Notes](https://github.com/Sch3lp/LeadDevNotes/blob/master/leaddev9.md)

### Sam Lambert - The argument for simplicity
Sam Lambert ([@isamlambert](http://twitter.com/@isamlambert)) taught us a bit about how they work at github.

They deploy with hubot in slack so they can easily backtrace what happened before and after in the conversation that is deploying to production. Neat!

If there's one thing he wanted us to take along it was to get a therapist. People laughed awkwardly, but he was dead serious. It was great to see this taboo being taken down.

At the end, in stead of mentioning his own internet _location_ he shared some people he wants us to look up, so here are the ones I managed to note down:
[@ihavenotea](http://twitter.com/@ihavenotea), [@jessfraz](http://twitter.com/@jessfraz), [@eanakashima](http://twitter.com/@eanakashima).

Slides | [Notes](https://github.com/Sch3lp/LeadDevNotes/blob/master/leaddev10.md)

### Nickolas Means - How to crash an airplane
Jezus christ, how do I even begin summarizing this talk.

Nickolas ([@nmeans](http://twitter.com/@nmeans), airplane afficionado) left the audience mesmerized and awe struck after channeling his inner _Shaman_, telling us a story about how a horrible plane crash could've turned out even worse if it weren't for _Cockpit Resource Management_.
And making the analogy to what makes up a good team.

If there's one presentation you should watch of this conference, it's this one.

A grasp out of some of his quotes:

_Cooperation over Heroics_

_Everyone has a voice._

_As leaders we need to avoid teams to develop dominant voices, especially our own. Use your authority to ensure every voice is heard._

_Software is a team sport._

Slides | [Notes](https://github.com/Sch3lp/LeadDevNotes/blob/master/leaddev11.md)

## Day 2