+++
author = "Sally"
categories = ["General"]
class = "bi-5"
date = "2017-10-27T16:55:00+01:00"
description = "This is the story of the CTO support and mentoring that I’ve been doing with Bec from Prolifiko, plus some of Bec’s thoughts on our journey."
headerimg = "/img/content/blog/l/20171006-books.jpg"
tags = ["mentoring"]
title = "Case study: part-time CTO support and mentoring with Prolifiko"
type = "post"
url = "/blog/2017/10/27/prolifiko-CTO-support-and-mentoring/"
+++

<p class="lede">Working on large projects for well-known brands is great – great for business, great challenges to to grips with, and a great sense of pride in being able to mention things that others may be aware of.  It’s also just a small segment of the people and businesses who need help and advice, and by only working with big name organisations you can miss out on different types of challenges and some really exciting new ideas. Because of this I’ve always been keen to work with everyone - from global companies to new startups.</p>

Run by Chris and Bec, [Prolifiko](prolifiko.com) (and its earlier form, Write Track) is one of these smaller entities. It’s a productivity tool for writers, based around building habits and providing encouragement to set and meet little goals. They’re one of my longest-running relationships, but this has also evolved over time. This is the story of the work that I’ve been doing with them, plus some of Bec’s thoughts on the journey. We've decided to share our story on [National Mentoring Day](https://twitter.com/hashtag/NationalMentoringDay).

