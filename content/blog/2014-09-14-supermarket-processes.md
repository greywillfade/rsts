---
title: Improving supermarket processes with technology
author: Sally
type: post
date: 2014-09-14T18:26:20+00:00
url: /blog/2014/09/14/supermarket-processes/
headerimg: /img/content/blog/l/supermarket.jpg
class: bi-1
categories:
  - Observations
tags:
  - experiences
  - sainsburys
  - scales
  - supermarket
  - technology

---
We’re lucky, here in Colchester, that we have access to so much great East Anglian produce. From Mersea Island oysters, to Cromer Crab, to samphire, pork and more, the ingredients available round here are exceptional. In addition to food, possibly due to the fact that we’re one of <a href="http://en.wikipedia.org/wiki/Colchester#Climate" target="_blank">Britain’s driest regions</a> we also have some great local vineyards and breweries. As CAMRA hold multiple beer festivals here a year, and we had some great food and drink festivals this summer, I’m slowly working my way through all of our ales.

It’s not only that the produce exists, but it’s thanks to places like the amazing <a href="http://st-botolphs.org/" target="_blank">Waiting Room</a> making decisions like exclusively serving local drinks that it gets exposed to the public. It’s great for people to be able to trust quality too &#8211; one of my favourite treats is to go and buy a fiver’s worth of salmon (which equates to ridiculous amounts) from <a href="http://www.thefoodcompany.co.uk/" target="_blank">The Food Company</a>, slice it up, and sit there munching on my mountain of sashimi. This is something I could never do previously, as I have never lived near to a fishmonger whose quality I trusted. With all of this, you come away having had a great experience, and thinking better of the companies involved.

## &#8220;I took her to a supermarket&#8221;

Sadly, however, sometimes it’s still necessary to go to a supermarket. The closest two to me are Asda and Sainsbury&#8217;s. Sainsbury’s is pretty much what you’d expect, but is housed within a large, airy, light building, with wide aisles, and generally is a supermarket experience that is considerably more pleasant than most. Giving too much away about the kind of person I am, I was actually quite excited about it when I moved here. One of the features I like, which they have had for years in different branches, is that of self-scan, where you walk around with a scanner (pretending you&#8217;re in a sci-fi film), and logging everything you add to your bags, before handing back the scanner and paying on exit. I love this system, but the one criticism that I have of it is the self-service weighing machines involved in buying loose fruit and vegetables. It genuinely makes me sad whenever I have to use them&#8230;

{{< tweet 326410193997017088 >}}

&#8230;partly because of some questionable design decisions, but I’ll come on to the main reason in a sec. Sadly, despite Sainsbury’s saying they’ll log my comments, nothing has changed since then.

More and more frequently, when I go into the shop, all but one of the touch screens will be out of service, usually due to a ‘printer feed fault’. I have my suspicions that this is due to the sticky labels running out, which, again, I suspect is due to a huge amount of wastage.

Here’s an out of order machine from my trip to the Colchester branch earlier today:

<figure>
<img src="/img/content/blog/l/20140914-scales1.jpg" alt="Broken Scan & Go scales" />
<figcaption>Broken Scan & Go scales</figcaption>
</figure>

Here’s a ‘working’ machine, except funnily enough, with an exposed broken-looking printer, and many, many un-used labels adorning a discarded potato. It’s almost modern art.

<figure>
<img src="/img/content/blog/l/20140914-scales2.jpg" alt="Scan & Go scales" />
<figcaption>Scan & Go scales</figcaption>
</figure>


Today, instead of grumbling to myself throughout the interaction, I thought I’d do the other grumbly thing I know how to do &#8211; take a video, and write a blog post. Below is a video of my experience of trying to get a label to print for two onions.

The first thing you may notice is that there’s no intuitive categorisation. What do onions come under? Apples? Pears? No, too specific. Maybe ‘root veg’, or ‘exotics’? I could do another video on the difficulties on actually finding a product within these, but I’ve long since given up using the category screen, and by default just go straight to the search now.

