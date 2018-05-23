+++
author = "Sally"
categories = ["General"]
class = "bi-2"
date = "2018-05-16T14:00:00+01:00"
description = "In this post we’ll look at tailoring experiences to different situations and needs, using the concept of enhancements."
headerimg = "/img/content/blog/l/20180516-hdr.jpg"
tags = ["digital transformation", "enhancement"]
title = "Finding enhancements"
type = "post"
url = "/blog/2018/05/16/finding-enhancements/"
+++

<p class="lede">In this post we’ll look at tailoring experiences to different situations and needs, using the concept of enhancements.</p>

Attend any front-end developer conference at the moment and you’ll undoubtedly hear the phrase *“progressive enhancement”* frequently mentioned. From the days where implementing *“graceful degradation”* showed that you cared a little bit more about people who weren’t using the latest shiny browser or device, the industry has now generally come to accept a different mantra as best practice: everyone should have a good experience regardless of their situation, and if they can handle shinier or fancier things let’s layer that on top **as a bonus**.

This is a drum that has been banged by many people in different ways, and we can see some examples in different forms — from mobile-first media (and container) queries expanding as space allows, to CSS floats enhanced with flexbox (…enhanced with Grid), to JavaScript APIs kicking in if they’re supported.

So *“what does this have to do with transformation?”* I hear you ask. Good question.

## Enhancing your strategy
Outside of the fact that progressive enhancement is a great approach and something that you should really take a look at if you’re not already, we can also apply this kind of thinking to when we’re planning our overall strategy. Rather than this being something that developers consider at the point of implementation, we can think about the different layers of experiences that we want to provide as part of our overall strategy.

Here’s a basic example.

If you’re booking a flight or hotel, one of your goals would be to feel secure that your booking has been placed successfully.

When booking online, this is achieved with a confirmation page at the end of a transaction. Job done! However, some websites then try to get you to download their app, under the guise of it **being more convenient for you whilst abroad to be offline**. Knowing that data may be costly, the two big players below have used this as a marketing point whilst also meeting a need.


<figure>
<img src="/img/content/blog/l/20180516-eg1.jpg" style="max-width:600px;" alt="hotels.com app prompt" />
<img src="/img/content/blog/l/20180516-eg2.jpg" style="max-width:600px;" alt="booking.com app prompt" />
<figcaption>Both hotels.com and booking.com employ this tactic.</figcaption>
</figure>


It’s a kind of enhancement, in that it’s offering customers additional features on top of their base experience. You’ve booked, you saw the confirmation, and you can print the confirmation from their site. You may also have an email, which is in itself an enhancement. The app is a bonus, should people choose to use it, and it’s a good way for the company to get on another channel to market to you.

But we can do better than this.

The notion of **progressive web apps** means that we can use JavaScript to do a lot of that ‘appy stuff’. A person can book, have their email, print it, or download an app. But by implementing offline capabilities for the *website* we could better serve people at home (saving them their normal data, or removing their frustration when they’re trying to check something whilst on the train to the airport), as well as abroad when they’re even more data-conscious. We could — with their permission of course, and if their device supports it — use geolocation to send them a notification allowing them to instantly bring up their booking details when they reach their hotel.  They wouldn’t need to go through the extra step of adding another app - this would all be layered on top of their initial experience, without any additional friction at all.  This isn’t an implementation choice that should be left up to developers; this is something that potentially changes the business strategy.

Let’s look at another example.

I’m a big [Monzo](https://monzo.com/) fan. On a blog post they’ve released today, called [Supporting People to Self-Exclude from Gambling](https://monzo.com/blog/2018/05/16/gambling-self-exclusion/), they detail how they’re thinking about the varying situations their customers may be in, and considering different ways that they may be able to offer support whilst always leaving the person in control. They also wrote previously about other ways that they’re considering the relationship between mental health and spending: [Designing a product with mental health issues in mind](https://monzo.com/blog/2017/01/27/designing-product-mental-health-mind/)

The examples they include are very different types of enhancements, but are important ones. Monzo is a bank, and like most banks they focus primarily on money coming in, going out, and what happens in between. However, these additional explorations show that not only are they thinking about the big picture of service design around their product, but they’re also considering the impact that they can have societally. These arguably niche bits of functionality and use cases would almost certainly not have been considered by many companies who had successfully got to the point of transactions working well.

## Finding your own enhancements
The big question is this: whilst striving to provide an excellent core service, how can you introduce enhancements to better serve people in different situations?

In order to think about this, you can run through a few steps. As always, these will need to be tweaked to match your business’ individual situation, or the area that you’re looking at.

* Map out what’s in place already
* Ask yourself what’s your ideal place to be
* No, *really*. You’re being too sensible. If money, time, and resources weren’t an issue, where would you *really* like to get to?
* How does what you’ve mapped out change for different situations and different customers? Try not to think too broadly here and over-generalise with your handful of known personas. Again, really push the edge cases and explore very niche situations.
* How can you use principles of layering and enhancing experiences onto what’s already in place (rather than making something totally new) to achieve this **without technology**?
* How does this change when you think about **with technology?**
* Think about what valuable ideas have come out of this exercise (but make sure you’re not falling into the trap of measuring ‘value’ only in terms of direct monetary gain).

The process of finding strategic enhancements shouldn’t be scary. It’s not about totally changing direction, or starting everything again. If you always think in terms of layers and evolving the options available rather than these being entirely separate developments then you’ll find that you’ll have an easier time getting others to give their buy-in.

Keeping an eye on technology developments in order to be aware of what’s gathering pace can help you to be mindful of where new enhancements can come from. Many of the browser makers tweet and blog regularly about things they’re excited about, such as Microsoft’s [What’s new Edge Developer notes](https://docs.microsoft.com/en-us/microsoft-edge/dev-guide).

## Workshop available

If you’d like to learn more about some of the new technologies that facilitate enhancements, I’m now running a brand new workshop: [Workshop: Making the most of the modern web : Records Sound the Same](/services/workshops/making-the-most-of-the-modern-web/) It’s a half- or full-day training course for senior digital leaders who want to understand more about how the modern web can support their business and customers, and covers areas like progressive web apps, web payments, and more. Get in touch if you’d like to arrange a workshop at your company.