## First contact
The first I knew of the product was when Bec posted on [Ada's List](http://adaslist.co/) (a community for women working within tech and digital) asking for some help. They already had a fully-functioning social platform allowing writers to track goals and support each other, but this hadn’t entirely been planned:

**What made you decide to leap into the startup world?**

> **Bec:** Having a startup wasn’t a dream of mine. I had an idea that just wouldn’t go away and I was determined to do something about it. I was working as the director of a writers’ centre and came across a problem that writers had with finishing their projects – at the time I was using my iPhone to track diet, exercise and health and realised that people needed a FitBit for writing. I fell into the world of design thinking, persuasive technology and startups and soon Prolifiko was born.

Whilst Bec and Chris had the vision, the technical solution to bring this to life had been architected entirely by a third party. Bec didn’t always have visibility of the reasons behind all of the choices made, or fully understand the way that everything worked; its capabilities and limitations. She wanted to take a bit of a pause for a neutral to assess the tech that was in place, and to put in place a roadmap for the future.

**Why did you feel that you needed some extra help when you first put that message on Adas List?**

> **Bec:** Though I’d managed large digital projects in previous roles, I didn’t have any technical or coding skills. From the outside, the world of tech can be quite exclusive – there are high barriers to entry with impenetrable language and processes. I wanted someone to help me translate and navigate this new world.

Over December 2014 we did a number of things…

* Documented the technology stack, hosting, and architecture
* Basic code review
* Site usability review
* Responsive/cross-browser review
* CMS review
* Captured key site processes and tech impact.
* Accessibility review
* Performance review
* Analytics review.
* Bugs and usability

…all presented back with some recommendations on what I remember as a pretty epic phone call.

## Mentoring
After that, our relationship started to shift a little bit, and we sporadically kept in touch informally over email to see how things were going. At the start of 2016, Bec emailed to say that they’d been digging through data, spending time talking to users, working out what they enjoyed doing, and had come up with a plan for their next steps. She was after a _“sense check and a shove in the right direction”_.

As they were self-funding we were all incredibly mindful of cost. Instead of a larger up-front piece of work we instead decided to switch to a time bank, where Prolifiko were able to call on me whenever they had little queries come up. After running successfully in this way for several months, we eventually found that we’d unconsciously fallen into more of a mentor/mentee relationship than one of client and service provider.

Without a CTO or permanent development resource in place, Bec felt that she was needing some consistent support in order to help her run the business. Using different freelance parties for development and design work brought with it a number of challenges - amongst other things: how much she should be dictating the tech approaches vs letting developers do what they want, how to judge the quality of work, *how* they work together, how Prolifiko should write briefs, and how they know if someone’s talking sense! Having someone on hand to chat to and seek advice from became a useful sounding board and steering tool.

**What have the challenges been of running a startup without a CTO on board?**

> **Bec:** The toughest thing is being able to make decisions or technical choices without having all the skills and experience. As a manager within business I got used to delegating but in an early startup there’s no-one to delegate to – you have to take responsibility for your choices, which means you need good information and evidence. That ended up being a benefit as I had to ask questions, learn, and ‘own’ my choices – even when they were wrong. I learnt from my mistakes, though it was pretty painful at times.

At the moment it works quite simply:

* We speak roughly every month. This is now a mix of general catching up on life, plus Bec will have some things that she wants to get my advice on.
* I advise on what I can there and then, and will send over links or look things up quickly if there’s any resources I know will help. If there’s extra work needed (e.g. writing procurement specs) then I’d do that separately after the call.
* Likewise, Bec often has words of wisdom for me. As someone running her own business, who’s previously worked as a head of UX and innovation, and who’s done a lot of side-business things that are relevant to my plans I always find her advice invaluable in return.
* It has got to the point now where I’m invested in the friendship and mentoring as much as the product itself, and am happy to do extra things whenever I have capacity. I once ran some bespoke SQL queries on a Postgres instance to get stats for Bec when I was jetlagged and awake in the middle of the night in Japan, despite being chastised for doing so!

<figure>
<img src="/img/content/blog/l/20171027-proto.jpg" alt="Bec and her prototype" />
<figcaption>Bec Evans, and screenshots of a Prolifiko prototype app</figcaption>
</figure>

## Re-formalising the relationship
More recently, the product has received some funding as Prolifiko has joined the Ignite accelerator. Under more scrutiny and planning some important bursts of changes, Bec wanted to be sure that there was a clear, accurate set of documentation around the current state of the Prolifiko technology.

After talking through the needs it became apparent that this was more work than I’d normally be able to squeeze in during our chats. On this instance we decided to return to a more traditional, booked piece of work, which meant that I could prioritise it and take proper time rather than squeezing it in.

**Why did you feel that you wanted the documentation doing, and what has it given you?**

> **Bec:** The last project we worked on was getting technical documentation in place. Prolifiko got to the stage where there was a relatively stable architecture and we were using a variety of suppliers and third party products, tools, and APIs. I was using more freelancers so need to be able to quickly explain the set up and then Prolifiko got a place on an accelerator so the pressure was on for me to have documentation and be able to explain it. The process of compiling the documentation was a brilliant learning experience, and having it there has given me confidence. It’s very much a live document that needs updating regularly as things change and I feel able to do that myself now.

We chose to use Google Docs as the current home, as it meant that we could very simply get collaborative input from Bec, Chris and her development team. Starting by sending out some general questions to kick things off, I then went through the different systems, capturing important aspects as I went.

Areas that we ended up covering included:

* **Current technical architecture and choices** - this element was written in as much plain language as possible, both for the benefit of Bec and Chris as non-technical founders who needed to understand concepts, but also to make sure that new team members were as clear as possible. This included a diagram of how all of the pieces fit together, the stories of why decisions and tech selections had been made, and simple explanations of what things actually *are or do* (words like Webpack and Babel often don’t mean much to some people on their own!).
*  **Where everything is** - a simple list, but an important one. This captured all relevant URLs and details of repositories, so that a new team member could quickly get an overview of where everything lived.
* **Creation of standards and principles** that the team should work to, including capturing fledgeling coding standards that the lead developer had begun to define.
* **A template for briefing** front-end and back-end freelancers.

There was also a specific piece of investigation where one element of the tech stack had been causing problems, so I wanted to not only understand the background of what had been created and why, but to send over some easy to understand recommendations for the future.


## The value of an ongoing relationship
The changing nature of our relationship, from the first rather rigid piece of work through to chatty phone calls and a mutual benefit have been something that I never expected when we first made contact. I’ve learned a lot about the startup world by living through the Prolifiko experiences, and always come away from our calls feeling that I’ve not only helped, but have been given something back.

From Bec’s perspective, I’ll let her words speak for themselves.

**How has having a mentor regularly available helped?**

> **Bec:** Having a mentor with a regular check in has made a huge difference to me. When you work with someone over time you build up trust – it’s so important for me to be able ask the stupid questions, without being judged, and not feel patronised when things are explained. In the startup world there’s a lot of bravado – everyone is crushing it all the time. But that’s bullshit. Accept what you don’t know, ask for help, get answers and learn then you’ll have a better idea and your startup might be one of the 10% that succeeds. I strongly recommend that people find mentors to support and push them.

The other interesting element is that despite having chatted online and on the phone since 2014, we’ve only met once in person, at the Adas List conference last year. With most of my work being colocated at key periods is really important to me, but Prolifiko’s remote team has shown me that it is very possible to form strong relationships and efficient work practices without any face to face time.

Whilst we’ve managed to keep everything very fluid and relaxed, these kind of support arrangements sometimes need to be more formal - one of the services that I offer is to work with organisations and individuals to provide consultancy or to give interim CTO/CDO support whilst they find the right permanent person (even working with them to make that happen), and typically this follows a more traditional format.

Other times, mentoring can be a really good low-key solution, and it also matches with many of the Records Sound the Same values: it leaves people with skills and knowledge rather than just doing the work, I get to work with nice people, and I get to experience a range of situations.

**Do you have any advice that you’d give to people following a similar path to yours?**

> **Bec:** My only advice is to just do it. Don’t put off trying something new because you don’t have all the skills – the best way to learn is to try. Have the confidence to start something and the humility to ask for help and support. Getting Prolifiko out of my head and into the world has been the most thrilling, exciting, scary thing I’ve ever done. You can do something too.


**Anything else you'd like to say!**

> **Bec:** Just thank you Sally! It’s been great having you on the journey. I couldn’t have done it without you. You have no idea how much you’ve helped.

If you'd like to know more about Prolifiko you can go to the (soon to be revamped!) [website](prolifiko.com), or say hello to them on [Twitter](https://twitter.com/beprolifiko). Here's a [really nice piece from The Guardian](https://www.theguardian.com/books/ng-interactive/2017/mar/20/how-to-finish-a-novel-tracking-book-progress-wyl-menmuir), telling the story of how Wyl Menmuir used the service to write his Booker-longlisted debut novel.