As you can see from the video, the touch capabilities are awful. I know we’ve all been spoilt now, but come on, the Concept Keyboard peripheral for the BBC Micro was better than this. Take particular note that I’m attempting to press softly, hard, quickly, and for a longer time, and I still don’t know how best to select. When it does select, it chooses neighbouring P instead of O (despite me appearing to press directly over O), and when I went to hit ‘back’, the screen had switched to the search results at the same time, making me hit something unintentional, and printing out a wasted label. On starting again, it inexplicably took me straight through to potatoes &#8211; possibly a leftover of the Ps and Os being entered?

There a lots of other little niggles, but you can see for yourself.

{{< youtube H9M7y2Qdkno >}}


## So what could be better?

Firstly, it struck me how completely inaccessible this situation is. People with less mobility, or who are blind, are going to struggle. \*I\* struggle, and I’m a young person who works with technology for a living. There is no keyboard option, no audio output or screenreader, and it&#8217;s all very limited.

This isn’t a situation that needs a complex technical solution. There are all sorts of ways that it could be made infinitely more clever, and which could better interface directly with the hand-held self-scan devices (item on scales to scanner via NFC, or weight sensors \*in\* scanners, for instance), but they’re probably overkill. I’ve listed some thoughts in a minute regardless, but for a quick fix, a better visual interface, and better ways of interacting with it are all that are needed.

We can maybe take it a bit further though. Selecting a product, associating this with weight, and printing a label that can be scanned are the three key elements of the current system. To update this, it’s worth asking some questions, doing some research, and working out whether these are the real needs. For instance, does the requirement to weigh something even need a screen, or a printer? For example, consider the option that each basket of produce has a small weighing area, with an associated display. Due to location, the user wouldn’t need to select a product. A label wouldn’t need to be printed, because a barcode could be shown on the display, ready to be scanned immediately, and reducing both the environmental impact in terms of paper wastage, cost, and potential system errors (running out of labels). The questions around individual scales would likely be areas like management (how often to things change location, crash, do users understand that they can only use the scales in front of the produce), and the cost of introducing multiple, smaller scales rather than single units. A quick look into things like weight sensors for the Raspberry Pi and similar, show that you can pick up sensor hardware for less than $10. A lot of the education would be around the messaging, and how obvious the presentation of single-type scales was, but in comparison to the current situation there are clearly flaws at present too.

{{< tweet 348815482515759104 >}}

 Because of the location of this labelling, I without fail take a pepper over to the scales and get frustrated when I can’t see them on the system. You’re just meant to scan the tiny barcode on the side of the pepper.

And, moving away from the weighing side of things slightly&#8230; what if separate scanner hardware isn&#8217;t even needed? Yes, you’ll likely want generic, store, default back-up devices for those who can’t, or don’t want to do this, but what if people could create shopping lists on their devices, where you can use the device camera as the mechanism of grabbing barcodes, ticking off the items as they get scanned? With device-centric payment now more present than ever before with the recent Apple announcement, this could also translate through into a much more seamless payment process. This also wouldn’t need to involve complicated app development &#8211; the HTML5 input element could be used to grab an image from the camera, or there are numerous JavaScript libraries already available to grab data from barcodes. Storing data locally would negate the need for any persistent shopping list storage, and really there are hundreds of ways you could take all of this, using existing web technologies, and simple hardware sensors.

## The future

I’d love to see more companies embracing this kind of thinking in the future. The major supermarkets have all made a move towards more technology-based solutions over recent years, with self-scan, self-service checkout, and other experiences that minimise human contact being more common &#8211; great for those who hate small talk and who like to make their weekly shop as efficient as possible. On the other hand, it feels like we’ve got a long way to go. The experiences we have designed, and the technology in use is all very reminiscent of translating what we know, rather than opening our possibilities up to what we could be doing.

Sainsbury’s, if you’re reading this, I’d love to help you work out how technology can better support your customers. We could do some research, put together some prototypes, do lots of testing, and put together a plan that makes you look awesome and brings people to your shops, just to use the great experience you’ve created. Let’s do it. It’ll be fun.

Whether you&#8217;re Sainsbury&#8217;s or not, you can contact me at sally@recordssoundthesame.com if you&#8217;d like to have a chat, or to discuss anything in this post further.
