---
title: Why I built a static website using Astro
author: Elizabeth Tai
datetime: 2023-01-18T04:58:53Z
slug: why-astro
featured: false
draft: false
tags:
  - astro

description: After years on Squarespace's basic personal plan, I was getting restless. I wanted more freedom from a walled garden hosting service. Enter static websites. But there's a slight problem - I'm a non-developer.
---

I moved from Wordpress to Squarespace six years ago. Managing my self-hosted Wordpress was taking so much of my time that writing took a back seat. I was also living in dread of the next bug or server outtage. Once, I was blacklisted by Google after being hacked!

That's when I entertained the idea of using Squarespace, eventhough I considered it expensive. But I soon realised that over the years my Wordpress hosting had gotten increasingly pricier. So much so that it was going to be _cheaper_ to run it on Squarespace! Besides, with Squarespace, I didn't have to worry about backend stuff, and I was willing to pay their price for peace of mind.

So I moved, and for most of the years that I've been with them, I was a satisfied customer.

Then, around 2020 they announced Squarespace 7.1.

## Life in a walled garden

I was all for moving my Squarespace 7.0 website to 7.1 until I found out that I had to “copy and paste” all my content to the new Squarespace version. (Read: [Moving from Squarespace version 7.0 to version 7.1 checklist](https://support.squarespace.com/hc/en-us/articles/360038270572-Moving-from-Squarespace-version-7-0-to-version-7-1-checklist).)

I couldn’t believe they didn’t create an easier way for clients to port their contents over to the new format.

Annoyed, I didn't do it. Besides, I liked the Brine theme.

I was also increasingly uncomfortable with the fact that if I wanted to move away from Squarespace, it'll probably be difficult to do so.

Unlike content management systems (CMS) like Wordpress, Squarespace's web builder is proprietary and while you could import the contents of your website to a Wordpress website via an XML file, the result is often less than satisfactory.

I ported over the XML file to a wordpress.com site recently to test it out, and it resulted in posts riddled with huge, empty spaces and duplicate images. This required a massive amount of fixing on my part to get it readable. Imagine doing this for every single page when you have over 300 posts.

## Slow page loads and sudden price hikes

Then I became more aware of how inefficient Squarespace websites can be.

After Google began prioritising page speeds for SEO, I ran audits and PageSpeed Insights on my Squarespace 7.0 website. It failed the Core Web Vitals Assessment for mobile and desktop. Performance was at 34% and 69% respectively.

There was nothing I could really do to improve the speed short of overhauling my website.

The last straw was when they raised my annual fee from US$96 to US$120. That’s a 25% increase!

This got me thinking a lot about relying on platforms like Squarespace where you are literally captive to their system and they can force you into higher price brackets. Don't get me wrong, I'd still recommend Squarespace for certain use cases, but I've clearly outgrown the service.

The price issue became a really big concern during the pandemic when my finances took a big hit. I wondered if I would be able to afford paying the then US$96 fee with a weakened Malaysia ringgit if I was out of a job for years. To get some perspective, imagine having to pay about US$450 per year for a basic plan on Squarespace. That's how it feels like for a Malaysian.

The thought of being out of work and having to rely on an expensive website to get work made me worry. (My website has gotten me freelance writing jobs in the past.)

So, I began toying with the idea of finding a cheaper way to keep a website on the web.

That's when I stumbled on the concept of static websites. The more I researched, the more I realised it was aimed at developers or software engineers who were code savvy.

Could a non-developer like me build a static website?

Since I'm a sucker for really tough projects like these, I dove in.

And discovered that the documentation for most static website generators (SSGs) were written for developers and were nigh incomprehensible to non-developers.

I almost gave up on the idea when going through the documentation for the "easiest" static website generator Hugo. There was just no way to understand what I needed to do because I had no prior knowledge of things like Git, Github, React, JSnode and more.

I find my Mandarin classes easier to understand, really.

Then, Sarah Rainsberger popped up in my Mastodon feed one day to recommend Astro to me. She happened to write Astro's documentation, by the way. There were strong hints of it being easy to use.

Now, I've heard all this before and was really skeptical, but I took a peek at their documentation, and as a working technical writer, I was seriously impressed!

**First win:** They didn't assume that I was a developer.

**Second win:** They created a [tutorial](https://docs.astro.build/en/tutorial/0-introduction/) on how to set up your Astro blog.

Can I say how much I love the tutorial? I adore checking things off like a good little student, and I get such a dopamine rush when I do it.

Thanks to the documentation, I was able to put up a static website (this blog!) in a week.

This goes to show how important documentation is. It often determines if a software will be adopted, and Astro won me over because of their non-developer-friendly documentation.

Now, I'm not blaming other SSGs, mind you. Most SSGs are a labour of love run by small teams of volunteers or single developers. Resources are thin and documentation is often equally sparse. They have a manpower problem, and they try their best. Personally, I'd be happy to contribute! Just haven't found an easy way to do it yet.

What do you think? [Share your thoughts on Linkedin](https://www.linkedin.com/posts/elizabethtai_developer-wordpress-websites-activity-7023063249558396928-Mn0z?utm_source=share&utm_medium=member_desktop).
