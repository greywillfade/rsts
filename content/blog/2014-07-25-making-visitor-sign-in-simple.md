---
title: Making visitor sign-in simple
author: Sally
type: post
date: 2014-07-25T09:49:17+00:00
url: /blog/2014/07/25/making-visitor-sign-in-simple/
headerimg: /img/content/blog/l/visitor.jpg
class: bi-6
categories:
  - Observations
tags:
  - interface
  - ODI
  - sign-in
  - technology

---
I’m working with the <a href="http://theodi.org" target="_blank">Open Data Institute</a> on a project at the moment, and besides getting incredibly excited about the stuff we’re working on (it’s amazingly cool), I love some of the little touches around the ODI’s office.

The first thing that I noticed back when I first came here a few months ago was the sign-in system at the front desk. With their permission, I couldn’t resist taking some photos and writing this post.

When you exit the lift, you’re greeted by an iPad, with the prompt _“Touch to sign in/out”_ (see above). You’re guided through a series of steps, the first of which is to enter your email. It was suggested to me (when he saw me loitering by it) by ODI-er and part-creator Dave that he feels this should have a predictive element, however I wonder about potentially exposing people’s emails when they didn’t explicitly state they should be shared.

<figure>
<img src="/img/content/blog/l/20140725-step2.jpg" alt="ODI sign-in step 2" />
<figcaption>ODI sign-in step 2</figcaption>
</figure>

If your meeting is in the system, the iPad tries to retrieve your name for you to confirm, but allows you to amend as necessary.

<figure>
<img src="/img/content/blog/l/20140725-step3.jpg" alt="ODI sign-in step 3" />
<figcaption>ODI sign-in step 3</figcaption>
</figure>

If this is your first time visiting, you’re asked which sector you work in. I’m not sure why this is collected, but seeing as it’s the Open Data Institute, I’m sure there’s an interesting reason. I&#8217;ll try to find out.

<figure>
<img src="/img/content/blog/l/20140725-step4.jpg" alt="ODI sign-in step 4" />
<figcaption>ODI sign-in step 4</figcaption>
</figure>

The next step is something I love. On typing in a character, you’re immediately presented with a match of potential names, along with their photo. When you’re not sure on what someone looks like, this is a nice touch for you to know when your host turns up.

<figure>
<img src="/img/content/blog/l/20140725-step5.jpg" alt="ODI sign-in step 5" />
<figcaption>ODI sign-in step 5</figcaption>
</figure>

The next screen states how your data is used, and states that it is actually optional for you to give it to them.

<figure>
<img src="/img/content/blog/l/20140725-step6.jpg" alt="ODI sign-in step 6" />
<figcaption>ODI sign-in step 6</figcaption>
</figure>

Finally, the last screen gives you the ability to associate a contactless card with your account (there’s a sensor pad hooked up to the iPad, which you can see in the header image, and using a card bypasses entry of your personal details), or to register for email updates containing the raw data they gather on you.

<figure>
<img src="/img/content/blog/l/20140725-step7.jpg" alt="ODI sign-in step 7" />
<figcaption>ODI sign-in step 7</figcaption>
</figure>

What I love about this process is the following:

  * It&#8217;s friendly, helpful, and simple. Instructions are in plain English, and helpful features such as predictive text, and photos of real people are used.
  * Both touch and other keyboard-based mechanisms are supported.
  * It uses technology (NFC) to make things even more simple &#8211; as a progressive enhancement not as a mandatory element &#8211; and allows the person signing in an element of choice with the kind of card that works for them.
  * It gives people a simple way of being sent their own data.
  * It&#8217;s more useful than a sign in book &#8211; data in a structured, digital format can be analysed much more easily than paper-based processes.

The code for the sign-in system website (it’s just a website, not any kind of unnecessarily fancy app) is on the <a href="https://github.com/theodi/signin-system" target="_blank">ODI&#8217;s GitHub</a>, because they like openness around here… so much that they even maintain information on GitHub of <a href="https://github.com/theodi/hot-drinks" target="_blank">how everyone likes their tea</a>. Amazing.
