---
title: A practical guide to Progressive Web Apps for organisations who don’t know anything about Progressive Web Apps
author: Sally
type: post
date: 2017-01-27T15:13:28+00:00
url: /blog/2017/01/27/a-practical-guide-to-pwas/
headerimg: /img/content/blog/l/PWA-phoneheader.jpg
class: bi-3
categories:
  - Work

---
<p class="lede">
  The realm of front-end web technologies (things like HTML, CSS and JavaScript) is an area that has been moving incredibly fast in recent years. With a number of my clients, I’ve been providing advice around a strategy for ‘keeping up’ with these changes, which is often prompted retrospectively by people feeling that they’ve already fallen behind. As part of this work, I often promote the concepts of <a href="https://en.wikipedia.org/wiki/Progressive_enhancement">progressive enhancement</a> (starting with a base experience for everyone and layering capabilities on top), encouraging people to consider features that may not yet be fully rolled out across browsers (but which are already here in others), and try to get them excited about some capabilities that they may not have come across yet.
</p>

A common scenario is that many organisations have been building and rolling out tools in the form of native apps, primarily because of requirements around features that the web historically hasn’t offered, or browsers haven’t supported &#8212; for instance apps are often touted as the best way to do things like reading content offline, or having push notifications. Building a website and multiple apps for different platforms can be expensive and make maintenance difficult, however. Some organisations are ending up with numerous simple, individual apps (across different platforms) that need to be built, managed and updated, when actually, web technologies have made huge leaps and bounds for cases like this. I wanted to write this article to highlight the progress that has been made across some of these areas, and to perhaps introduce some new readers to the idea of what are now being labelled as **Progressive Web Apps**.

## What&#8217;s a Progressive Web App?

Progressive Web Apps (sometimes referred to as PWAs, because everything in tech needs an acronym) is the encapsulating term for websites following a certain approach, that meet particular [technical criteria][1]. The “app” involvement in the name isn’t an accident &#8211; these creations share much of the functionality that you’ll find in native experiences &#8211; but really, they’re just websites.

Google’s Progressive Web App [introductory site][2] declares them to be:

> “…user experiences that have the reach of the web, and are:
>
>   * **Reliable** &#8212; Load instantly and never show the downasaur*, even in uncertain network conditions.
>   * **Fast** &#8212; Respond quickly to user interactions with silky smooth animations and no janky scrolling.
>   * **Engaging** &#8212; Feel like a natural app on the device, with an immersive user experience.
>
> This new level of of quality allows Progressive Web Apps to earn a place on the user&#8217;s home screen.”

Simply put, PWAs can work offline, are performant, secure, can be accessed from a home screen, load without feeling like they’re running within a browser, and can do things like notifications. You can use this kind of approach in conjunction with other capabilities to do things like capture form data, and sync it back to somewhere central when connection is regained. Sounding pretty good eh?

Features like offline capabilities are particularly desirable in situations like international projects, where data costs are relatively higher and connectivity may be poor. Some good sites to explore this further are Tim Kadlec&#8217;s:

  * [What Does My Site Cost?][3] shows how much it may cost people around the world to use your site.
  * [The Web, Worldwide][4] shows how the web is experienced by people around the world.

Generally though, we should be thinking about these principles regardless of where our audience is. By caching and only making requests when absolutely necessary you can save people data, and that’s good no matter where in the world we live. Someone’s also just as likely to have terrible signal if they’re on the Tube in central London, as they are if they’re in the wilderness.

(As an aside, it was only from reading the above that I found out about the “Downasaur” name, which I love)

## Show, don’t tell

It’s probably much easier to use an example, or several examples. [PWA.rocks][5] is a site that collects numerous examples of different types of PWAs, spanning maps, games, news, a book, and most importantly, Pokemon. You may notice some familiar names in the list &#8211; people like the Financial Times and Flipboard are already rolling out these approaches.

Within these examples, there are a few important things to learn about how PWAs work. First, is that if you go to the sites once, and then turn your internet connection off, you should still be able to use them. You may not be able to use _all_ of the pages &#8212; you usually have to visit individual pages first, or sometimes ask for something to be available offline &#8212; but this is very much dependent on how the site has been planned to work. More on that later.

Another thing of note which some of those example sites offer is the ability to [‘install’ the app][6] to your home screen with a custom icon, as you would with a native app on something like Android or iOS. If certain criteria are met, you should be shown a prompt like this:

<figure>
<img src="/img/content/blog/l/20170127add-to-home-screen.gif" alt="PWA example" />
<figcaption>Image from the Google PWA site</figcaption>
</figure>

One important point here &#8212; in keeping with our earlier discussion of the pace of change, at present if you add to your home screen it does just that &#8212; adds an icon to the screen. It’s basically a glorified bookmark, and the icon won’t show up in your main collection of applications… yet. That’s all changing, and soon your web apps will be able to sit happily alongside their native friends.

<!-- tweet removed - tweet 824430047012401152 -->

