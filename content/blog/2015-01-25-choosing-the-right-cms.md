---
title: Choosing the ‘right’ CMS
author: Sally
type: post
date: 2015-01-25T12:44:21+00:00
url: /blog/2015/01/25/choosing-the-right-cms/
class: bi-6
categories:
  - Opinion
tags:
  - CMS
  - decisions
  - planning
  - requirements
  - strategy
  - technology

---
<p class="enhance">
  This topic is one of the oldest items that I’ve had in my ever-changing list of ideas to write about, however recently Chris Coyier posted a tweet that sparked some interesting discussion, and the varied responses prompted me to finally put fingers to keyboard to air my views on the matter. How do you choose the right CMS? <em>Is</em> there a right CMS? As you have probably deduced from my liberal usage of quote marks in the title of this post, I&#8217;m of the opinion that things aren&#8217;t quite as clear-cut as we&#8217;d always like them to be.
</p>

For reference, the discussion-starting tweet from Chris was this:

{{< tweet 554694495233900544 >}}

&#8216;CMS&#8217;, for those who are unfamiliar with the term, is an abbreviation of Content Management System. This, at its heart refers to the ability to manage content in a user-friendly way that doesn&#8217;t typically require any coding knowledge. The actual approach, power, flexibility, and functionality given will depend on the product, and these vary hugely from one CMS to another.

## So what’s the problem?

Chris’ tweet, or even his friend’s question are not inherently bad. They do not state that they require an immediate &#8216;correct&#8217; answer, only that they’re looking for opinions. In contrast, many responses seemed to take the view that they should state a solution instantly, which I found to be all-too reflective of many in our industry&#8217;s eagerness to jump to technical conclusions.

Before I continue, I&#8217;d like to say that this post isn&#8217;t intended as a criticism of Chris or any of the people who responded to his tweet. I simply found this bait too tempting to ignore, and it was a great collection of views that illustrated some points around CMS choice really nicely.

A number of people jumped in with definitive (and often single-word solutions), ranging from WordPress, to Drupal, to Sitecore, to MODX, to Adobe CQ5 to Perch, to ExpressionEngine, to many others. If you know a little bit about Content Management Systems, you&#8217;ll likely have an idea that these are incredibly different products, all with different features, technical dependencies and impacts, and will result in wildly varying implementation approaches.

{{< tweet 554694765686444032 >}}

Two wildly different products, each with totally different base capabilities and knock-on impacts from usage.

All too fast, you also inevitably end up with this situation:

{{< tweet 554694807139123201 >}}

{{< tweet 554694862394892289 >}}

Yes Drupal! No Drupal!

Providing solutions with no understanding and no reasoning is a pet hate of mine, and is something that I feel can be a big factor in projects that later fail. Our tendency to jump in with a solution and approach before knowing anything about the realities of the situation is, I personally feel, unprofessional, and can lead to the creation of sites that are totally wrong for their users&#8217; needs. And by &#8216;user&#8217;, I don&#8217;t just mean &#8216;people who visit the site&#8217;. Administrators, and people who manage the site are users too &#8211; something which all too often gets forgotten.

I appreciate the fact that Twitter probably isn&#8217;t the best platform to have this discussion on, and that the character limitations were likely a cause in why people didn&#8217;t elaborate on their choices, however I personally believe that blanket statements like the above are unhelpful and potentially dangerous. We sometimes forget that these kind of discussions are often watched keenly by people who look to us as sage sources of wisdom; people including [new developers][1]. By providing no context to our answered choices, we may encourage others to start doing the same.

