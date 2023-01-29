---
title: Why I'm NOT moving from Squarespace to Astro
author: Elizabeth Tai
datetime: 2023-01-27T04:58:53Z
slug: not-moving-squarespace-to-astro
featured: false
draft: false
tags:
  - astro
  - squarespacetowordpress

description: I'm still moving out of Squarespace, but I'm not going turn it into a static website. What I'm doing instead.
---

In my last post, [Why I built a static website using Astro](/posts/why-astro/) I explained the reasons why I was making the move. It was mostly because of financial reasons, and also the frustration I had with bloated websites which did not perform well with Google's PageSpeed tests. And yeah, the frustration of being steadily locked into a proprietary system which makes it increasingly difficult to move out of.

You would think after my whinging about Squarespace, and the joy that came with building Front Matter (this website), that I'd naturally move it all to Astro.

No, I'm not. Heck no.

It's nothing to do with Astro's build, functions or capabilities. I adore Astro's simplicity, ease of use and beginner-friendliness. Here's why:

## Reason 1 - I don't have the skills to manage a static website - yet

I'm better than the average computer user, certainly, but I probably need to know much more about coding if I'm to move 300+ pages of content to a static website and manage it.

Right now, I am still discovering weird quirks when working with this Astro website. Sometimes, posts just would not upload, or if they do, VSCode will spit out indicipherable code that indicates that I've comitted some kind of fatal, naughty coding faux pas. This probably has a lot to do with my lack of experience with this whole _waves hands around_ command line coding thing.

Over time, when I gain more skills and confidence, I may choose to move to a static website. But that's still a big IF.

## Reason 2 - Squarespace doesn't make migration easy

Unlike Wordpress websites, I can't just move my Squarespace website to another Squarespace-like platform. Namely, becausere there are NO Squarespace-like platforms. With Wordpress websites, all I have to do is download an XML file of my website and just plug it into any Wordpress hosting service. There's only one Squarespace web builder, and if you want to move it to another place you'd have to somehow convert your website to fit the new place's content management system, whether it is Ghost, Wordpress or a static website.

As I am painfully discovering, the conversion process isn't smooth. I'm now copying and pasting every single post out of Squarespace into Wordpress. That's a subject of another post, but here's why below:

## Reason 3 - It's difficult to convert Squarespace blog posts into markdown

Squarespace has a method of converting blog posts into Wordpress-compatible XML. Or so they say.

I did use their function to convert the XML into markdown files using this git package: [wordpress export to markdown](https://github.com/lonekorean/wordpress-export-to-markdown). However, the files were not recognised by Astro. Why? Probably because the markdown contained lots of code that it didn't recognise.

So, I plugged that Squarespace-produced XML file into a wordpress.com staging website and discovered that each post had blocks of code that Wordpress didn't recognise. Super. It looks like I have to clean those blocks out of every single one of my 260+ posts before I could get a "clean" XML file. That will take far too long as Wordpress.com seemed to resist my attempts to remove said blocks unless I do several workarounds.

So ... even if I do manage to do all the above, there's no guarantee that the markdown files will display on my Astro website. Unless I make sure that ever post is nuked of weird code. It's just way faster to copy and paste everything, weirdly enough.

## Reason 4 - Because developers caution me about using static websites

Static websites are beloved by developers. But here's one thing I notice about the developers who say that.

They don't write a lot on their blogs.

Like, we're talking about maybe a dozen blog posts for the entire website, or perhaps 30+ or so.

I have nearly 300 pages worth of content. (And if I really include all the embarassingly angsty oversharing posts I wrote in the early 2000s, probably more than a thousand.)

There is no doubt that there are developers who have 1000+ pages of content and very happily doing so with a static website, but let's face it - unless I connect the static website with a headless CMS, it's going to be hell to use VSCode to wade through thousands of markdown files. And if one of them have some weird code that gives VSCode an aneuresym? Eh, this non-developer will have a helluva time trying to figure out what went wrong.

This video, [Why I Switched To Astro But You Probably Shouldn’t](https://youtu.be/YtaR_I65wmI), was also very revealing.

One day, his Gatsby website just ... stopped working. He had over a 100 posts by then.

"Nothing I did could fix it," he laments. And he is clearly an experienced developer!

My mind was made up when I spoke to a developer on Mastodon about this, and he said that managing a static website is 10x harder than a Wordpress website. I remembered _that_ hell, and I wasn't going to let my primary online presence to be hell to manage.

So, as much as I'd like to demonstrate my superhero coding skills to the world, there's one thing I am determined to do:

## Reason 5 - I want to focus on writing

I love tweaking websites. Like, _love_. Building content taxonomies is one of the most pleasurable activities for me. And design. I really love making my website look good.

But.

It takes me away from the no.1 thing I needed to do more of: Write.

My goal for 2023 is not just to document and share what I've learned as a technical writer, but to get my long-frozen fiction muscles warm again.

As much as I adore the simplicity of Astro and its speedy gonzalez performance, that's why I'm not moving my 260+ posts Squarespace website to ... wordpress.com.

Yes, yes, I can hear your protests already. And that's why that's the subject of the next blog post!