As another example of changes rolling out, I was contacted by [Alex Russell][8] (a software engineer at Google working on Chrome, Blink and the broader web platform) after originally publishing these thoughts. The documentation on [Google’s Web App Install Banner][6] page currently states that the banner will be triggered if the site _“Is visited at least twice, with at least five minutes between visits”_, plus meets other technical criteria. Alex very helpfully provided the following updates to changes in how PWAs are being handled in Google Chrome:

  * You can now trigger Add-to-Homescreen on the **first** visit _if_ the ‘site engagement score’ gets high enough
  * What&#8217;s a site engagement score? Well, you can see what Google Chrome thinks you engage with a lot at <chrome://site-engagement/>. (You need to be using Google Chrome for this link to work).

  {{< tweet 825178274506485760 >}}


## In practical terms, what does this mean for me?

If this is something that sounds interesting, then there are a few things that I’d like you to think about.

### Think about your audience

First, is the kind of functionality you&#8217;re excited about an _enhancement_, or is it something that’s absolutely central to the needs of your project? Second, but related, is to think **who** your project is for and what their device capabilities are likely to be. Check your analytics, speak to people about their habits and needs, and go from there.

One of my clients, a large charity, had some manuals that they needed to very quickly distribute to their international teams. These needed to be digital, available offline, and to work on specific lower-capability devices. The original plan had been to create an app, but we talked about whether a PWA approach may work. In the end it was decided that it wasn’t the best approach for the immediate rollout due to a lack of support on the particular device setup needed, but that it was something that they’d factor into future planning. That’s ok. Whilst progressive enhancement means that a base experience should be available to all, if one of the enhancements (e.g. offline) is a fundamental requirement and is [not yet][9] supported by the browsers that your audience uses (or won&#8217;t ever be if the devices are much older and not likely to be replaced), then you probably need to take a different approach.

However, when those enhancements are _optional_, then you can start using them today &#8211; you absolutely don’t need to wait for every browser under the sun to support something new; let the people whose devices _do_ offer them the capabilities use them now!

### Plan your approach

If this sounds good, then the next step is to start planning how you want these features to work. If you want offline capabilities you’ll need to think about what files/content need caching, and what kind of user experience is best for your situation. The way that offline works is to basically set a list of files (including images, styles, etc) that you want to cache. The device can either check the cache first and if _then_ something is not found try to request it from the web, or _always_ try to request it from the web and fall back to a local cache if it can&#8217;t connect.

### Talk to your developers

You should also have a chat to your web teams about the technical requirements, and whether there would be any challenges. PWAs are all about the client-side, the stuff that happens in your browser rather than on the server, and it won’t matter whether you’re using PHP or .NET or Ruby to power your site. What will be important is to know whether you can do things like run the site over HTTPS (you may be doing that already), or that performance has been focused on (you’re hopefully doing this too). In theory, you should be able to add this into your builds as another layer fairly easily. In practice, it’s always better to ask your developers how they feel about it rather than assuming!

If you already have budgets and timings in place, you’ll need to understand that these kind of features will add time and complexity into a build, and you may get some push-back or reluctance because of this. Early on, when not many people are doing things like PWAs they may be hesitant because it may take them too much time for them to be able to factor these kind of enhancements in. Generally, as approaches become better adopted and are seen as normal, they&#8217;ll be done by default. Responsive web design is a good example of this &#8211; many people originally saw it as a &#8216;nice to have&#8217; or something they couldn&#8217;t afford to do! It’s likely that progressive web features will go the same way, so if you can’t do them now, keep them in mind for the future.

## If you’re interested in learning more

We can do some brilliant things with web technologies nowadays, and I’d encourage everyone to learn more about what’s possible right now, as well as what will be possible very soon. Don’t forget &#8211; if something’s available to some and not to others right now, that’s not a reason to deprive those who _can_ use it (although other factors like your budget and priorities may be!). By using progressive enhancement, starting with an experience everyone can use, and layering on the extra presentation and functionality, we can get the best of both worlds.

If you’d like to know more about what can the web do some great sites are [whatwebcando.today][10] (tells you what your device is capable of) and [caniuse.com][11] (a bit more technical, but a great resource if you’re interested).

For those who are keen to jump straight in and start building, I can recommend Google’s [Your First Progressive Web App][12] tutorial &#8211; this is extremely simple and is a great start to get you up and running.

Finally, if you think that it would be useful to discuss these principles in person, or to talk about getting some help with things your company is looking to do with digital, I’d love to have a chat. You can reach me at sally at recordssoundthesame.com.

 [1]: https://developers.google.com/web/progressive-web-apps/checklist
 [2]: https://developers.google.com/web/progressive-web-apps/
 [3]: https://whatdoesmysitecost.com/
 [4]: https://www.webworldwide.io/
 [5]: https://pwa.rocks/
 [6]: https://developers.google.com/web/fundamentals/engage-and-retain/app-install-banners/
 [7]: http://recordssoundthesame.com/wp-content/uploads/2017/01/add-to-home-screen.gif
 [8]: https://twitter.com/slightlylate/
 [9]: http://caniuse.com/#feat=serviceworkers
 [10]: https://whatwebcando.today
 [11]: http://caniuse.com
 [12]: https://developers.google.com/web/fundamentals/getting-started/codelabs/your-first-pwapp/