I read down the replies, and was pleased to see that my good friend Paul had responded with a great point that echoed my views (he&#8217;s suffered many years of me ranting on the subject of technical choices).

{{< tweet 554712653948788736 >}}

Thankfully he wasn&#8217;t alone:

{{< tweet 554694690059337728 >}}

{{< tweet 554695825537126404 >}}

The issue of CMS choice (as with all technical choices that have a user impact) is something that I care about an awful lot. It&#8217;s a big part of what I help people with when they bring me in to work with them, and I constantly battle with the &#8220;just tell us what we should use&#8221; (or worse, &#8220;We definitely need to use&#8230;&#8221;) mentality before anyone fully understands the project.

For this reason, I want to look at some of the common problems and misperception of CMS choice, along with areas that you should consider when looking for a CMS.

## &#8220;The agency should decide&#8221;

{{< tweet 554696192756830208 >}}

A lovely sentiment, if your agency is truly impartial, or knowledgeable enough to make a reasoned choice. Sadly, that isn&#8217;t always the reality of things for many clients.

Once upon a time, I worked for an agency where, at the time, a brief would come in, and a chosen solution would go back out as part of the pitch. Decisions would be made on the bare minimum of information &#8211; information that was sometimes incorrect &#8211; purely because of a need to show a strength of conviction in the response, as well as to gauge pricing and resource availability for the developers.

Sometimes this is inevitable &#8211; for example RFPs with a requirement to state a solution &#8211; however even there I would suggest that you give an indication of the type of approach that _may_ work, any knock-on impacts of this approach, and that you require further investigation and (most importantly) collaboration with the client to decide.

Of course what the tweet above doesn&#8217;t seem to consider is that agencies responding to a brief very often have preferences based on their own situation. They will have developers skilled in certain programming languages, products, and ways of working rather than others, and naturally they&#8217;ll suggest a CMS that they have experience with. Is the solution they&#8217;re proposing really what&#8217;s best for the client, or what fits their scheduling holes or the skill sets they have to hand?

In a recent article by Matt Griffin on A List Apart, a quote illustrates this issue further:

> Back in 2008 (when we started Bearded), one of our differentiators was that we built every site on a CMS. At the time, many agencies had not-insignificant revenue streams derived from updating their clients’ site content on their behalf.
>
> But we didn’t want to do that work, and our clients didn’t want to pay for it. Building their site on a CMS and training them to use it was a natural solution. It solved both of our problems, recurring revenue be damned! It gave our clients power that they wanted and needed.

&#8211; <a href="http://alistapart.com/column/the-people-are-the-work/" target="_blank">The People Are The Work</a>

Bearded were doing a good thing here, and should be applauded. We can see some parallels though &#8211; are some agencies now simply repeating the lock-in model of old, but instead of doing manual updates, just providing a solution that means it&#8217;s difficult for their client to go elsewhere? This is one of the things that I work independently with people to help with &#8211; solutions that meet their needs rather than being dictated by someone else&#8217;s convenience.

Now, of course not all agencies are like this, and hopefully most recommendations are grounded on some great thinking, however this is something that many clients don&#8217;t consider when putting a project out for tender. I&#8217;m also not saying that agencies and developers shouldn&#8217;t specialise and suggest their chosen solution when it&#8217;s appropriate; far from it. In fact, as pointed out by a former colleague of mine, an agency that is completely neutral may not have enough expert knowledge to be able to advise well enough, and may not be able to deliver as well as someone who is an expert. My issue is when a preferred solution is pushed without knowing about the actual project needs.

 CMSs aren&#8217;t just background technology like a choice of framework or library, that your clients probably won&#8217;t care about. There is a user impact, and choices on this front will likely have a number of further ramifications.

## The product can do everything

Many people are of the opinion that whichever solution you pick, it&#8217;s flexible enough to meet whatever needs happen to come up. You see this quite a lot in particular circles &#8211; for example many WordPress developers will staunchly defend the fact that it&#8217;s &#8220;_more than just a blogging platform_&#8220;, and that it can do anything you need it to do.

This is also a view that you&#8217;ll probably get should you consult the vendors themselves &#8211; they don&#8217;t want to lose out by saying they can&#8217;t do something, but may omit exactly how well they do it, how much extra effort it is, or what this looks like.

{{< tweet 554696032856993792 >}}

It probably can do everything, eventually, but should it? There&#8217;s more to your CMS choice than simply the technology and features that you need.  For example, as I mentioned in my original definition, one of the aims of introducing a CMS is to take away some of the complexity of updating content through the use of a standard interface. This interface differs wildly for different content management systems out-of-the-box, and each has their own approach to workflow. Will the standard interface do everything you need, right from the start? What&#8217;s the amount of customisation needed to fit your needs, and to adapt the built-in experience to your workflows? This is only one aspect that may need to be customised. Another example is the product&#8217;s ability to integrate well with other systems that you may already have in place. Some have partnerships and official plug-ins and connectors available. Others will require you to write your own.

Your chosen product probably _can_ do everything, however if you end up in a situation that requires extensive customisation and extension of the core platform in numerous areas, you could find that something else may have done the job much quicker, and possibly better. Systems such as SharePoint work very well for document and marketing management, but have much more limited capabilities around more powerful web-specific content management. If you want to integrate something like Microsoft Dynamics with ExpressionEngine, you&#8217;re going to require more custom development than other CMSs who have given this partnership specific consideration. Some products are naturally more suited to specific requirements, and ensuring that you understand these needs up-front can make sure that you end up with a solution that isn&#8217;t hacked to death.

## Everyone else is using it

Unsurprisingly, many of the responses were geared around the idea that if other similar institutions using something, then that means it&#8217;d be a good solution for them too:

{{< tweet 554695376763363330 >}}

<!--554698912926556160 removed -->

{{< tweet 554700426935681024 >}}

{{< tweet 554700944806776833 >}}

{{< tweet 554701083394584576 >}}

{{< tweet 554711104338006016 >}}

{{< tweet 554722612254101504 >}}

As you can see, again there is no consensus about what is best, however choices often end up being justified because &#8220;_If BRAND X is using something (and they&#8217;re a bit like us in terms of the real world), then that&#8217;ll definitely meet our online needs!_&#8220;. It&#8217;s risk-mitigation, and a way to cover the back of the decision-maker. It can&#8217;t possibly be a bad choice if it&#8217;s worked for everyone else, so if the project fails, it&#8217;s definitely not down to the choice of the CMS&#8230; right? The reality is that one university will likely have some similar content and needs to another, but again, they will have utterly different situations.

The above can also easily lead to a false sense of security around one particular solution. Whilst working with a Premier League football club on a new site build, I found it fascinating to learn about the amount of lock-in that can be involved in these decisions. Outside of contractual and deal-based obligations, many clubs made their choices of technology based on what everyone else was doing. Certain products were able to pick up a lot of business because they were seen as being the only choice &#8211; for example the proliferation of the usage of [Perform&#8217;s CMS][2] within the sporting industry for a long time. Along came Manchester City FC, with a social media and interaction-heavy, redesigned site in 2009, and suddenly everyone wanted &#8220;_that_&#8220;. The CMS was naturally only one part of this, but with Sitecore powering the MCFC experience, suddenly a number of other key football clubs switched to Sitecore.

## Is bespoke best?

{{< tweet 554694798075232256 >}}

When I started out as a back-end developer, my work was almost exclusively on bespoke CMS systems. At the time, as in the A List Apart quote above, productised CMSs weren&#8217;t widespread and the agency I worked for wanted to give their clients the ability to manage their own content. We created a scaffolding system, allowing us to quickly generate the code and database scripts that we needed, following a common structure and conventions, and we could make it do whatever we wanted.

Bespoke systems are great for this &#8211; you have total control over them, you build them to meet yours and your clients&#8217; needs, and can theoretically use them to cater for any unique requirements that come up. This is the approach taken by people like <a href="https://medium.com/@itsleesimpson/how-to-design-a-cms-for-the-modern-newsroom-f11a53f8539f" target="_blank">The Guardian</a>. They&#8217;re pretty smart, right? If it&#8217;s good enough for them, shouldn&#8217;t it be good enough for me? Perhaps, but do you have the time, resources, and man-power of the Guardian team? Do you need something as flexible as they do? The danger here can be that someone decides to go bespoke based on the successes of others rather than their own needs, when actually bespoke systems come with a number of caveats.

In my own experience, we moved away from bespoke systems for a number of reasons. First, despite it being sold as a custom solution, it wasn&#8217;t. Not really. It was an instance of a general solution that got rolled out for everyone, and didn&#8217;t ever really differ visually, functionally, or in terms of workflow. Some clients struggled with the interface, and we tried to get some UX time for it, but that never really came to fruition for a few reasons, so everyone was stuck with quite a &#8216;developery&#8217; experience. This is likely what you&#8217;d get if you went to an agency &#8211; it&#8217;s highly likely that the &#8216;bespoke&#8217; solution you&#8217;re being offered is actually just an in-house CMS, rather than being truly bespoke. If it truly is, then you&#8217;ll probably be paying much, much more for something unproven and built from scratch.

Where customisation did occur, we ended up having fragmentation. Some clients had older version of individual modules, or were actually on an entirely outdated version of the core system. This made updates more difficult to manage, as new staff had to be trained up on the quirks of each roll-out. Ideally everything would have been factored back into the core, and there would have been a way to roll out updates to everyone, but that required the time to proactively go back and do this &#8211; time that was destined to be spent on pushing forward with new builds. Where standards themselves had moved on, this also needed to be kept up to date. We were very, very busy, and there was never enough time for internal product development. You run into the conflicts that many see &#8211; running a service business vs managing a product.

Outside of the norm, if it hadn&#8217;t been built already, everything required custom development to be bolted onto the main framework. This again caused fragmentation for maintenance, and was often not very cost-effective for clients. Towards the end of the bespoke era, other solutions had community-written plugins that could quickly be added, and it just wasn&#8217;t feasible to compete. With a truly bespoke system you don&#8217;t get the benefit of community efforts, including extensions, documentation, and a pool of developers familiar with the CMS. You can easily end up in a situation of vendor-lock in, being able to work only with the company (or developers &#8211; sometimes it&#8217;s someone&#8217;s &#8216;baby&#8217;) who provided the solution &#8211; many agencies won&#8217;t touch the ongoing maintenance of someone else&#8217;s system, and would propose a rebuild.

You&#8217;re probably getting the feeling that I personally don&#8217;t experience bespoke builds being viable unless you have a dedicated internal product team. The caveat to this is of course that it&#8217;s entirely down to the nature of the audience, and the reason it&#8217;s being created, bringing me nicely on to a situation where I think bespoke systems can be great:

## Not just for developers

An exception to the above is of course is the &#8216;CMS&#8217; that&#8217;s actually in place to simplify repetitive tasks, or for the convenience of the developer. These kind of interfaces are brilliant, and most developer has probably made them in their time in order to help with day to day efficiency.

The problem comes when the interface is really meant _just_ for developers. I recently worked on a project where the CMS was the standard Django admin install, and whilst it provided some basic management functionality to the business owner, it was extremely difficult and limited for her to use. None of her requirements &#8211; reporting, business intelligence about her users, the ability to update certain areas of content &#8211; were catered for at all. She had simply been presented with this as &#8216;the CMS&#8217; without any further discussion being held about needs.

Build bespoke, build tools for your own use, but don&#8217;t be so blinkered to expect everyone else to be able to use something in the same way that you can.

## How to choose the right CMS for you

As experts it may be tempting to shift the burden and responsibility of decision making, and to get the client to choose. However we shouldn&#8217;t want to do this &#8211; we should be telling people what is best based on our expert recommendations, but ensure that these are fully informed, arrived at collaboratively, and in the best interests of the clients, not ourselves and our personal feelings.

We&#8217;ve looked at a lot of potential problems, and reasons why we shouldn&#8217;t approach our choice in certain ways, so how should we be approaching it? There are a _lot_ of CMSs out there. What are the areas that are important to consider when trying to choose one?

&nbsp;

  * **Features** &#8211; what features do you need, and which products support those best?
  * **Costs** &#8211; initial cost of purchase and build, ongoing &#8216;maintenance&#8217; licensing costs (including things like databases and hosting, not just the CMS), cost of developers with these skills.
  * **Open source vs proprietary.**
  * **Development impact** &#8211; is your in-house team trained on this programming language and product? Are you buying a proprietary bespoke solution locking you into a certain agency? Will your CMS choice tie you to a certain approach for the project &#8211; for example some are more component based, and some are page-based.
  * **Impact on other technical elements** &#8211; Will the product choice have dependencies? &#8211; e.g. is it compatible with your existing hosting? Are there knock on impacts &#8211; e.g. Mura CMS needs ColdFusion or Railo, and it can be difficult to get good ColdFusion developers nowadays.
  * **What level of complexity do you need? &#8211;** Are you being sold an impressive solution that&#8217;s too complex, or a simple solution that will need to be drastically extended?
  * **What&#8217;s the experience of the people who will be using the system?** &#8211; What are their workflows? Does the business need to adapt, as well as the system?
  * **How well does it integrate with the other things you want to use?** &#8211; Does it have an API? Is it easy to bring in data from outside sources if needed? You may want to bring in say, booking data from a specific system, and combine that with editorial content not available to manage within the other system. Common areas to consider include integration with mailing systems, CRMs etc.
  * **Ensure that technical solutions aren&#8217;t dictating too much** &#8211; For example you don&#8217;t want your URL design to be compromised by a CMS that will only output content in a particular structure, and which won&#8217;t play well with re-writes.
  * **Track record for product updates, future roadmap, security, stability** &#8211; You may not want to adopt a new product too soon &#8211; for example <a href="http://umbraco.com/follow-us/blog-archive/2012/6/13/v5-rip.aspx" target="_blank">Umbraco 5 was later dropped by the company after launch</a>, causing issues for those who had already adopted it.
  * **Multilingual needs, both in terms of the site itself, and the admin interface** &#8211; If different language versions of the site are required, is this an exact translated clone, or will there be tailoring for the local market?
  * **Are editors likely to be using devices?** &#8211; How does this fit with the standard editing interfaces and capabilities? Can they work offline?
  * **Does anything need to be migrated, and how does that fit with the new system?**
  * **Number of concurrent admin users** &#8211; often used as a way for certain solutions to hugely ramp up licensing. Trying to circumvent this by creating custom admin screens using an API may circumvent terms of use of the software.
  * **What kind of support do you need from the vendor, and what&#8217;s this going to cost you?**
  * **Static site generation vs dynamic** &#8211; would a file-based system meet your needs?

&nbsp;

These are just a few examples of the kind of things that should be considered, and the exact nature of the investigation and decision-making process will vary hugely from one project to another.

## Conclusion

In my humble opinion there is rarely ever a single correct CMS choice for a project, and you&#8217;ll probably have a couple of candidates that will do an equally great job in different ways. Each will have their pros and cons, and may impact on other areas of the project and your development in general, so you&#8217;ll need to know what this means for you. When making this kind of decision, do your research, establish your needs, work with neutral experts, and make sure that any choice is a joint decision between the business, developers, and user experience/content teams.

If you need any advice about working on a project like this, I&#8217;m available to hire so please get in touch! You can email me using sally@recordssoundthesame.com, or feel free to tweet me your thoughts using <a href="http://twitter.com/sjenkinson" target="_blank">@sjenkinson</a>.

 [1]: https://ccharlottespencer.wordpress.com/2015/01/09/as-a-new-developer/
 [2]: http://www.performgroup.co.uk/
